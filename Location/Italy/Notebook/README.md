BSD in Italy - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

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

Total: 76

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| eMachines     | eME728                      | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| HP            | Laptop 15-da0xxx            | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Unknown       | Unknown                     | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Acer          | AOD260                      | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Acer          | Aspire E1-522               | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| Acer          | Aspire E1-522               | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Deciso        | OPNsense Appliance          | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| ASUSTek       | X555LJ                      | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| TUXEDO        | N14xWU                      | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Unknown       | Unknown                     | [341401bb02](https://bsd-hardware.info/?probe=341401bb02) | Jan 04, 2022 |
| Unknown       | Unknown                     | [46e5f9b021](https://bsd-hardware.info/?probe=46e5f9b021) | Dec 29, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| Acer          | Aspire 5749Z                | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| ASUSTek       | 1000                        | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Toshiba       | Satellite C855-1U4          | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| HP            | ProBook 470 G4              | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | [40c180238f](https://bsd-hardware.info/?probe=40c180238f) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| ASUSTek       | X555LJ                      | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| Lenovo        | G505 20240                  | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| Lenovo        | B590 62743PG                | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| HP            | Laptop 15-da0xxx            | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| HP            | Laptop 15-da0xxx            | [a7a25be087](https://bsd-hardware.info/?probe=a7a25be087) | Mar 16, 2021 |
| HP            | Laptop 15-da0xxx            | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| ASUSTek       | G1S                         | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Acer          | Extensa 5635Z               | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| eMachines     | eME732ZG                    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | ProBook 470 G4              | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| HP            | Laptop 15-da0xxx            | [d6bc2b2c1d](https://bsd-hardware.info/?probe=d6bc2b2c1d) | Feb 08, 2021 |
| ASUSTek       | X502CA                      | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| HP            | Laptop 15-da0xxx            | [869d894f4f](https://bsd-hardware.info/?probe=869d894f4f) | Jan 30, 2021 |
| HP            | Laptop 15-da0xxx            | [3e37c56f14](https://bsd-hardware.info/?probe=3e37c56f14) | Jan 23, 2021 |
| Apple         | MacBook4,1                  | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| HP            | ProBook 470 G4              | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| HP            | ProBook 470 G4              | [55c762d22e](https://bsd-hardware.info/?probe=55c762d22e) | Jan 17, 2021 |
| HP            | ProBook 470 G4              | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Dell          | Precision 3510              | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| HP            | Laptop 15-da0xxx            | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Apple         | MacBookAir7,2               | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2f119a81b4](https://bsd-hardware.info/?probe=2f119a81b4) | Aug 13, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 10        | 17.86%  |
| helloSystem 0.5.0    | 5         | 8.93%   |
| helloSystem 0.4.0    | 5         | 8.93%   |
| helloSystem 0.6.0    | 3         | 5.36%   |
| NomadBSD 1.3.2       | 2         | 3.57%   |
| helloSystem 0.3.0    | 2         | 3.57%   |
| GhostBSD 21.08.27    | 2         | 3.57%   |
| GhostBSD 20.04.02    | 2         | 3.57%   |
| OPNsense 22.1.9      | 1         | 1.79%   |
| OPNsense 22.1.6      | 1         | 1.79%   |
| OPNsense 21.7.7      | 1         | 1.79%   |
| OPNsense 21.1        | 1         | 1.79%   |
| OpenBSD 7.1          | 1         | 1.79%   |
| OpenBSD 6.8          | 1         | 1.79%   |
| OpenBSD 6.7          | 1         | 1.79%   |
| NomadBSD 5806f915    | 1         | 1.79%   |
| NomadBSD 1.4         | 1         | 1.79%   |
| NomadBSD 1.3.1       | 1         | 1.79%   |
| NetBSD 9.2_STABLE    | 1         | 1.79%   |
| NetBSD 9.2           | 1         | 1.79%   |
| NetBSD 9.1           | 1         | 1.79%   |
| NetBSD 9.0           | 1         | 1.79%   |
| helloSystem 0.8.0    | 1         | 1.79%   |
| GhostBSD 22.06.26    | 1         | 1.79%   |
| FreeBSD 14.0-CURRENT | 1         | 1.79%   |
| FreeBSD 13.1         | 1         | 1.79%   |
| FreeBSD 13.0-p4      | 1         | 1.79%   |
| FreeBSD 13.0-CURRENT | 1         | 1.79%   |
| FreeBSD 13.0         | 1         | 1.79%   |
| FreeBSD 12.2-p4      | 1         | 1.79%   |
| FreeBSD 12.2-p2      | 1         | 1.79%   |
| FreeBSD 12.1-p10     | 1         | 1.79%   |
| FreeBSD 12.0-p13     | 1         | 1.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 24        | 46.15%  |
| FreeBSD     | 9         | 17.31%  |
| NomadBSD    | 5         | 9.62%   |
| OPNsense    | 4         | 7.69%   |
| GhostBSD    | 4         | 7.69%   |
| OpenBSD     | 3         | 5.77%   |
| NetBSD      | 3         | 5.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 49        | 96.08%  |
| i386  | 2         | 3.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 24        | 45.28%  |
| Console      | 6         | 11.32%  |
| Openbox      | 5         | 9.43%   |
| i3           | 3         | 5.66%   |
| Cinnamon     | 3         | 5.66%   |
| XFCE         | 2         | 3.77%   |
| KDE5         | 2         | 3.77%   |
| fvwm         | 2         | 3.77%   |
| ctwm         | 2         | 3.77%   |
| TWM          | 1         | 1.89%   |
| MATE         | 1         | 1.89%   |
| LXQt         | 1         | 1.89%   |
| Fluxbox      | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 47        | 92.16%  |
| Console | 4         | 7.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 31        | 60.78%  |
| Console | 13        | 25.49%  |
| LightDM | 4         | 7.84%   |
| SDDM    | 2         | 3.92%   |
| XDM     | 1         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| en_US            | 31        | 59.62%  |
| it_IT            | 8         | 15.38%  |
| Unknown          | 7         | 13.46%  |
| C                | 2         | 3.85%   |
| ru_RU            | 1         | 1.92%   |
| it_IT.ISO8859-15 | 1         | 1.92%   |
| it_IT.ISO8859-1  | 1         | 1.92%   |
| en_GB            | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 43        | 84.31%  |
| BIOS | 8         | 15.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 30        | 57.69%  |
| Ufs    | 15        | 28.85%  |
| Cd9660 | 4         | 7.69%   |
| Ffs    | 3         | 5.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 45        | 88.24%  |
| MBR     | 4         | 7.84%   |
| Unknown | 2         | 3.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 13        | 25.49%  |
| ASUSTek Computer    | 10        | 19.61%  |
| Hewlett-Packard     | 5         | 9.8%    |
| Acer                | 5         | 9.8%    |
| Dell                | 3         | 5.88%   |
| Apple               | 3         | 5.88%   |
| Toshiba             | 2         | 3.92%   |
| eMachines           | 2         | 3.92%   |
| Unknown             | 2         | 3.92%   |
| TUXEDO              | 1         | 1.96%   |
| Samsung Electronics | 1         | 1.96%   |
| Packard Bell        | 1         | 1.96%   |
| MSI                 | 1         | 1.96%   |
| IBM                 | 1         | 1.96%   |
| Deciso              | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Laptop 15-da0xxx                      | 2         | 3.92%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 3.92%   |
| Apple MacBook4,1                         | 2         | 3.92%   |
| Unknown                                  | 2         | 3.92%   |
| TUXEDO N14xWU                            | 1         | 1.96%   |
| Toshiba Satellite C855-1U4               | 1         | 1.96%   |
| Toshiba PORTEGE M780                     | 1         | 1.96%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 1.96%   |
| Packard Bell EasyNote_MX61-B-038         | 1         | 1.96%   |
| MSI GF65 Thin 10SER                      | 1         | 1.96%   |
| Lenovo ThinkPad X260 20F5S82N00          | 1         | 1.96%   |
| Lenovo ThinkPad X250 20CMS0FA00          | 1         | 1.96%   |
| Lenovo ThinkPad X240 20AMS0J01N          | 1         | 1.96%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00 | 1         | 1.96%   |
| Lenovo ThinkPad T495 20NJS0KP00          | 1         | 1.96%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 1.96%   |
| Lenovo ThinkPad T440 20B7S1C600          | 1         | 1.96%   |
| Lenovo ThinkPad T430 23501B3             | 1         | 1.96%   |
| Lenovo ThinkPad T420 4236BD5             | 1         | 1.96%   |
| Lenovo ThinkPad L530 24812TG             | 1         | 1.96%   |
| Lenovo G505 20240                        | 1         | 1.96%   |
| Lenovo G50-45 80E3                       | 1         | 1.96%   |
| Lenovo B590 62743PG                      | 1         | 1.96%   |
| IBM ThinkPad R51 2887AVG                 | 1         | 1.96%   |
| HP ProBook 470 G4                        | 1         | 1.96%   |
| HP Mini 210-1000                         | 1         | 1.96%   |
| HP EliteBook 6930p                       | 1         | 1.96%   |
| eMachines eME732ZG                       | 1         | 1.96%   |
| eMachines eME728                         | 1         | 1.96%   |
| Dell Precision 3510                      | 1         | 1.96%   |
| Dell Latitude E5450                      | 1         | 1.96%   |
| Dell Inspiron 15-3552                    | 1         | 1.96%   |
| Deciso OPNsense Appliance                | 1         | 1.96%   |
| ASUS X555LJ                              | 1         | 1.96%   |
| ASUS X555LD                              | 1         | 1.96%   |
| ASUS X502CA                              | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X515UA_M515UA   | 1         | 1.96%   |
| ASUS K52F                                | 1         | 1.96%   |
| ASUS G1S                                 | 1         | 1.96%   |
| ASUS F50SL                               | 1         | 1.96%   |
| ASUS 1000                                | 1         | 1.96%   |
| Apple MacBookAir7,2                      | 1         | 1.96%   |
| Acer V5-131                              | 1         | 1.96%   |
| Acer Extensa 5635Z                       | 1         | 1.96%   |
| Acer Aspire E1-522                       | 1         | 1.96%   |
| Acer Aspire 5749Z                        | 1         | 1.96%   |
| Acer AOD260                              | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 19.61%  |
| ASUS VivoBook         | 3         | 5.88%   |
| HP Laptop             | 2         | 3.92%   |
| Apple MacBook4        | 2         | 3.92%   |
| Acer Aspire           | 2         | 3.92%   |
| Unknown               | 2         | 3.92%   |
| TUXEDO N14xWU         | 1         | 1.96%   |
| Toshiba Satellite     | 1         | 1.96%   |
| Toshiba PORTEGE       | 1         | 1.96%   |
| Samsung 3570R         | 1         | 1.96%   |
| Packard Bell EasyNote | 1         | 1.96%   |
| MSI GF65              | 1         | 1.96%   |
| Lenovo G505           | 1         | 1.96%   |
| Lenovo G50-45         | 1         | 1.96%   |
| Lenovo B590           | 1         | 1.96%   |
| IBM ThinkPad          | 1         | 1.96%   |
| HP ProBook            | 1         | 1.96%   |
| HP Mini               | 1         | 1.96%   |
| HP EliteBook          | 1         | 1.96%   |
| eMachines eME732ZG    | 1         | 1.96%   |
| eMachines eME728      | 1         | 1.96%   |
| Dell Precision        | 1         | 1.96%   |
| Dell Latitude         | 1         | 1.96%   |
| Dell Inspiron         | 1         | 1.96%   |
| Deciso OPNsense       | 1         | 1.96%   |
| ASUS X555LJ           | 1         | 1.96%   |
| ASUS X555LD           | 1         | 1.96%   |
| ASUS X502CA           | 1         | 1.96%   |
| ASUS K52F             | 1         | 1.96%   |
| ASUS G1S              | 1         | 1.96%   |
| ASUS F50SL            | 1         | 1.96%   |
| ASUS 1000             | 1         | 1.96%   |
| Apple MacBookAir7     | 1         | 1.96%   |
| Acer V5-131           | 1         | 1.96%   |
| Acer Extensa          | 1         | 1.96%   |
| Acer AOD260           | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 8         | 15.69%  |
| 2019 | 7         | 13.73%  |
| 2011 | 5         | 9.8%    |
| 2014 | 4         | 7.84%   |
| 2010 | 4         | 7.84%   |
| 2020 | 3         | 5.88%   |
| 2016 | 3         | 5.88%   |
| 2015 | 3         | 5.88%   |
| 2008 | 3         | 5.88%   |
| 2021 | 2         | 3.92%   |
| 2018 | 2         | 3.92%   |
| 2009 | 2         | 3.92%   |
| 2007 | 2         | 3.92%   |
| 2022 | 1         | 1.96%   |
| 2012 | 1         | 1.96%   |
| 2006 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 51        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 20        | 38.46%  |
| 4.01-8.0   | 19        | 36.54%  |
| 2.01-3.0   | 4         | 7.69%   |
| 16.01-24.0 | 4         | 7.69%   |
| 32.01-64.0 | 2         | 3.85%   |
| 3.01-4.0   | 1         | 1.92%   |
| 24.01-32.0 | 1         | 1.92%   |
| 0.01-0.5   | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 34        | 65.38%  |
| 0.51-1.0  | 8         | 15.38%  |
| 2.01-3.0  | 3         | 5.77%   |
| Unknown   | 3         | 5.77%   |
| 4.01-8.0  | 2         | 3.85%   |
| 1.01-2.0  | 1         | 1.92%   |
| 8.01-16.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 73.08%  |
| 2      | 12        | 23.08%  |
| 0      | 2         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 63.46%  |
| Yes       | 19        | 36.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 90.2%   |
| No        | 5         | 9.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 92.16%  |
| No        | 4         | 7.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 57.69%  |
| No        | 22        | 42.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 51        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Rome                     | 9         | 15.52%  |
| Milan                    | 5         | 8.62%   |
| Turin                    | 3         | 5.17%   |
| Bologna                  | 3         | 5.17%   |
| Trieste                  | 2         | 3.45%   |
| Rho                      | 2         | 3.45%   |
| Monterotondo             | 2         | 3.45%   |
| Brescia                  | 2         | 3.45%   |
| Vigonovo                 | 1         | 1.72%   |
| Udine                    | 1         | 1.72%   |
| Solarino                 | 1         | 1.72%   |
| Sesto San Giovanni       | 1         | 1.72%   |
| Saronno                  | 1         | 1.72%   |
| Roncade                  | 1         | 1.72%   |
| Resana                   | 1         | 1.72%   |
| Piovene Rocchette        | 1         | 1.72%   |
| Pessano Con Bornago      | 1         | 1.72%   |
| Passignano sul Trasimeno | 1         | 1.72%   |
| Padova                   | 1         | 1.72%   |
| Nughedu San Nicolo       | 1         | 1.72%   |
| Massa Lombarda           | 1         | 1.72%   |
| Malnate                  | 1         | 1.72%   |
| Macerata                 | 1         | 1.72%   |
| Lurago Marinone          | 1         | 1.72%   |
| Lissone                  | 1         | 1.72%   |
| Genzano di Roma          | 1         | 1.72%   |
| Galliera Veneta          | 1         | 1.72%   |
| Gallarate                | 1         | 1.72%   |
| Fiumicino                | 1         | 1.72%   |
| Farneto                  | 1         | 1.72%   |
| Concesio                 | 1         | 1.72%   |
| Cogolo                   | 1         | 1.72%   |
| Cardito                  | 1         | 1.72%   |
| Brugherio                | 1         | 1.72%   |
| Bergamo                  | 1         | 1.72%   |
| Arezzo                   | 1         | 1.72%   |
| Albano Sant'Alessandro   | 1         | 1.72%   |
| Adelfia                  | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 19     | 17.24%  |
| WDC                 | 6         | 7      | 10.34%  |
| Toshiba             | 5         | 5      | 8.62%   |
| Seagate             | 5         | 9      | 8.62%   |
| Crucial             | 5         | 7      | 8.62%   |
| SanDisk             | 4         | 4      | 6.9%    |
| Kingston            | 4         | 5      | 6.9%    |
| Hitachi             | 3         | 4      | 5.17%   |
| Leven               | 2         | 2      | 3.45%   |
| KingSpec            | 2         | 2      | 3.45%   |
| Union Memory        | 1         | 1      | 1.72%   |
| Transcend           | 1         | 1      | 1.72%   |
| Micron Technology   | 1         | 1      | 1.72%   |
| KingDian            | 1         | 1      | 1.72%   |
| Intenso             | 1         | 1      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| Indilinx            | 1         | 1      | 1.72%   |
| HGST                | 1         | 1      | 1.72%   |
| Fujitsu             | 1         | 1      | 1.72%   |
| FORESEE             | 1         | 2      | 1.72%   |
| ASUSTek Computer    | 1         | 2      | 1.72%   |
| Apple               | 1         | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 3.23%   |
| Samsung SSD 860 EVO 500GB                       | 2         | 3.23%   |
| Samsung SSD 860 EVO 250GB                       | 2         | 3.23%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 3.23%   |
| KingSpec Q-720 720GB                            | 2         | 3.23%   |
| WDC WDS120G2G0A-00JH30 120GB                    | 1         | 1.61%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 1.61%   |
| WDC WD3200BEKX-60B7WT0 320GB                    | 1         | 1.61%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 1.61%   |
| WDC WD2500BEVS-22UST0 250GB                     | 1         | 1.61%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 1.61%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 1.61%   |
| Toshiba TR200 240GB                             | 1         | 1.61%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.61%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.61%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 1.61%   |
| Toshiba MK2561GSYN 250GB                        | 1         | 1.61%   |
| Seagate ST9320320AS 320GB                       | 1         | 1.61%   |
| Seagate ST9160821AS 160GB                       | 1         | 1.61%   |
| Seagate ST9160411AS 160GB                       | 1         | 1.61%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.61%   |
| Seagate ST500LM030-1RK17D 500GB                 | 1         | 1.61%   |
| Seagate ST1000LM014-1EJ164 1TB                  | 1         | 1.61%   |
| SanDisk X400 M.2 2280 512GB                     | 1         | 1.61%   |
| SanDisk SSD P4 8GB                              | 1         | 1.61%   |
| SanDisk SDSSDP064G 64GB                         | 1         | 1.61%   |
| SanDisk SD9SN8W-128G-1006 128GB                 | 1         | 1.61%   |
| Samsung SSD 970 EVO 250GB                       | 1         | 1.61%   |
| Samsung SSD 870 EVO 1TB                         | 1         | 1.61%   |
| Samsung SSD 860 QVO 1TB                         | 1         | 1.61%   |
| Samsung SSD 850 EVO 250GB                       | 1         | 1.61%   |
| Samsung MZVLQ512HALU-00000 512GB                | 1         | 1.61%   |
| Samsung MZVLB512HAJQ-000L7 512GB                | 1         | 1.61%   |
| Micron 2210_MTFDHBA512QFD 512GB                 | 1         | 1.61%   |
| Leven JAJS600M512C 512GB                        | 1         | 1.61%   |
| Leven JAJS300M480C 480GB                        | 1         | 1.61%   |
| Kingston SA400S37240G 240GB                     | 1         | 1.61%   |
| Kingston SA400S37120G 120GB                     | 1         | 1.61%   |
| Kingston RBUSNS8154P3256GJ3 256GB               | 1         | 1.61%   |
| Kingston OM8PCP3512F-AB 512GB                   | 1         | 1.61%   |
| KingDian S200 60GB                              | 1         | 1.61%   |
| Intenso SSD Sata III 256GB                      | 1         | 1.61%   |
| Intel SSDSC2BF180A4L 180GB                      | 1         | 1.61%   |
| Indilinx InM2246S3-64G                          | 1         | 1.61%   |
| Hitachi HTS548040M9AT00 40GB                    | 1         | 1.61%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 1.61%   |
| Hitachi HTS542525K9SA00 250GB                   | 1         | 1.61%   |
| HGST HTS545050A7E680 500GB                      | 1         | 1.61%   |
| Fujitsu MHY2120BH 120GB                         | 1         | 1.61%   |
| FORESEE 128GB SSD                               | 1         | 1.61%   |
| Crucial CT525MX300SSD1 528GB                    | 1         | 1.61%   |
| Crucial CT500MX500SSD1 500GB                    | 1         | 1.61%   |
| Crucial CT240BX500SSD1 240GB                    | 1         | 1.61%   |
| Crucial CT120BX300SSD1 120GB                    | 1         | 1.61%   |
| Crucial CT1000MX500SSD1 1TB                     | 1         | 1.61%   |
| ASUS PHISON SSD 32GB                            | 1         | 1.61%   |
| Apple SSD SM0128G 121GB                         | 1         | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 9      | 29.41%  |
| Toshiba | 4         | 4      | 23.53%  |
| WDC     | 3         | 4      | 17.65%  |
| Hitachi | 3         | 4      | 17.65%  |
| HGST    | 1         | 1      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 16     | 23.53%  |
| Crucial             | 5         | 7      | 14.71%  |
| SanDisk             | 4         | 4      | 11.76%  |
| WDC                 | 3         | 3      | 8.82%   |
| Leven               | 2         | 2      | 5.88%   |
| Kingston            | 2         | 2      | 5.88%   |
| KingSpec            | 2         | 2      | 5.88%   |
| Toshiba             | 1         | 1      | 2.94%   |
| KingDian            | 1         | 1      | 2.94%   |
| Intenso             | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Indilinx            | 1         | 1      | 2.94%   |
| FORESEE             | 1         | 2      | 2.94%   |
| ASUSTek Computer    | 1         | 2      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 31        | 46     | 56.36%  |
| HDD  | 16        | 23     | 29.09%  |
| NVMe | 8         | 9      | 14.55%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 69     | 84.31%  |
| NVMe | 8         | 9      | 15.69%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 49     | 84.44%  |
| 0.51-1.0   | 7         | 20     | 15.56%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 25        | 47.17%  |
| 101-250    | 10        | 18.87%  |
| 251-500    | 9         | 16.98%  |
| 21-50      | 5         | 9.43%   |
| 501-1000   | 2         | 3.77%   |
| 51-100     | 2         | 3.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 47        | 87.04%  |
| 21-50   | 6         | 11.11%  |
| 51-100  | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB        | 1         | 1      | 11.11%  |
| Seagate ST9160821AS 160GB       | 1         | 1      | 11.11%  |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 11.11%  |
| SanDisk SDSSDP064G 64GB         | 1         | 1      | 11.11%  |
| SanDisk SD9SN8W-128G-1006 128GB | 1         | 1      | 11.11%  |
| Intel SSDSC2BF180A4L 180GB      | 1         | 1      | 11.11%  |
| Hitachi HTS548040M9AT00 40GB    | 1         | 2      | 11.11%  |
| Hitachi HTS545050A7E380 500GB   | 1         | 1      | 11.11%  |
| Crucial CT525MX300SSD1 528GB    | 1         | 3      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 22.22%  |
| SanDisk | 2         | 2      | 22.22%  |
| Hitachi | 2         | 3      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Intel   | 1         | 1      | 11.11%  |
| Crucial | 1         | 3      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| Hitachi | 2         | 3      | 40%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 55.56%  |
| SSD  | 4         | 6      | 44.44%  |

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
| Works    | 41        | 64     | 80.39%  |
| Malfunc  | 9         | 12     | 17.65%  |
| Detected | 1         | 2      | 1.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 38        | 67.86%  |
| AMD                              | 7         | 12.5%   |
| Samsung Electronics              | 4         | 7.14%   |
| Kingston Technology Company      | 2         | 3.57%   |
| Union Memory (Shenzhen)          | 1         | 1.79%   |
| Silicon Integrated Systems [SiS] | 1         | 1.79%   |
| Micron Technology                | 1         | 1.79%   |
| JMicron Technology               | 1         | 1.79%   |
| Unknown                          | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 10.77%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 9.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 6.15%   |
| Unknown                                                                                | 4         | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 4.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 4.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 4.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 4.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 3.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 3.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 3.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 3.08%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 1.54%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1.54%   |
| Samsung SM951 AHCI                                                                     | 1         | 1.54%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 1.54%   |
| JMicron JMB360 AHCI Controller                                                         | 1         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.54%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.54%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.54%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 1         | 1.54%   |
| AMD SB600 IDE                                                                          | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 66.67%  |
| IDE  | 10        | 16.67%  |
| NVMe | 8         | 13.33%  |
| RAID | 2         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 82.35%  |
| AMD    | 9         | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 3.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 3.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 3.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 2         | 3.85%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 2         | 3.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 3.85%   |
| Intel Pentium M processor                       | 1         | 1.92%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 1.92%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 1.92%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 1.92%   |
| Intel Pentium CPU P6200 @ 2.13GH                | 1         | 1.92%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 1.92%   |
| Intel Pentium CPU 997 @ 1.60GHz                 | 1         | 1.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 1.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 1.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 1.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.92%   |
| Intel Core i5-5350U CPU @ 1.80GHz               | 1         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 1.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.92%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 1.92%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 1.92%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 1.92%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 1.92%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 1         | 1.92%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 1.92%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1         | 1.92%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 1.92%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz            | 1         | 1.92%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 1.92%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 1.92%   |
| Intel Celeron CPU 847 @ 1.10GHz                 | 1         | 1.92%   |
| Intel Celeron CPU 1017U @ 1.60GHz               | 1         | 1.92%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 1.92%   |
| Intel 686-class                                 | 1         | 1.92%   |
| AMD Turion 64 X2 Mobile Technology TL-60        | 1         | 1.92%   |
| AMD Ryzen Embedded V1500B                       | 1         | 1.92%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.92%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics     | 1         | 1.92%   |
| AMD A6-5200 APU with Radeon HD Graphics         | 1         | 1.92%   |
| AMD A4-5000 APU with Radeon HD Graphics         | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 28.85%  |
| Intel Core i7           | 6         | 11.54%  |
| Intel Core 2 Duo        | 5         | 9.62%   |
| Intel Pentium           | 4         | 7.69%   |
| Intel Core i3           | 3         | 5.77%   |
| Intel Celeron           | 3         | 5.77%   |
| Intel Atom              | 3         | 5.77%   |
| AMD Ryzen 5             | 3         | 5.77%   |
| Intel Pentium Dual-Core | 2         | 3.85%   |
| Intel Pentium M         | 1         | 1.92%   |
| Intel 686-class         | 1         | 1.92%   |
| AMD Turion 64 X2 Mobile | 1         | 1.92%   |
| AMD Ryzen Embedded      | 1         | 1.92%   |
| AMD Ryzen 7 PRO         | 1         | 1.92%   |
| AMD E1                  | 1         | 1.92%   |
| AMD A6                  | 1         | 1.92%   |
| AMD A4                  | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 30        | 57.69%  |
| Unknown | 8         | 15.38%  |
| 4       | 7         | 13.46%  |
| 8       | 4         | 7.69%   |
| 1       | 2         | 3.85%   |
| 12      | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 49        | 94.23%  |
| 2       | 2         | 3.85%   |
| Unknown | 1         | 1.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 26        | 50%     |
| 1       | 18        | 34.62%  |
| Unknown | 8         | 15.38%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| SandyBridge | 6         | 11.54%  |
| Penryn      | 6         | 11.54%  |
| KabyLake    | 5         | 9.62%   |
| IvyBridge   | 5         | 9.62%   |
| Broadwell   | 5         | 9.62%   |
| Zen+        | 3         | 5.77%   |
| Westmere    | 3         | 5.77%   |
| Haswell     | 3         | 5.77%   |
| Bonnell     | 3         | 5.77%   |
| Skylake     | 2         | 3.85%   |
| Jaguar      | 2         | 3.85%   |
| Unknown     | 2         | 3.85%   |
| Zen         | 1         | 1.92%   |
| Silvermont  | 1         | 1.92%   |
| Puma        | 1         | 1.92%   |
| P6          | 1         | 1.92%   |
| K8 Hammer   | 1         | 1.92%   |
| Core        | 1         | 1.92%   |
| CometLake   | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 66.07%  |
| AMD    | 13        | 23.21%  |
| Nvidia | 6         | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 10%     |
| Intel HD Graphics 5500                                                                   | 4         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 6.67%   |
| Intel UHD Graphics 620                                                                   | 3         | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 5%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 3.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 3.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.33%   |
| Intel HD Graphics 620                                                                    | 2         | 3.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.33%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 3.33%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.67%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.67%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.67%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.67%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.67%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.67%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.67%   |
| Intel HD Graphics 530                                                                    | 1         | 1.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.67%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.67%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                                  | 1         | 1.67%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 1.67%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 1.67%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.67%   |
| AMD RV610/M72-S [Mobility Radeon HD 2400]                                                | 1         | 1.67%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.67%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 1.67%   |
| AMD Lucienne                                                                             | 1         | 1.67%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 1.67%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.67%   |
| AMD Cape Verde PRO / Venus LE / Tropo PRO-L [Radeon HD 8830M / R7 250 / R7 M465X]        | 1         | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 47.06%  |
| 1 x AMD        | 11        | 21.57%  |
| 2 x Intel      | 7         | 13.73%  |
| Intel + Nvidia | 5         | 9.8%    |
| Other          | 1         | 1.96%   |
| 2 x AMD        | 1         | 1.96%   |
| 1 x Nvidia     | 1         | 1.96%   |
| Intel + AMD    | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 88.46%  |
| Unknown     | 5         | 9.62%   |
| Proprietary | 1         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 78.43%  |
| 0.01-0.5   | 7         | 13.73%  |
| 1.01-2.0   | 3         | 5.88%   |
| 3.01-4.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 13        | 32.5%   |
| LG Display          | 7         | 17.5%   |
| BOE                 | 5         | 12.5%   |
| Chimei Innolux      | 4         | 10%     |
| Samsung Electronics | 2         | 5%      |
| Lenovo              | 2         | 5%      |
| Apple               | 2         | 5%      |
| ___                 | 1         | 2.5%    |
| LG Philips          | 1         | 2.5%    |
| Hewlett-Packard     | 1         | 2.5%    |
| HannStar            | 1         | 2.5%    |
| Fujitsu Siemens     | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 2         | 5%      |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 2         | 5%      |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 2.5%    |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 2.5%    |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch          | 1         | 2.5%    |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 2.5%    |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 2.5%    |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch           | 1         | 2.5%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 2.5%    |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 1         | 2.5%    |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                 | 1         | 2.5%    |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                 | 1         | 2.5%    |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                 | 1         | 2.5%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO31D2 1024x600 220x130mm 10.1-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch        | 1         | 2.5%    |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 1         | 2.5%    |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                 | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 21        | 53.85%  |
| 1920x1080 (FHD)  | 11        | 28.21%  |
| 1600x900 (HD+)   | 2         | 5.13%   |
| 1280x800 (WXGA)  | 2         | 5.13%   |
| 1024x600         | 2         | 5.13%   |
| 1440x900 (WXGA+) | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 21        | 52.5%   |
| 13      | 10        | 25%     |
| 12      | 2         | 5%      |
| 10      | 2         | 5%      |
| 24      | 1         | 2.5%    |
| 23      | 1         | 2.5%    |
| 17      | 1         | 2.5%    |
| 11      | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 72.5%   |
| 201-300     | 7         | 17.5%   |
| 501-600     | 2         | 5%      |
| 351-400     | 1         | 2.5%    |
| Unknown     | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 91.89%  |
| 16/10 | 3         | 8.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 14        | 35%     |
| 81-90          | 10        | 25%     |
| 101-110        | 7         | 17.5%   |
| 61-70          | 2         | 5%      |
| 41-50          | 2         | 5%      |
| 201-250        | 2         | 5%      |
| 51-60          | 1         | 2.5%    |
| 121-130        | 1         | 2.5%    |
| Unknown        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 19        | 47.5%   |
| 121-160 | 11        | 27.5%   |
| 51-100  | 8         | 20%     |
| 161-240 | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 39        | 73.58%  |
| 0     | 11        | 20.75%  |
| 2     | 3         | 5.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 30.38%  |
| Qualcomm Atheros                 | 18        | 22.78%  |
| Realtek Semiconductor            | 17        | 21.52%  |
| Broadcom                         | 8         | 10.13%  |
| Marvell Technology Group         | 2         | 2.53%   |
| Huawei Technologies              | 2         | 2.53%   |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |
| Samsung Electronics              | 1         | 1.27%   |
| OPPO Electronics                 | 1         | 1.27%   |
| NetGear                          | 1         | 1.27%   |
| JMicron Technology               | 1         | 1.27%   |
| Hewlett-Packard                  | 1         | 1.27%   |
| Edimax Technology                | 1         | 1.27%   |
| AMD                              | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 13        | 12.5%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.81%   |
| Intel Wireless 7265                                                     | 5         | 4.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.85%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2         | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 1.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.92%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 1.92%   |
| Intel Wireless 8260                                                     | 2         | 1.92%   |
| Intel Wireless 7260                                                     | 2         | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.92%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.92%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.92%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.96%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.96%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.96%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data         | 1         | 0.96%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.96%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.96%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.96%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.96%   |
| Intel I211 Gigabit Network Connection                                   | 1         | 0.96%   |
| Intel I210 Gigabit Network Connection                                   | 1         | 0.96%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.96%   |
| Intel Ethernet Connection I218-V                                        | 1         | 0.96%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.96%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 1         | 0.96%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                      | 1         | 0.96%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 0.96%   |
| Intel 82574L Gigabit Network Connection                                 | 1         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                | 1         | 0.96%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                        | 1         | 0.96%   |
| Huawei E353/E3131                                                       | 1         | 0.96%   |
| HP un2400 Gobi Wireless Modem (QDL mode)                                | 1         | 0.96%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 37.25%  |
| Qualcomm Atheros      | 17        | 33.33%  |
| Broadcom              | 7         | 13.73%  |
| Realtek Semiconductor | 6         | 11.76%  |
| NetGear               | 1         | 1.96%   |
| Edimax Technology     | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 9.8%    |
| Intel Wireless 7265                                                     | 5         | 9.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 7.84%   |
| Intel Wireless 8265 / 8275                                              | 4         | 7.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.92%   |
| Intel Wireless 8260                                                     | 2         | 3.92%   |
| Intel Wireless 7260                                                     | 2         | 3.92%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 3.92%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 3.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.96%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.96%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 1.96%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.96%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.96%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.96%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 16        | 32.65%  |
| Intel                            | 16        | 32.65%  |
| Qualcomm Atheros                 | 8         | 16.33%  |
| Marvell Technology Group         | 2         | 4.08%   |
| Broadcom                         | 2         | 4.08%   |
| Silicon Integrated Systems [SiS] | 1         | 2.04%   |
| Samsung Electronics              | 1         | 2.04%   |
| OPPO Electronics                 | 1         | 2.04%   |
| JMicron Technology               | 1         | 2.04%   |
| AMD                              | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 26.53%  |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 6.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.04%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 2.04%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.04%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.04%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.04%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 2.04%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.04%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.04%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.04%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 48.45%  |
| Ethernet | 46        | 47.42%  |
| Modem    | 3         | 3.09%   |
| Unknown  | 1         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 52.11%  |
| Ethernet | 34        | 47.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 80.39%  |
| 1     | 6         | 11.76%  |
| 6     | 2         | 3.92%   |
| 5     | 1         | 1.96%   |
| 3     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 39.39%  |
| Qualcomm Atheros Communications | 4         | 12.12%  |
| Realtek Semiconductor           | 3         | 9.09%   |
| Lite-On Technology              | 2         | 6.06%   |
| IMC Networks                    | 2         | 6.06%   |
| Broadcom                        | 2         | 6.06%   |
| Apple                           | 2         | 6.06%   |
| Toshiba                         | 1         | 3.03%   |
| Hewlett-Packard                 | 1         | 3.03%   |
| Foxconn / Hon Hai               | 1         | 3.03%   |
| Cambridge Silicon Radio         | 1         | 3.03%   |
| ASUSTek Computer                | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 33.33%  |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 6.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 6.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 6.06%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 3.03%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 3.03%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 3.03%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 3.03%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 3.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 3.03%   |
| Intel AX201 Bluetooth                                       | 1         | 3.03%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 3.03%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 3.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 3.03%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 3.03%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 3.03%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 3.03%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 40        | 72.73%  |
| AMD                              | 12        | 21.82%  |
| Silicon Integrated Systems [SiS] | 1         | 1.82%   |
| Nvidia                           | 1         | 1.82%   |
| C-Media Electronics              | 1         | 1.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 9.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 8.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 7.04%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 7.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 7.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 4.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 4.23%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.23%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.23%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.41%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.41%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 33.33%  |
| SK hynix            | 11        | 17.46%  |
| Kingston            | 7         | 11.11%  |
| Unknown             | 6         | 9.52%   |
| Micron Technology   | 5         | 7.94%   |
| Unknown             | 4         | 6.35%   |
| Crucial             | 3         | 4.76%   |
| Nanya Technology    | 2         | 3.17%   |
| Transcend           | 1         | 1.59%   |
| Ramaxel Technology  | 1         | 1.59%   |
| ASint Technology    | 1         | 1.59%   |
| A-DATA Technology   | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 8.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 4.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 4.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 2.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.94%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 2.94%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                      | 2         | 2.94%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 1.47%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.47%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 1         | 1.47%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.47%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s          | 1         | 1.47%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.47%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.47%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 667MT/s            | 1         | 1.47%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.47%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s             | 1         | 1.47%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1067MT/s             | 1         | 1.47%   |
| Micron RAM MT41K512M8RH-125:E 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Micron RAM 8KTF5126 4HZ-1G6D1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| Micron RAM 8JTF25664HZ-1G4H1 2GB SODIMM DDR3 1067MT/s            | 1         | 1.47%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.47%   |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 800MT/s            | 1         | 1.47%   |
| Kingston RAM 99U5469-035.A00LF 4096MB SODIMM DDR3 1333MT/s       | 1         | 1.47%   |
| Kingston RAM 9905469-144.A00LF 4GB SODIMM DDR3 1333MT/s          | 1         | 1.47%   |
| Crucial RAM CT16G4SFRA32A.C8FB 16GB SODIMM DDR4 3200MT/s         | 1         | 1.47%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 1.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 1         | 1.47%   |
| ASint RAM SSZ3128M8-EDJEF 2GB SODIMM DDR3 1067MT/s               | 1         | 1.47%   |
| ASint RAM SSY3128M8-EDJEF 1GB SODIMM DDR3 1067MT/s               | 1         | 1.47%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2133MT/s                       | 1         | 1.47%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 25        | 51.02%  |
| DDR4    | 11        | 22.45%  |
| DDR2    | 7         | 14.29%  |
| SDRAM   | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| LPDDR3  | 1         | 2.04%   |
| DDR     | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 95.92%  |
| Row Of Chips | 1         | 2.04%   |
| Chip         | 1         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 24        | 43.64%  |
| 2048  | 13        | 23.64%  |
| 8192  | 11        | 20%     |
| 16384 | 4         | 7.27%   |
| 1024  | 2         | 3.64%   |
| 256   | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 30.91%  |
| 2667    | 6         | 10.91%  |
| 667     | 6         | 10.91%  |
| 1067    | 4         | 7.27%   |
| 2400    | 3         | 5.45%   |
| 2133    | 3         | 5.45%   |
| 1334    | 3         | 5.45%   |
| 1333    | 3         | 5.45%   |
| 800     | 3         | 5.45%   |
| Unknown | 3         | 5.45%   |
| 3200    | 2         | 3.64%   |
| 1867    | 1         | 1.82%   |
| 333     | 1         | 1.82%   |

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
| Chicony Electronics                    | 13        | 34.21%  |
| IMC Networks                           | 6         | 15.79%  |
| Realtek Semiconductor                  | 4         | 10.53%  |
| Acer                                   | 4         | 10.53%  |
| ALi                                    | 3         | 7.89%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Silicon Motion                         | 2         | 5.26%   |
| Suyin                                  | 1         | 2.63%   |
| Microdia                               | 1         | 2.63%   |
| Lite-On Technology                     | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                  | 2         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 5.26%   |
| Chicony Integrated Camera                                  | 2         | 5.26%   |
| Chicony HD WebCam (Acer)                                   | 2         | 5.26%   |
| ALi Gateway Webcam                                         | 2         | 5.26%   |
| Acer Integrated Camera                                     | 2         | 5.26%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                   | 1         | 2.63%   |
| Sunplus Integrated Camera                                  | 1         | 2.63%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 2.63%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 2.63%   |
| Silicon Motion HP Webcam-50                                | 1         | 2.63%   |
| Realtek USB Camera                                         | 1         | 2.63%   |
| Realtek Integrated_Webcam_HD                               | 1         | 2.63%   |
| Microdia Integrated_Webcam_HD                              | 1         | 2.63%   |
| Lite-On HP TrueVision HD Camera                            | 1         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 2.63%   |
| IMC Networks USB2.0 UVC HD Webcam                          | 1         | 2.63%   |
| IMC Networks Integrated Webcam                             | 1         | 2.63%   |
| IMC Networks Integrated Camera                             | 1         | 2.63%   |
| Chicony WebCam                                             | 1         | 2.63%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 2.63%   |
| Chicony ThinkPad T490 Webcam                               | 1         | 2.63%   |
| Chicony Thinkpad T430 camera                               | 1         | 2.63%   |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 2.63%   |
| Chicony HP TrueVision HD Camera                            | 1         | 2.63%   |
| Chicony 2.0M UVC Webcam / CNF7129                          | 1         | 2.63%   |
| Chicony 1.3M Webcam                                        | 1         | 2.63%   |
| Chicony 1.3 MPixel UVC Webcam                              | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 2.63%   |
| ALi M5602 Video Camera Controller                          | 1         | 2.63%   |
| Acer SunplusIT INC. Integrated Camera                      | 1         | 2.63%   |
| Acer HD Webcam                                             | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 2         | 33.33%  |
| Validity Sensors      | 1         | 16.67%  |
| Upek                  | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 16.67%  |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 16.67%  |
| AuthenTec AES2810                                      | 1         | 16.67%  |
| AuthenTec AES1600                                      | 1         | 16.67%  |

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
| 2     | 19        | 35.85%  |
| 1     | 13        | 24.53%  |
| 0     | 11        | 20.75%  |
| 3     | 8         | 15.09%  |
| 4     | 2         | 3.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 30        | 38.46%  |
| Card reader              | 14        | 17.95%  |
| Bluetooth                | 12        | 15.38%  |
| Net/wireless             | 11        | 14.1%   |
| Fingerprint reader       | 6         | 7.69%   |
| Graphics card            | 2         | 2.56%   |
| Network                  | 1         | 1.28%   |
| Modem                    | 1         | 1.28%   |
| Firewire controller      | 1         | 1.28%   |

