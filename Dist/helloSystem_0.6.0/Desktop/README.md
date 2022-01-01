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
| amd64 | 57       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 57       | 98.28%  |
| GNOME        | 1        | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 57       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 57       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 57       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 50       | 87.72%  |
| BIOS | 7        | 12.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 57       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 57       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 26.32%  |
| ASRock              | 8        | 14.04%  |
| Hewlett-Packard     | 6        | 10.53%  |
| Gigabyte Technology | 6        | 10.53%  |
| MSI                 | 4        | 7.02%   |
| Dell                | 3        | 5.26%   |
| Lenovo              | 2        | 3.51%   |
| Intel               | 2        | 3.51%   |
| T-bao               | 1        | 1.75%   |
| Shuttle             | 1        | 1.75%   |
| Sapphire            | 1        | 1.75%   |
| PCPartner           | 1        | 1.75%   |
| Medion              | 1        | 1.75%   |
| Itautec             | 1        | 1.75%   |
| Gateway             | 1        | 1.75%   |
| Fujitsu             | 1        | 1.75%   |
| Apple               | 1        | 1.75%   |
| Acer                | 1        | 1.75%   |
| Unknown             | 1        | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| T-bao MINI PC                      | 1        | 1.75%   |
| Shuttle SH61R                      | 1        | 1.75%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044  | 1        | 1.75%   |
| PCPartner DREAMSYS                 | 1        | 1.75%   |
| MSI MS-7C91                        | 1        | 1.75%   |
| MSI MS-7B93                        | 1        | 1.75%   |
| MSI MS-7A40                        | 1        | 1.75%   |
| MSI MS-7592                        | 1        | 1.75%   |
| Medion H61H2-LM3                   | 1        | 1.75%   |
| Lenovo ThinkCentre M83 10AHS35Q00  | 1        | 1.75%   |
| Lenovo ThinkCentre E73z 10BD004RRU | 1        | 1.75%   |
| Itautec Infoway ST-4344            | 1        | 1.75%   |
| Intel H81                          | 1        | 1.75%   |
| Intel H61                          | 1        | 1.75%   |
| HP [AH877AV] _ Currency Bulk P     | 1        | 1.75%   |
| HP ProLiant ML350 G5               | 1        | 1.75%   |
| HP EliteDesk 800 G2 SFF            | 1        | 1.75%   |
| HP Compaq Elite 8300 USDT          | 1        | 1.75%   |
| HP Compaq Elite 8300 SFF           | 1        | 1.75%   |
| HP 260-p026                        | 1        | 1.75%   |
| Gigabyte H410M S2 V2               | 1        | 1.75%   |
| Gigabyte H270M-DS3H                | 1        | 1.75%   |
| Gigabyte G41MT-S2                  | 1        | 1.75%   |
| Gigabyte F2A78M-DS2                | 1        | 1.75%   |
| Gigabyte B450 AORUS M              | 1        | 1.75%   |
| Gigabyte 990FXA-UD3                | 1        | 1.75%   |
| Gateway DX4840                     | 1        | 1.75%   |
| Fujitsu D3220-A1                   | 1        | 1.75%   |
| Dell OptiPlex 390                  | 1        | 1.75%   |
| Dell OptiPlex 3040                 | 1        | 1.75%   |
| Dell OptiPlex 3020M                | 1        | 1.75%   |
| ASUS TUF GAMING X570-PLUS          | 1        | 1.75%   |
| ASUS TUF B450M-PRO GAMING          | 1        | 1.75%   |
| ASUS TUF B360M-PLUS GAMING S       | 1        | 1.75%   |
| ASUS ROG STRIX X470-F GAMING       | 1        | 1.75%   |
| ASUS Pro WS X570-ACE               | 1        | 1.75%   |
| ASUS P7H55-M LX                    | 1        | 1.75%   |
| ASUS P5P43TD PRO                   | 1        | 1.75%   |
| ASUS M5A97 R2.0                    | 1        | 1.75%   |
| ASUS M5A78L/USB3                   | 1        | 1.75%   |
| ASUS M5A78L-M/USB3                 | 1        | 1.75%   |
| ASUS H110M-PLUS                    | 1        | 1.75%   |
| ASUS H110M-K                       | 1        | 1.75%   |
| ASUS exone Business 1203           | 1        | 1.75%   |
| ASUS CROSSHAIR V FORMULA-Z         | 1        | 1.75%   |
| ASUS All Series                    | 1        | 1.75%   |
| ASRock Z390 Pro4                   | 1        | 1.75%   |
| ASRock X570 Phantom Gaming 4       | 1        | 1.75%   |
| ASRock X370 Gaming X               | 1        | 1.75%   |
| ASRock X300M-STX                   | 1        | 1.75%   |
| ASRock B450 Gaming-ITX/ac          | 1        | 1.75%   |
| ASRock B365M-ITX/ac                | 1        | 1.75%   |
| ASRock AB350 Pro4                  | 1        | 1.75%   |
| ASRock A320M-DGS                   | 1        | 1.75%   |
| Apple MacPro5,1                    | 1        | 1.75%   |
| Acer Veriton M430                  | 1        | 1.75%   |
| Unknown                            | 1        | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 3        | 5.26%   |
| ASUS TUF            | 3        | 5.26%   |
| Lenovo ThinkCentre  | 2        | 3.51%   |
| HP Compaq           | 2        | 3.51%   |
| T-bao MINI          | 1        | 1.75%   |
| Shuttle SH61R       | 1        | 1.75%   |
| Sapphire EDGE-FT1M1 | 1        | 1.75%   |
| PCPartner DREAMSYS  | 1        | 1.75%   |
| MSI MS-7C91         | 1        | 1.75%   |
| MSI MS-7B93         | 1        | 1.75%   |
| MSI MS-7A40         | 1        | 1.75%   |
| MSI MS-7592         | 1        | 1.75%   |
| Medion H61H2-LM3    | 1        | 1.75%   |
| Itautec Infoway     | 1        | 1.75%   |
| Intel H81           | 1        | 1.75%   |
| Intel H61           | 1        | 1.75%   |
| HP [AH877AV]        | 1        | 1.75%   |
| HP ProLiant         | 1        | 1.75%   |
| HP EliteDesk        | 1        | 1.75%   |
| HP 260-p026         | 1        | 1.75%   |
| Gigabyte H410M      | 1        | 1.75%   |
| Gigabyte H270M-DS3H | 1        | 1.75%   |
| Gigabyte G41MT-S2   | 1        | 1.75%   |
| Gigabyte F2A78M-DS2 | 1        | 1.75%   |
| Gigabyte B450       | 1        | 1.75%   |
| Gigabyte 990FXA-UD3 | 1        | 1.75%   |
| Gateway DX4840      | 1        | 1.75%   |
| Fujitsu D3220-A1    | 1        | 1.75%   |
| ASUS ROG            | 1        | 1.75%   |
| ASUS Pro            | 1        | 1.75%   |
| ASUS P7H55-M        | 1        | 1.75%   |
| ASUS P5P43TD        | 1        | 1.75%   |
| ASUS M5A97          | 1        | 1.75%   |
| ASUS M5A78L-M       | 1        | 1.75%   |
| ASUS M5A78L         | 1        | 1.75%   |
| ASUS H110M-PLUS     | 1        | 1.75%   |
| ASUS H110M-K        | 1        | 1.75%   |
| ASUS exone          | 1        | 1.75%   |
| ASUS CROSSHAIR      | 1        | 1.75%   |
| ASUS All            | 1        | 1.75%   |
| ASRock Z390         | 1        | 1.75%   |
| ASRock X570         | 1        | 1.75%   |
| ASRock X370         | 1        | 1.75%   |
| ASRock X300M-STX    | 1        | 1.75%   |
| ASRock B450         | 1        | 1.75%   |
| ASRock B365M-ITX    | 1        | 1.75%   |
| ASRock AB350        | 1        | 1.75%   |
| ASRock A320M-DGS    | 1        | 1.75%   |
| Apple MacPro5       | 1        | 1.75%   |
| Acer Veriton        | 1        | 1.75%   |
| Unknown             | 1        | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 9        | 15.79%  |
| 2020 | 8        | 14.04%  |
| 2019 | 8        | 14.04%  |
| 2015 | 5        | 8.77%   |
| 2016 | 4        | 7.02%   |
| 2012 | 4        | 7.02%   |
| 2010 | 4        | 7.02%   |
| 2018 | 3        | 5.26%   |
| 2017 | 3        | 5.26%   |
| 2013 | 3        | 5.26%   |
| 2011 | 3        | 5.26%   |
| 2014 | 1        | 1.75%   |
| 2009 | 1        | 1.75%   |
| 2007 | 1        | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 57       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 57       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 21       | 36.84%  |
| 8.01-16.0   | 15       | 26.32%  |
| 4.01-8.0    | 9        | 15.79%  |
| 32.01-64.0  | 9        | 15.79%  |
| 64.01-256.0 | 3        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 26       | 45.61%  |
| 0.01-0.5 | 20       | 35.09%  |
| 1.01-2.0 | 10       | 17.54%  |
| 3.01-4.0 | 1        | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 44.07%  |
| 2      | 16       | 27.12%  |
| 3      | 9        | 15.25%  |
| 4      | 7        | 11.86%  |
| 5      | 1        | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 63.16%  |
| Yes       | 21       | 36.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 56       | 98.25%  |
| No        | 1        | 1.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 66.67%  |
| Yes       | 19       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 77.19%  |
| Yes       | 13       | 22.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 8        | 14.04%  |
| Russia      | 6        | 10.53%  |
| Germany     | 6        | 10.53%  |
| Brazil      | 4        | 7.02%   |
| Poland      | 3        | 5.26%   |
| Italy       | 3        | 5.26%   |
| Australia   | 3        | 5.26%   |
| Ukraine     | 2        | 3.51%   |
| Spain       | 2        | 3.51%   |
| India       | 2        | 3.51%   |
| China       | 2        | 3.51%   |
| UK          | 1        | 1.75%   |
| Turkey      | 1        | 1.75%   |
| Thailand    | 1        | 1.75%   |
| Taiwan      | 1        | 1.75%   |
| Switzerland | 1        | 1.75%   |
| South Korea | 1        | 1.75%   |
| Netherlands | 1        | 1.75%   |
| Mexico      | 1        | 1.75%   |
| Hungary     | 1        | 1.75%   |
| Hong Kong   | 1        | 1.75%   |
| Guatemala   | 1        | 1.75%   |
| Finland     | 1        | 1.75%   |
| Denmark     | 1        | 1.75%   |
| Chile       | 1        | 1.75%   |
| Canada      | 1        | 1.75%   |
| Bulgaria    | 1        | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Marlborough       | 2        | 3.51%   |
| Hobart            | 2        | 3.51%   |
| Yekaterinburg     | 1        | 1.75%   |
| Xiamen            | 1        | 1.75%   |
| Wolgast           | 1        | 1.75%   |
| Warrenton         | 1        | 1.75%   |
| Voronezh          | 1        | 1.75%   |
| Tula de Allende   | 1        | 1.75%   |
| Torre del Mar     | 1        | 1.75%   |
| Tampa             | 1        | 1.75%   |
| Stuttgart         | 1        | 1.75%   |
| Stralsund         | 1        | 1.75%   |
| Sofia             | 1        | 1.75%   |
| Siedlce           | 1        | 1.75%   |
| Shepetivka        | 1        | 1.75%   |
| Santiago          | 1        | 1.75%   |
| Rzesz??w          | 1        | 1.75%   |
| Rostov-on-Don     | 1        | 1.75%   |
| Riehen            | 1        | 1.75%   |
| Richmond          | 1        | 1.75%   |
| Reriutaba         | 1        | 1.75%   |
| Qingdao           | 1        | 1.75%   |
| Pistoia           | 1        | 1.75%   |
| Old Town          | 1        | 1.75%   |
| Nieuwegein        | 1        | 1.75%   |
| Newtownabbey      | 1        | 1.75%   |
| Munich            | 1        | 1.75%   |
| Moscow            | 1        | 1.75%   |
| Manaus            | 1        | 1.75%   |
| Kyiv              | 1        | 1.75%   |
| Kosekoy           | 1        | 1.75%   |
| Kochi             | 1        | 1.75%   |
| Kirkkonummi       | 1        | 1.75%   |
| Katowice          | 1        | 1.75%   |
| Irkutsk           | 1        | 1.75%   |
| Inhapim           | 1        | 1.75%   |
| Ilh?©us           | 1        | 1.75%   |
| Idaho Falls       | 1        | 1.75%   |
| Hsinchu           | 1        | 1.75%   |
| Hong Kong         | 1        | 1.75%   |
| Hicksville        | 1        | 1.75%   |
| Heidelberg        | 1        | 1.75%   |
| Gy?‘r             | 1        | 1.75%   |
| Gwangyang         | 1        | 1.75%   |
| Guatemala City    | 1        | 1.75%   |
| Grottazzolina     | 1        | 1.75%   |
| Fuente Carreteros | 1        | 1.75%   |
| Frederiksberg     | 1        | 1.75%   |
| Filderstadt       | 1        | 1.75%   |
| Ernakulam         | 1        | 1.75%   |
| Chelyabinsk       | 1        | 1.75%   |
| Brisbane          | 1        | 1.75%   |
| Bari              | 1        | 1.75%   |
| Bangkok           | 1        | 1.75%   |
| Anaheim           | 1        | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 29     | 25.53%  |
| Seagate             | 16       | 20     | 17.02%  |
| Samsung Electronics | 13       | 18     | 13.83%  |
| Hitachi             | 5        | 7      | 5.32%   |
| Crucial             | 5        | 8      | 5.32%   |
| Toshiba             | 4        | 6      | 4.26%   |
| Kingston            | 4        | 7      | 4.26%   |
| SanDisk             | 3        | 3      | 3.19%   |
| Smartbuy            | 2        | 2      | 2.13%   |
| Intel               | 2        | 2      | 2.13%   |
| China               | 2        | 2      | 2.13%   |
| A-DATA Technology   | 2        | 4      | 2.13%   |
| Verbatim            | 1        | 1      | 1.06%   |
| SPCC                | 1        | 1      | 1.06%   |
| Silicon Motion      | 1        | 1      | 1.06%   |
| PNY                 | 1        | 1      | 1.06%   |
| PLEXTOR             | 1        | 1      | 1.06%   |
| LITEONIT            | 1        | 1      | 1.06%   |
| KingSpec            | 1        | 1      | 1.06%   |
| Hewlett-Packard     | 1        | 1      | 1.06%   |
| GOODRAM             | 1        | 1      | 1.06%   |
| Gigabyte Technology | 1        | 1      | 1.06%   |
| Corsair             | 1        | 1      | 1.06%   |
| Apacer              | 1        | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB           | 3        | 2.7%    |
| WDC WDS100T2B0C-00PXH0 1TB          | 2        | 1.8%    |
| WDC WD3200BPVT-22JJ5T0 320GB        | 2        | 1.8%    |
| Toshiba DT01ACA100 1TB              | 2        | 1.8%    |
| Seagate ST3500312CS 500GB           | 2        | 1.8%    |
| SanDisk SDSSDA240G 240GB            | 2        | 1.8%    |
| Samsung SSD 850 EVO 250GB           | 2        | 1.8%    |
| Samsung HD322HJ 320GB               | 2        | 1.8%    |
| China SATA SSD 120GB                | 2        | 1.8%    |
| WDC WDS250G2X0C-00L350 250GB        | 1        | 0.9%    |
| WDC WD800JD-00LSA0 80GB             | 1        | 0.9%    |
| WDC WD5000LPCX-00VHAT0 500GB        | 1        | 0.9%    |
| WDC WD5000AAVS-00ZTB0 500GB         | 1        | 0.9%    |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 0.9%    |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 0.9%    |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 0.9%    |
| WDC WD40EZRZ-22GXCB0 4TB            | 1        | 0.9%    |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 0.9%    |
| WDC WD30EZRZ-00WN9B0 3TB            | 1        | 0.9%    |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1        | 0.9%    |
| WDC WD2500JD-75HBB0 250GB           | 1        | 0.9%    |
| WDC WD2500BEVS-22UST0 250GB         | 1        | 0.9%    |
| WDC WD20SMZW-11YFCS0 2TB            | 1        | 0.9%    |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 0.9%    |
| WDC WD1600AAJS-00WAA0 160GB         | 1        | 0.9%    |
| WDC WD1600AAJS-00V4A0 160GB         | 1        | 0.9%    |
| WDC WD10SPZX-22Z10T0 1TB            | 1        | 0.9%    |
| WDC WD10JMVW-11AJGS0 1TB            | 1        | 0.9%    |
| WDC WD10EZRX-00A8LB0 1TB            | 1        | 0.9%    |
| WDC WD10EZEX-75WN4A1 1TB            | 1        | 0.9%    |
| WDC WD10EFRX-68FYTN0 1TB            | 1        | 0.9%    |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 0.9%    |
| Verbatim Vi550 S3 SSD 128GB         | 1        | 0.9%    |
| Toshiba MQ01UBD100 1TB              | 1        | 0.9%    |
| Toshiba HDWD110 1TB                 | 1        | 0.9%    |
| Toshiba DT01ACA050 500GB            | 1        | 0.9%    |
| SPCC M.2 PCIe SSD 256GB             | 1        | 0.9%    |
| Smartbuy SSD 240GB                  | 1        | 0.9%    |
| Smartbuy SSD 120GB                  | 1        | 0.9%    |
| Silicon Motion ASint AS806 128GB    | 1        | 0.9%    |
| Seagate ST9320325AS 320GB           | 1        | 0.9%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 0.9%    |
| Seagate ST500LM000-1EJ162 500GB     | 1        | 0.9%    |
| Seagate ST500DM002-1SB10A 500GB     | 1        | 0.9%    |
| Seagate ST500DM002-1BD142 500GB     | 1        | 0.9%    |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 0.9%    |
| Seagate ST3500413AS 500GB           | 1        | 0.9%    |
| Seagate ST3250318AS 250GB           | 1        | 0.9%    |
| Seagate ST3160813AS 160GB           | 1        | 0.9%    |
| Seagate ST31000524AS 1TB            | 1        | 0.9%    |
| Seagate ST3000DM001-1CH166 3TB      | 1        | 0.9%    |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 0.9%    |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 0.9%    |
| Seagate ST1000LM048-2E7172 1TB      | 1        | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB      | 1        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 0.9%    |
| SanDisk SDSSDA120G 120GB            | 1        | 0.9%    |
| Samsung SSD 970 EVO Plus 500GB      | 1        | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 26     | 42.31%  |
| Seagate             | 16       | 20     | 30.77%  |
| Hitachi             | 5        | 7      | 9.62%   |
| Toshiba             | 4        | 6      | 7.69%   |
| Samsung Electronics | 4        | 6      | 7.69%   |
| Hewlett-Packard     | 1        | 1      | 1.92%   |

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
| HDD  | 38       | 66     | 48.72%  |
| SSD  | 28       | 40     | 35.9%   |
| NVMe | 12       | 14     | 15.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 51       | 106    | 80.95%  |
| NVMe | 12       | 14     | 19.05%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 45       | 67     | 58.44%  |
| 0.51-1.0   | 20       | 24     | 25.97%  |
| 1.01-2.0   | 6        | 7      | 7.79%   |
| 2.01-3.0   | 4        | 6      | 5.19%   |
| 3.01-4.0   | 2        | 2      | 2.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 36       | 63.16%  |
| 101-250    | 13       | 22.81%  |
| 251-500    | 6        | 10.53%  |
| 21-50      | 1        | 1.75%   |
| 51-100     | 1        | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 57       | 100%    |

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
| Works    | 52       | 101    | 76.47%  |
| Malfunc  | 15       | 18     | 22.06%  |
| Detected | 1        | 1      | 1.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 34       | 46.58%  |
| AMD                        | 22       | 30.14%  |
| Sandisk                    | 3        | 4.11%   |
| Samsung Electronics        | 3        | 4.11%   |
| Phison Electronics         | 3        | 4.11%   |
| ASMedia Technology         | 3        | 4.11%   |
| Silicon Motion             | 1        | 1.37%   |
| Lite-On IT Corp. / Plextor | 1        | 1.37%   |
| JMicron Technology         | 1        | 1.37%   |
| Hewlett-Packard            | 1        | 1.37%   |
| ADATA Technology           | 1        | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 14.77%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 5.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 5.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 5.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 5.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.41%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.41%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.14%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.14%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.14%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.14%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.14%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]                       | 1        | 1.14%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.14%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.14%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.14%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.14%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.14%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.14%   |
| HP Smart Array E200i (SAS Controller)                                                   | 1        | 1.14%   |
| HP Smart Array Controller                                                               | 1        | 1.14%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.14%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 1.14%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.14%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.14%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 44       | 63.77%  |
| NVMe | 12       | 17.39%  |
| IDE  | 12       | 17.39%  |
| RAID | 1        | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 34       | 59.65%  |
| AMD    | 23       | 40.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor           | 3        | 5.26%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 3.51%   |
| Intel Core i3-6100T CPU @ 3.20GHz             | 2        | 3.51%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2        | 3.51%   |
| AMD FX-8350 Eight-Core Processor              | 2        | 3.51%   |
| Intel Xeon CPU W3680 @ 3.33GHz                | 1        | 1.75%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1        | 1.75%   |
| Intel Xeon                                    | 1        | 1.75%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 1.75%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1        | 1.75%   |
| Intel Genuine CPU 2160 @ 1.80GHz              | 1        | 1.75%   |
| Intel Core i7-9700F CPU @ 3.00GHz             | 1        | 1.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1        | 1.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 1.75%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1        | 1.75%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 1.75%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1        | 1.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 1.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1        | 1.75%   |
| Intel Core i5-4570S CPU @ 2.90GHz             | 1        | 1.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 1.75%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1        | 1.75%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 1        | 1.75%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 1        | 1.75%   |
| Intel Core i5 CPU 661 @ 3.33GHz               | 1        | 1.75%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1        | 1.75%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 1        | 1.75%   |
| Intel Core i3-4150T CPU @ 3.00GHz             | 1        | 1.75%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1        | 1.75%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 1        | 1.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 1.75%   |
| Intel Core i3-2120 CPU @ 3.30GH               | 1        | 1.75%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz         | 1        | 1.75%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1        | 1.75%   |
| Intel Core 2 Duo CPU                          | 1        | 1.75%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1        | 1.75%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1        | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1        | 1.75%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1        | 1.75%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 1        | 1.75%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 1        | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1        | 1.75%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1        | 1.75%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 1        | 1.75%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 1        | 1.75%   |
| AMD Phenom II X6 1045T Processor              | 1        | 1.75%   |
| AMD Phenom II X4 965 Processor                | 1        | 1.75%   |
| AMD FX-6300 Six-Core Processor                | 1        | 1.75%   |
| AMD FX-6100 Six-Core Processor                | 1        | 1.75%   |
| AMD E-450 APU with Radeon HD Graphics         | 1        | 1.75%   |
| AMD A4-7300 APU with Radeon HD Graphics       | 1        | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 10       | 17.54%  |
| Intel Core i3           | 9        | 15.79%  |
| Intel Core i7           | 6        | 10.53%  |
| AMD Ryzen 5             | 5        | 8.77%   |
| AMD Ryzen 7             | 4        | 7.02%   |
| AMD FX                  | 4        | 7.02%   |
| Intel Xeon              | 3        | 5.26%   |
| AMD Ryzen 9             | 3        | 5.26%   |
| Intel Core 2 Duo        | 2        | 3.51%   |
| AMD Ryzen 3             | 2        | 3.51%   |
| Intel Pentium Dual-Core | 1        | 1.75%   |
| Intel Pentium           | 1        | 1.75%   |
| Intel Genuine           | 1        | 1.75%   |
| Intel Core 2 Quad       | 1        | 1.75%   |
| AMD Ryzen 5 PRO         | 1        | 1.75%   |
| AMD Phenom II X6        | 1        | 1.75%   |
| AMD Phenom II X4        | 1        | 1.75%   |
| AMD E                   | 1        | 1.75%   |
| AMD A4                  | 1        | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 17       | 29.82%  |
| 2       | 15       | 26.32%  |
| 12      | 6        | 10.53%  |
| 6       | 6        | 10.53%  |
| 8       | 5        | 8.77%   |
| 16      | 4        | 7.02%   |
| 24      | 3        | 5.26%   |
| Unknown | 1        | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 96.49%  |
| 2      | 2        | 3.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 40       | 70.18%  |
| 2       | 16       | 28.07%  |
| Unknown | 1        | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 7        | 12.28%  |
| Haswell     | 7        | 12.28%  |
| Zen 2       | 6        | 10.53%  |
| Zen         | 5        | 8.77%   |
| SandyBridge | 5        | 8.77%   |
| Penryn      | 5        | 8.77%   |
| Piledriver  | 4        | 7.02%   |
| Zen+        | 3        | 5.26%   |
| Skylake     | 3        | 5.26%   |
| Westmere    | 2        | 3.51%   |
| K10         | 2        | 3.51%   |
| IvyBridge   | 2        | 3.51%   |
| Zen 3       | 1        | 1.75%   |
| Nehalem     | 1        | 1.75%   |
| Core        | 1        | 1.75%   |
| CometLake   | 1        | 1.75%   |
| Bulldozer   | 1        | 1.75%   |
| Bobcat      | 1        | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 24       | 40%     |
| AMD    | 20       | 33.33%  |
| Intel  | 16       | 26.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 8.33%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 6.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 3.33%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.33%   |
| Intel HD Graphics 630                                                       | 2        | 3.33%   |
| Intel HD Graphics 530                                                       | 2        | 3.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.33%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 2        | 3.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 3.33%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.67%   |
| Nvidia GT215 [GeForce GT 220]                                               | 1        | 1.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1        | 1.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.67%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.67%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.67%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1        | 1.67%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.67%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.67%   |
| Nvidia G92 [GeForce GT 330]                                                 | 1        | 1.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.67%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.67%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.67%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.67%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.67%   |
| AMD Richland [Radeon HD 8470D]                                              | 1        | 1.67%   |
| AMD Renoir                                                                  | 1        | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.67%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.67%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 22       | 38.6%   |
| 1 x AMD        | 19       | 33.33%  |
| 1 x Intel      | 12       | 21.05%  |
| Intel + Nvidia | 2        | 3.51%   |
| 2 x Intel      | 1        | 1.75%   |
| Intel + AMD    | 1        | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 78.95%  |
| Proprietary | 11       | 19.3%   |
| Unknown     | 1        | 1.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 54.39%  |
| 1.01-2.0   | 7        | 12.28%  |
| 3.01-4.0   | 6        | 10.53%  |
| 0.01-0.5   | 5        | 8.77%   |
| 7.01-8.0   | 3        | 5.26%   |
| 5.01-6.0   | 3        | 5.26%   |
| 0.51-1.0   | 2        | 3.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 14.71%  |
| Hewlett-Packard      | 4        | 11.76%  |
| Iiyama               | 3        | 8.82%   |
| Philips              | 2        | 5.88%   |
| Lenovo               | 2        | 5.88%   |
| Goldstar             | 2        | 5.88%   |
| Dell                 | 2        | 5.88%   |
| BenQ                 | 2        | 5.88%   |
| Ancor Communications | 2        | 5.88%   |
| Acer                 | 2        | 5.88%   |
| Vizio                | 1        | 2.94%   |
| ViewSonic            | 1        | 2.94%   |
| Medion               | 1        | 2.94%   |
| Haier                | 1        | 2.94%   |
| Eizo                 | 1        | 2.94%   |
| ASUSTek Computer     | 1        | 2.94%   |
| AOC                  | 1        | 2.94%   |
| ALP                  | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 2        | 5.88%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch               | 1        | 2.94%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch           | 1        | 2.94%   |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch    | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                     | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 1        | 2.94%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch  | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1        | 2.94%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 2.94%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 1        | 2.94%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                  | 1        | 2.94%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch               | 1        | 2.94%   |
| Lenovo LEN-E73Z-D LEN00A1 1600x900 440x240mm 19.7-inch               | 1        | 2.94%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                | 1        | 2.94%   |
| Hewlett-Packard ZR22w HWP2867 1920x1080 480x270mm 21.7-inch          | 1        | 2.94%   |
| Hewlett-Packard E243m HPN3465 1920x1080 530x300mm 24.0-inch          | 1        | 2.94%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x290mm 23.1-inch           | 1        | 2.94%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch            | 1        | 2.94%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch             | 1        | 2.94%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 2.94%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                | 1        | 2.94%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                   | 1        | 2.94%   |
| Dell E228WFP DELD014 1680x1050 470x300mm 22.0-inch                   | 1        | 2.94%   |
| Dell 1708FP DEL4024 1280x1024 340x270mm 17.1-inch                    | 1        | 2.94%   |
| BenQ LCD Monitor BNQ7725 1920x1080 480x270mm 21.7-inch               | 1        | 2.94%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 1        | 2.94%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch         | 1        | 2.94%   |
| AOC LE19W037 AOC1907 1360x768 410x230mm 18.5-inch                    | 1        | 2.94%   |
| Ancor Communications MW221 ACI22B1 1680x1050 470x300mm 22.0-inch     | 1        | 2.94%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch     | 1        | 2.94%   |
| ALP 2476 IPS ALP2476 1920x1080 530x300mm 24.0-inch                   | 1        | 2.94%   |
| Acer ET430K ACR0558 3840x2160 940x530mm 42.5-inch                    | 1        | 2.94%   |
| Acer B223W ACR0018 1680x1050 470x300mm 22.0-inch                     | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 50%     |
| 1680x1050 (WSXGA+) | 3        | 8.82%   |
| 1366x768 (WXGA)    | 3        | 8.82%   |
| 1920x1200 (WUXGA)  | 2        | 5.88%   |
| 1600x900 (HD+)     | 2        | 5.88%   |
| 1024x768 (XGA)     | 2        | 5.88%   |
| 3840x2160 (4K)     | 1        | 2.94%   |
| 2560x1440 (QHD)    | 1        | 2.94%   |
| 1920x540           | 1        | 2.94%   |
| 1360x768           | 1        | 2.94%   |
| 1280x1024 (SXGA)   | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 8        | 23.53%  |
| 24      | 5        | 14.71%  |
| 21      | 5        | 14.71%  |
| 18      | 4        | 11.76%  |
| 22      | 3        | 8.82%   |
| 19      | 2        | 5.88%   |
| 14      | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 42      | 1        | 2.94%   |
| 27      | 1        | 2.94%   |
| 17      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 41.18%  |
| 401-500     | 14       | 41.18%  |
| 201-300     | 2        | 5.88%   |
| Unknown     | 2        | 5.88%   |
| 301-350     | 1        | 2.94%   |
| 901-1000    | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 26       | 76.47%  |
| 16/10 | 5        | 14.71%  |
| 4/3   | 2        | 5.88%   |
| 5/4   | 1        | 2.94%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 55.88%  |
| 141-150        | 5        | 14.71%  |
| 251-300        | 2        | 5.88%   |
| 151-200        | 2        | 5.88%   |
| 101-110        | 2        | 5.88%   |
| Unknown        | 2        | 5.88%   |
| 301-350        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 76.47%  |
| 101-120 | 6        | 17.65%  |
| Unknown | 2        | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 57.89%  |
| 0     | 23       | 40.35%  |
| 2     | 1        | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 35       | 46.67%  |
| Intel                    | 21       | 28%     |
| Broadcom                 | 7        | 9.33%   |
| Qualcomm Atheros         | 4        | 5.33%   |
| Ralink Technology        | 2        | 2.67%   |
| Ralink                   | 1        | 1.33%   |
| Marvell Technology Group | 1        | 1.33%   |
| IMC Networks             | 1        | 1.33%   |
| Belkin Components        | 1        | 1.33%   |
| ASUSTek Computer         | 1        | 1.33%   |
| Aquantia                 | 1        | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30       | 37.04%  |
| Intel I211 Gigabit Network Connection                                          | 6        | 7.41%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 2.47%   |
| Intel Ethernet Connection I217-V                                               | 2        | 2.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2        | 2.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.23%   |
| Ralink RT3072 Wireless Adapter                                                 | 1        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 1.23%   |
| Ralink RT2561/RT61 rev B 802.11g                                               | 1        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 1.23%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 1.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.23%   |
| Intel Wireless 7265                                                            | 1        | 1.23%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.23%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.23%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.23%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.23%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 1.23%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.23%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter    | 1        | 1.23%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 1.23%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 1.23%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 1.23%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 1        | 1.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 1        | 1.23%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]             | 1        | 1.23%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                      | 1        | 1.23%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1        | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 23.81%  |
| Realtek Semiconductor | 4        | 19.05%  |
| Broadcom              | 4        | 19.05%  |
| Ralink Technology     | 2        | 9.52%   |
| Qualcomm Atheros      | 2        | 9.52%   |
| Ralink                | 1        | 4.76%   |
| IMC Networks          | 1        | 4.76%   |
| Belkin Components     | 1        | 4.76%   |
| ASUSTek Computer      | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2        | 9.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 2        | 9.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1        | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 4.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 1        | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 4.55%   |
| Ralink RT3072 Wireless Adapter                                              | 1        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                             | 1        | 4.55%   |
| Ralink RT2561/RT61 rev B 802.11g                                            | 1        | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 4.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1        | 4.55%   |
| Intel Wireless 7265                                                         | 1        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                         | 1        | 4.55%   |
| Intel Centrino Wireless-N 105                                               | 1        | 4.55%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 4.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                          | 1        | 4.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1        | 4.55%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]          | 1        | 4.55%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 32       | 55.17%  |
| Intel                    | 19       | 32.76%  |
| Broadcom                 | 3        | 5.17%   |
| Qualcomm Atheros         | 2        | 3.45%   |
| Marvell Technology Group | 1        | 1.72%   |
| Aquantia                 | 1        | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30       | 51.72%  |
| Intel I211 Gigabit Network Connection                                          | 6        | 10.34%  |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 5.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 3.45%   |
| Intel Ethernet Connection I217-V                                               | 2        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2        | 3.45%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 1.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 1.72%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.72%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.72%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.72%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 1.72%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.72%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 1.72%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 1.72%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 1.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 73.68%  |
| WiFi     | 19       | 25%     |
| Unknown  | 1        | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 81.16%  |
| WiFi     | 13       | 18.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 70.18%  |
| 2     | 15       | 26.32%  |
| 3     | 2        | 3.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 96.55%  |
| Yes  | 2        | 3.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 30.77%  |
| Apple                   | 3        | 23.08%  |
| Realtek Semiconductor   | 2        | 15.38%  |
| Foxconn / Hon Hai       | 1        | 7.69%   |
| Cambridge Silicon Radio | 1        | 7.69%   |
| Broadcom                | 1        | 7.69%   |
| ASUSTek Computer        | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 15.38%  |
| Apple Apple Broadcom Built-in Bluetooth             | 2        | 15.38%  |
| Realtek  Bluetooth Adapter                          | 1        | 7.69%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| Intel AX200 Bluetooth                               | 1        | 7.69%   |
| Foxconn / Hon Hai Broadcom Bluetooth 4.0 USB        | 1        | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 7.69%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 7.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 32       | 33.68%  |
| AMD                     | 28       | 29.47%  |
| Nvidia                  | 22       | 23.16%  |
| C-Media Electronics     | 5        | 5.26%   |
| Texas Instruments       | 2        | 2.11%   |
| Logitech                | 2        | 2.11%   |
| Plantronics             | 1        | 1.05%   |
| Hewlett-Packard         | 1        | 1.05%   |
| Creative Labs           | 1        | 1.05%   |
| BEHRINGER International | 1        | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 6.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 6.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 5.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 5.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 4.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 4.5%    |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 3.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 2.7%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3        | 2.7%    |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.8%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.8%    |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.8%    |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.8%    |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.8%    |
| Plantronics Plantronics Blackwire 325.1                                    | 1        | 0.9%    |
| Nvidia High Definition Audio Controller                                    | 1        | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.9%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.9%    |
| Logitech HD Webcam C910                                                    | 1        | 0.9%    |
| Logitech HD Webcam C510                                                    | 1        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.9%    |
| Hewlett-Packard E243m                                                      | 1        | 0.9%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 0.9%    |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 0.9%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.9%    |
| C-Media Electronics Audio Adapter                                          | 1        | 0.9%    |
| BEHRINGER International UMC202HD 192k                                      | 1        | 0.9%    |
| AMD Wrestler HDMI Audio                                                    | 1        | 0.9%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 0.9%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 0.9%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 0.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 0.9%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 1        | 0.9%    |
| AMD FCH Azalia Controller                                                  | 1        | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 12       | 18.18%  |
| Samsung Electronics | 9        | 13.64%  |
| Crucial             | 8        | 12.12%  |
| Unknown             | 7        | 10.61%  |
| SK Hynix            | 4        | 6.06%   |
| G.Skill             | 4        | 6.06%   |
| Corsair             | 4        | 6.06%   |
| Team                | 3        | 4.55%   |
| Nanya Technology    | 3        | 4.55%   |
| Unknown             | 3        | 4.55%   |
| Transcend           | 2        | 3.03%   |
| Micron Technology   | 2        | 3.03%   |
| A-DATA Technology   | 2        | 3.03%   |
| Ramaxel Technology  | 1        | 1.52%   |
| Patriot             | 1        | 1.52%   |
| Hikvision           | 1        | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 3        | 4.41%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s     | 2        | 2.94%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s   | 2        | 2.94%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s    | 2        | 2.94%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 1        | 1.47%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s             | 1        | 1.47%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                | 1        | 1.47%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 1.47%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 1.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.47%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 1.47%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 1.47%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s       | 1        | 1.47%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s      | 1        | 1.47%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.47%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.47%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 1.47%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                | 1        | 1.47%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s              | 1        | 1.47%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 1.47%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1600MT/s         | 1        | 1.47%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s     | 1        | 1.47%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1067MT/s     | 1        | 1.47%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.47%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 1.47%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s   | 1        | 1.47%   |
| Patriot RAM Module 2GB DIMM DDR2 533MT/s                | 1        | 1.47%   |
| Nanya RAM NT4GC72B8PB0NF-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.47%   |
| Nanya RAM M2F4G64CC88D7N-DI 4GB DIMM DDR3 1600MT/s      | 1        | 1.47%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.47%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s      | 1        | 1.47%   |
| Micron RAM 4ATF51264HZ-2G6B1 4GB SODIMM DDR4 1200MT/s   | 1        | 1.47%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s   | 1        | 1.47%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3200MT/s   | 1        | 1.47%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 1        | 1.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s       | 1        | 1.47%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 1        | 1.47%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s | 1        | 1.47%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s       | 1        | 1.47%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s  | 1        | 1.47%   |
| Kingston RAM 99U5665-001.A00G 4GB DIMM DDR4 2400MT/s    | 1        | 1.47%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.47%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 1.47%   |
| Kingston RAM 9905734-180.A00G 16GB DIMM DDR4 2666MT/s   | 1        | 1.47%   |
| Kingston RAM 9905665-020.A00G 4GB DIMM DDR4 2667MT/s    | 1        | 1.47%   |
| Hikvision RAM HKED3041AAB3H3HA1 4GB DIMM DDR3 1600MT/s  | 1        | 1.47%   |
| G.Skill RAM F4-3866C18-8GTZR 8GB DIMM DDR4 2133MT/s     | 1        | 1.47%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 1        | 1.47%   |
| G.Skill RAM F4-2400C15-8GFT 8GB DIMM DDR4 2400MT/s      | 1        | 1.47%   |
| G.Skill RAM F4-2133C15-16GIS 16GB DIMM DDR4 2133MT/s    | 1        | 1.47%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s             | 1        | 1.47%   |
| Crucial RAM CT4G4DFS824A.C8FF 4GB DIMM DDR4 2667MT/s    | 1        | 1.47%   |
| Crucial RAM CT4G4DFS8213.C8FBD1 4GB DIMM DDR4 2133MT/s  | 1        | 1.47%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s | 1        | 1.47%   |
| Crucial RAM BL8G32C16U4BL.M8FE 8GB DIMM DDR4 2667MT/s   | 1        | 1.47%   |
| Crucial RAM BL8G30C15U4B.M8FE 8GB DIMM DDR4 2666MT/s    | 1        | 1.47%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s    | 1        | 1.47%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 2133MT/s  | 1        | 1.47%   |
| Corsair RAM CMV4GX3M1A133 4GB DIMM DDR3 1333MT/s        | 1        | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 26       | 45.61%  |
| DDR3    | 23       | 40.35%  |
| Unknown | 4        | 7.02%   |
| DDR2    | 2        | 3.51%   |
| SDRAM   | 1        | 1.75%   |
| DDR     | 1        | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 51       | 89.47%  |
| SODIMM  | 5        | 8.77%   |
| FB-DIMM | 1        | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 35.48%  |
| 4096  | 21       | 33.87%  |
| 2048  | 9        | 14.52%  |
| 16384 | 8        | 12.9%   |
| 32768 | 1        | 1.61%   |
| 1024  | 1        | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 15       | 25.42%  |
| 1333  | 12       | 20.34%  |
| 2667  | 6        | 10.17%  |
| 2400  | 6        | 10.17%  |
| 3200  | 5        | 8.47%   |
| 2133  | 5        | 8.47%   |
| 2666  | 2        | 3.39%   |
| 400   | 2        | 3.39%   |
| 3000  | 1        | 1.69%   |
| 1200  | 1        | 1.69%   |
| 1066  | 1        | 1.69%   |
| 800   | 1        | 1.69%   |
| 667   | 1        | 1.69%   |
| 533   | 1        | 1.69%   |

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
| 1     | 26       | 45.61%  |
| 0     | 22       | 38.6%   |
| 2     | 8        | 14.04%  |
| 3     | 1        | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 25       | 59.52%  |
| Net/wireless             | 8        | 19.05%  |
| Sound                    | 3        | 7.14%   |
| Net/ethernet             | 2        | 4.76%   |
| Firewire controller      | 2        | 4.76%   |
| Network                  | 1        | 2.38%   |
| Card reader              | 1        | 2.38%   |

