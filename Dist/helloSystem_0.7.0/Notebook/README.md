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
| HP       | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Acer     | V5-131                      | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| Dell     | Latitude E4310              | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple    | MacBook4,1                  | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo   | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple    | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Apple    | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell     | Latitude E5470              | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| Dell     | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo   | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo   | IdeaPad 110S-11IBR 80WG     | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| TUXEDO   | InfinityBook13V3            | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO   | InfinityBook13V3            | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| Lenovo   | ThinkPad T450 20BUS0VH08    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung  | N100                        | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo   | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo   | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| Acer     | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| ASUSTek  | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek  | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Acer     | Aspire E5-511G              | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD | U12CT                       | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Dell     | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo   | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Dell     | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP       | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Lenovo   | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP       | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| HP       | G62                         | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
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
| amd64 | 86        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 85        | 98.84%  |
| GNOME        | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 86        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 86        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 82        | 95.35%  |
| uk_UA | 1         | 1.16%   |
| fr_FR | 1         | 1.16%   |
| es_ES | 1         | 1.16%   |
| C     | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 84        | 97.67%  |
| BIOS | 2         | 2.33%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 48        | 54.55%  |
| Zfs    | 40        | 45.45%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 86        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 31.4%   |
| Hewlett-Packard     | 13        | 15.12%  |
| Dell                | 13        | 15.12%  |
| Acer                | 10        | 11.63%  |
| ASUSTek Computer    | 6         | 6.98%   |
| Apple               | 6         | 6.98%   |
| Toshiba             | 4         | 4.65%   |
| Samsung Electronics | 3         | 3.49%   |
| TWINHEAD            | 1         | 1.16%   |
| TUXEDO              | 1         | 1.16%   |
| Notebook            | 1         | 1.16%   |
| Gateway             | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude E5470                      | 2         | 2.33%   |
| Apple MacBook4,1                         | 2         | 2.33%   |
| Acer V5-131                              | 2         | 2.33%   |
| TWINHEAD U12CT                           | 1         | 1.16%   |
| TUXEDO InfinityBook13V3                  | 1         | 1.16%   |
| Toshiba Satellite S55t-B                 | 1         | 1.16%   |
| Toshiba Satellite L550                   | 1         | 1.16%   |
| Toshiba Satellite C640                   | 1         | 1.16%   |
| Toshiba Satellite C50-B                  | 1         | 1.16%   |
| Samsung N150P/N210P/N220P                | 1         | 1.16%   |
| Samsung N100                             | 1         | 1.16%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 1.16%   |
| Notebook N15_17RD                        | 1         | 1.16%   |
| Lenovo V310-14IKB 80T2                   | 1         | 1.16%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01    | 1         | 1.16%   |
| Lenovo ThinkPad X250 20CLS1WP01          | 1         | 1.16%   |
| Lenovo ThinkPad X240 20AMS2QDOC          | 1         | 1.16%   |
| Lenovo ThinkPad X220 Tablet 42962WU      | 1         | 1.16%   |
| Lenovo ThinkPad X220 4293AF4             | 1         | 1.16%   |
| Lenovo ThinkPad X220 4291H77             | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 1.16%   |
| Lenovo ThinkPad T61 766301U              | 1         | 1.16%   |
| Lenovo ThinkPad T60 1951FEG              | 1         | 1.16%   |
| Lenovo ThinkPad T510 4384AJ6             | 1         | 1.16%   |
| Lenovo ThinkPad T460 20FMS75800          | 1         | 1.16%   |
| Lenovo ThinkPad T440p 20AWS3RH00         | 1         | 1.16%   |
| Lenovo ThinkPad T440 20B7000PHV          | 1         | 1.16%   |
| Lenovo ThinkPad T430 2349AK1             | 1         | 1.16%   |
| Lenovo ThinkPad T410 2537EA8             | 1         | 1.16%   |
| Lenovo ThinkPad T410 2522E38             | 1         | 1.16%   |
| Lenovo ThinkPad SL510 2847R96            | 1         | 1.16%   |
| Lenovo ThinkPad R61 8935WCS              | 1         | 1.16%   |
| Lenovo ThinkPad L450 20DSS1S402          | 1         | 1.16%   |
| Lenovo ThinkPad E580 20KS005BRI          | 1         | 1.16%   |
| Lenovo ThinkPad E15 20RD0011MX           | 1         | 1.16%   |
| Lenovo Legion Y540-15IRH 81SX            | 1         | 1.16%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL    | 1         | 1.16%   |
| Lenovo IdeaPad 510-15IKB 80SV            | 1         | 1.16%   |
| Lenovo IdeaPad 110S-11IBR 80WG           | 1         | 1.16%   |
| Lenovo E31-80 80MX                       | 1         | 1.16%   |
| HP ZBook Studio G4                       | 1         | 1.16%   |
| HP ProBook 655 G1                        | 1         | 1.16%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.16%   |
| HP Pavilion Gaming Laptop 15-ec2xxx      | 1         | 1.16%   |
| HP Mini 210-1000                         | 1         | 1.16%   |
| HP Laptop 15-rb0xx                       | 1         | 1.16%   |
| HP Laptop 15-bw0xx                       | 1         | 1.16%   |
| HP Laptop 14-dk0xxx                      | 1         | 1.16%   |
| HP G62                                   | 1         | 1.16%   |
| HP EliteBook Folio 9470m                 | 1         | 1.16%   |
| HP EliteBook 6930p                       | 1         | 1.16%   |
| HP EliteBook 2560p                       | 1         | 1.16%   |
| HP 15 Notebook PC                        | 1         | 1.16%   |
| Gateway NE56R                            | 1         | 1.16%   |
| Dell Venue 11 Pro 7140                   | 1         | 1.16%   |
| Dell Latitude E6540                      | 1         | 1.16%   |
| Dell Latitude E6530                      | 1         | 1.16%   |
| Dell Latitude E5430 non-vPro             | 1         | 1.16%   |
| Dell Latitude E4310                      | 1         | 1.16%   |
| Dell Latitude D630                       | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 21        | 24.42%  |
| Dell Latitude           | 9         | 10.47%  |
| Acer Aspire             | 6         | 6.98%   |
| Toshiba Satellite       | 4         | 4.65%   |
| Lenovo IdeaPad          | 3         | 3.49%   |
| HP Laptop               | 3         | 3.49%   |
| HP EliteBook            | 3         | 3.49%   |
| Dell Inspiron           | 3         | 3.49%   |
| HP Pavilion             | 2         | 2.33%   |
| Apple MacBook4          | 2         | 2.33%   |
| Acer V5-131             | 2         | 2.33%   |
| TWINHEAD U12CT          | 1         | 1.16%   |
| TUXEDO InfinityBook13V3 | 1         | 1.16%   |
| Samsung N150P           | 1         | 1.16%   |
| Samsung N100            | 1         | 1.16%   |
| Samsung 305E4A          | 1         | 1.16%   |
| Notebook N15            | 1         | 1.16%   |
| Lenovo V310-14IKB       | 1         | 1.16%   |
| Lenovo Legion           | 1         | 1.16%   |
| Lenovo E31-80           | 1         | 1.16%   |
| HP ZBook                | 1         | 1.16%   |
| HP ProBook              | 1         | 1.16%   |
| HP Mini                 | 1         | 1.16%   |
| HP G62                  | 1         | 1.16%   |
| HP 15                   | 1         | 1.16%   |
| Gateway NE56R           | 1         | 1.16%   |
| Dell Venue              | 1         | 1.16%   |
| ASUS X555LA             | 1         | 1.16%   |
| ASUS X540LA             | 1         | 1.16%   |
| ASUS S550CA             | 1         | 1.16%   |
| ASUS N56VB              | 1         | 1.16%   |
| ASUS K52Jc              | 1         | 1.16%   |
| ASUS ASUS               | 1         | 1.16%   |
| Apple MacBookAir5       | 1         | 1.16%   |
| Apple MacBookAir1       | 1         | 1.16%   |
| Apple MacBook6          | 1         | 1.16%   |
| Apple MacBook5          | 1         | 1.16%   |
| Acer TravelMate         | 1         | 1.16%   |
| Acer Swift              | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2015 | 10        | 11.63%  |
| 2010 | 10        | 11.63%  |
| 2021 | 9         | 10.47%  |
| 2018 | 9         | 10.47%  |
| 2013 | 8         | 9.3%    |
| 2017 | 6         | 6.98%   |
| 2011 | 6         | 6.98%   |
| 2016 | 5         | 5.81%   |
| 2008 | 5         | 5.81%   |
| 2020 | 4         | 4.65%   |
| 2014 | 4         | 4.65%   |
| 2012 | 4         | 4.65%   |
| 2009 | 2         | 2.33%   |
| 2007 | 2         | 2.33%   |
| 2019 | 1         | 1.16%   |
| 2006 | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 86        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 86        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 33        | 38.37%  |
| 8.01-16.0  | 27        | 31.4%   |
| 16.01-24.0 | 16        | 18.6%   |
| 2.01-3.0   | 8         | 9.3%    |
| 32.01-64.0 | 1         | 1.16%   |
| 3.01-4.0   | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 59        | 68.6%   |
| 0.51-1.0 | 22        | 25.58%  |
| 1.01-2.0 | 3         | 3.49%   |
| 2.01-3.0 | 2         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 61        | 70.11%  |
| 2      | 21        | 24.14%  |
| 0      | 3         | 3.45%   |
| 3      | 2         | 2.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 60.47%  |
| Yes       | 34        | 39.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 91.86%  |
| No        | 7         | 8.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 68.6%   |
| No        | 27        | 31.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 16        | 18.6%   |
| Germany     | 7         | 8.14%   |
| Russia      | 6         | 6.98%   |
| Ukraine     | 4         | 4.65%   |
| UK          | 4         | 4.65%   |
| Romania     | 4         | 4.65%   |
| Spain       | 3         | 3.49%   |
| Netherlands | 3         | 3.49%   |
| Italy       | 3         | 3.49%   |
| France      | 3         | 3.49%   |
| Vietnam     | 2         | 2.33%   |
| Poland      | 2         | 2.33%   |
| Peru        | 2         | 2.33%   |
| Mexico      | 2         | 2.33%   |
| Indonesia   | 2         | 2.33%   |
| Hungary     | 2         | 2.33%   |
| Greece      | 2         | 2.33%   |
| Denmark     | 2         | 2.33%   |
| Chile       | 2         | 2.33%   |
| Brazil      | 2         | 2.33%   |
| Tanzania    | 1         | 1.16%   |
| Sweden      | 1         | 1.16%   |
| Portugal    | 1         | 1.16%   |
| Norway      | 1         | 1.16%   |
| Malaysia    | 1         | 1.16%   |
| Lithuania   | 1         | 1.16%   |
| India       | 1         | 1.16%   |
| Georgia     | 1         | 1.16%   |
| Cuba        | 1         | 1.16%   |
| Bulgaria    | 1         | 1.16%   |
| Belarus     | 1         | 1.16%   |
| Austria     | 1         | 1.16%   |
| Argentina   | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 3         | 3.45%   |
| Warsaw                        | 2         | 2.3%    |
| Lima                          | 2         | 2.3%    |
| Leatherhead                   | 2         | 2.3%    |
| Jakarta                       | 2         | 2.3%    |
| Hanoi                         | 2         | 2.3%    |
| Dijon                         | 2         | 2.3%    |
| Amsterdam                     | 2         | 2.3%    |
| Zaporizhzhya                  | 1         | 1.15%   |
| Zapopan                       | 1         | 1.15%   |
| Youngsville                   | 1         | 1.15%   |
| Yaphank                       | 1         | 1.15%   |
| Vilnius                       | 1         | 1.15%   |
| VÃ¤sterÃ¥s                | 1         | 1.15%   |
| Ugarchin                      | 1         | 1.15%   |
| Turley                        | 1         | 1.15%   |
| Turin                         | 1         | 1.15%   |
| Torokszentmiklos              | 1         | 1.15%   |
| Tiruchi                       | 1         | 1.15%   |
| Thessaloniki                  | 1         | 1.15%   |
| Susanville                    | 1         | 1.15%   |
| Suceava                       | 1         | 1.15%   |
| St Petersburg                 | 1         | 1.15%   |
| Shah Alam                     | 1         | 1.15%   |
| Sevastopol                    | 1         | 1.15%   |
| Seattle                       | 1         | 1.15%   |
| San SebastiÃ¡n de los Reyes | 1         | 1.15%   |
| San Luis PotosÃ­ City       | 1         | 1.15%   |
| San Antonio                   | 1         | 1.15%   |
| Riverton                      | 1         | 1.15%   |
| Rio de Janeiro                | 1         | 1.15%   |
| Rho                           | 1         | 1.15%   |
| Ransbach-Baumbach             | 1         | 1.15%   |
| Pruszcz Gdanski               | 1         | 1.15%   |
| Potsdam                       | 1         | 1.15%   |
| Piovene Rocchette             | 1         | 1.15%   |
| Pflugerville                  | 1         | 1.15%   |
| Patterson                     | 1         | 1.15%   |
| Orlando                       | 1         | 1.15%   |
| Oldenburg                     | 1         | 1.15%   |
| Odense                        | 1         | 1.15%   |
| Nesttun                       | 1         | 1.15%   |
| Mt. Pleasant                  | 1         | 1.15%   |
| Minsk                         | 1         | 1.15%   |
| Minneapolis                   | 1         | 1.15%   |
| Mendoza                       | 1         | 1.15%   |
| Mage                          | 1         | 1.15%   |
| Longfield                     | 1         | 1.15%   |
| Leipzig                       | 1         | 1.15%   |
| Lalinde                       | 1         | 1.15%   |
| Kyiv                          | 1         | 1.15%   |
| Kstovo                        | 1         | 1.15%   |
| Krasnoyarsk                   | 1         | 1.15%   |
| Kharkiv                       | 1         | 1.15%   |
| Kassel                        | 1         | 1.15%   |
| K'alak'i T'bilisi             | 1         | 1.15%   |
| Iquique                       | 1         | 1.15%   |
| Inverkeithing                 | 1         | 1.15%   |
| Hvidovre                      | 1         | 1.15%   |
| Hoogeveen                     | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 24        | 24     | 22.02%  |
| Samsung Electronics | 12        | 13     | 11.01%  |
| Toshiba             | 10        | 10     | 9.17%   |
| Kingston            | 10        | 11     | 9.17%   |
| Crucial             | 8         | 8      | 7.34%   |
| Seagate             | 6         | 7      | 5.5%    |
| SanDisk             | 6         | 7      | 5.5%    |
| Intel               | 6         | 7      | 5.5%    |
| Hitachi             | 3         | 3      | 2.75%   |
| HGST                | 3         | 3      | 2.75%   |
| SPCC                | 2         | 3      | 1.83%   |
| Patriot             | 2         | 2      | 1.83%   |
| Fujitsu             | 2         | 2      | 1.83%   |
| A-DATA Technology   | 2         | 2      | 1.83%   |
| Transcend           | 1         | 1      | 0.92%   |
| Team                | 1         | 1      | 0.92%   |
| SK Hynix            | 1         | 1      | 0.92%   |
| Mushkin             | 1         | 1      | 0.92%   |
| Micron Technology   | 1         | 1      | 0.92%   |
| KingSpec            | 1         | 1      | 0.92%   |
| Intenso             | 1         | 1      | 0.92%   |
| Integral            | 1         | 1      | 0.92%   |
| Hewlett-Packard     | 1         | 1      | 0.92%   |
| Corsair             | 1         | 1      | 0.92%   |
| Apple               | 1         | 1      | 0.92%   |
| Apacer              | 1         | 1      | 0.92%   |
| AGI                 | 1         | 1      | 0.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 3         | 2.7%    |
| Kingston SA400S37120G 120GB          | 3         | 2.7%    |
| HGST HTS545050A7E680 500GB           | 3         | 2.7%    |
| Crucial CT500MX500SSD1 500GB         | 3         | 2.7%    |
| WDC WDS120G2G0A-00JH30 120GB         | 2         | 1.8%    |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1.8%    |
| Samsung MZVLW256HEHP-000L7 256GB     | 2         | 1.8%    |
| Kingston SA400S37240G 240GB          | 2         | 1.8%    |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.8%    |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.9%    |
| WDC WDBNCE5000PNC 500GB              | 1         | 0.9%    |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.9%    |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.9%    |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.9%    |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.9%    |
| WDC WD5000BPKX-22HPJT0 500GB         | 1         | 0.9%    |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.9%    |
| WDC WD1600BEVT-80A23T0 160GB         | 1         | 0.9%    |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.9%    |
| WDC WD1600BEKT-66F3T2 160GB          | 1         | 0.9%    |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 0.9%    |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.9%    |
| WDC WD10SDZW-11UMGS0 1TB             | 1         | 0.9%    |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.9%    |
| WDC WD10JMVW-11AJGS4 1TB             | 1         | 0.9%    |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB | 1         | 0.9%    |
| WDC PC SN530 NVMe 256GB              | 1         | 0.9%    |
| Transcend TS240GMTS420S 240GB        | 1         | 0.9%    |
| Toshiba THNSNX024GMNT 24GB           | 1         | 0.9%    |
| Toshiba MQ01ABD100 1TB               | 1         | 0.9%    |
| Toshiba MQ01ABD075 752GB             | 1         | 0.9%    |
| Toshiba MK8034GSX 80GB               | 1         | 0.9%    |
| Toshiba MK3265GSXN 320GB             | 1         | 0.9%    |
| Toshiba MK3261GSYN 320GB             | 1         | 0.9%    |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 0.9%    |
| Team TEAML5Lite3D120G 120GB          | 1         | 0.9%    |
| SPCC Solid State Disk 512GB          | 1         | 0.9%    |
| SPCC Solid State Disk 256GB          | 1         | 0.9%    |
| SK Hynix HFS256G39TND-N210A 256GB    | 1         | 0.9%    |
| Seagate ST980813AS 80GB              | 1         | 0.9%    |
| Seagate ST9640320AS 640GB            | 1         | 0.9%    |
| Seagate ST9320423AS 320GB            | 1         | 0.9%    |
| Seagate ST9160411AS 160GB            | 1         | 0.9%    |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.9%    |
| SanDisk X110 M.2 2260 256GB          | 1         | 0.9%    |
| SanDisk SSD PLUS 480 GB              | 1         | 0.9%    |
| SanDisk SDSSDH3 512G                 | 1         | 0.9%    |
| SanDisk SDSA5GK-016G-1006 16GB       | 1         | 0.9%    |
| SanDisk SD8TB8U512G1001 512GB        | 1         | 0.9%    |
| SanDisk SD6SB1M064G 64GB             | 1         | 0.9%    |
| Samsung SSD PM841 2.5-inch 7mm 256GB | 1         | 0.9%    |
| Samsung SSD 980 PRO 1TB              | 1         | 0.9%    |
| Samsung SSD 950 PRO 512GB            | 1         | 0.9%    |
| Samsung SSD 860 EVO 500GB            | 1         | 0.9%    |
| Samsung SSD 850 EVO 500GB            | 1         | 0.9%    |
| Samsung Portable SSD T5 500GB        | 1         | 0.9%    |
| Samsung MZNLN256HMHQ-000H7 256GB     | 1         | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 17     | 42.5%   |
| Toshiba             | 8         | 8      | 20%     |
| Seagate             | 6         | 7      | 15%     |
| Hitachi             | 3         | 3      | 7.5%    |
| HGST                | 3         | 3      | 7.5%    |
| Samsung Electronics | 2         | 2      | 5%      |
| Fujitsu             | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 8      | 14.81%  |
| Crucial             | 8         | 8      | 14.81%  |
| SanDisk             | 6         | 7      | 11.11%  |
| Samsung Electronics | 6         | 6      | 11.11%  |
| WDC                 | 4         | 4      | 7.41%   |
| Intel               | 4         | 4      | 7.41%   |
| SPCC                | 2         | 3      | 3.7%    |
| Patriot             | 2         | 2      | 3.7%    |
| Transcend           | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| Team                | 1         | 1      | 1.85%   |
| SK Hynix            | 1         | 1      | 1.85%   |
| Mushkin             | 1         | 1      | 1.85%   |
| KingSpec            | 1         | 1      | 1.85%   |
| Intenso             | 1         | 1      | 1.85%   |
| Integral            | 1         | 1      | 1.85%   |
| Hewlett-Packard     | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| Corsair             | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |
| Apacer              | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 45        | 56     | 46.39%  |
| HDD  | 36        | 41     | 37.11%  |
| NVMe | 16        | 18     | 16.49%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 97     | 82.61%  |
| NVMe | 16        | 18     | 17.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 82     | 82.72%  |
| 0.51-1.0   | 13        | 14     | 16.05%  |
| 1.01-2.0   | 1         | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 48        | 55.17%  |
| 251-500    | 15        | 17.24%  |
| 101-250    | 14        | 16.09%  |
| 21-50      | 4         | 4.6%    |
| 501-1000   | 4         | 4.6%    |
| 51-100     | 2         | 2.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 86        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 4.17%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 4.17%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 4.17%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 4.17%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 4.17%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 4.17%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 4.17%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 4.17%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 4.17%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 4.17%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 4.17%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 4.17%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 4.17%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 4.17%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4.17%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 4.17%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 4.17%   |
| Hitachi HTS542516K9SA00 160GB      | 1         | 1      | 4.17%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 4.17%   |
| AGI AGI512G16AI198 512GB           | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 29.17%  |
| Toshiba             | 7         | 7      | 29.17%  |
| Seagate             | 4         | 4      | 16.67%  |
| Samsung Electronics | 2         | 2      | 8.33%   |
| Hitachi             | 2         | 2      | 8.33%   |
| HGST                | 1         | 1      | 4.17%   |
| AGI                 | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 31.82%  |
| Toshiba             | 6         | 6      | 27.27%  |
| Seagate             | 4         | 4      | 18.18%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Hitachi             | 2         | 2      | 9.09%   |
| HGST                | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 22     | 91.3%   |
| NVMe | 1         | 1      | 4.35%   |
| SSD  | 1         | 1      | 4.35%   |

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
| Works    | 63        | 90     | 72.41%  |
| Malfunc  | 23        | 24     | 26.44%  |
| Detected | 1         | 1      | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 74        | 77.08%  |
| AMD                         | 6         | 6.25%   |
| Samsung Electronics         | 5         | 5.21%   |
| Sandisk                     | 3         | 3.13%   |
| Nvidia                      | 2         | 2.08%   |
| Kingston Technology Company | 2         | 2.08%   |
| Silicon Motion              | 1         | 1.04%   |
| Micron Technology           | 1         | 1.04%   |
| KIOXIA                      | 1         | 1.04%   |
| ADATA Technology            | 1         | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 9.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 9.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 5.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 5.71%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 5.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 4.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 3.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 3.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 2.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.86%   |
| Unknown                                                                          | 3         | 2.86%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.9%    |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.95%   |
| Sandisk unknown                                                                  | 1         | 0.95%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.95%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.95%   |
| KIOXIA unknown                                                                   | 1         | 0.95%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.95%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.95%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.95%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.95%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 77        | 74.04%  |
| NVMe | 16        | 15.38%  |
| IDE  | 8         | 7.69%   |
| RAID | 3         | 2.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 90.7%   |
| AMD    | 8         | 9.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz    | 4         | 4.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 3         | 3.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 3         | 3.49%   |
| Intel CPU Version                    | 2         | 2.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 2.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 2         | 2.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 2         | 2.33%   |
| Intel Core i5 CPU M 520 @ 2.40GHz    | 2         | 2.33%   |
| Intel Core i3 CPU M 330 @ 2.13GHz    | 2         | 2.33%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz | 2         | 2.33%   |
| Intel Atom CPU N450 @ 1.66GHz        | 2         | 2.33%   |
| Intel Pentium CPU N3540 @ 2.16GHz    | 1         | 1.16%   |
| Intel Pentium CPU N3530 @ 2.16GHz    | 1         | 1.16%   |
| Intel Core M-5Y71 CPU @ 1.20GHz      | 1         | 1.16%   |
| Intel Core i7-9750HF CPU @ 2.60GHz   | 1         | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 1         | 1.16%   |
| Intel Core i7-7600U CPU @ 2.80GHz    | 1         | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 1         | 1.16%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 1         | 1.16%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 1         | 1.16%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz   | 1         | 1.16%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 1         | 1.16%   |
| Intel Core i7-3630QM CPU @ 2.40GHz   | 1         | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz   | 1         | 1.16%   |
| Intel Core i5-9300H CPU @ 2.40GHz    | 1         | 1.16%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 1         | 1.16%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz   | 1         | 1.16%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz   | 1         | 1.16%   |
| Intel Core i5-4300U CPU @ 1.90GHz    | 1         | 1.16%   |
| Intel Core i5-4300M CPU @ 2.60GHz    | 1         | 1.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.16%   |
| Intel Core i5-3437U CPU @ 1.90GHz    | 1         | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 1         | 1.16%   |
| Intel Core i5-3317U CPU @ 1.70GHz    | 1         | 1.16%   |
| Intel Core i5-10300H CPU @ 2.50GHz   | 1         | 1.16%   |
| Intel Core i5 CPU U 560 @ 1.33GHz    | 1         | 1.16%   |
| Intel Core i5 CPU M 560 @ 2.67GHz    | 1         | 1.16%   |
| Intel Core i5 CPU M 520 @ 2.40GH     | 1         | 1.16%   |
| Intel Core i3-6006U CPU @ 2.00GHz    | 1         | 1.16%   |
| Intel Core i3-4010U CPU @ 1.70GHz    | 1         | 1.16%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 1         | 1.16%   |
| Intel Core i3-3227U CPU @ 1.90GHz    | 1         | 1.16%   |
| Intel Core i3-3217U CPU @ 1.80GHz    | 1         | 1.16%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 1         | 1.16%   |
| Intel Core i3 CPU M 390 @ 2.67GHz    | 1         | 1.16%   |
| Intel Core i3 CPU M 370 @ 2.40GHz    | 1         | 1.16%   |
| Intel Core i3 CPU M 350 @ 2.27GH     | 1         | 1.16%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz | 1         | 1.16%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz | 1         | 1.16%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz | 1         | 1.16%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz | 1         | 1.16%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz | 1         | 1.16%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz | 1         | 1.16%   |
| Intel Core 2 Duo                     | 1         | 1.16%   |
| Intel Core 2 CPU                     | 1         | 1.16%   |
| Intel Celeron CPU N3350 @ 1.10GHz    | 1         | 1.16%   |
| Intel Celeron CPU N3060 @ 1.60GHz    | 1         | 1.16%   |
| Intel Celeron CPU N3050 @ 1.60GHz    | 1         | 1.16%   |
| Intel Celeron CPU N2940 @ 1.83GHz    | 1         | 1.16%   |
| Intel Celeron CPU B830 @ 1.80GHz     | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 32        | 37.21%  |
| Intel Core i3    | 11        | 12.79%  |
| Intel Core i7    | 10        | 11.63%  |
| Intel Core 2 Duo | 9         | 10.47%  |
| Intel Celeron    | 7         | 8.14%   |
| Intel Atom       | 3         | 3.49%   |
| AMD Ryzen 5      | 3         | 3.49%   |
| Other            | 2         | 2.33%   |
| Intel Pentium    | 2         | 2.33%   |
| AMD A6           | 2         | 2.33%   |
| Intel Core M     | 1         | 1.16%   |
| Intel Core 2     | 1         | 1.16%   |
| AMD Ryzen 3      | 1         | 1.16%   |
| AMD E2           | 1         | 1.16%   |
| AMD A10          | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 53        | 61.63%  |
| 4       | 17        | 19.77%  |
| Unknown | 11        | 12.79%  |
| 12      | 2         | 2.33%   |
| 8       | 1         | 1.16%   |
| 6       | 1         | 1.16%   |
| 1       | 1         | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 79        | 91.86%  |
| 2       | 5         | 5.81%   |
| Unknown | 2         | 2.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 53        | 61.63%  |
| 1       | 22        | 25.58%  |
| Unknown | 11        | 12.79%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 12        | 13.95%  |
| Westmere    | 10        | 11.63%  |
| IvyBridge   | 10        | 11.63%  |
| Penryn      | 8         | 9.3%    |
| Skylake     | 7         | 8.14%   |
| Haswell     | 7         | 8.14%   |
| SandyBridge | 6         | 6.98%   |
| Silvermont  | 5         | 5.81%   |
| Core        | 4         | 4.65%   |
| Broadwell   | 4         | 4.65%   |
| Bonnell     | 3         | 3.49%   |
| Zen+        | 2         | 2.33%   |
| Excavator   | 2         | 2.33%   |
| Zen 3       | 1         | 1.16%   |
| Zen 2       | 1         | 1.16%   |
| Piledriver  | 1         | 1.16%   |
| K10 Llano   | 1         | 1.16%   |
| Goldmont    | 1         | 1.16%   |
| CometLake   | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 67%     |
| Nvidia | 18        | 18%     |
| AMD    | 15        | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 9.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.71%   |
| Intel HD Graphics 620                                                                    | 5         | 4.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 3.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 3.81%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.86%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.86%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.86%   |
| Nvidia TU117M                                                                            | 2         | 1.9%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.9%    |
| Intel HD Graphics 530                                                                    | 2         | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.95%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.95%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.95%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.95%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.95%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.95%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.95%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 0.95%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.95%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.95%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 0.95%   |
| Nvidia G86M [Quadro NVS 135M]                                                            | 1         | 0.95%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.95%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.95%   |
| Intel HD Graphics 630                                                                    | 1         | 0.95%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.95%   |
| Intel HD Graphics 520                                                                    | 1         | 0.95%   |
| Intel HD Graphics 500                                                                    | 1         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.95%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.95%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.95%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.95%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.95%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 0.95%   |
| AMD Renoir                                                                               | 1         | 0.95%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1         | 0.95%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 0.95%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 0.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 0.95%   |
| AMD Cezanne                                                                              | 1         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 53.49%  |
| 2 x Intel      | 9         | 10.47%  |
| 1 x AMD        | 9         | 10.47%  |
| 1 x Nvidia     | 8         | 9.3%    |
| Intel + Nvidia | 8         | 9.3%    |
| Intel + AMD    | 4         | 4.65%   |
| AMD + Nvidia   | 2         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 77        | 89.53%  |
| Proprietary | 9         | 10.47%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 80.23%  |
| 0.01-0.5   | 9         | 10.47%  |
| 0.51-1.0   | 4         | 4.65%   |
| 1.01-2.0   | 2         | 2.33%   |
| 5.01-6.0   | 1         | 1.16%   |
| 3.01-4.0   | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 18.48%  |
| AU Optronics            | 15        | 16.3%   |
| Samsung Electronics     | 13        | 14.13%  |
| Chimei Innolux          | 12        | 13.04%  |
| BOE                     | 11        | 11.96%  |
| Lenovo                  | 10        | 10.87%  |
| Apple                   | 6         | 6.52%   |
| Toshiba                 | 1         | 1.09%   |
| Philips                 | 1         | 1.09%   |
| Lenovo Group Limited    | 1         | 1.09%   |
| LED                     | 1         | 1.09%   |
| Chi Mei Optoelectronics | 1         | 1.09%   |
| BenQ                    | 1         | 1.09%   |
| Ancor Communications    | 1         | 1.09%   |
| Acer                    | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 240x130mm 10.7-inch    | 2         | 2.13%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch            | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 2         | 2.13%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 1.06%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch        | 1         | 1.06%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 1.06%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 1.06%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 1         | 1.06%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD03DF 1366x768 340x190mm 15.3-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD0324 1280x800 220x140mm 10.3-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch              | 1         | 1.06%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch              | 1         | 1.06%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 530x300mm 24.0-inch                 | 1         | 1.06%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch                 | 1         | 1.06%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                  | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.06%   |
| Lenovo Group Limited LCD Monitor 1280x800                                | 1         | 1.06%   |
| LED LCD Monitor LED2345 1920x1080 890x500mm 40.2-inch                    | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 360x200mm 16.2-inch         | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 340x190mm 15.3-inch         | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 310x170mm 13.9-inch          | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 310x170mm 13.9-inch         | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 310x170mm 13.9-inch          | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1362 1366x768 290x160mm 13.0-inch          | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 1.06%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 1.06%   |
| BOE LCD Monitor BOE083A 1920x1080 340x190mm 15.3-inch                    | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 39        | 44.32%  |
| 1920x1080 (FHD)   | 25        | 28.41%  |
| 1280x800 (WXGA)   | 12        | 13.64%  |
| 1600x900 (HD+)    | 3         | 3.41%   |
| 2560x1440 (QHD)   | 2         | 2.27%   |
| 1024x600          | 2         | 2.27%   |
| 3840x2160 (4K)    | 1         | 1.14%   |
| 1920x540          | 1         | 1.14%   |
| 1920x1200 (WUXGA) | 1         | 1.14%   |
| 1440x900 (WXGA+)  | 1         | 1.14%   |
| 1024x768 (XGA)    | 1         | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 32.98%  |
| 13      | 24        | 25.53%  |
| 12      | 10        | 10.64%  |
| 14      | 5         | 5.32%   |
| 11      | 4         | 4.26%   |
| 27      | 3         | 3.19%   |
| 24      | 3         | 3.19%   |
| 17      | 3         | 3.19%   |
| 10      | 3         | 3.19%   |
| 23      | 2         | 2.13%   |
| 54      | 1         | 1.06%   |
| 40      | 1         | 1.06%   |
| 31      | 1         | 1.06%   |
| 18      | 1         | 1.06%   |
| 16      | 1         | 1.06%   |
| Unknown | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 48.94%  |
| 201-300     | 31        | 32.98%  |
| 501-600     | 8         | 8.51%   |
| 351-400     | 4         | 4.26%   |
| 801-900     | 1         | 1.06%   |
| 601-700     | 1         | 1.06%   |
| 401-500     | 1         | 1.06%   |
| 1001-1500   | 1         | 1.06%   |
| Unknown     | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 80.95%  |
| 16/10   | 12        | 14.29%  |
| 3/2     | 2         | 2.38%   |
| 4/3     | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 26        | 27.66%  |
| 81-90          | 24        | 25.53%  |
| 61-70          | 10        | 10.64%  |
| 101-110        | 6         | 6.38%   |
| 71-80          | 4         | 4.26%   |
| 51-60          | 4         | 4.26%   |
| 201-250        | 4         | 4.26%   |
| 41-50          | 3         | 3.19%   |
| 301-350        | 3         | 3.19%   |
| 121-130        | 3         | 3.19%   |
| More than 1000 | 1         | 1.06%   |
| 351-500        | 1         | 1.06%   |
| 251-300        | 1         | 1.06%   |
| 141-150        | 1         | 1.06%   |
| 111-120        | 1         | 1.06%   |
| 501-1000       | 1         | 1.06%   |
| Unknown        | 1         | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 39        | 42.39%  |
| 101-120 | 35        | 38.04%  |
| 51-100  | 14        | 15.22%  |
| 161-240 | 3         | 3.26%   |
| Unknown | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 74        | 85.06%  |
| 2     | 11        | 12.64%  |
| 0     | 2         | 2.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 49        | 34.27%  |
| Realtek Semiconductor             | 37        | 25.87%  |
| Broadcom                          | 20        | 13.99%  |
| Qualcomm Atheros                  | 19        | 13.29%  |
| Marvell Technology Group          | 4         | 2.8%    |
| Nvidia                            | 2         | 1.4%    |
| NetGear                           | 2         | 1.4%    |
| Dell                              | 2         | 1.4%    |
| TP-Link                           | 1         | 0.7%    |
| Sierra Wireless                   | 1         | 0.7%    |
| Mercucys                          | 1         | 0.7%    |
| JMicron Technology                | 1         | 0.7%    |
| Hewlett-Packard                   | 1         | 0.7%    |
| Google                            | 1         | 0.7%    |
| Ericsson Business Mobile Networks | 1         | 0.7%    |
| D-Link System                     | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 13.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.33%   |
| Intel Wireless 8260                                               | 6         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 2.78%   |
| Intel Wireless 7265                                               | 4         | 2.22%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 2.22%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.67%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.67%   |
| Intel Wireless 7260                                               | 3         | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.67%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 1.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1.11%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 2         | 1.11%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.11%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.11%   |
| Intel WiFi Link 5100                                              | 2         | 1.11%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.11%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 1.11%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.11%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.56%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                     | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.56%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                   | 1         | 0.56%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 0.56%   |
| Mercucys MERCUSYS Wireless USB Adapter                            | 1         | 0.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.56%   |
| Intel Wireless 3160                                               | 1         | 0.56%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 51.06%  |
| Qualcomm Atheros      | 18        | 19.15%  |
| Broadcom              | 13        | 13.83%  |
| Realtek Semiconductor | 9         | 9.57%   |
| NetGear               | 2         | 2.13%   |
| TP-Link               | 1         | 1.06%   |
| Sierra Wireless       | 1         | 1.06%   |
| Mercucys              | 1         | 1.06%   |
| Dell                  | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 6.19%   |
| Intel Wireless 8260                                            | 6         | 6.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 5.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 5.15%   |
| Intel Wireless 7265                                            | 4         | 4.12%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 4.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 3.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 3.09%   |
| Intel Wireless 8265 / 8275                                     | 3         | 3.09%   |
| Intel Wireless 7260                                            | 3         | 3.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 3.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 3.09%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 3.09%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 3.09%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 2.06%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 2         | 2.06%   |
| Intel WiFi Link 5100                                           | 2         | 2.06%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 2.06%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 2.06%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 2.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 1.03%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 1.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.03%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.03%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                | 1         | 1.03%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 1.03%   |
| Mercucys MERCUSYS Wireless USB Adapter                         | 1         | 1.03%   |
| Intel Wireless 3160                                            | 1         | 1.03%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.03%   |
| Intel Centrino Wireless-N 100                                  | 1         | 1.03%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.03%   |
| Dell Hub of E-Port Replicator                                  | 1         | 1.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.03%   |
| Broadcom BCM43227 802.11b/g/n                                  | 1         | 1.03%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 43.04%  |
| Intel                    | 27        | 34.18%  |
| Broadcom                 | 7         | 8.86%   |
| Marvell Technology Group | 4         | 5.06%   |
| Qualcomm Atheros         | 3         | 3.8%    |
| Nvidia                   | 2         | 2.53%   |
| JMicron Technology       | 1         | 1.27%   |
| Google                   | 1         | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 30.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 12.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 8.86%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 5.06%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 3.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 3.8%    |
| Nvidia MCP79 Ethernet                                             | 2         | 2.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 2.53%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.27%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.27%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.27%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.27%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.27%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.27%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 50.89%  |
| Ethernet | 79        | 46.75%  |
| Unknown  | 3         | 1.78%   |
| Modem    | 1         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 78        | 51.32%  |
| WiFi     | 71        | 46.71%  |
| Unknown  | 3         | 1.97%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 77        | 89.53%  |
| 1     | 9         | 10.47%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 80        | 93.02%  |
| Yes  | 6         | 6.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 42.37%  |
| Broadcom                        | 9         | 15.25%  |
| Apple                           | 6         | 10.17%  |
| Qualcomm Atheros Communications | 5         | 8.47%   |
| Realtek Semiconductor           | 3         | 5.08%   |
| Lite-On Technology              | 2         | 3.39%   |
| IMC Networks                    | 2         | 3.39%   |
| Hewlett-Packard                 | 2         | 3.39%   |
| Foxconn / Hon Hai               | 2         | 3.39%   |
| Dell                            | 2         | 3.39%   |
| Cambridge Silicon Radio         | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 19        | 31.15%  |
| Broadcom BCM2045B (BDC-2.1)                            | 5         | 8.2%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                | 3         | 4.92%   |
| Apple Built-in iSight (no firmware loaded)             | 3         | 4.92%   |
| Realtek  Bluetooth 4.2 Adapter                         | 2         | 3.28%   |
| Realtek Bluetooth Radio                                | 2         | 3.28%   |
| Intel AX200 Bluetooth                                  | 2         | 3.28%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 2         | 3.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 1.64%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)        | 1         | 1.64%   |
| Lite-On Realtek Bluetooth Adapter                      | 1         | 1.64%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                       | 1         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 1         | 1.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 1         | 1.64%   |
| Intel AX201 Bluetooth                                  | 1         | 1.64%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 1.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 1.64%   |
| HP Broadcom 2070 Bluetooth Combo                       | 1         | 1.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 1         | 1.64%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0       | 1         | 1.64%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 1.64%   |
| Dell DW375 Bluetooth Module                            | 1         | 1.64%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 1.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 1         | 1.64%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device | 1         | 1.64%   |
| Broadcom BCM43142 Bluetooth 4.0                        | 1         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 1.64%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]       | 1         | 1.64%   |
| Apple Broadcom Bluetooth 2.1 module                    | 1         | 1.64%   |
| Apple Bluetooth Host Controller                        | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 76        | 78.35%  |
| AMD                 | 10        | 10.31%  |
| Nvidia              | 8         | 8.25%   |
| Texas Instruments   | 1         | 1.03%   |
| GN Netcom           | 1         | 1.03%   |
| Creative Technology | 1         | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 11.4%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 9.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 8.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 5.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 4.39%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 4.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 3.51%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 3.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.63%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.75%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.75%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.75%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.75%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.88%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.88%   |
| Creative Technology SB X-Fi Surround 5.1                                                          | 1         | 0.88%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.88%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 34.34%  |
| SK Hynix            | 15        | 15.15%  |
| Kingston            | 12        | 12.12%  |
| Unknown             | 7         | 7.07%   |
| Micron Technology   | 6         | 6.06%   |
| Ramaxel Technology  | 5         | 5.05%   |
| Nanya Technology    | 4         | 4.04%   |
| Elpida              | 3         | 3.03%   |
| Crucial             | 3         | 3.03%   |
| 48spaces            | 2         | 2.02%   |
| Smart               | 1         | 1.01%   |
| Silicon Power       | 1         | 1.01%   |
| Sesame              | 1         | 1.01%   |
| Kingmax             | 1         | 1.01%   |
| Corsair             | 1         | 1.01%   |
| Apacer              | 1         | 1.01%   |
| A-DATA Technology   | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 3.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 3.74%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 3.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 3.74%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.87%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 1.87%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s                          | 2         | 1.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 2         | 1.87%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 1.87%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 1.87%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 1.87%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.93%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.93%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.93%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.93%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 0.93%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.93%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.93%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.93%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.93%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 0.93%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.93%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.93%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s          | 1         | 0.93%   |
| Silicon Power RAM SP008GBSFU240B02 8GB SODIMM DDR4 2400MT/s               | 1         | 0.93%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                               | 1         | 0.93%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 0.93%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.93%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s                     | 1         | 0.93%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2133MT/s                     | 1         | 0.93%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.93%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.93%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 667MT/s                     | 1         | 0.93%   |
| Ramaxel RAM RMT3190ME76F8F1600 2GB SODIMM DDR3 1067MT/s                   | 1         | 0.93%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.93%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1066MT/s                   | 1         | 0.93%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s                      | 1         | 0.93%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 1         | 0.93%   |
| Nanya RAM Module 2GB SODIMM DDR2 800MT/s                                  | 1         | 0.93%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                                  | 1         | 0.93%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 48        | 57.14%  |
| DDR4   | 21        | 25%     |
| DDR2   | 13        | 15.48%  |
| LPDDR3 | 2         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 98.81%  |
| Row Of Chips | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 35.48%  |
| 2048  | 26        | 27.96%  |
| 8192  | 22        | 23.66%  |
| 16384 | 7         | 7.53%   |
| 1024  | 4         | 4.3%    |
| 32768 | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 31.18%  |
| 1334    | 11        | 11.83%  |
| 667     | 11        | 11.83%  |
| 2667    | 10        | 10.75%  |
| 1333    | 9         | 9.68%   |
| 2400    | 6         | 6.45%   |
| 1067    | 5         | 5.38%   |
| 3200    | 4         | 4.3%    |
| 2133    | 3         | 3.23%   |
| 1867    | 2         | 2.15%   |
| 1066    | 1         | 1.08%   |
| 800     | 1         | 1.08%   |
| Unknown | 1         | 1.08%   |

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
| Chicony Electronics                    | 20        | 30.3%   |
| Realtek Semiconductor                  | 7         | 10.61%  |
| Quanta                                 | 5         | 7.58%   |
| Lite-On Technology                     | 5         | 7.58%   |
| Microdia                               | 4         | 6.06%   |
| IMC Networks                           | 4         | 6.06%   |
| Sunplus Innovation Technology          | 3         | 4.55%   |
| Z-Star Microelectronics                | 2         | 3.03%   |
| Suyin                                  | 2         | 3.03%   |
| Lenovo                                 | 2         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.03%   |
| Alcor Micro                            | 2         | 3.03%   |
| Acer                                   | 2         | 3.03%   |
| Syntek                                 | 1         | 1.52%   |
| Silicon Motion                         | 1         | 1.52%   |
| Primax Electronics                     | 1         | 1.52%   |
| Luxvisions Innotech Limited            | 1         | 1.52%   |
| Importek                               | 1         | 1.52%   |
| Apple                                  | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                                   | 3         | 4.48%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 4.48%   |
| Chicony HD WebCam                                           | 3         | 4.48%   |
| Chicony EasyCamera                                          | 3         | 4.48%   |
| Realtek USB Camera                                          | 2         | 2.99%   |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 2.99%   |
| Quanta HP TrueVision HD Camera                              | 2         | 2.99%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 1.49%   |
| Z-Star Webcam                                               | 1         | 1.49%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.49%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 1.49%   |
| Suyin HD Video WebCam                                       | 1         | 1.49%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.49%   |
| Sunplus Integrated Camera                                   | 1         | 1.49%   |
| Sunplus HP Universal Camera                                 | 1         | 1.49%   |
| Silicon Motion HP Webcam-50                                 | 1         | 1.49%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.49%   |
| Realtek Integrated_Webcam_FHD                               | 1         | 1.49%   |
| Realtek Integrated_Webcam_8M                                | 1         | 1.49%   |
| Realtek HD WebCam                                           | 1         | 1.49%   |
| Quanta Realtek DMFT - RGB                                   | 1         | 1.49%   |
| Quanta HP Webcam                                            | 1         | 1.49%   |
| Quanta HD WebCam                                            | 1         | 1.49%   |
| Primax Dell Laptop Integrated Webcam 2Mpix                  | 1         | 1.49%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.49%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.49%   |
| Microdia Integrated Webcam                                  | 1         | 1.49%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 1.49%   |
| Lite-On TOSHIBA Web Camera - HD                             | 1         | 1.49%   |
| Lite-On HP HD Camera                                        | 1         | 1.49%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 1.49%   |
| Lenovo Integrated Webcam                                    | 1         | 1.49%   |
| Importek TOSHIBA Web Camera                                 | 1         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.49%   |
| IMC Networks SunplusIT Integrated Camera                    | 1         | 1.49%   |
| IMC Networks Integrated Camera                              | 1         | 1.49%   |
| IMC Networks EasyCamera                                     | 1         | 1.49%   |
| Chicony Webcam-101                                          | 1         | 1.49%   |
| Chicony UVC 1.00 device HD UVC WebCam                       | 1         | 1.49%   |
| Chicony USB2.0 VGA UVC WebCam                               | 1         | 1.49%   |
| Chicony USB 2.0 VGA UVC WebCam                              | 1         | 1.49%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.49%   |
| Chicony thinkpad t430s camera                               | 1         | 1.49%   |
| Chicony Integrated Camera                                   | 1         | 1.49%   |
| Chicony HP Webcam                                           | 1         | 1.49%   |
| Chicony HD WebCam (Acer)                                    | 1         | 1.49%   |
| Chicony Chicony USB 2.0 Camera                              | 1         | 1.49%   |
| Chicony 1.3M Webcam                                         | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 1.49%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 1.49%   |
| Alcor Micro HD WebCam                                       | 1         | 1.49%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 1.49%   |
| Acer ThinkPad P50 Integrated Camera                         | 1         | 1.49%   |
| Acer SunplusIT INC. Integrated Camera                       | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 36.84%  |
| Upek                  | 5         | 26.32%  |
| STMicroelectronics    | 2         | 10.53%  |
| LighTuning Technology | 2         | 10.53%  |
| AuthenTec             | 2         | 10.53%  |
| Synaptics             | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 21.05%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 10.53%  |
| Validity Sensors Synaptics WBDI                        | 2         | 10.53%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS491                                | 1         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.26%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 5.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| AuthenTec AES2810                                      | 1         | 5.26%   |
| AuthenTec AES1600                                      | 1         | 5.26%   |

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
| 1     | 34        | 39.08%  |
| 2     | 24        | 27.59%  |
| 0     | 14        | 16.09%  |
| 3     | 10        | 11.49%  |
| 4     | 5         | 5.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 57        | 47.11%  |
| Fingerprint reader       | 19        | 15.7%   |
| Net/wireless             | 18        | 14.88%  |
| Bluetooth                | 15        | 12.4%   |
| Card reader              | 11        | 9.09%   |
| Sound                    | 1         | 0.83%   |

