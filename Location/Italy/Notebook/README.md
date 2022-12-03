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

Total: 73

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| HP            | Laptop 15-da0xxx            | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
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
| HP            | Laptop 15-da0xxx            | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| ASUSTek       | G1S                         | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Acer          | Extensa 5635Z               | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| eMachines     | eME732ZG                    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | ProBook 470 G4              | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| ASUSTek       | X502CA                      | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| Apple         | MacBook4,1                  | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| HP            | ProBook 470 G4              | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
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
| helloSystem 0.7.0    | 11        | 18.64%  |
| helloSystem 0.5.0    | 5         | 8.47%   |
| helloSystem 0.4.0    | 5         | 8.47%   |
| helloSystem 0.6.0    | 3         | 5.08%   |
| NomadBSD 1.3.2       | 2         | 3.39%   |
| helloSystem 0.3.0    | 2         | 3.39%   |
| GhostBSD 21.08.27    | 2         | 3.39%   |
| GhostBSD 20.04.02    | 2         | 3.39%   |
| FreeBSD 13.1         | 2         | 3.39%   |
| OPNsense 22.1.9      | 1         | 1.69%   |
| OPNsense 22.1.6      | 1         | 1.69%   |
| OPNsense 21.7.7      | 1         | 1.69%   |
| OPNsense 21.1        | 1         | 1.69%   |
| OpenBSD 7.1          | 1         | 1.69%   |
| OpenBSD 6.8          | 1         | 1.69%   |
| OpenBSD 6.7          | 1         | 1.69%   |
| NomadBSD 5806f915    | 1         | 1.69%   |
| NomadBSD 1.4         | 1         | 1.69%   |
| NomadBSD 1.3.1       | 1         | 1.69%   |
| NetBSD 9.2_STABLE    | 1         | 1.69%   |
| NetBSD 9.2           | 1         | 1.69%   |
| NetBSD 9.1           | 1         | 1.69%   |
| NetBSD 9.0           | 1         | 1.69%   |
| helloSystem 0.8.0    | 1         | 1.69%   |
| GhostBSD 22.11.02    | 1         | 1.69%   |
| GhostBSD 22.06.26    | 1         | 1.69%   |
| FreeBSD 14.0-CURRENT | 1         | 1.69%   |
| FreeBSD 13.0-p4      | 1         | 1.69%   |
| FreeBSD 13.0-CURRENT | 1         | 1.69%   |
| FreeBSD 13.0         | 1         | 1.69%   |
| FreeBSD 12.2-p4      | 1         | 1.69%   |
| FreeBSD 12.2-p2      | 1         | 1.69%   |
| FreeBSD 12.1-p10     | 1         | 1.69%   |
| FreeBSD 12.0-p13     | 1         | 1.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 25        | 46.3%   |
| FreeBSD     | 10        | 18.52%  |
| NomadBSD    | 5         | 9.26%   |
| OPNsense    | 4         | 7.41%   |
| GhostBSD    | 4         | 7.41%   |
| OpenBSD     | 3         | 5.56%   |
| NetBSD      | 3         | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 51        | 96.23%  |
| i386  | 2         | 3.77%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 25        | 45.45%  |
| Console      | 6         | 10.91%  |
| Openbox      | 5         | 9.09%   |
| KDE5         | 3         | 5.45%   |
| i3           | 3         | 5.45%   |
| Cinnamon     | 3         | 5.45%   |
| XFCE         | 2         | 3.64%   |
| fvwm         | 2         | 3.64%   |
| ctwm         | 2         | 3.64%   |
| TWM          | 1         | 1.82%   |
| MATE         | 1         | 1.82%   |
| LXQt         | 1         | 1.82%   |
| Fluxbox      | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 48        | 90.57%  |
| Console | 4         | 7.55%   |
| Wayland | 1         | 1.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 32        | 60.38%  |
| Console | 13        | 24.53%  |
| LightDM | 4         | 7.55%   |
| SDDM    | 3         | 5.66%   |
| XDM     | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| en_US            | 32        | 59.26%  |
| it_IT            | 8         | 14.81%  |
| Unknown          | 7         | 12.96%  |
| C                | 3         | 5.56%   |
| ru_RU            | 1         | 1.85%   |
| it_IT.ISO8859-15 | 1         | 1.85%   |
| it_IT.ISO8859-1  | 1         | 1.85%   |
| en_GB            | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 44        | 83.02%  |
| BIOS | 9         | 16.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 31        | 57.41%  |
| Ufs    | 16        | 29.63%  |
| Cd9660 | 4         | 7.41%   |
| Ffs    | 3         | 5.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 46        | 86.79%  |
| MBR     | 5         | 9.43%   |
| Unknown | 2         | 3.77%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 26.42%  |
| ASUSTek Computer    | 10        | 18.87%  |
| Hewlett-Packard     | 5         | 9.43%   |
| Acer                | 5         | 9.43%   |
| Dell                | 4         | 7.55%   |
| Apple               | 3         | 5.66%   |
| Toshiba             | 2         | 3.77%   |
| eMachines           | 2         | 3.77%   |
| Unknown             | 2         | 3.77%   |
| TUXEDO              | 1         | 1.89%   |
| Samsung Electronics | 1         | 1.89%   |
| Packard Bell        | 1         | 1.89%   |
| MSI                 | 1         | 1.89%   |
| IBM                 | 1         | 1.89%   |
| Deciso              | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Laptop 15-da0xxx                      | 2         | 3.77%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 3.77%   |
| Apple MacBook4,1                         | 2         | 3.77%   |
| Unknown                                  | 2         | 3.77%   |
| TUXEDO N14xWU                            | 1         | 1.89%   |
| Toshiba Satellite C855-1U4               | 1         | 1.89%   |
| Toshiba PORTEGE M780                     | 1         | 1.89%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 1.89%   |
| Packard Bell EasyNote_MX61-B-038         | 1         | 1.89%   |
| MSI GF65 Thin 10SER                      | 1         | 1.89%   |
| Lenovo ThinkPad X260 20F5S82N00          | 1         | 1.89%   |
| Lenovo ThinkPad X250 20CMS0FA00          | 1         | 1.89%   |
| Lenovo ThinkPad X240 20AMS0J01N          | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00 | 1         | 1.89%   |
| Lenovo ThinkPad T495 20NJS0KP00          | 1         | 1.89%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 1.89%   |
| Lenovo ThinkPad T440 20B7S1C600          | 1         | 1.89%   |
| Lenovo ThinkPad T430 23501B3             | 1         | 1.89%   |
| Lenovo ThinkPad T420 4236BD5             | 1         | 1.89%   |
| Lenovo ThinkPad L530 24812TG             | 1         | 1.89%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 1.89%   |
| Lenovo G505 20240                        | 1         | 1.89%   |
| Lenovo G50-45 80E3                       | 1         | 1.89%   |
| Lenovo B590 62743PG                      | 1         | 1.89%   |
| IBM ThinkPad R51 2887AVG                 | 1         | 1.89%   |
| HP ProBook 470 G4                        | 1         | 1.89%   |
| HP Mini 210-1000                         | 1         | 1.89%   |
| HP EliteBook 6930p                       | 1         | 1.89%   |
| eMachines eME732ZG                       | 1         | 1.89%   |
| eMachines eME728                         | 1         | 1.89%   |
| Dell Vostro 3550                         | 1         | 1.89%   |
| Dell Precision 3510                      | 1         | 1.89%   |
| Dell Latitude E5450                      | 1         | 1.89%   |
| Dell Inspiron 15-3552                    | 1         | 1.89%   |
| Deciso OPNsense Appliance                | 1         | 1.89%   |
| ASUS X555LJ                              | 1         | 1.89%   |
| ASUS X555LD                              | 1         | 1.89%   |
| ASUS X502CA                              | 1         | 1.89%   |
| ASUS VivoBook_ASUSLaptop X515UA_M515UA   | 1         | 1.89%   |
| ASUS K52F                                | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 18.87%  |
| ASUS VivoBook         | 3         | 5.66%   |
| HP Laptop             | 2         | 3.77%   |
| Apple MacBook4        | 2         | 3.77%   |
| Acer Aspire           | 2         | 3.77%   |
| Unknown               | 2         | 3.77%   |
| TUXEDO N14xWU         | 1         | 1.89%   |
| Toshiba Satellite     | 1         | 1.89%   |
| Toshiba PORTEGE       | 1         | 1.89%   |
| Samsung 3570R         | 1         | 1.89%   |
| Packard Bell EasyNote | 1         | 1.89%   |
| MSI GF65              | 1         | 1.89%   |
| Lenovo IdeaPad        | 1         | 1.89%   |
| Lenovo G505           | 1         | 1.89%   |
| Lenovo G50-45         | 1         | 1.89%   |
| Lenovo B590           | 1         | 1.89%   |
| IBM ThinkPad          | 1         | 1.89%   |
| HP ProBook            | 1         | 1.89%   |
| HP Mini               | 1         | 1.89%   |
| HP EliteBook          | 1         | 1.89%   |
| eMachines eME732ZG    | 1         | 1.89%   |
| eMachines eME728      | 1         | 1.89%   |
| Dell Vostro           | 1         | 1.89%   |
| Dell Precision        | 1         | 1.89%   |
| Dell Latitude         | 1         | 1.89%   |
| Dell Inspiron         | 1         | 1.89%   |
| Deciso OPNsense       | 1         | 1.89%   |
| ASUS X555LJ           | 1         | 1.89%   |
| ASUS X555LD           | 1         | 1.89%   |
| ASUS X502CA           | 1         | 1.89%   |
| ASUS K52F             | 1         | 1.89%   |
| ASUS G1S              | 1         | 1.89%   |
| ASUS F50SL            | 1         | 1.89%   |
| ASUS 1000             | 1         | 1.89%   |
| Apple MacBookAir7     | 1         | 1.89%   |
| Acer V5-131           | 1         | 1.89%   |
| Acer Extensa          | 1         | 1.89%   |
| Acer AOD260           | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 8         | 15.09%  |
| 2019 | 7         | 13.21%  |
| 2011 | 5         | 9.43%   |
| 2014 | 4         | 7.55%   |
| 2010 | 4         | 7.55%   |
| 2021 | 3         | 5.66%   |
| 2020 | 3         | 5.66%   |
| 2016 | 3         | 5.66%   |
| 2015 | 3         | 5.66%   |
| 2008 | 3         | 5.66%   |
| 2018 | 2         | 3.77%   |
| 2012 | 2         | 3.77%   |
| 2009 | 2         | 3.77%   |
| 2007 | 2         | 3.77%   |
| 2022 | 1         | 1.89%   |
| 2006 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 53        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 21        | 38.89%  |
| 4.01-8.0   | 20        | 37.04%  |
| 2.01-3.0   | 4         | 7.41%   |
| 16.01-24.0 | 4         | 7.41%   |
| 32.01-64.0 | 2         | 3.7%    |
| 3.01-4.0   | 1         | 1.85%   |
| 24.01-32.0 | 1         | 1.85%   |
| 0.01-0.5   | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 34        | 62.96%  |
| 0.51-1.0  | 8         | 14.81%  |
| 2.01-3.0  | 4         | 7.41%   |
| Unknown   | 3         | 5.56%   |
| 4.01-8.0  | 2         | 3.7%    |
| 1.01-2.0  | 2         | 3.7%    |
| 8.01-16.0 | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 74.07%  |
| 2      | 12        | 22.22%  |
| 0      | 2         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 62.96%  |
| Yes       | 20        | 37.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 88.68%  |
| No        | 6         | 11.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 92.45%  |
| No        | 4         | 7.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 59.26%  |
| No        | 22        | 40.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 53        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Rome                     | 10        | 16.67%  |
| Milan                    | 5         | 8.33%   |
| Turin                    | 3         | 5%      |
| Bologna                  | 3         | 5%      |
| Trieste                  | 2         | 3.33%   |
| Rho                      | 2         | 3.33%   |
| Monterotondo             | 2         | 3.33%   |
| Brescia                  | 2         | 3.33%   |
| Vigonovo                 | 1         | 1.67%   |
| Udine                    | 1         | 1.67%   |
| Solarino                 | 1         | 1.67%   |
| Sesto San Giovanni       | 1         | 1.67%   |
| Saronno                  | 1         | 1.67%   |
| Roncade                  | 1         | 1.67%   |
| Resana                   | 1         | 1.67%   |
| Piovene Rocchette        | 1         | 1.67%   |
| Pessano Con Bornago      | 1         | 1.67%   |
| Passignano sul Trasimeno | 1         | 1.67%   |
| Padova                   | 1         | 1.67%   |
| Nughedu San Nicolo       | 1         | 1.67%   |
| Massa Lombarda           | 1         | 1.67%   |
| Malnate                  | 1         | 1.67%   |
| Macerata                 | 1         | 1.67%   |
| Lurago Marinone          | 1         | 1.67%   |
| Lissone                  | 1         | 1.67%   |
| Genzano di Roma          | 1         | 1.67%   |
| Gattinara                | 1         | 1.67%   |
| Galliera Veneta          | 1         | 1.67%   |
| Gallarate                | 1         | 1.67%   |
| Fiumicino                | 1         | 1.67%   |
| Farneto                  | 1         | 1.67%   |
| Concesio                 | 1         | 1.67%   |
| Cogolo                   | 1         | 1.67%   |
| Cardito                  | 1         | 1.67%   |
| Brugherio                | 1         | 1.67%   |
| Bergamo                  | 1         | 1.67%   |
| Arezzo                   | 1         | 1.67%   |
| Albano Sant'Alessandro   | 1         | 1.67%   |
| Adelfia                  | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 18     | 16.67%  |
| Seagate             | 7         | 8      | 11.67%  |
| WDC                 | 6         | 7      | 10%     |
| Toshiba             | 5         | 5      | 8.33%   |
| Crucial             | 5         | 7      | 8.33%   |
| SanDisk             | 4         | 4      | 6.67%   |
| Kingston            | 4         | 5      | 6.67%   |
| Hitachi             | 3         | 4      | 5%      |
| Leven               | 2         | 2      | 3.33%   |
| KingSpec            | 2         | 2      | 3.33%   |
| Union Memory        | 1         | 1      | 1.67%   |
| Transcend           | 1         | 1      | 1.67%   |
| Micron Technology   | 1         | 1      | 1.67%   |
| KingDian            | 1         | 1      | 1.67%   |
| Intenso             | 1         | 1      | 1.67%   |
| Intel               | 1         | 1      | 1.67%   |
| Indilinx            | 1         | 1      | 1.67%   |
| HGST                | 1         | 1      | 1.67%   |
| Fujitsu             | 1         | 1      | 1.67%   |
| FORESEE             | 1         | 2      | 1.67%   |
| ASUSTek Computer    | 1         | 2      | 1.67%   |
| Apple               | 1         | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 3.13%   |
| Samsung SSD 860 EVO 500GB                       | 2         | 3.13%   |
| Samsung SSD 860 EVO 250GB                       | 2         | 3.13%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 3.13%   |
| KingSpec Q-720 720GB                            | 2         | 3.13%   |
| WDC WDS120G2G0A-00JH30 120GB                    | 1         | 1.56%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 1.56%   |
| WDC WD3200BEKX-60B7WT0 320GB                    | 1         | 1.56%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 1.56%   |
| WDC WD2500BEVS-22UST0 250GB                     | 1         | 1.56%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 1.56%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 1.56%   |
| Toshiba TR200 240GB                             | 1         | 1.56%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.56%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.56%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 1.56%   |
| Toshiba MK2561GSYN 250GB                        | 1         | 1.56%   |
| Seagate ST9750420AS 752GB                       | 1         | 1.56%   |
| Seagate ST9320320AS 320GB                       | 1         | 1.56%   |
| Seagate ST9160821AS 160GB                       | 1         | 1.56%   |
| Seagate ST9160411AS 160GB                       | 1         | 1.56%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.56%   |
| Seagate ST500LM030-1RK17D 500GB                 | 1         | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 1.56%   |
| Seagate ST1000LM014-1EJ164 1TB                  | 1         | 1.56%   |
| SanDisk X400 M.2 2280 512GB                     | 1         | 1.56%   |
| SanDisk SSD P4 8GB                              | 1         | 1.56%   |
| SanDisk SDSSDP064G 64GB                         | 1         | 1.56%   |
| SanDisk SD9SN8W-128G-1006 128GB                 | 1         | 1.56%   |
| Samsung SSD 970 EVO 250GB                       | 1         | 1.56%   |
| Samsung SSD 870 EVO 1TB                         | 1         | 1.56%   |
| Samsung SSD 860 QVO 1TB                         | 1         | 1.56%   |
| Samsung SSD 850 EVO 250GB                       | 1         | 1.56%   |
| Samsung MZVLQ512HALU-00000 512GB                | 1         | 1.56%   |
| Samsung MZVLB512HAJQ-000L7 512GB                | 1         | 1.56%   |
| Micron 2210_MTFDHBA512QFD 512GB                 | 1         | 1.56%   |
| Leven JAJS600M512C 512GB                        | 1         | 1.56%   |
| Leven JAJS300M480C 480GB                        | 1         | 1.56%   |
| Kingston SA400S37240G 240GB                     | 1         | 1.56%   |
| Kingston SA400S37120G 120GB                     | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 36.84%  |
| Toshiba | 4         | 4      | 21.05%  |
| WDC     | 3         | 4      | 15.79%  |
| Hitachi | 3         | 4      | 15.79%  |
| HGST    | 1         | 1      | 5.26%   |
| Fujitsu | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 15     | 23.53%  |
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
| SSD  | 31        | 45     | 54.39%  |
| HDD  | 18        | 22     | 31.58%  |
| NVMe | 8         | 9      | 14.04%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 67     | 84.91%  |
| NVMe | 8         | 9      | 15.09%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 49     | 80.85%  |
| 0.51-1.0   | 9         | 18     | 19.15%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 25        | 45.45%  |
| 101-250    | 10        | 18.18%  |
| 251-500    | 9         | 16.36%  |
| 21-50      | 5         | 9.09%   |
| 501-1000   | 3         | 5.45%   |
| 51-100     | 3         | 5.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 49        | 87.5%   |
| 21-50   | 6         | 10.71%  |
| 51-100  | 1         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB        | 1         | 1      | 10%     |
| Seagate ST9750420AS 752GB       | 1         | 1      | 10%     |
| Seagate ST9160821AS 160GB       | 1         | 1      | 10%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 10%     |
| SanDisk SDSSDP064G 64GB         | 1         | 1      | 10%     |
| SanDisk SD9SN8W-128G-1006 128GB | 1         | 1      | 10%     |
| Intel SSDSC2BF180A4L 180GB      | 1         | 1      | 10%     |
| Hitachi HTS548040M9AT00 37GB    | 1         | 2      | 10%     |
| Hitachi HTS545050A7E380 500GB   | 1         | 1      | 10%     |
| Crucial CT525MX300SSD1 528GB    | 1         | 3      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| SanDisk | 2         | 2      | 20%     |
| Hitachi | 2         | 3      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Intel   | 1         | 1      | 10%     |
| Crucial | 1         | 3      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| Hitachi | 2         | 3      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 60%     |
| SSD  | 4         | 6      | 40%     |

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
| Works    | 42        | 61     | 79.25%  |
| Malfunc  | 10        | 13     | 18.87%  |
| Detected | 1         | 2      | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 67.24%  |
| AMD                              | 8         | 13.79%  |
| Samsung Electronics              | 4         | 6.9%    |
| Kingston Technology Company      | 2         | 3.45%   |
| Union Memory (Shenzhen)          | 1         | 1.72%   |
| Transcend                        | 1         | 1.72%   |
| Silicon Integrated Systems [SiS] | 1         | 1.72%   |
| Micron Technology                | 1         | 1.72%   |
| JMicron Technology               | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 10.45%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 10.45%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 7.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 5.97%   |
| Unknown                                                                                | 4         | 5.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 4.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 4.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 4.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 4.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.99%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 2.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.99%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 1.49%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1.49%   |
| Samsung SM951 AHCI                                                                     | 1         | 1.49%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.49%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 1.49%   |
| JMicron JMB360 AHCI Controller                                                         | 1         | 1.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.49%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.49%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.49%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 1         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.49%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 1         | 1.49%   |
| AMD SB600 IDE                                                                          | 1         | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 42        | 67.74%  |
| IDE  | 10        | 16.13%  |
| NVMe | 8         | 12.9%   |
| RAID | 2         | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 81.13%  |
| AMD    | 10        | 18.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 5.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 3.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 3.7%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 3.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.7%    |
| Intel Pentium M processor                     | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.85%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.85%   |
| Intel Pentium CPU P6200 @ 2.13GH              | 1         | 1.85%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 1.85%   |
| Intel Pentium CPU 997 @ 1.60GHz               | 1         | 1.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 1.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.85%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.85%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz          | 1         | 1.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.85%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 1.85%   |
| Intel Celeron CPU 1017U @ 1.60GHz             | 1         | 1.85%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 1.85%   |
| Intel 686-class                               | 1         | 1.85%   |
| AMD Turion 64 X2 Mobile Technology TL-60      | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 29.63%  |
| Intel Core i7           | 6         | 11.11%  |
| Intel Core 2 Duo        | 5         | 9.26%   |
| Intel Pentium           | 4         | 7.41%   |
| Intel Core i3           | 3         | 5.56%   |
| Intel Celeron           | 3         | 5.56%   |
| Intel Atom              | 3         | 5.56%   |
| AMD Ryzen 5             | 3         | 5.56%   |
| Intel Pentium Dual-Core | 2         | 3.7%    |
| Other                   | 1         | 1.85%   |
| Intel Pentium M         | 1         | 1.85%   |
| Intel 686-class         | 1         | 1.85%   |
| AMD Turion 64 X2 Mobile | 1         | 1.85%   |
| AMD Ryzen Embedded      | 1         | 1.85%   |
| AMD Ryzen 7 PRO         | 1         | 1.85%   |
| AMD E1                  | 1         | 1.85%   |
| AMD A6                  | 1         | 1.85%   |
| AMD A4                  | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 32        | 59.26%  |
| Unknown | 8         | 14.81%  |
| 4       | 7         | 12.96%  |
| 8       | 4         | 7.41%   |
| 1       | 2         | 3.7%    |
| 12      | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 51        | 94.44%  |
| 2       | 2         | 3.7%    |
| Unknown | 1         | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 27        | 50%     |
| 1       | 19        | 35.19%  |
| Unknown | 8         | 14.81%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| SandyBridge | 7         | 12.96%  |
| Penryn      | 6         | 11.11%  |
| KabyLake    | 5         | 9.26%   |
| IvyBridge   | 5         | 9.26%   |
| Broadwell   | 5         | 9.26%   |
| Zen+        | 3         | 5.56%   |
| Westmere    | 3         | 5.56%   |
| Haswell     | 3         | 5.56%   |
| Bonnell     | 3         | 5.56%   |
| Zen         | 2         | 3.7%    |
| Skylake     | 2         | 3.7%    |
| Jaguar      | 2         | 3.7%    |
| Unknown     | 2         | 3.7%    |
| Silvermont  | 1         | 1.85%   |
| Puma        | 1         | 1.85%   |
| P6          | 1         | 1.85%   |
| K8 Hammer   | 1         | 1.85%   |
| Core        | 1         | 1.85%   |
| CometLake   | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 64.41%  |
| AMD    | 15        | 25.42%  |
| Nvidia | 6         | 10.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 11.11%  |
| Intel HD Graphics 5500                                                                   | 4         | 6.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 6.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 6.35%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 4.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 3.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 3.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.17%   |
| Intel HD Graphics 620                                                                    | 2         | 3.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 3.17%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.59%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.59%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.59%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.59%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.59%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.59%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.59%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.59%   |
| Intel HD Graphics 530                                                                    | 1         | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.59%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.59%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.59%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                                  | 1         | 1.59%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 1.59%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 1.59%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.59%   |
| AMD RV610/M72-S [Mobility Radeon HD 2400]                                                | 1         | 1.59%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.59%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 1.59%   |
| AMD Lucienne                                                                             | 1         | 1.59%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 1.59%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.59%   |
| AMD Cape Verde PRO / Venus LE / Tropo PRO-L [Radeon HD 8830M / R7 250 / R7 M465X]        | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 45.28%  |
| 1 x AMD        | 12        | 22.64%  |
| 2 x Intel      | 7         | 13.21%  |
| Intel + Nvidia | 5         | 9.43%   |
| Intel + AMD    | 2         | 3.77%   |
| Other          | 1         | 1.89%   |
| 2 x AMD        | 1         | 1.89%   |
| 1 x Nvidia     | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 48        | 87.27%  |
| Unknown     | 5         | 9.09%   |
| Proprietary | 2         | 3.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 75.47%  |
| 0.01-0.5   | 7         | 13.21%  |
| 1.01-2.0   | 4         | 7.55%   |
| 3.01-4.0   | 1         | 1.89%   |
| 0.51-1.0   | 1         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 13        | 31.71%  |
| LG Display          | 7         | 17.07%  |
| Chimei Innolux      | 5         | 12.2%   |
| BOE                 | 5         | 12.2%   |
| Samsung Electronics | 2         | 4.88%   |
| Lenovo              | 2         | 4.88%   |
| Apple               | 2         | 4.88%   |
| ___                 | 1         | 2.44%   |
| LG Philips          | 1         | 2.44%   |
| Hewlett-Packard     | 1         | 2.44%   |
| HannStar            | 1         | 2.44%   |
| Fujitsu Siemens     | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 2         | 4.88%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 2         | 4.88%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 2.44%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 2.44%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch          | 1         | 2.44%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch              | 1         | 2.44%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 2.44%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch           | 1         | 2.44%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 2.44%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch     | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 1         | 2.44%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 2.44%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                | 1         | 2.44%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                 | 1         | 2.44%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch       | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 220x130mm 10.1-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch        | 1         | 2.44%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 1         | 2.44%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                 | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 22        | 55%     |
| 1920x1080 (FHD)  | 11        | 27.5%   |
| 1600x900 (HD+)   | 2         | 5%      |
| 1280x800 (WXGA)  | 2         | 5%      |
| 1024x600         | 2         | 5%      |
| 1440x900 (WXGA+) | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 22        | 53.66%  |
| 13      | 10        | 24.39%  |
| 12      | 2         | 4.88%   |
| 10      | 2         | 4.88%   |
| 24      | 1         | 2.44%   |
| 23      | 1         | 2.44%   |
| 17      | 1         | 2.44%   |
| 11      | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 73.17%  |
| 201-300     | 7         | 17.07%  |
| 501-600     | 2         | 4.88%   |
| 351-400     | 1         | 2.44%   |
| Unknown     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 92.11%  |
| 16/10 | 3         | 7.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 15        | 36.59%  |
| 81-90          | 10        | 24.39%  |
| 101-110        | 7         | 17.07%  |
| 61-70          | 2         | 4.88%   |
| 41-50          | 2         | 4.88%   |
| 201-250        | 2         | 4.88%   |
| 51-60          | 1         | 2.44%   |
| 121-130        | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 20        | 48.78%  |
| 121-160 | 11        | 26.83%  |
| 51-100  | 8         | 19.51%  |
| 161-240 | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 72.73%  |
| 0     | 12        | 21.82%  |
| 2     | 3         | 5.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 28.57%  |
| Qualcomm Atheros                 | 20        | 23.81%  |
| Realtek Semiconductor            | 18        | 21.43%  |
| Broadcom                         | 8         | 9.52%   |
| Ralink Technology                | 2         | 2.38%   |
| Marvell Technology Group         | 2         | 2.38%   |
| Huawei Technologies              | 2         | 2.38%   |
| Silicon Integrated Systems [SiS] | 1         | 1.19%   |
| Samsung Electronics              | 1         | 1.19%   |
| OPPO Electronics                 | 1         | 1.19%   |
| NetGear                          | 1         | 1.19%   |
| JMicron Technology               | 1         | 1.19%   |
| Hewlett-Packard                  | 1         | 1.19%   |
| Edimax Technology                | 1         | 1.19%   |
| AMD                              | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 14        | 12.84%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.59%   |
| Intel Wireless 7265                                                     | 5         | 4.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.67%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.75%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2         | 1.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 1.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.83%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 1.83%   |
| Intel Wireless 8260                                                     | 2         | 1.83%   |
| Intel Wireless 7260                                                     | 2         | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.83%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.83%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.83%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.92%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.92%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.92%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data         | 1         | 0.92%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.92%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 19        | 34.55%  |
| Intel                 | 19        | 34.55%  |
| Broadcom              | 7         | 12.73%  |
| Realtek Semiconductor | 6         | 10.91%  |
| Ralink Technology     | 2         | 3.64%   |
| NetGear               | 1         | 1.82%   |
| Edimax Technology     | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 9.09%   |
| Intel Wireless 7265                                                     | 5         | 9.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 7.27%   |
| Intel Wireless 8265 / 8275                                              | 4         | 7.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 5.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.64%   |
| Intel Wireless 8260                                                     | 2         | 3.64%   |
| Intel Wireless 7260                                                     | 2         | 3.64%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 3.64%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 3.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.82%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.82%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.82%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.82%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 1.82%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.82%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.82%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.82%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 17        | 34%     |
| Intel                            | 16        | 32%     |
| Qualcomm Atheros                 | 8         | 16%     |
| Marvell Technology Group         | 2         | 4%      |
| Broadcom                         | 2         | 4%      |
| Silicon Integrated Systems [SiS] | 1         | 2%      |
| Samsung Electronics              | 1         | 2%      |
| OPPO Electronics                 | 1         | 2%      |
| JMicron Technology               | 1         | 2%      |
| AMD                              | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 28%     |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 6%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2%      |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 2%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2%      |
| Intel I211 Gigabit Network Connection                             | 1         | 2%      |
| Intel I210 Gigabit Network Connection                             | 1         | 2%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 2%      |
| Intel Ethernet Connection I218-V                                  | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2%      |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 2%      |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2%      |
| Intel 82574L Gigabit Network Connection                           | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2%      |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 49%     |
| Ethernet | 47        | 47%     |
| Modem    | 3         | 3%      |
| Unknown  | 1         | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 52.78%  |
| Ethernet | 34        | 47.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 42        | 79.25%  |
| 1     | 7         | 13.21%  |
| 6     | 2         | 3.77%   |
| 5     | 1         | 1.89%   |
| 3     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 37.14%  |
| Qualcomm Atheros Communications | 6         | 17.14%  |
| Realtek Semiconductor           | 3         | 8.57%   |
| Lite-On Technology              | 2         | 5.71%   |
| IMC Networks                    | 2         | 5.71%   |
| Broadcom                        | 2         | 5.71%   |
| Apple                           | 2         | 5.71%   |
| Toshiba                         | 1         | 2.86%   |
| Hewlett-Packard                 | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Cambridge Silicon Radio         | 1         | 2.86%   |
| ASUSTek Computer                | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 31.43%  |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 5.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 5.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 5.71%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 2.86%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 2.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 2.86%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.86%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 2.86%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 2.86%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 2.86%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2.86%   |
| Intel AX201 Bluetooth                                       | 1         | 2.86%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 2.86%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 2.86%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2.86%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 2.86%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 2.86%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 41        | 71.93%  |
| AMD                              | 13        | 22.81%  |
| Silicon Integrated Systems [SiS] | 1         | 1.75%   |
| Nvidia                           | 1         | 1.75%   |
| C-Media Electronics              | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 9.46%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 8.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 8.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 6.76%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 6.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 5.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 4.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 4.05%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.05%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.05%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.35%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.35%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.35%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.35%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.35%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 31.82%  |
| SK hynix            | 12        | 18.18%  |
| Kingston            | 7         | 10.61%  |
| Micron Technology   | 6         | 9.09%   |
| Unknown             | 6         | 9.09%   |
| Unknown             | 4         | 6.06%   |
| Crucial             | 4         | 6.06%   |
| Nanya Technology    | 2         | 3.03%   |
| Transcend           | 1         | 1.52%   |
| Ramaxel Technology  | 1         | 1.52%   |
| ASint Technology    | 1         | 1.52%   |
| A-DATA Technology   | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 8.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 4.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 4.23%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 2.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.82%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 2.82%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                      | 2         | 2.82%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 1.41%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.41%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 1         | 1.41%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.41%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s          | 1         | 1.41%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.41%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.41%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.41%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 667MT/s            | 1         | 1.41%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.41%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s             | 1         | 1.41%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1067MT/s             | 1         | 1.41%   |
| Micron RAM MT41K512M8RH-125:E 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.41%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 26        | 50.98%  |
| DDR4    | 12        | 23.53%  |
| DDR2    | 7         | 13.73%  |
| SDRAM   | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| LPDDR3  | 1         | 1.96%   |
| DDR     | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 94.12%  |
| Row Of Chips | 2         | 3.92%   |
| Chip         | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 43.1%   |
| 2048  | 14        | 24.14%  |
| 8192  | 12        | 20.69%  |
| 16384 | 4         | 6.9%    |
| 1024  | 2         | 3.45%   |
| 256   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 30.36%  |
| 2667    | 6         | 10.71%  |
| 667     | 6         | 10.71%  |
| 2400    | 4         | 7.14%   |
| 1333    | 4         | 7.14%   |
| 1067    | 4         | 7.14%   |
| 2133    | 3         | 5.36%   |
| 1334    | 3         | 5.36%   |
| Unknown | 3         | 5.36%   |
| 3200    | 2         | 3.57%   |
| 800     | 2         | 3.57%   |
| 1867    | 1         | 1.79%   |
| 333     | 1         | 1.79%   |

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
| Chicony Electronics                    | 13        | 32.5%   |
| IMC Networks                           | 6         | 15%     |
| Realtek Semiconductor                  | 4         | 10%     |
| Acer                                   | 4         | 10%     |
| Sunplus Innovation Technology          | 3         | 7.5%    |
| ALi                                    | 3         | 7.5%    |
| Silicon Motion                         | 2         | 5%      |
| Syntek                                 | 1         | 2.5%    |
| Suyin                                  | 1         | 2.5%    |
| Microdia                               | 1         | 2.5%    |
| Lite-On Technology                     | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                  | 2         | 5%      |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 5%      |
| Chicony Integrated Camera                                  | 2         | 5%      |
| Chicony HD WebCam (Acer)                                   | 2         | 5%      |
| ALi Gateway Webcam                                         | 2         | 5%      |
| Acer Integrated Camera                                     | 2         | 5%      |
| Syntek EasyCamera                                          | 1         | 2.5%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                   | 1         | 2.5%    |
| Sunplus Laptop_Integrated_Webcam_FHD                       | 1         | 2.5%    |
| Sunplus Integrated Camera                                  | 1         | 2.5%    |
| Sunplus Dell E5570 integrated webcam                       | 1         | 2.5%    |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 2.5%    |
| Silicon Motion HP Webcam-50                                | 1         | 2.5%    |
| Realtek USB Camera                                         | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD                               | 1         | 2.5%    |
| Microdia Integrated_Webcam_HD                              | 1         | 2.5%    |
| Lite-On HP TrueVision HD Camera                            | 1         | 2.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 2.5%    |
| IMC Networks USB2.0 UVC HD Webcam                          | 1         | 2.5%    |
| IMC Networks Integrated Webcam                             | 1         | 2.5%    |
| IMC Networks Integrated Camera                             | 1         | 2.5%    |
| Chicony WebCam                                             | 1         | 2.5%    |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 2.5%    |
| Chicony ThinkPad T490 Webcam                               | 1         | 2.5%    |
| Chicony Thinkpad T430 camera                               | 1         | 2.5%    |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 2.5%    |
| Chicony HP TrueVision HD Camera                            | 1         | 2.5%    |
| Chicony 2.0M UVC Webcam / CNF7129                          | 1         | 2.5%    |
| Chicony 1.3M Webcam                                        | 1         | 2.5%    |
| Chicony 1.3 MPixel UVC Webcam                              | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 2.5%    |
| ALi M5602 Video Camera Controller                          | 1         | 2.5%    |
| Acer SunplusIT INC. Integrated Camera                      | 1         | 2.5%    |
| Acer HD Webcam                                             | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 2         | 28.57%  |
| AuthenTec             | 2         | 28.57%  |
| Upek                  | 1         | 14.29%  |
| Synaptics             | 1         | 14.29%  |
| Elan Microelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 14.29%  |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 14.29%  |
| AuthenTec AES2810                                      | 1         | 14.29%  |
| AuthenTec AES1600                                      | 1         | 14.29%  |

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
| 2     | 19        | 33.93%  |
| 1     | 15        | 26.79%  |
| 0     | 11        | 19.64%  |
| 3     | 9         | 16.07%  |
| 4     | 2         | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 31        | 37.8%   |
| Card reader              | 14        | 17.07%  |
| Bluetooth                | 13        | 15.85%  |
| Net/wireless             | 12        | 14.63%  |
| Fingerprint reader       | 7         | 8.54%   |
| Graphics card            | 2         | 2.44%   |
| Network                  | 1         | 1.22%   |
| Modem                    | 1         | 1.22%   |
| Firewire controller      | 1         | 1.22%   |

