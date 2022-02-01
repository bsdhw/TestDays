helloSystem 0.7.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

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

| Vendor   | Model                       | Probe                                                     | Date         |
|----------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo   | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| HP       | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Apple    | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung  | N150P/N210P/N220P           | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Apple    | MacBook5,2                  | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer     | Aspire 5930                 | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| ASUSTek  | ASUS TUF Gaming A15 FA50... | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| Dell     | Latitude 7280               | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| Lenovo   | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI      | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP       | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| HP       | Pavilion Gaming Laptop 1... | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Acer     | Aspire ES1-311              | [83addddaa5](https://bsd-hardware.info/?probe=83addddaa5) | Jan 22, 2022 |
| Dell     | Latitude E6540              | [529768f8c8](https://bsd-hardware.info/?probe=529768f8c8) | Jan 21, 2022 |
| HP       | EliteBook 2560p             | [4d04ececbb](https://bsd-hardware.info/?probe=4d04ececbb) | Jan 19, 2022 |
| Lenovo   | Legion Y540-15IRH 81SX      | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| Acer     | V5-131                      | [ff427cb0c9](https://bsd-hardware.info/?probe=ff427cb0c9) | Jan 18, 2022 |
| Gateway  | NE56R                       | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Lenovo   | ThinkPad T410 2522E38       | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Dell     | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Lenovo   | ThinkPad T440 20B7000PHV    | [9584ae69fa](https://bsd-hardware.info/?probe=9584ae69fa) | Jan 16, 2022 |
| Lenovo   | ThinkPad R61 8935WCS        | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| Lenovo   | ThinkPad X220 Tablet 429... | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| Acer     | V5-131                      | [e4d0f66ff8](https://bsd-hardware.info/?probe=e4d0f66ff8) | Jan 13, 2022 |
| Acer     | Aspire ES1-533              | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Acer     | Aspire E5-476G              | [2a8624ee35](https://bsd-hardware.info/?probe=2a8624ee35) | Jan 10, 2022 |
| Lenovo   | ThinkPad L450 20DSS1S402    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Dell     | Latitude E6530              | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell     | Inspiron 3505               | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell     | Inspiron 3505               | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo   | ThinkPad E15 20RD0011MX     | [0fa4700d17](https://bsd-hardware.info/?probe=0fa4700d17) | Jan 07, 2022 |
| HP       | Laptop 14-dk0xxx            | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| Notebook | N15_17RD                    | [47c30b962d](https://bsd-hardware.info/?probe=47c30b962d) | Jan 05, 2022 |
| Lenovo   | ThinkPad L450 20DSS1S402    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| Dell     | Latitude 7380               | [590b374836](https://bsd-hardware.info/?probe=590b374836) | Jan 02, 2022 |
| Dell     | Latitude E6540              | [f5a43a9f8b](https://bsd-hardware.info/?probe=f5a43a9f8b) | Jan 02, 2022 |
| Lenovo   | ThinkPad X220 4293AF4       | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| Dell     | Latitude E6540              | [97d152656e](https://bsd-hardware.info/?probe=97d152656e) | Dec 31, 2021 |
| HP       | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Acer     | Aspire 5742G                | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| ASUSTek  | S550CA                      | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Lenovo   | ThinkPad E580 20KS005BRI    | [b533989df5](https://bsd-hardware.info/?probe=b533989df5) | Dec 29, 2021 |
| Dell     | Inspiron 3521               | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Lenovo   | ThinkPad T460 20FMS75800    | [5f17e74f2f](https://bsd-hardware.info/?probe=5f17e74f2f) | Dec 27, 2021 |
| Acer     | Aspire 5742G                | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Acer     | TravelMate 5760G            | [46204b90d0](https://bsd-hardware.info/?probe=46204b90d0) | Dec 24, 2021 |
| Lenovo   | ThinkPad SL510 2847R96      | [b0a9802877](https://bsd-hardware.info/?probe=b0a9802877) | Dec 22, 2021 |
| Lenovo   | ThinkPad T410 2537EA8       | [8b457cd635](https://bsd-hardware.info/?probe=8b457cd635) | Dec 22, 2021 |
| Lenovo   | ThinkPad X250 20CLS1WP01    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| Toshiba  | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| Samsung  | 305E4A/305E5A/305E7A        | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo   | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| HP       | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP       | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba  | Satellite L550              | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek  | N56VB                       | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP       | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo   | IdeaPad 510-15IKB 80SV      | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| Dell     | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| HP       | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| Apple    | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| ASUSTek  | X540LA                      | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek  | X540LA                      | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer     | Swift SF314-52              | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Toshiba  | Satellite S55t-B            | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| Lenovo   | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Lenovo   | V310-14IKB 80T2             | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| Toshiba  | Satellite C640              | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba  | Satellite C640              | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Lenovo   | ThinkPad T60 1951FEG        | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| ASUSTek  | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| Apple    | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP       | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 63        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 63        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 63        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 62        | 98.41%  |
| fr_FR | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 96.83%  |
| BIOS | 2         | 3.17%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 37        | 57.81%  |
| Zfs    | 27        | 42.19%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 63        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 33.33%  |
| Hewlett-Packard     | 9         | 14.29%  |
| Dell                | 8         | 12.7%   |
| Acer                | 8         | 12.7%   |
| ASUSTek Computer    | 5         | 7.94%   |
| Toshiba             | 4         | 6.35%   |
| Apple               | 4         | 6.35%   |
| Samsung Electronics | 2         | 3.17%   |
| Notebook            | 1         | 1.59%   |
| Gateway             | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B                 | 1         | 1.59%   |
| Toshiba Satellite L550                   | 1         | 1.59%   |
| Toshiba Satellite C640                   | 1         | 1.59%   |
| Toshiba Satellite C50-B                  | 1         | 1.59%   |
| Samsung N150P/N210P/N220P                | 1         | 1.59%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 1.59%   |
| Notebook N15_17RD                        | 1         | 1.59%   |
| Lenovo V310-14IKB 80T2                   | 1         | 1.59%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01    | 1         | 1.59%   |
| Lenovo ThinkPad X250 20CLS1WP01          | 1         | 1.59%   |
| Lenovo ThinkPad X240 20AMS2QDOC          | 1         | 1.59%   |
| Lenovo ThinkPad X220 Tablet 42962WU      | 1         | 1.59%   |
| Lenovo ThinkPad X220 4293AF4             | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 1.59%   |
| Lenovo ThinkPad T60 1951FEG              | 1         | 1.59%   |
| Lenovo ThinkPad T510 4384AJ6             | 1         | 1.59%   |
| Lenovo ThinkPad T460 20FMS75800          | 1         | 1.59%   |
| Lenovo ThinkPad T440 20B7000PHV          | 1         | 1.59%   |
| Lenovo ThinkPad T410 2537EA8             | 1         | 1.59%   |
| Lenovo ThinkPad T410 2522E38             | 1         | 1.59%   |
| Lenovo ThinkPad SL510 2847R96            | 1         | 1.59%   |
| Lenovo ThinkPad R61 8935WCS              | 1         | 1.59%   |
| Lenovo ThinkPad L450 20DSS1S402          | 1         | 1.59%   |
| Lenovo ThinkPad E580 20KS005BRI          | 1         | 1.59%   |
| Lenovo ThinkPad E15 20RD0011MX           | 1         | 1.59%   |
| Lenovo Legion Y540-15IRH 81SX            | 1         | 1.59%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL    | 1         | 1.59%   |
| Lenovo IdeaPad 510-15IKB 80SV            | 1         | 1.59%   |
| HP ZBook Studio G4                       | 1         | 1.59%   |
| HP ProBook 655 G1                        | 1         | 1.59%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.59%   |
| HP Pavilion Gaming Laptop 15-ec2xxx      | 1         | 1.59%   |
| HP Laptop 15-rb0xx                       | 1         | 1.59%   |
| HP Laptop 15-bw0xx                       | 1         | 1.59%   |
| HP Laptop 14-dk0xxx                      | 1         | 1.59%   |
| HP EliteBook 2560p                       | 1         | 1.59%   |
| HP 15 Notebook PC                        | 1         | 1.59%   |
| Gateway NE56R                            | 1         | 1.59%   |
| Dell Latitude E6540                      | 1         | 1.59%   |
| Dell Latitude E6530                      | 1         | 1.59%   |
| Dell Latitude E5470                      | 1         | 1.59%   |
| Dell Latitude E5430 non-vPro             | 1         | 1.59%   |
| Dell Latitude 7380                       | 1         | 1.59%   |
| Dell Latitude 7280                       | 1         | 1.59%   |
| Dell Inspiron 3521                       | 1         | 1.59%   |
| Dell Inspiron 3505                       | 1         | 1.59%   |
| ASUS X540LA                              | 1         | 1.59%   |
| ASUS S550CA                              | 1         | 1.59%   |
| ASUS N56VB                               | 1         | 1.59%   |
| ASUS K52Jc                               | 1         | 1.59%   |
| ASUS ASUS TUF Gaming A15 FA506IH_FA506IH | 1         | 1.59%   |
| Apple MacBookAir5,1                      | 1         | 1.59%   |
| Apple MacBookAir1,1                      | 1         | 1.59%   |
| Apple MacBook5,2                         | 1         | 1.59%   |
| Apple MacBook4,1                         | 1         | 1.59%   |
| Acer V5-131                              | 1         | 1.59%   |
| Acer TravelMate 5760G                    | 1         | 1.59%   |
| Acer Swift SF314-52                      | 1         | 1.59%   |
| Acer Aspire ES1-533                      | 1         | 1.59%   |
| Acer Aspire ES1-311                      | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 17        | 26.98%  |
| Dell Latitude     | 6         | 9.52%   |
| Acer Aspire       | 5         | 7.94%   |
| Toshiba Satellite | 4         | 6.35%   |
| HP Laptop         | 3         | 4.76%   |
| Lenovo IdeaPad    | 2         | 3.17%   |
| HP Pavilion       | 2         | 3.17%   |
| Dell Inspiron     | 2         | 3.17%   |
| Samsung N150P     | 1         | 1.59%   |
| Samsung 305E4A    | 1         | 1.59%   |
| Notebook N15      | 1         | 1.59%   |
| Lenovo V310-14IKB | 1         | 1.59%   |
| Lenovo Legion     | 1         | 1.59%   |
| HP ZBook          | 1         | 1.59%   |
| HP ProBook        | 1         | 1.59%   |
| HP EliteBook      | 1         | 1.59%   |
| HP 15             | 1         | 1.59%   |
| Gateway NE56R     | 1         | 1.59%   |
| ASUS X540LA       | 1         | 1.59%   |
| ASUS S550CA       | 1         | 1.59%   |
| ASUS N56VB        | 1         | 1.59%   |
| ASUS K52Jc        | 1         | 1.59%   |
| ASUS ASUS         | 1         | 1.59%   |
| Apple MacBookAir5 | 1         | 1.59%   |
| Apple MacBookAir1 | 1         | 1.59%   |
| Apple MacBook5    | 1         | 1.59%   |
| Apple MacBook4    | 1         | 1.59%   |
| Acer V5-131       | 1         | 1.59%   |
| Acer TravelMate   | 1         | 1.59%   |
| Acer Swift        | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 9         | 14.29%  |
| 2015 | 8         | 12.7%   |
| 2010 | 7         | 11.11%  |
| 2018 | 5         | 7.94%   |
| 2017 | 5         | 7.94%   |
| 2013 | 5         | 7.94%   |
| 2020 | 4         | 6.35%   |
| 2012 | 4         | 6.35%   |
| 2016 | 3         | 4.76%   |
| 2014 | 3         | 4.76%   |
| 2011 | 3         | 4.76%   |
| 2008 | 3         | 4.76%   |
| 2019 | 1         | 1.59%   |
| 2009 | 1         | 1.59%   |
| 2007 | 1         | 1.59%   |
| 2006 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 26        | 41.27%  |
| 8.01-16.0  | 18        | 28.57%  |
| 16.01-24.0 | 14        | 22.22%  |
| 2.01-3.0   | 3         | 4.76%   |
| 32.01-64.0 | 1         | 1.59%   |
| 3.01-4.0   | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 41        | 65.08%  |
| 0.51-1.0 | 17        | 26.98%  |
| 1.01-2.0 | 3         | 4.76%   |
| 2.01-3.0 | 2         | 3.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 67.19%  |
| 2      | 16        | 25%     |
| 3      | 3         | 4.69%   |
| 0      | 2         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 60.32%  |
| Yes       | 25        | 39.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 93.65%  |
| No        | 4         | 6.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 69.84%  |
| No        | 19        | 30.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 15.87%  |
| Germany     | 5         | 7.94%   |
| Russia      | 4         | 6.35%   |
| Romania     | 4         | 6.35%   |
| UK          | 3         | 4.76%   |
| Netherlands | 3         | 4.76%   |
| France      | 3         | 4.76%   |
| Vietnam     | 2         | 3.17%   |
| Ukraine     | 2         | 3.17%   |
| Poland      | 2         | 3.17%   |
| Peru        | 2         | 3.17%   |
| Mexico      | 2         | 3.17%   |
| Indonesia   | 2         | 3.17%   |
| Hungary     | 2         | 3.17%   |
| Denmark     | 2         | 3.17%   |
| Brazil      | 2         | 3.17%   |
| Sweden      | 1         | 1.59%   |
| Spain       | 1         | 1.59%   |
| Portugal    | 1         | 1.59%   |
| Norway      | 1         | 1.59%   |
| Malaysia    | 1         | 1.59%   |
| Lithuania   | 1         | 1.59%   |
| India       | 1         | 1.59%   |
| Georgia     | 1         | 1.59%   |
| Cuba        | 1         | 1.59%   |
| Chile       | 1         | 1.59%   |
| Bulgaria    | 1         | 1.59%   |
| Austria     | 1         | 1.59%   |
| Argentina   | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 3.13%   |
| Moscow                | 2         | 3.13%   |
| Lima                  | 2         | 3.13%   |
| Leatherhead           | 2         | 3.13%   |
| Jakarta               | 2         | 3.13%   |
| Hanoi                 | 2         | 3.13%   |
| Dijon                 | 2         | 3.13%   |
| Amsterdam             | 2         | 3.13%   |
| Zaporizhzhya          | 1         | 1.56%   |
| Zapopan               | 1         | 1.56%   |
| Yaphank               | 1         | 1.56%   |
| Vilnius               | 1         | 1.56%   |
| V?¤ster??s            | 1         | 1.56%   |
| Ugarchin              | 1         | 1.56%   |
| Torokszentmiklos      | 1         | 1.56%   |
| Tiruchi               | 1         | 1.56%   |
| Suceava               | 1         | 1.56%   |
| Shah Alam             | 1         | 1.56%   |
| Sevastopol            | 1         | 1.56%   |
| Seattle               | 1         | 1.56%   |
| San Luis Potos?­ City | 1         | 1.56%   |
| San Antonio           | 1         | 1.56%   |
| Riverton              | 1         | 1.56%   |
| Rio de Janeiro        | 1         | 1.56%   |
| Pruszcz Gdanski       | 1         | 1.56%   |
| Potsdam               | 1         | 1.56%   |
| Pflugerville          | 1         | 1.56%   |
| Patterson             | 1         | 1.56%   |
| Oldenburg             | 1         | 1.56%   |
| Odense                | 1         | 1.56%   |
| Nesttun               | 1         | 1.56%   |
| Mt. Pleasant          | 1         | 1.56%   |
| Mendoza               | 1         | 1.56%   |
| Mage                  | 1         | 1.56%   |
| Longfield             | 1         | 1.56%   |
| Lalinde               | 1         | 1.56%   |
| Kstovo                | 1         | 1.56%   |
| Krasnoyarsk           | 1         | 1.56%   |
| Kassel                | 1         | 1.56%   |
| K'alak'i T'bilisi     | 1         | 1.56%   |
| Iquique               | 1         | 1.56%   |
| Hvidovre              | 1         | 1.56%   |
| Hoogeveen             | 1         | 1.56%   |
| Hicksville            | 1         | 1.56%   |
| Havana                | 1         | 1.56%   |
| Hackettstown          | 1         | 1.56%   |
| Donauw?¶rth           | 1         | 1.56%   |
| Detmold               | 1         | 1.56%   |
| Craiova               | 1         | 1.56%   |
| Coria del R?­o        | 1         | 1.56%   |
| Cluj-Napoca           | 1         | 1.56%   |
| Budapest              | 1         | 1.56%   |
| Bucharest             | 1         | 1.56%   |
| Bruck an der Mur      | 1         | 1.56%   |
| Antioch               | 1         | 1.56%   |
| Anadia                | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 18     | 21.95%  |
| Toshiba             | 10        | 10     | 12.2%   |
| Kingston            | 9         | 10     | 10.98%  |
| Samsung Electronics | 8         | 9      | 9.76%   |
| SanDisk             | 5         | 5      | 6.1%    |
| Intel               | 5         | 6      | 6.1%    |
| Seagate             | 4         | 5      | 4.88%   |
| HGST                | 3         | 3      | 3.66%   |
| Crucial             | 3         | 3      | 3.66%   |
| Patriot             | 2         | 2      | 2.44%   |
| A-DATA Technology   | 2         | 2      | 2.44%   |
| Transcend           | 1         | 1      | 1.22%   |
| SPCC                | 1         | 1      | 1.22%   |
| SK Hynix            | 1         | 1      | 1.22%   |
| Micron Technology   | 1         | 1      | 1.22%   |
| KingSpec            | 1         | 1      | 1.22%   |
| Integral            | 1         | 1      | 1.22%   |
| Hitachi             | 1         | 1      | 1.22%   |
| Hewlett-Packard     | 1         | 1      | 1.22%   |
| Fujitsu             | 1         | 1      | 1.22%   |
| Corsair             | 1         | 1      | 1.22%   |
| Apple               | 1         | 1      | 1.22%   |
| Apacer              | 1         | 1      | 1.22%   |
| AGI                 | 1         | 1      | 1.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 3         | 3.57%   |
| Kingston SA400S37120G 120GB          | 3         | 3.57%   |
| HGST HTS545050A7E680 500GB           | 3         | 3.57%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 3.57%   |
| WDC WDS120G2G0A-00JH30 120GB         | 2         | 2.38%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 2.38%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 2         | 2.38%   |
| Kingston SA400S37240G 240GB          | 2         | 2.38%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 1.19%   |
| WDC WDBNCE5000PNC 500GB              | 1         | 1.19%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.19%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 1.19%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 1.19%   |
| WDC WD5000BPKX-22HPJT0 500GB         | 1         | 1.19%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.19%   |
| WDC WD1600BEVT-80A23T0 160GB         | 1         | 1.19%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 1.19%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 1.19%   |
| WDC WD10SDZW-11UMGS0 1TB             | 1         | 1.19%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1.19%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB | 1         | 1.19%   |
| WDC PC SN530 NVMe 256GB              | 1         | 1.19%   |
| Transcend TS240GMTS420S 240GB        | 1         | 1.19%   |
| Toshiba THNSNX024GMNT 24GB           | 1         | 1.19%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1.19%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1.19%   |
| Toshiba MK8034GSX 80GB               | 1         | 1.19%   |
| Toshiba MK3265GSXN 320GB             | 1         | 1.19%   |
| Toshiba MK3261GSYN 320GB             | 1         | 1.19%   |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 1.19%   |
| SPCC Solid State Disk 256GB          | 1         | 1.19%   |
| SK Hynix HFS256G39TND-N210A 256GB    | 1         | 1.19%   |
| Seagate ST980813AS 80GB              | 1         | 1.19%   |
| Seagate ST9640320AS 640GB            | 1         | 1.19%   |
| Seagate ST9320423AS 320GB            | 1         | 1.19%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 1.19%   |
| SanDisk SSD PLUS 480 GB              | 1         | 1.19%   |
| SanDisk SDSSDH3 512G                 | 1         | 1.19%   |
| SanDisk SDSA5GK-016G-1006 16GB       | 1         | 1.19%   |
| SanDisk SD8TB8U512G1001 512GB        | 1         | 1.19%   |
| SanDisk SD6SB1M064G 64GB             | 1         | 1.19%   |
| Samsung SSD PM841 2.5-inch 7mm 256GB | 1         | 1.19%   |
| Samsung SSD 980 PRO 1TB              | 1         | 1.19%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.19%   |
| Samsung Portable SSD T5 500GB        | 1         | 1.19%   |
| Samsung MZNLN256HMHQ-000H7 256GB     | 1         | 1.19%   |
| Samsung MZALQ512HALU-000L2 512GB     | 1         | 1.19%   |
| Samsung HS082HB 80GB                 | 1         | 1.19%   |
| Patriot Burst 960GB                  | 1         | 1.19%   |
| Patriot Burst 120GB                  | 1         | 1.19%   |
| Micron MTFDHBA512TCK 512GB           | 1         | 1.19%   |
| Kingston SQ500S37240G 240GB          | 1         | 1.19%   |
| Kingston SA400M8240G 240GB           | 1         | 1.19%   |
| Kingston RBUSNS8154P3256GJ1 256GB    | 1         | 1.19%   |
| Kingston OM8SBP3512K-AH 512GB        | 1         | 1.19%   |
| KingSpec NT-256 256GB                | 1         | 1.19%   |
| Intel SSDSC2KF180H6L 180GB           | 1         | 1.19%   |
| Intel SSDSC2BF180A4L 180GB           | 1         | 1.19%   |
| Intel SSDSC2BF180A4H 180GB           | 1         | 1.19%   |
| Intel SSDPEKKF256G8L 256GB           | 1         | 1.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 40%     |
| Toshiba             | 8         | 8      | 26.67%  |
| Seagate             | 4         | 5      | 13.33%  |
| HGST                | 3         | 3      | 10%     |
| Samsung Electronics | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 18.42%  |
| SanDisk             | 5         | 5      | 13.16%  |
| Samsung Electronics | 4         | 4      | 10.53%  |
| WDC                 | 3         | 3      | 7.89%   |
| Intel               | 3         | 3      | 7.89%   |
| Crucial             | 3         | 3      | 7.89%   |
| Patriot             | 2         | 2      | 5.26%   |
| Transcend           | 1         | 1      | 2.63%   |
| Toshiba             | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| SK Hynix            | 1         | 1      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| Integral            | 1         | 1      | 2.63%   |
| Hewlett-Packard     | 1         | 1      | 2.63%   |
| Corsair             | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |
| Apacer              | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 32        | 38     | 43.84%  |
| HDD  | 26        | 31     | 35.62%  |
| NVMe | 15        | 17     | 20.55%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 69     | 78.26%  |
| NVMe | 15        | 17     | 21.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 59     | 82.76%  |
| 0.51-1.0   | 10        | 10     | 17.24%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 37        | 57.81%  |
| 251-500    | 13        | 20.31%  |
| 101-250    | 7         | 10.94%  |
| 501-1000   | 3         | 4.69%   |
| 21-50      | 2         | 3.13%   |
| 51-100     | 2         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 63        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB     | 1         | 1      | 5.56%   |
| WDC WD5000LPCX-60VHAT0 500GB     | 1         | 1      | 5.56%   |
| WDC WD5000BPVT-22HXZT3 500GB     | 1         | 1      | 5.56%   |
| WDC WD3200BEVT-22ZCT0 320GB      | 1         | 1      | 5.56%   |
| WDC WD1600BEVT-80A23T0 160GB     | 1         | 1      | 5.56%   |
| Toshiba THNSNX024GMNT 24GB       | 1         | 1      | 5.56%   |
| Toshiba MQ01ABF050 500GB         | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB         | 1         | 1      | 5.56%   |
| Toshiba MK8034GSX 80GB           | 1         | 1      | 5.56%   |
| Toshiba MK3265GSXN 320GB         | 1         | 1      | 5.56%   |
| Toshiba MK3261GSYN 320GB         | 1         | 1      | 5.56%   |
| Seagate ST9640320AS 640GB        | 1         | 1      | 5.56%   |
| Seagate ST9320423AS 320GB        | 1         | 1      | 5.56%   |
| Seagate ST320LT007-9ZV142 320GB  | 1         | 1      | 5.56%   |
| Samsung Electronics HS082HB 80GB | 1         | 1      | 5.56%   |
| HGST HTS545050A7E680 500GB       | 1         | 1      | 5.56%   |
| AGI AGI512G16AI198 512GB         | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 38.89%  |
| WDC                 | 5         | 5      | 27.78%  |
| Seagate             | 3         | 3      | 16.67%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| AGI                 | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 37.5%   |
| WDC                 | 5         | 5      | 31.25%  |
| Seagate             | 3         | 3      | 18.75%  |
| Samsung Electronics | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 16     | 88.24%  |
| NVMe | 1         | 1      | 5.88%   |
| SSD  | 1         | 1      | 5.88%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 47        | 67     | 72.31%  |
| Malfunc  | 17        | 18     | 26.15%  |
| Detected | 1         | 1      | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 52        | 72.22%  |
| AMD                         | 6         | 8.33%   |
| Samsung Electronics         | 4         | 5.56%   |
| Sandisk                     | 3         | 4.17%   |
| Kingston Technology Company | 2         | 2.78%   |
| Silicon Motion              | 1         | 1.39%   |
| Nvidia                      | 1         | 1.39%   |
| Micron Technology           | 1         | 1.39%   |
| KIOXIA                      | 1         | 1.39%   |
| ADATA Technology            | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 10.39%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 7.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 5.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 5.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 3.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 3.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 3.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 3.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 3.9%    |
| Unknown                                                                          | 3         | 3.9%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 2.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 2.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.3%    |
| Sandisk unknown                                                                  | 1         | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.3%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.3%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.3%    |
| KIOXIA unknown                                                                   | 1         | 1.3%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.3%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.3%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.3%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.3%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 56        | 72.73%  |
| NVMe | 15        | 19.48%  |
| IDE  | 4         | 5.19%   |
| RAID | 2         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 87.3%   |
| AMD    | 8         | 12.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 4.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 4.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 4.76%   |
| Intel CPU Version                             | 2         | 3.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 3.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 3.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 3.17%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 3.17%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.59%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.59%   |
| Intel Core i7-9750HF CPU @ 2.60GHz            | 1         | 1.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.59%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.59%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.59%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.59%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.59%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.59%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.59%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 1.59%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.59%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.59%   |
| Intel Core i3 CPU M 390 @ 2.67GHz             | 1         | 1.59%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i3 CPU M 350 @ 2.27GH              | 1         | 1.59%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 1.59%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 1         | 1.59%   |
| Intel Core 2 CPU                              | 1         | 1.59%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.59%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 1.59%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 1.59%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 1.59%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 1.59%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 1.59%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 1         | 1.59%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.59%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 1         | 1.59%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G  | 1         | 1.59%   |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 1.59%   |
| AMD A10-5750M APU with Radeon HD Graphics     | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 24        | 38.1%   |
| Intel Core i7    | 9         | 14.29%  |
| Intel Core i3    | 8         | 12.7%   |
| Intel Core 2 Duo | 4         | 6.35%   |
| Intel Celeron    | 4         | 6.35%   |
| AMD Ryzen 5      | 3         | 4.76%   |
| Other            | 2         | 3.17%   |
| Intel Pentium    | 2         | 3.17%   |
| AMD A6           | 2         | 3.17%   |
| Intel Core 2     | 1         | 1.59%   |
| Intel Atom       | 1         | 1.59%   |
| AMD Ryzen 3      | 1         | 1.59%   |
| AMD E2           | 1         | 1.59%   |
| AMD A10          | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 38        | 60.32%  |
| 4       | 15        | 23.81%  |
| Unknown | 6         | 9.52%   |
| 12      | 2         | 3.17%   |
| 8       | 1         | 1.59%   |
| 6       | 1         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 59        | 93.65%  |
| 2       | 3         | 4.76%   |
| Unknown | 1         | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 40        | 63.49%  |
| 1       | 17        | 26.98%  |
| Unknown | 6         | 9.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 12        | 19.05%  |
| Westmere    | 7         | 11.11%  |
| IvyBridge   | 7         | 11.11%  |
| SandyBridge | 5         | 7.94%   |
| Penryn      | 5         | 7.94%   |
| Skylake     | 4         | 6.35%   |
| Haswell     | 4         | 6.35%   |
| Silvermont  | 3         | 4.76%   |
| Broadwell   | 3         | 4.76%   |
| Zen+        | 2         | 3.17%   |
| Excavator   | 2         | 3.17%   |
| Core        | 2         | 3.17%   |
| Zen 3       | 1         | 1.59%   |
| Zen 2       | 1         | 1.59%   |
| Piledriver  | 1         | 1.59%   |
| K10 Llano   | 1         | 1.59%   |
| Goldmont    | 1         | 1.59%   |
| CometLake   | 1         | 1.59%   |
| Bonnell     | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 64.47%  |
| Nvidia | 14        | 18.42%  |
| AMD    | 13        | 17.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 8.75%   |
| Intel HD Graphics 620                                                                    | 5         | 6.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 6.25%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 3.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 3.75%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.75%   |
| Nvidia TU117M                                                                            | 2         | 2.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.25%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.25%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.25%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.25%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 1.25%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 1.25%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.25%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.25%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.25%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 1.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.25%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.25%   |
| Intel HD Graphics 630                                                                    | 1         | 1.25%   |
| Intel HD Graphics 530                                                                    | 1         | 1.25%   |
| Intel HD Graphics 500                                                                    | 1         | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.25%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.25%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.25%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.25%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.25%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 1.25%   |
| AMD Renoir                                                                               | 1         | 1.25%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.25%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 1.25%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.25%   |
| AMD Cezanne                                                                              | 1         | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 50.79%  |
| Intel + Nvidia | 7         | 11.11%  |
| 1 x AMD        | 7         | 11.11%  |
| 2 x Intel      | 6         | 9.52%   |
| 1 x Nvidia     | 5         | 7.94%   |
| Intel + AMD    | 4         | 6.35%   |
| AMD + Nvidia   | 2         | 3.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 58        | 92.06%  |
| Proprietary | 5         | 7.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 80.95%  |
| 0.51-1.0   | 4         | 6.35%   |
| 0.01-0.5   | 4         | 6.35%   |
| 1.01-2.0   | 2         | 3.17%   |
| 5.01-6.0   | 1         | 1.59%   |
| 3.01-4.0   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 12        | 17.39%  |
| BOE                     | 11        | 15.94%  |
| Samsung Electronics     | 10        | 14.49%  |
| AU Optronics            | 10        | 14.49%  |
| Lenovo                  | 8         | 11.59%  |
| Chimei Innolux          | 8         | 11.59%  |
| Apple                   | 4         | 5.8%    |
| Philips                 | 1         | 1.45%   |
| LED                     | 1         | 1.45%   |
| Chi Mei Optoelectronics | 1         | 1.45%   |
| BenQ                    | 1         | 1.45%   |
| Ancor Communications    | 1         | 1.45%   |
| Acer                    | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 2         | 2.82%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch        | 1         | 1.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 1.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 1.41%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 1         | 1.41%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch              | 1         | 1.41%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 530x300mm 24.0-inch                 | 1         | 1.41%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch                 | 1         | 1.41%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                  | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 1         | 1.41%   |
| LED LCD Monitor LED2345 1920x1080 890x500mm 40.2-inch                    | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 360x200mm 16.2-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 340x190mm 15.3-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 310x170mm 13.9-inch          | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 310x170mm 13.9-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1362 1366x768 290x160mm 13.0-inch          | 1         | 1.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 1.41%   |
| BOE LCD Monitor BOE083A 1920x1080 340x190mm 15.3-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE06FF 1920x1080 340x190mm 15.3-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                     | 1         | 1.41%   |
| BOE LCD Monitor BOE06C8 1366x768 280x160mm 12.7-inch                     | 1         | 1.41%   |
| BOE LCD Monitor BOE06A5 1366x768 340x190mm 15.3-inch                     | 1         | 1.41%   |
| BOE LCD Monitor BOE0698 1366x768 310x170mm 13.9-inch                     | 1         | 1.41%   |
| BOE LCD Monitor BOE0662 1366x768 340x190mm 15.3-inch                     | 1         | 1.41%   |
| BOE LCD Monitor BOE065E 1920x1080 340x190mm 15.3-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE0653 1920x1080 310x170mm 13.9-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE0600 1366x768 310x170mm 13.9-inch                     | 1         | 1.41%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                        | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch            | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO313E 1600x900 310x170mm 13.9-inch            | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch           | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 340x190mm 15.3-inch            | 1         | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 29        | 43.94%  |
| 1920x1080 (FHD)   | 22        | 33.33%  |
| 1280x800 (WXGA)   | 6         | 9.09%   |
| 2560x1440 (QHD)   | 2         | 3.03%   |
| 1600x900 (HD+)    | 2         | 3.03%   |
| 3840x2160 (4K)    | 1         | 1.52%   |
| 1920x1200 (WUXGA) | 1         | 1.52%   |
| 1440x900 (WXGA+)  | 1         | 1.52%   |
| 1024x768 (XGA)    | 1         | 1.52%   |
| 1024x600          | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 27        | 38.03%  |
| 13     | 16        | 22.54%  |
| 12     | 7         | 9.86%   |
| 27     | 3         | 4.23%   |
| 24     | 3         | 4.23%   |
| 17     | 3         | 4.23%   |
| 14     | 3         | 4.23%   |
| 23     | 2         | 2.82%   |
| 11     | 2         | 2.82%   |
| 54     | 1         | 1.41%   |
| 40     | 1         | 1.41%   |
| 18     | 1         | 1.41%   |
| 16     | 1         | 1.41%   |
| 10     | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 53.52%  |
| 201-300     | 18        | 25.35%  |
| 501-600     | 8         | 11.27%  |
| 351-400     | 4         | 5.63%   |
| 801-900     | 1         | 1.41%   |
| 401-500     | 1         | 1.41%   |
| 1001-1500   | 1         | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 85.48%  |
| 16/10 | 6         | 9.68%   |
| 3/2   | 2         | 3.23%   |
| 4/3   | 1         | 1.61%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 32.39%  |
| 81-90          | 16        | 22.54%  |
| 61-70          | 7         | 9.86%   |
| 101-110        | 5         | 7.04%   |
| 201-250        | 4         | 5.63%   |
| 301-350        | 3         | 4.23%   |
| 121-130        | 3         | 4.23%   |
| 71-80          | 2         | 2.82%   |
| 51-60          | 2         | 2.82%   |
| More than 1000 | 1         | 1.41%   |
| 41-50          | 1         | 1.41%   |
| 251-300        | 1         | 1.41%   |
| 141-150        | 1         | 1.41%   |
| 111-120        | 1         | 1.41%   |
| 501-1000       | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 30        | 42.86%  |
| 101-120 | 25        | 35.71%  |
| 51-100  | 13        | 18.57%  |
| 161-240 | 2         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 52        | 81.25%  |
| 2     | 10        | 15.63%  |
| 0     | 2         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 34        | 33.33%  |
| Realtek Semiconductor             | 27        | 26.47%  |
| Qualcomm Atheros                  | 15        | 14.71%  |
| Broadcom                          | 14        | 13.73%  |
| Marvell Technology Group          | 3         | 2.94%   |
| TP-Link                           | 1         | 0.98%   |
| Sierra Wireless                   | 1         | 0.98%   |
| Nvidia                            | 1         | 0.98%   |
| NetGear                           | 1         | 0.98%   |
| JMicron Technology                | 1         | 0.98%   |
| Google                            | 1         | 0.98%   |
| Ericsson Business Mobile Networks | 1         | 0.98%   |
| Dell                              | 1         | 0.98%   |
| D-Link System                     | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 20        | 15.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 6         | 4.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 4         | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 3.05%   |
| Intel Wireless 8260                                                         | 4         | 3.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 4         | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3         | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 2.29%   |
| Intel Wireless 8265 / 8275                                                  | 3         | 2.29%   |
| Intel Wireless 7265                                                         | 3         | 2.29%   |
| Intel Ethernet Connection I219-LM                                           | 3         | 2.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 2.29%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 2.29%   |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 2.29%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 2         | 1.53%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 2         | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 1.53%   |
| Intel Wireless 7260                                                         | 2         | 1.53%   |
| Intel WiFi Link 5100                                                        | 2         | 1.53%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 1.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 1.53%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 1.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 2         | 1.53%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 1.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                             | 2         | 1.53%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 2         | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 2         | 1.53%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1         | 0.76%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                               | 1         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 1         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                    | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                  | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 0.76%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                 | 1         | 0.76%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                     | 1         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                     | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 1         | 0.76%   |
| Intel Wireless 3160                                                         | 1         | 0.76%   |
| Intel Ethernet Connection I217-LM                                           | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-V                                        | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                       | 1         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 1         | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 1         | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1         | 0.76%   |
| Intel 82573L Gigabit Ethernet Controller                                    | 1         | 0.76%   |
| Google Nexus/Pixel Device (tether)                                          | 1         | 0.76%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 0.76%   |
| Dell Hub of E-Port Replicator                                               | 1         | 0.76%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072]        | 1         | 0.76%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                            | 1         | 0.76%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                      | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 49.25%  |
| Qualcomm Atheros      | 14        | 20.9%   |
| Broadcom              | 9         | 13.43%  |
| Realtek Semiconductor | 7         | 10.45%  |
| TP-Link               | 1         | 1.49%   |
| Sierra Wireless       | 1         | 1.49%   |
| NetGear               | 1         | 1.49%   |
| Dell                  | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 5.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 5.71%   |
| Intel Wireless 8260                                            | 4         | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 4.29%   |
| Intel Wireless 8265 / 8275                                     | 3         | 4.29%   |
| Intel Wireless 7265                                            | 3         | 4.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.29%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 4.29%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 2.86%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 2         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.86%   |
| Intel Wireless 7260                                            | 2         | 2.86%   |
| Intel WiFi Link 5100                                           | 2         | 2.86%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 2.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 2.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 2.86%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.86%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 1.43%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 1.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.43%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 1.43%   |
| Intel Wireless 3160                                            | 1         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.43%   |
| Dell Hub of E-Port Replicator                                  | 1         | 1.43%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.43%   |
| Broadcom BCM43227 802.11b/g/n                                  | 1         | 1.43%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.43%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 44.07%  |
| Intel                    | 19        | 32.2%   |
| Broadcom                 | 5         | 8.47%   |
| Qualcomm Atheros         | 3         | 5.08%   |
| Marvell Technology Group | 3         | 5.08%   |
| Nvidia                   | 1         | 1.69%   |
| JMicron Technology       | 1         | 1.69%   |
| Google                   | 1         | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 33.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 10.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 6.78%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 5.08%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 5.08%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 3.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.69%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.69%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.69%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.69%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.69%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.69%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.69%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.69%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 50.81%  |
| Ethernet | 59        | 47.58%  |
| Unknown  | 2         | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 58        | 53.21%  |
| WiFi     | 49        | 44.95%  |
| Unknown  | 2         | 1.83%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 57        | 90.48%  |
| 1     | 6         | 9.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 93.65%  |
| Yes  | 4         | 6.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 43.18%  |
| Broadcom                        | 7         | 15.91%  |
| Qualcomm Atheros Communications | 4         | 9.09%   |
| Apple                           | 4         | 9.09%   |
| Realtek Semiconductor           | 3         | 6.82%   |
| Lite-On Technology              | 2         | 4.55%   |
| IMC Networks                    | 2         | 4.55%   |
| Hewlett-Packard                 | 1         | 2.27%   |
| Foxconn / Hon Hai               | 1         | 2.27%   |
| Dell                            | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 14        | 30.43%  |
| Broadcom BCM2045B (BDC-2.1)                            | 4         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                         | 2         | 4.35%   |
| Realtek Bluetooth Radio                                | 2         | 4.35%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                | 2         | 4.35%   |
| Intel AX200 Bluetooth                                  | 2         | 4.35%   |
| Apple Built-in iSight (no firmware loaded)             | 2         | 4.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 2         | 4.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 2.17%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)        | 1         | 2.17%   |
| Lite-On Realtek Bluetooth Adapter                      | 1         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                       | 1         | 2.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 1         | 2.17%   |
| Intel AX201 Bluetooth                                  | 1         | 2.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 2.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 2.17%   |
| HP Broadcom 2070 Bluetooth Combo                       | 1         | 2.17%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0       | 1         | 2.17%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 2.17%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device | 1         | 2.17%   |
| Broadcom BCM43142 Bluetooth 4.0                        | 1         | 2.17%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]       | 1         | 2.17%   |
| Apple Broadcom Bluetooth 2.1 module                    | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 54        | 75%     |
| AMD               | 9         | 12.5%   |
| Nvidia            | 7         | 9.72%   |
| Texas Instruments | 1         | 1.39%   |
| GN Netcom         | 1         | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 12.79%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 9.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 8.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.65%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 4         | 4.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 3.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.49%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.49%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.33%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.33%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.33%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 1.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.16%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.16%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 1.16%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.16%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.16%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 36.11%  |
| SK Hynix            | 10        | 13.89%  |
| Kingston            | 9         | 12.5%   |
| Unknown             | 6         | 8.33%   |
| Ramaxel Technology  | 5         | 6.94%   |
| Micron Technology   | 4         | 5.56%   |
| Nanya Technology    | 2         | 2.78%   |
| Elpida              | 2         | 2.78%   |
| Smart               | 1         | 1.39%   |
| Silicon Power       | 1         | 1.39%   |
| Kingmax             | 1         | 1.39%   |
| Crucial             | 1         | 1.39%   |
| Corsair             | 1         | 1.39%   |
| A-DATA Technology   | 1         | 1.39%   |
| 48spaces            | 1         | 1.39%   |
| Unknown             | 1         | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 5.19%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 3.9%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 2.6%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s                 | 2         | 2.6%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 2.6%    |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 2         | 2.6%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.3%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.3%    |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 1         | 1.3%    |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s            | 1         | 1.3%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.3%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.3%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s          | 1         | 1.3%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.3%    |
| Silicon Power RAM SP008GBSFU240B02 8GB SODIMM DDR4 2400MT/s      | 1         | 1.3%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.3%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s            | 1         | 1.3%    |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 1.3%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.3%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.3%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 1.3%    |
| Ramaxel RAM RMT3190ME76F8F1600 2GB SODIMM DDR3 1067MT/s          | 1         | 1.3%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.3%    |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1066MT/s          | 1         | 1.3%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.3%    |
| Nanya RAM Module 2GB SODIMM DDR2 800MT/s                         | 1         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.3%    |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.3%    |
| Kingston RAM TSB16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| Kingston RAM TSB1066D3S7ELF/2G 2GB SODIMM DDR3 1067MT/s          | 1         | 1.3%    |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 1         | 1.3%    |
| Kingston RAM KF2666C16S4/32G 32GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| Kingston RAM ASU1333D3S9DR8/2G 2GB SODIMM DDR3 1333MT/s          | 1         | 1.3%    |
| Kingston RAM ACR256X64D3S1066C7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.3%    |
| Kingston RAM ACR24D4S7S8MB-4 4GB SODIMM DDR4 2400MT/s            | 1         | 1.3%    |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s         | 1         | 1.3%    |
| Kingston RAM 99U5594-001.A00LF 2GB SODIMM DDR3 1067MT/s          | 1         | 1.3%    |
| Kingston RAM 9905630-033.A00G 16GB SODIMM DDR4 2133MT/s          | 1         | 1.3%    |
| Kingmax RAM FSFE85F-C8HS9 2GB SODIMM DDR3 1067MT/s               | 1         | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 34        | 54.84%  |
| DDR4   | 20        | 32.26%  |
| DDR2   | 7         | 11.29%  |
| LPDDR3 | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 98.39%  |
| Row Of Chips | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 24        | 34.78%  |
| 8192  | 18        | 26.09%  |
| 2048  | 18        | 26.09%  |
| 16384 | 6         | 8.7%    |
| 1024  | 2         | 2.9%    |
| 32768 | 1         | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 20        | 28.99%  |
| 2667    | 9         | 13.04%  |
| 1334    | 7         | 10.14%  |
| 1333    | 7         | 10.14%  |
| 2400    | 6         | 8.7%    |
| 667     | 5         | 7.25%   |
| 3200    | 4         | 5.8%    |
| 2133    | 3         | 4.35%   |
| 1067    | 3         | 4.35%   |
| 1867    | 2         | 2.9%    |
| 1066    | 1         | 1.45%   |
| 800     | 1         | 1.45%   |
| Unknown | 1         | 1.45%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 28%     |
| Quanta                                 | 5         | 10%     |
| Realtek Semiconductor                  | 4         | 8%      |
| Lite-On Technology                     | 4         | 8%      |
| IMC Networks                           | 4         | 8%      |
| Sunplus Innovation Technology          | 3         | 6%      |
| Z-Star Microelectronics                | 2         | 4%      |
| Suyin                                  | 2         | 4%      |
| Microdia                               | 2         | 4%      |
| Lenovo                                 | 2         | 4%      |
| Alcor Micro                            | 2         | 4%      |
| Acer                                   | 2         | 4%      |
| Luxvisions Innotech Limited            | 1         | 2%      |
| Importek                               | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2%      |
| Apple                                  | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Realtek USB2.0 PC Camera                    | 2         | 4%      |
| Quanta HP TrueVision HD Camera                      | 2         | 4%      |
| Lite-On Integrated Camera                           | 2         | 4%      |
| Chicony Lenovo Integrated Camera (0.3MP)            | 2         | 4%      |
| Chicony HD WebCam                                   | 2         | 4%      |
| Chicony EasyCamera                                  | 2         | 4%      |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 2%      |
| Z-Star Webcam                                       | 1         | 2%      |
| Suyin Integrated_Webcam_HD                          | 1         | 2%      |
| Suyin HD Video WebCam                               | 1         | 2%      |
| Sunplus Integrated_Webcam_HD                        | 1         | 2%      |
| Sunplus Integrated Camera                           | 1         | 2%      |
| Sunplus HP Universal Camera                         | 1         | 2%      |
| Realtek USB Camera                                  | 1         | 2%      |
| Realtek HD WebCam                                   | 1         | 2%      |
| Quanta Realtek DMFT - RGB                           | 1         | 2%      |
| Quanta HP Webcam                                    | 1         | 2%      |
| Quanta HD WebCam                                    | 1         | 2%      |
| Microdia Integrated_Webcam_HD                       | 1         | 2%      |
| Microdia Integrated Webcam                          | 1         | 2%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2%      |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 2%      |
| Lite-On HP HD Camera                                | 1         | 2%      |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 2%      |
| Lenovo Integrated Webcam                            | 1         | 2%      |
| Importek TOSHIBA Web Camera                         | 1         | 2%      |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2%      |
| IMC Networks SunplusIT Integrated Camera            | 1         | 2%      |
| IMC Networks Integrated Camera                      | 1         | 2%      |
| IMC Networks EasyCamera                             | 1         | 2%      |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 2%      |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 2%      |
| Chicony USB 2.0 VGA UVC WebCam                      | 1         | 2%      |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 2%      |
| Chicony Integrated Camera                           | 1         | 2%      |
| Chicony HP Webcam                                   | 1         | 2%      |
| Chicony Chicony USB 2.0 Camera                      | 1         | 2%      |
| Chicony 1.3M Webcam                                 | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 2%      |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 2%      |
| Alcor Micro HD WebCam                               | 1         | 2%      |
| Alcor Micro Acer Integrated Webcam                  | 1         | 2%      |
| Acer ThinkPad P50 Integrated Camera                 | 1         | 2%      |
| Acer SunplusIT INC. Integrated Camera               | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 38.46%  |
| Upek                  | 3         | 23.08%  |
| LighTuning Technology | 2         | 15.38%  |
| Synaptics             | 1         | 7.69%   |
| STMicroelectronics    | 1         | 7.69%   |
| AuthenTec             | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 23.08%  |
| Validity Sensors Synaptics WBDI                        | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.69%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 7.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.69%   |
| AuthenTec AES1600                                      | 1         | 7.69%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 39.06%  |
| 2     | 19        | 29.69%  |
| 3     | 9         | 14.06%  |
| 0     | 7         | 10.94%  |
| 4     | 4         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 44        | 46.32%  |
| Net/wireless             | 16        | 16.84%  |
| Fingerprint reader       | 13        | 13.68%  |
| Bluetooth                | 13        | 13.68%  |
| Card reader              | 8         | 8.42%   |
| Sound                    | 1         | 1.05%   |

