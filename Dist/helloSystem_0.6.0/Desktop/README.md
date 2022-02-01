helloSystem 0.6.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 59       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 59       | 98.33%  |
| GNOME        | 1        | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 59       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 59       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 59       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 51       | 86.44%  |
| BIOS | 8        | 13.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 59       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 59       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 25.42%  |
| ASRock              | 8        | 13.56%  |
| Hewlett-Packard     | 6        | 10.17%  |
| Gigabyte Technology | 6        | 10.17%  |
| Dell                | 5        | 8.47%   |
| MSI                 | 4        | 6.78%   |
| Lenovo              | 2        | 3.39%   |
| Intel               | 2        | 3.39%   |
| T-bao               | 1        | 1.69%   |
| Shuttle             | 1        | 1.69%   |
| Sapphire            | 1        | 1.69%   |
| PCPartner           | 1        | 1.69%   |
| Medion              | 1        | 1.69%   |
| Itautec             | 1        | 1.69%   |
| Gateway             | 1        | 1.69%   |
| Fujitsu             | 1        | 1.69%   |
| Apple               | 1        | 1.69%   |
| Acer                | 1        | 1.69%   |
| Unknown             | 1        | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| T-bao MINI PC                      | 1        | 1.69%   |
| Shuttle SH61R                      | 1        | 1.69%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044  | 1        | 1.69%   |
| PCPartner DREAMSYS                 | 1        | 1.69%   |
| MSI MS-7C91                        | 1        | 1.69%   |
| MSI MS-7B93                        | 1        | 1.69%   |
| MSI MS-7A40                        | 1        | 1.69%   |
| MSI MS-7592                        | 1        | 1.69%   |
| Medion H61H2-LM3                   | 1        | 1.69%   |
| Lenovo ThinkCentre M83 10AHS35Q00  | 1        | 1.69%   |
| Lenovo ThinkCentre E73z 10BD004RRU | 1        | 1.69%   |
| Itautec Infoway ST-4344            | 1        | 1.69%   |
| Intel H81                          | 1        | 1.69%   |
| Intel H61                          | 1        | 1.69%   |
| HP [AH877AV] _ Currency Bulk P     | 1        | 1.69%   |
| HP ProLiant ML350 G5               | 1        | 1.69%   |
| HP EliteDesk 800 G2 SFF            | 1        | 1.69%   |
| HP Compaq Elite 8300 USDT          | 1        | 1.69%   |
| HP Compaq Elite 8300 SFF           | 1        | 1.69%   |
| HP 260-p026                        | 1        | 1.69%   |
| Gigabyte H410M S2 V2               | 1        | 1.69%   |
| Gigabyte H270M-DS3H                | 1        | 1.69%   |
| Gigabyte G41MT-S2                  | 1        | 1.69%   |
| Gigabyte F2A78M-DS2                | 1        | 1.69%   |
| Gigabyte B450 AORUS M              | 1        | 1.69%   |
| Gigabyte 990FXA-UD3                | 1        | 1.69%   |
| Gateway DX4840                     | 1        | 1.69%   |
| Fujitsu D3220-A1                   | 1        | 1.69%   |
| Dell Studio XPS 9100               | 1        | 1.69%   |
| Dell OptiPlex 9020                 | 1        | 1.69%   |
| Dell OptiPlex 390                  | 1        | 1.69%   |
| Dell OptiPlex 3040                 | 1        | 1.69%   |
| Dell OptiPlex 3020M                | 1        | 1.69%   |
| ASUS TUF GAMING X570-PLUS          | 1        | 1.69%   |
| ASUS TUF B450M-PRO GAMING          | 1        | 1.69%   |
| ASUS TUF B360M-PLUS GAMING S       | 1        | 1.69%   |
| ASUS ROG STRIX X470-F GAMING       | 1        | 1.69%   |
| ASUS Pro WS X570-ACE               | 1        | 1.69%   |
| ASUS P7H55-M LX                    | 1        | 1.69%   |
| ASUS P5P43TD PRO                   | 1        | 1.69%   |
| ASUS M5A97 R2.0                    | 1        | 1.69%   |
| ASUS M5A78L/USB3                   | 1        | 1.69%   |
| ASUS M5A78L-M/USB3                 | 1        | 1.69%   |
| ASUS H110M-PLUS                    | 1        | 1.69%   |
| ASUS H110M-K                       | 1        | 1.69%   |
| ASUS exone Business 1203           | 1        | 1.69%   |
| ASUS CROSSHAIR V FORMULA-Z         | 1        | 1.69%   |
| ASUS All Series                    | 1        | 1.69%   |
| ASRock Z390 Pro4                   | 1        | 1.69%   |
| ASRock X570 Phantom Gaming 4       | 1        | 1.69%   |
| ASRock X370 Gaming X               | 1        | 1.69%   |
| ASRock X300M-STX                   | 1        | 1.69%   |
| ASRock B450 Gaming-ITX/ac          | 1        | 1.69%   |
| ASRock B365M-ITX/ac                | 1        | 1.69%   |
| ASRock AB350 Pro4                  | 1        | 1.69%   |
| ASRock A320M-DGS                   | 1        | 1.69%   |
| Apple MacPro5,1                    | 1        | 1.69%   |
| Acer Veriton M430                  | 1        | 1.69%   |
| Unknown                            | 1        | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 4        | 6.78%   |
| ASUS TUF            | 3        | 5.08%   |
| Lenovo ThinkCentre  | 2        | 3.39%   |
| HP Compaq           | 2        | 3.39%   |
| T-bao MINI          | 1        | 1.69%   |
| Shuttle SH61R       | 1        | 1.69%   |
| Sapphire EDGE-FT1M1 | 1        | 1.69%   |
| PCPartner DREAMSYS  | 1        | 1.69%   |
| MSI MS-7C91         | 1        | 1.69%   |
| MSI MS-7B93         | 1        | 1.69%   |
| MSI MS-7A40         | 1        | 1.69%   |
| MSI MS-7592         | 1        | 1.69%   |
| Medion H61H2-LM3    | 1        | 1.69%   |
| Itautec Infoway     | 1        | 1.69%   |
| Intel H81           | 1        | 1.69%   |
| Intel H61           | 1        | 1.69%   |
| HP [AH877AV]        | 1        | 1.69%   |
| HP ProLiant         | 1        | 1.69%   |
| HP EliteDesk        | 1        | 1.69%   |
| HP 260-p026         | 1        | 1.69%   |
| Gigabyte H410M      | 1        | 1.69%   |
| Gigabyte H270M-DS3H | 1        | 1.69%   |
| Gigabyte G41MT-S2   | 1        | 1.69%   |
| Gigabyte F2A78M-DS2 | 1        | 1.69%   |
| Gigabyte B450       | 1        | 1.69%   |
| Gigabyte 990FXA-UD3 | 1        | 1.69%   |
| Gateway DX4840      | 1        | 1.69%   |
| Fujitsu D3220-A1    | 1        | 1.69%   |
| Dell Studio         | 1        | 1.69%   |
| ASUS ROG            | 1        | 1.69%   |
| ASUS Pro            | 1        | 1.69%   |
| ASUS P7H55-M        | 1        | 1.69%   |
| ASUS P5P43TD        | 1        | 1.69%   |
| ASUS M5A97          | 1        | 1.69%   |
| ASUS M5A78L-M       | 1        | 1.69%   |
| ASUS M5A78L         | 1        | 1.69%   |
| ASUS H110M-PLUS     | 1        | 1.69%   |
| ASUS H110M-K        | 1        | 1.69%   |
| ASUS exone          | 1        | 1.69%   |
| ASUS CROSSHAIR      | 1        | 1.69%   |
| ASUS All            | 1        | 1.69%   |
| ASRock Z390         | 1        | 1.69%   |
| ASRock X570         | 1        | 1.69%   |
| ASRock X370         | 1        | 1.69%   |
| ASRock X300M-STX    | 1        | 1.69%   |
| ASRock B450         | 1        | 1.69%   |
| ASRock B365M-ITX    | 1        | 1.69%   |
| ASRock AB350        | 1        | 1.69%   |
| ASRock A320M-DGS    | 1        | 1.69%   |
| Apple MacPro5       | 1        | 1.69%   |
| Acer Veriton        | 1        | 1.69%   |
| Unknown             | 1        | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 8        | 13.56%  |
| 2021 | 6        | 10.17%  |
| 2010 | 6        | 10.17%  |
| 2020 | 5        | 8.47%   |
| 2016 | 5        | 8.47%   |
| 2015 | 5        | 8.47%   |
| 2013 | 5        | 8.47%   |
| 2018 | 4        | 6.78%   |
| 2017 | 4        | 6.78%   |
| 2012 | 4        | 6.78%   |
| 2011 | 3        | 5.08%   |
| 2014 | 2        | 3.39%   |
| 2009 | 1        | 1.69%   |
| 2007 | 1        | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 59       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 21       | 35.59%  |
| 8.01-16.0   | 16       | 27.12%  |
| 4.01-8.0    | 10       | 16.95%  |
| 32.01-64.0  | 9        | 15.25%  |
| 64.01-256.0 | 3        | 5.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 26       | 44.07%  |
| 0.01-0.5 | 22       | 37.29%  |
| 1.01-2.0 | 10       | 16.95%  |
| 3.01-4.0 | 1        | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 42.62%  |
| 2      | 17       | 27.87%  |
| 3      | 10       | 16.39%  |
| 4      | 7        | 11.48%  |
| 5      | 1        | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 61.02%  |
| Yes       | 23       | 38.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 58       | 98.31%  |
| No        | 1        | 1.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 66.1%   |
| Yes       | 20       | 33.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 76.27%  |
| Yes       | 14       | 23.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 15.25%  |
| Russia      | 6        | 10.17%  |
| Germany     | 6        | 10.17%  |
| Poland      | 4        | 6.78%   |
| Brazil      | 4        | 6.78%   |
| Italy       | 3        | 5.08%   |
| Australia   | 3        | 5.08%   |
| Ukraine     | 2        | 3.39%   |
| Spain       | 2        | 3.39%   |
| India       | 2        | 3.39%   |
| China       | 2        | 3.39%   |
| UK          | 1        | 1.69%   |
| Turkey      | 1        | 1.69%   |
| Thailand    | 1        | 1.69%   |
| Taiwan      | 1        | 1.69%   |
| Switzerland | 1        | 1.69%   |
| South Korea | 1        | 1.69%   |
| Netherlands | 1        | 1.69%   |
| Mexico      | 1        | 1.69%   |
| Hungary     | 1        | 1.69%   |
| Hong Kong   | 1        | 1.69%   |
| Guatemala   | 1        | 1.69%   |
| Finland     | 1        | 1.69%   |
| Denmark     | 1        | 1.69%   |
| Chile       | 1        | 1.69%   |
| Canada      | 1        | 1.69%   |
| Bulgaria    | 1        | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Marlborough       | 2        | 3.39%   |
| Hobart            | 2        | 3.39%   |
| Yekaterinburg     | 1        | 1.69%   |
| Xiamen            | 1        | 1.69%   |
| Wolgast           | 1        | 1.69%   |
| Warrenton         | 1        | 1.69%   |
| Voronezh          | 1        | 1.69%   |
| Tula de Allende   | 1        | 1.69%   |
| Torre del Mar     | 1        | 1.69%   |
| Tampa             | 1        | 1.69%   |
| Stuttgart         | 1        | 1.69%   |
| Stralsund         | 1        | 1.69%   |
| Sofia             | 1        | 1.69%   |
| Siedlce           | 1        | 1.69%   |
| Shepetivka        | 1        | 1.69%   |
| Santiago          | 1        | 1.69%   |
| Rzesz??w          | 1        | 1.69%   |
| Rostov-on-Don     | 1        | 1.69%   |
| Riehen            | 1        | 1.69%   |
| Richmond          | 1        | 1.69%   |
| Reriutaba         | 1        | 1.69%   |
| Qingdao           | 1        | 1.69%   |
| Pistoia           | 1        | 1.69%   |
| Old Town          | 1        | 1.69%   |
| Nieuwegein        | 1        | 1.69%   |
| Newtownabbey      | 1        | 1.69%   |
| Munich            | 1        | 1.69%   |
| Moscow            | 1        | 1.69%   |
| Manaus            | 1        | 1.69%   |
| Kyiv              | 1        | 1.69%   |
| Kosekoy           | 1        | 1.69%   |
| Kochi             | 1        | 1.69%   |
| Kirkkonummi       | 1        | 1.69%   |
| Katowice          | 1        | 1.69%   |
| Irkutsk           | 1        | 1.69%   |
| Inhapim           | 1        | 1.69%   |
| Ilh?©us           | 1        | 1.69%   |
| Idaho Falls       | 1        | 1.69%   |
| Hsinchu           | 1        | 1.69%   |
| Hong Kong         | 1        | 1.69%   |
| Hicksville        | 1        | 1.69%   |
| Heidelberg        | 1        | 1.69%   |
| Harrisburg        | 1        | 1.69%   |
| Gy?‘r             | 1        | 1.69%   |
| Gwangyang         | 1        | 1.69%   |
| Guatemala City    | 1        | 1.69%   |
| Grottazzolina     | 1        | 1.69%   |
| Fuente Carreteros | 1        | 1.69%   |
| Frederiksberg     | 1        | 1.69%   |
| Filderstadt       | 1        | 1.69%   |
| Ernakulam         | 1        | 1.69%   |
| Chelyabinsk       | 1        | 1.69%   |
| Bydgoszcz         | 1        | 1.69%   |
| Brisbane          | 1        | 1.69%   |
| Bari              | 1        | 1.69%   |
| Bangkok           | 1        | 1.69%   |
| Anaheim           | 1        | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 31     | 25.51%  |
| Seagate             | 18       | 22     | 18.37%  |
| Samsung Electronics | 13       | 18     | 13.27%  |
| Toshiba             | 5        | 7      | 5.1%    |
| Hitachi             | 5        | 7      | 5.1%    |
| Crucial             | 5        | 8      | 5.1%    |
| Kingston            | 4        | 7      | 4.08%   |
| SanDisk             | 3        | 3      | 3.06%   |
| Smartbuy            | 2        | 2      | 2.04%   |
| Intel               | 2        | 2      | 2.04%   |
| China               | 2        | 2      | 2.04%   |
| A-DATA Technology   | 2        | 4      | 2.04%   |
| Verbatim            | 1        | 1      | 1.02%   |
| SPCC                | 1        | 1      | 1.02%   |
| Silicon Motion      | 1        | 1      | 1.02%   |
| PNY                 | 1        | 1      | 1.02%   |
| PLEXTOR             | 1        | 1      | 1.02%   |
| LITEONIT            | 1        | 1      | 1.02%   |
| KingSpec            | 1        | 1      | 1.02%   |
| Hewlett-Packard     | 1        | 1      | 1.02%   |
| GOODRAM             | 1        | 1      | 1.02%   |
| Gigabyte Technology | 1        | 1      | 1.02%   |
| Corsair             | 1        | 1      | 1.02%   |
| Apacer              | 1        | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB           | 3        | 2.59%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 2        | 1.72%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 2        | 1.72%   |
| Toshiba DT01ACA100 1TB              | 2        | 1.72%   |
| Seagate ST3500312CS 500GB           | 2        | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2        | 1.72%   |
| SanDisk SDSSDA240G 240GB            | 2        | 1.72%   |
| Samsung SSD 850 EVO 250GB           | 2        | 1.72%   |
| Samsung HD322HJ 320GB               | 2        | 1.72%   |
| China SATA SSD 120GB                | 2        | 1.72%   |
| WDC WDS250G2X0C-00L350 250GB        | 1        | 0.86%   |
| WDC WD800JD-00LSA0 80GB             | 1        | 0.86%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1        | 0.86%   |
| WDC WD5000AAVS-00ZTB0 500GB         | 1        | 0.86%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 0.86%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 0.86%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 0.86%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 0.86%   |
| WDC WD40EZRZ-22GXCB0 4TB            | 1        | 0.86%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 0.86%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 0.86%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1        | 0.86%   |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1        | 0.86%   |
| WDC WD2500JD-75HBB0 250GB           | 1        | 0.86%   |
| WDC WD2500BEVS-22UST0 250GB         | 1        | 0.86%   |
| WDC WD20SMZW-11YFCS0 2TB            | 1        | 0.86%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 0.86%   |
| WDC WD1600AAJS-00WAA0 160GB         | 1        | 0.86%   |
| WDC WD1600AAJS-00V4A0 160GB         | 1        | 0.86%   |
| WDC WD10SPZX-22Z10T0 1TB            | 1        | 0.86%   |
| WDC WD10JMVW-11AJGS0 1TB            | 1        | 0.86%   |
| WDC WD10EZRX-00A8LB0 1TB            | 1        | 0.86%   |
| WDC WD10EZEX-75WN4A1 1TB            | 1        | 0.86%   |
| WDC WD10EFRX-68FYTN0 1TB            | 1        | 0.86%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 0.86%   |
| WDC WD1001FAES-75W7A0 1TB           | 1        | 0.86%   |
| Verbatim Vi550 S3 SSD 128GB         | 1        | 0.86%   |
| Toshiba MQ01UBD100 1TB              | 1        | 0.86%   |
| Toshiba MQ01ABD032 320GB            | 1        | 0.86%   |
| Toshiba HDWD110 1TB                 | 1        | 0.86%   |
| Toshiba DT01ACA050 500GB            | 1        | 0.86%   |
| SPCC M.2 PCIe SSD 256GB             | 1        | 0.86%   |
| Smartbuy SSD 240GB                  | 1        | 0.86%   |
| Smartbuy SSD 120GB                  | 1        | 0.86%   |
| Silicon Motion ASint AS806 128GB    | 1        | 0.86%   |
| Seagate ST9320325AS 320GB           | 1        | 0.86%   |
| Seagate ST8000DM004-2U9188 8TB      | 1        | 0.86%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 0.86%   |
| Seagate ST500LM000-1EJ162 500GB     | 1        | 0.86%   |
| Seagate ST500DM002-1SB10A 500GB     | 1        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 0.86%   |
| Seagate ST3500413AS 500GB           | 1        | 0.86%   |
| Seagate ST3250318AS 250GB           | 1        | 0.86%   |
| Seagate ST3160813AS 160GB           | 1        | 0.86%   |
| Seagate ST31000524AS 1TB            | 1        | 0.86%   |
| Seagate ST3000DM001-1CH166 3TB      | 1        | 0.86%   |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 0.86%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 0.86%   |
| Seagate ST1000LM048-2E7172 1TB      | 1        | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 28     | 41.07%  |
| Seagate             | 18       | 22     | 32.14%  |
| Toshiba             | 5        | 7      | 8.93%   |
| Hitachi             | 5        | 7      | 8.93%   |
| Samsung Electronics | 4        | 6      | 7.14%   |
| Hewlett-Packard     | 1        | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 21.88%  |
| Crucial             | 5        | 8      | 15.63%  |
| Kingston            | 4        | 7      | 12.5%   |
| SanDisk             | 3        | 3      | 9.38%   |
| Smartbuy            | 2        | 2      | 6.25%   |
| China               | 2        | 2      | 6.25%   |
| Verbatim            | 1        | 1      | 3.13%   |
| PNY                 | 1        | 1      | 3.13%   |
| PLEXTOR             | 1        | 1      | 3.13%   |
| LITEONIT            | 1        | 1      | 3.13%   |
| KingSpec            | 1        | 1      | 3.13%   |
| Intel               | 1        | 1      | 3.13%   |
| GOODRAM             | 1        | 1      | 3.13%   |
| Apacer              | 1        | 1      | 3.13%   |
| A-DATA Technology   | 1        | 2      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 40       | 71     | 50%     |
| SSD  | 28       | 40     | 35%     |
| NVMe | 12       | 14     | 15%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 53       | 111    | 81.54%  |
| NVMe | 12       | 14     | 18.46%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 46       | 68     | 56.1%   |
| 0.51-1.0   | 22       | 26     | 26.83%  |
| 1.01-2.0   | 6        | 7      | 7.32%   |
| 2.01-3.0   | 4        | 6      | 4.88%   |
| 3.01-4.0   | 3        | 3      | 3.66%   |
| 4.01-10.0  | 1        | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 37       | 62.71%  |
| 101-250    | 13       | 22.03%  |
| 251-500    | 6        | 10.17%  |
| 21-50      | 1        | 1.69%   |
| 501-1000   | 1        | 1.69%   |
| 51-100     | 1        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 59       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 2        | 2      | 11.76%  |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 1      | 5.88%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1      | 5.88%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 1      | 5.88%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 1      | 5.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 1      | 5.88%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 1      | 5.88%   |
| WDC WD10JMVW-11AJGS0 1TB            | 1        | 1      | 5.88%   |
| Toshiba MQ01UBD100 1TB              | 1        | 1      | 5.88%   |
| Toshiba DT01ACA100 1TB              | 1        | 2      | 5.88%   |
| Seagate ST9320325AS 320GB           | 1        | 1      | 5.88%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 1      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 5.88%   |
| Seagate ST3500413AS 500GB           | 1        | 1      | 5.88%   |
| SanDisk SDSSDA240G 240GB            | 1        | 1      | 5.88%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 43.75%  |
| Seagate             | 4        | 4      | 25%     |
| Toshiba             | 2        | 3      | 12.5%   |
| Samsung Electronics | 2        | 3      | 12.5%   |
| SanDisk             | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 46.67%  |
| Seagate             | 4        | 4      | 26.67%  |
| Toshiba             | 2        | 3      | 13.33%  |
| Samsung Electronics | 2        | 3      | 13.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 17     | 93.33%  |
| SSD  | 1        | 1      | 6.67%   |

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
| Works    | 54       | 106    | 77.14%  |
| Malfunc  | 15       | 18     | 21.43%  |
| Detected | 1        | 1      | 1.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 37       | 48.68%  |
| AMD                        | 22       | 28.95%  |
| Sandisk                    | 3        | 3.95%   |
| Samsung Electronics        | 3        | 3.95%   |
| Phison Electronics         | 3        | 3.95%   |
| ASMedia Technology         | 3        | 3.95%   |
| Silicon Motion             | 1        | 1.32%   |
| Lite-On IT Corp. / Plextor | 1        | 1.32%   |
| JMicron Technology         | 1        | 1.32%   |
| Hewlett-Packard            | 1        | 1.32%   |
| ADATA Technology           | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 14.29%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 7.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 5.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 5.49%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 5.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.3%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 2.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.2%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.1%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.1%    |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.1%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.1%    |
| Phison E12 NVMe Controller                                                              | 1        | 1.1%    |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]                       | 1        | 1.1%    |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 1.1%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.1%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.1%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.1%    |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.1%    |
| HP Smart Array E200i (SAS Controller)                                                   | 1        | 1.1%    |
| HP Smart Array Controller                                                               | 1        | 1.1%    |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.1%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 1.1%    |
| AMD FCH SATA Controller D                                                               | 1        | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.1%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 47       | 65.28%  |
| NVMe | 12       | 16.67%  |
| IDE  | 12       | 16.67%  |
| RAID | 1        | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 61.02%  |
| AMD    | 23       | 38.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor           | 3        | 5.08%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 3.39%   |
| Intel Core i5-4570S CPU @ 2.90GHz             | 2        | 3.39%   |
| Intel Core i3-6100T CPU @ 3.20GHz             | 2        | 3.39%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2        | 3.39%   |
| AMD FX-8350 Eight-Core Processor              | 2        | 3.39%   |
| Intel Xeon CPU W3680 @ 3.33GHz                | 1        | 1.69%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1        | 1.69%   |
| Intel Xeon                                    | 1        | 1.69%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 1.69%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1        | 1.69%   |
| Intel Genuine CPU 2160 @ 1.80GHz              | 1        | 1.69%   |
| Intel Core i7-9700F CPU @ 3.00GHz             | 1        | 1.69%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1        | 1.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 1.69%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1        | 1.69%   |
| Intel Core i7 CPU 960 @ 3.20GHz               | 1        | 1.69%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 1.69%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1        | 1.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 1.69%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1        | 1.69%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 1.69%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1        | 1.69%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 1        | 1.69%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 1        | 1.69%   |
| Intel Core i5 CPU 661 @ 3.33GHz               | 1        | 1.69%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1        | 1.69%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 1        | 1.69%   |
| Intel Core i3-4150T CPU @ 3.00GHz             | 1        | 1.69%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1        | 1.69%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 1        | 1.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 1.69%   |
| Intel Core i3-2120 CPU @ 3.30GH               | 1        | 1.69%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz         | 1        | 1.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1        | 1.69%   |
| Intel Core 2 Duo CPU                          | 1        | 1.69%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1        | 1.69%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1        | 1.69%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1        | 1.69%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1        | 1.69%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 1        | 1.69%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 1        | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1        | 1.69%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1        | 1.69%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 1        | 1.69%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 1        | 1.69%   |
| AMD Phenom II X6 1045T Processor              | 1        | 1.69%   |
| AMD Phenom II X4 965 Processor                | 1        | 1.69%   |
| AMD FX-6300 Six-Core Processor                | 1        | 1.69%   |
| AMD FX-6100 Six-Core Processor                | 1        | 1.69%   |
| AMD E-450 APU with Radeon HD Graphics         | 1        | 1.69%   |
| AMD A4-7300 APU with Radeon HD Graphics       | 1        | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 18.64%  |
| Intel Core i3           | 9        | 15.25%  |
| Intel Core i7           | 7        | 11.86%  |
| AMD Ryzen 5             | 5        | 8.47%   |
| AMD Ryzen 7             | 4        | 6.78%   |
| AMD FX                  | 4        | 6.78%   |
| Intel Xeon              | 3        | 5.08%   |
| AMD Ryzen 9             | 3        | 5.08%   |
| Intel Core 2 Duo        | 2        | 3.39%   |
| AMD Ryzen 3             | 2        | 3.39%   |
| Intel Pentium Dual-Core | 1        | 1.69%   |
| Intel Pentium           | 1        | 1.69%   |
| Intel Genuine           | 1        | 1.69%   |
| Intel Core 2 Quad       | 1        | 1.69%   |
| AMD Ryzen 5 PRO         | 1        | 1.69%   |
| AMD Phenom II X6        | 1        | 1.69%   |
| AMD Phenom II X4        | 1        | 1.69%   |
| AMD E                   | 1        | 1.69%   |
| AMD A4                  | 1        | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 19       | 32.2%   |
| 2       | 15       | 25.42%  |
| 12      | 6        | 10.17%  |
| 6       | 6        | 10.17%  |
| 8       | 5        | 8.47%   |
| 16      | 4        | 6.78%   |
| 24      | 3        | 5.08%   |
| Unknown | 1        | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 57       | 96.61%  |
| 2      | 2        | 3.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 41       | 69.49%  |
| 2       | 17       | 28.81%  |
| Unknown | 1        | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 8        | 13.56%  |
| KabyLake    | 7        | 11.86%  |
| Zen 2       | 6        | 10.17%  |
| Zen         | 5        | 8.47%   |
| SandyBridge | 5        | 8.47%   |
| Penryn      | 5        | 8.47%   |
| Piledriver  | 4        | 6.78%   |
| Zen+        | 3        | 5.08%   |
| Skylake     | 3        | 5.08%   |
| Westmere    | 2        | 3.39%   |
| Nehalem     | 2        | 3.39%   |
| K10         | 2        | 3.39%   |
| IvyBridge   | 2        | 3.39%   |
| Zen 3       | 1        | 1.69%   |
| Core        | 1        | 1.69%   |
| CometLake   | 1        | 1.69%   |
| Bulldozer   | 1        | 1.69%   |
| Bobcat      | 1        | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 24       | 38.71%  |
| AMD    | 21       | 33.87%  |
| Intel  | 17       | 27.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 8.06%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 6.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 4.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 4.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 3.23%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 3.23%   |
| Intel HD Graphics 630                                                       | 2        | 3.23%   |
| Intel HD Graphics 530                                                       | 2        | 3.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.23%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 3.23%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 3.23%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.61%   |
| Nvidia GT215 [GeForce GT 220]                                               | 1        | 1.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.61%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1        | 1.61%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.61%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.61%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.61%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1        | 1.61%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.61%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.61%   |
| Nvidia G92 [GeForce GT 330]                                                 | 1        | 1.61%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.61%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.61%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.61%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.61%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.61%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.61%   |
| AMD Richland [Radeon HD 8470D]                                              | 1        | 1.61%   |
| AMD Renoir                                                                  | 1        | 1.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.61%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.61%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.61%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 22       | 37.29%  |
| 1 x AMD        | 20       | 33.9%   |
| 1 x Intel      | 13       | 22.03%  |
| Intel + Nvidia | 2        | 3.39%   |
| 2 x Intel      | 1        | 1.69%   |
| Intel + AMD    | 1        | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 79.66%  |
| Proprietary | 11       | 18.64%  |
| Unknown     | 1        | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 54.24%  |
| 1.01-2.0   | 7        | 11.86%  |
| 3.01-4.0   | 6        | 10.17%  |
| 0.01-0.5   | 5        | 8.47%   |
| 7.01-8.0   | 3        | 5.08%   |
| 5.01-6.0   | 3        | 5.08%   |
| 0.51-1.0   | 3        | 5.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 13.89%  |
| Hewlett-Packard      | 4        | 11.11%  |
| Iiyama               | 3        | 8.33%   |
| Goldstar             | 3        | 8.33%   |
| Dell                 | 3        | 8.33%   |
| Philips              | 2        | 5.56%   |
| Lenovo               | 2        | 5.56%   |
| BenQ                 | 2        | 5.56%   |
| Ancor Communications | 2        | 5.56%   |
| Acer                 | 2        | 5.56%   |
| Vizio                | 1        | 2.78%   |
| ViewSonic            | 1        | 2.78%   |
| Medion               | 1        | 2.78%   |
| Haier                | 1        | 2.78%   |
| Eizo                 | 1        | 2.78%   |
| ASUSTek Computer     | 1        | 2.78%   |
| AOC                  | 1        | 2.78%   |
| ALP                  | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 2        | 5.41%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch               | 1        | 2.7%    |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch           | 1        | 2.7%    |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch    | 1        | 2.7%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                     | 1        | 2.7%    |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 1        | 2.7%    |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch  | 1        | 2.7%    |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1        | 2.7%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 2.7%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 1        | 2.7%    |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                  | 1        | 2.7%    |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch               | 1        | 2.7%    |
| Lenovo LEN-E73Z-D LEN00A1 1600x900 440x240mm 19.7-inch               | 1        | 2.7%    |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                | 1        | 2.7%    |
| Hewlett-Packard ZR22w HWP2867 1920x1080 480x270mm 21.7-inch          | 1        | 2.7%    |
| Hewlett-Packard E243m HPN3465 1920x1080 530x300mm 24.0-inch          | 1        | 2.7%    |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x290mm 23.1-inch           | 1        | 2.7%    |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch            | 1        | 2.7%    |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch             | 1        | 2.7%    |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 2.7%    |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 1        | 2.7%    |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                | 1        | 2.7%    |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                   | 1        | 2.7%    |
| Dell ST2321L DELF033 1920x1080 510x290mm 23.1-inch                   | 1        | 2.7%    |
| Dell ST2321L DELF031 1920x1080 510x290mm 23.1-inch                   | 1        | 2.7%    |
| Dell E228WFP DELD014 1680x1050 470x300mm 22.0-inch                   | 1        | 2.7%    |
| Dell 1708FP DEL4024 1280x1024 340x270mm 17.1-inch                    | 1        | 2.7%    |
| BenQ LCD Monitor BNQ7725 1920x1080 480x270mm 21.7-inch               | 1        | 2.7%    |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 1        | 2.7%    |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch         | 1        | 2.7%    |
| AOC LE19W037 AOC1907 1360x768 410x230mm 18.5-inch                    | 1        | 2.7%    |
| Ancor Communications MW221 ACI22B1 1680x1050 470x300mm 22.0-inch     | 1        | 2.7%    |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch     | 1        | 2.7%    |
| ALP 2476 IPS ALP2476 1920x1080 530x300mm 24.0-inch                   | 1        | 2.7%    |
| Acer ET430K ACR0558 3840x2160 940x530mm 42.5-inch                    | 1        | 2.7%    |
| Acer B223W ACR0018 1680x1050 470x300mm 22.0-inch                     | 1        | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 50%     |
| 1366x768 (WXGA)    | 4        | 11.11%  |
| 1680x1050 (WSXGA+) | 3        | 8.33%   |
| 1920x1200 (WUXGA)  | 2        | 5.56%   |
| 1600x900 (HD+)     | 2        | 5.56%   |
| 1024x768 (XGA)     | 2        | 5.56%   |
| 3840x2160 (4K)     | 1        | 2.78%   |
| 2560x1440 (QHD)    | 1        | 2.78%   |
| 1920x540           | 1        | 2.78%   |
| 1360x768           | 1        | 2.78%   |
| 1280x1024 (SXGA)   | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 9        | 25%     |
| 24      | 5        | 13.89%  |
| 21      | 5        | 13.89%  |
| 18      | 5        | 13.89%  |
| 22      | 3        | 8.33%   |
| 19      | 2        | 5.56%   |
| 14      | 2        | 5.56%   |
| Unknown | 2        | 5.56%   |
| 42      | 1        | 2.78%   |
| 27      | 1        | 2.78%   |
| 17      | 1        | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 41.67%  |
| 401-500     | 15       | 41.67%  |
| 201-300     | 2        | 5.56%   |
| Unknown     | 2        | 5.56%   |
| 301-350     | 1        | 2.78%   |
| 901-1000    | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 28       | 77.78%  |
| 16/10 | 5        | 13.89%  |
| 4/3   | 2        | 5.56%   |
| 5/4   | 1        | 2.78%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 55.56%  |
| 141-150        | 6        | 16.67%  |
| 251-300        | 2        | 5.56%   |
| 151-200        | 2        | 5.56%   |
| 101-110        | 2        | 5.56%   |
| Unknown        | 2        | 5.56%   |
| 301-350        | 1        | 2.78%   |
| 501-1000       | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 77.78%  |
| 101-120 | 6        | 16.67%  |
| Unknown | 2        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 57.63%  |
| 0     | 23       | 38.98%  |
| 2     | 2        | 3.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 36       | 46.15%  |
| Intel                    | 22       | 28.21%  |
| Broadcom                 | 7        | 8.97%   |
| Qualcomm Atheros         | 5        | 6.41%   |
| Ralink Technology        | 2        | 2.56%   |
| Ralink                   | 1        | 1.28%   |
| Marvell Technology Group | 1        | 1.28%   |
| IMC Networks             | 1        | 1.28%   |
| Belkin Components        | 1        | 1.28%   |
| ASUSTek Computer         | 1        | 1.28%   |
| Aquantia                 | 1        | 1.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31       | 36.9%   |
| Intel I211 Gigabit Network Connection                                          | 6        | 7.14%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 2.38%   |
| Intel Ethernet Connection I217-V                                               | 2        | 2.38%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2        | 2.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2        | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.19%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.19%   |
| Ralink RT3072 Wireless Adapter                                                 | 1        | 1.19%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 1.19%   |
| Ralink RT2561/RT61 rev B 802.11g                                               | 1        | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1        | 1.19%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 1.19%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 1.19%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.19%   |
| Intel Wireless 7265                                                            | 1        | 1.19%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.19%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.19%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.19%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 1.19%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.19%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter    | 1        | 1.19%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 1.19%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 1.19%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 1.19%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 1        | 1.19%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 1        | 1.19%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]             | 1        | 1.19%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                      | 1        | 1.19%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1        | 1.19%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 22.73%  |
| Realtek Semiconductor | 4        | 18.18%  |
| Broadcom              | 4        | 18.18%  |
| Qualcomm Atheros      | 3        | 13.64%  |
| Ralink Technology     | 2        | 9.09%   |
| Ralink                | 1        | 4.55%   |
| IMC Networks          | 1        | 4.55%   |
| Belkin Components     | 1        | 4.55%   |
| ASUSTek Computer      | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2        | 8.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 2        | 8.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1        | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 4.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 1        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 4.35%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 4.35%   |
| Ralink RT3072 Wireless Adapter                                              | 1        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                             | 1        | 4.35%   |
| Ralink RT2561/RT61 rev B 802.11g                                            | 1        | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 4.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1        | 4.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 4.35%   |
| Intel Wireless 7265                                                         | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                         | 1        | 4.35%   |
| Intel Centrino Wireless-N 105                                               | 1        | 4.35%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 4.35%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                          | 1        | 4.35%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1        | 4.35%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]          | 1        | 4.35%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 33       | 55%     |
| Intel                    | 20       | 33.33%  |
| Broadcom                 | 3        | 5%      |
| Qualcomm Atheros         | 2        | 3.33%   |
| Marvell Technology Group | 1        | 1.67%   |
| Aquantia                 | 1        | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31       | 51.67%  |
| Intel I211 Gigabit Network Connection                                          | 6        | 10%     |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 3.33%   |
| Intel Ethernet Connection I217-V                                               | 2        | 3.33%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2        | 3.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 1.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 1.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.67%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.67%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 1.67%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.67%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 1.67%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 1.67%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 1.67%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1        | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 73.42%  |
| WiFi     | 20       | 25.32%  |
| Unknown  | 1        | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 80.56%  |
| WiFi     | 14       | 19.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 69.49%  |
| 2     | 16       | 27.12%  |
| 3     | 2        | 3.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 96.67%  |
| Yes  | 2        | 3.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 28.57%  |
| Apple                   | 3        | 21.43%  |
| Realtek Semiconductor   | 2        | 14.29%  |
| Cambridge Silicon Radio | 2        | 14.29%  |
| Foxconn / Hon Hai       | 1        | 7.14%   |
| Broadcom                | 1        | 7.14%   |
| ASUSTek Computer        | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 14.29%  |
| Apple Apple Broadcom Built-in Bluetooth             | 2        | 14.29%  |
| Realtek  Bluetooth Adapter                          | 1        | 7.14%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1        | 7.14%   |
| Intel Bluetooth wireless interface                  | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |
| Foxconn / Hon Hai Broadcom Bluetooth 4.0 USB        | 1        | 7.14%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 33       | 33.67%  |
| AMD                     | 29       | 29.59%  |
| Nvidia                  | 22       | 22.45%  |
| C-Media Electronics     | 5        | 5.1%    |
| Texas Instruments       | 2        | 2.04%   |
| Logitech                | 2        | 2.04%   |
| Creative Labs           | 2        | 2.04%   |
| Plantronics             | 1        | 1.02%   |
| Hewlett-Packard         | 1        | 1.02%   |
| BEHRINGER International | 1        | 1.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 6.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 6.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 5.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 5.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 4.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 4.35%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.48%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 3.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 2.61%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3        | 2.61%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.74%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.74%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.74%   |
| Plantronics Plantronics Blackwire 325.1                                    | 1        | 0.87%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.87%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.87%   |
| Logitech HD Webcam C910                                                    | 1        | 0.87%   |
| Logitech HD Webcam C510                                                    | 1        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.87%   |
| Hewlett-Packard E243m                                                      | 1        | 0.87%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 0.87%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 1        | 0.87%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 0.87%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.87%   |
| C-Media Electronics Audio Adapter                                          | 1        | 0.87%   |
| BEHRINGER International UMC202HD 192k                                      | 1        | 0.87%   |
| AMD Wrestler HDMI Audio                                                    | 1        | 0.87%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 0.87%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 0.87%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 0.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 0.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 0.87%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 1        | 0.87%   |
| AMD FCH Azalia Controller                                                  | 1        | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 12       | 17.65%  |
| Samsung Electronics | 11       | 16.18%  |
| Crucial             | 8        | 11.76%  |
| Unknown             | 7        | 10.29%  |
| SK Hynix            | 4        | 5.88%   |
| G.Skill             | 4        | 5.88%   |
| Corsair             | 4        | 5.88%   |
| Team                | 3        | 4.41%   |
| Nanya Technology    | 3        | 4.41%   |
| Unknown             | 3        | 4.41%   |
| Transcend           | 2        | 2.94%   |
| Micron Technology   | 2        | 2.94%   |
| A-DATA Technology   | 2        | 2.94%   |
| Ramaxel Technology  | 1        | 1.47%   |
| Patriot             | 1        | 1.47%   |
| Hikvision           | 1        | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 3        | 4.29%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s     | 2        | 2.86%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s   | 2        | 2.86%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1333MT/s          | 2        | 2.86%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s    | 2        | 2.86%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s             | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 1.43%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 1.43%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s       | 1        | 1.43%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s      | 1        | 1.43%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.43%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.43%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 1.43%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                | 1        | 1.43%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s              | 1        | 1.43%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 1.43%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1600MT/s         | 1        | 1.43%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s     | 1        | 1.43%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.43%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.43%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 1.43%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s   | 1        | 1.43%   |
| Patriot RAM Module 2GB DIMM DDR2 533MT/s                | 1        | 1.43%   |
| Nanya RAM NT4GC72B8PB0NF-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.43%   |
| Nanya RAM M2F4G64CC88D7N-DI 4GB DIMM DDR3 1600MT/s      | 1        | 1.43%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.43%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s      | 1        | 1.43%   |
| Micron RAM 4ATF51264HZ-2G6B1 4GB SODIMM DDR4 1200MT/s   | 1        | 1.43%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s   | 1        | 1.43%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3200MT/s   | 1        | 1.43%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 1        | 1.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s       | 1        | 1.43%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 1        | 1.43%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s | 1        | 1.43%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s       | 1        | 1.43%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s  | 1        | 1.43%   |
| Kingston RAM 99U5665-001.A00G 4GB DIMM DDR4 2400MT/s    | 1        | 1.43%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.43%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 1.43%   |
| Kingston RAM 9905734-180.A00G 16GB DIMM DDR4 2666MT/s   | 1        | 1.43%   |
| Kingston RAM 9905665-020.A00G 4GB DIMM DDR4 2667MT/s    | 1        | 1.43%   |
| Hikvision RAM HKED3041AAB3H3HA1 4GB DIMM DDR3 1600MT/s  | 1        | 1.43%   |
| G.Skill RAM F4-3866C18-8GTZR 8GB DIMM DDR4 2133MT/s     | 1        | 1.43%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 1        | 1.43%   |
| G.Skill RAM F4-2400C15-8GFT 8GB DIMM DDR4 2400MT/s      | 1        | 1.43%   |
| G.Skill RAM F4-2133C15-16GIS 16GB DIMM DDR4 2133MT/s    | 1        | 1.43%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s             | 1        | 1.43%   |
| Crucial RAM CT4G4DFS824A.C8FF 4GB DIMM DDR4 2667MT/s    | 1        | 1.43%   |
| Crucial RAM CT4G4DFS8213.C8FBD1 4GB DIMM DDR4 2133MT/s  | 1        | 1.43%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s | 1        | 1.43%   |
| Crucial RAM BL8G32C16U4BL.M8FE 8GB DIMM DDR4 2667MT/s   | 1        | 1.43%   |
| Crucial RAM BL8G30C15U4B.M8FE 8GB DIMM DDR4 2666MT/s    | 1        | 1.43%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s    | 1        | 1.43%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 2133MT/s  | 1        | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 26       | 44.07%  |
| DDR3    | 25       | 42.37%  |
| Unknown | 4        | 6.78%   |
| DDR2    | 2        | 3.39%   |
| SDRAM   | 1        | 1.69%   |
| DDR     | 1        | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 53       | 89.83%  |
| SODIMM  | 5        | 8.47%   |
| FB-DIMM | 1        | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 34.38%  |
| 4096  | 22       | 34.38%  |
| 2048  | 10       | 15.63%  |
| 16384 | 8        | 12.5%   |
| 32768 | 1        | 1.56%   |
| 1024  | 1        | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 16       | 26.23%  |
| 1333  | 13       | 21.31%  |
| 2667  | 6        | 9.84%   |
| 2400  | 6        | 9.84%   |
| 3200  | 5        | 8.2%    |
| 2133  | 5        | 8.2%    |
| 2666  | 2        | 3.28%   |
| 400   | 2        | 3.28%   |
| 3000  | 1        | 1.64%   |
| 1200  | 1        | 1.64%   |
| 1066  | 1        | 1.64%   |
| 800   | 1        | 1.64%   |
| 667   | 1        | 1.64%   |
| 533   | 1        | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 2        | 66.67%  |
| Lexmark International | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Lexmark International SINDOH A603_A608 Print | 1        | 33.33%  |
| Brother HL-L2310D series                     | 1        | 33.33%  |
| Brother DCP-J100                             | 1        | 33.33%  |

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
| 1     | 28       | 47.46%  |
| 0     | 22       | 37.29%  |
| 2     | 8        | 13.56%  |
| 3     | 1        | 1.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 26       | 59.09%  |
| Net/wireless             | 8        | 18.18%  |
| Sound                    | 3        | 6.82%   |
| Firewire controller      | 3        | 6.82%   |
| Net/ethernet             | 2        | 4.55%   |
| Network                  | 1        | 2.27%   |
| Card reader              | 1        | 2.27%   |

