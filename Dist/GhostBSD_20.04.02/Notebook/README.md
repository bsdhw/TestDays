GhostBSD 20.04.02 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for GhostBSD 20.04.02.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=ghostbsd-20.04.02

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Samsung       | 550P5C/550P7C               | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| HP            | Pavilion g6                 | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| Acer          | Aspire 5750                 | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Dell          | Latitude E5440              | [3f2e8586a7](https://bsd-hardware.info/?probe=3f2e8586a7) | Aug 05, 2021 |
| Dell          | Latitude E6430              | [4149fa5ec3](https://bsd-hardware.info/?probe=4149fa5ec3) | Aug 04, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| GPU Compan... | GWTN156-5                   | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Dell          | Latitude E5520              | [e0dd26220f](https://bsd-hardware.info/?probe=e0dd26220f) | Jul 21, 2021 |
| Apple         | MacBook5,1                  | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Dell          | Latitude E6420              | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | [a2deab0991](https://bsd-hardware.info/?probe=a2deab0991) | Jun 15, 2021 |
| Sony          | SVP1322M1EBI                | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [11fe52be5e](https://bsd-hardware.info/?probe=11fe52be5e) | May 13, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [f8389b0546](https://bsd-hardware.info/?probe=f8389b0546) | Apr 24, 2021 |
| HP            | Laptop 15-da0xxx            | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Apple         | MacBookPro8,1               | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Acer          | Aspire E5-521G              | [e2b6dbfe40](https://bsd-hardware.info/?probe=e2b6dbfe40) | Apr 01, 2021 |
| HP            | 255 G7 Notebook PC          | [3e500c12a3](https://bsd-hardware.info/?probe=3e500c12a3) | Mar 24, 2021 |
| HP            | Laptop 15-da0xxx            | [a7a25be087](https://bsd-hardware.info/?probe=a7a25be087) | Mar 16, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [c7f71901c3](https://bsd-hardware.info/?probe=c7f71901c3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [803974a844](https://bsd-hardware.info/?probe=803974a844) | Mar 11, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [196cd8a730](https://bsd-hardware.info/?probe=196cd8a730) | Mar 11, 2021 |
| Acer          | Aspire F5-573G              | [240171b234](https://bsd-hardware.info/?probe=240171b234) | Mar 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9ede3128c5](https://bsd-hardware.info/?probe=9ede3128c5) | Mar 07, 2021 |
| HP            | Laptop 15-db0xxx            | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [b85d23571e](https://bsd-hardware.info/?probe=b85d23571e) | Feb 23, 2021 |
| Acer          | Extensa 5635Z               | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| Apple         | MacBookPro5,5               | [9bbe1119a1](https://bsd-hardware.info/?probe=9bbe1119a1) | Feb 12, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| HP            | Laptop 15-da0xxx            | [d6bc2b2c1d](https://bsd-hardware.info/?probe=d6bc2b2c1d) | Feb 08, 2021 |
| Apple         | MacBookPro5,5               | [ffc0295ae1](https://bsd-hardware.info/?probe=ffc0295ae1) | Feb 07, 2021 |
| Apple         | MacBookPro5,5               | [13fdaa7c15](https://bsd-hardware.info/?probe=13fdaa7c15) | Feb 04, 2021 |
| Apple         | MacBookPro5,5               | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| HP            | Laptop 15-da0xxx            | [869d894f4f](https://bsd-hardware.info/?probe=869d894f4f) | Jan 30, 2021 |
| Dell          | Latitude 5480               | [9b38a72dd4](https://bsd-hardware.info/?probe=9b38a72dd4) | Jan 26, 2021 |
| HP            | Laptop 15-da0xxx            | [3e37c56f14](https://bsd-hardware.info/?probe=3e37c56f14) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Dell          | Inspiron 3542               | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| HP            | OMEN by HP Laptop           | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| ASUSTek       | X550LC                      | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [a395c023bf](https://bsd-hardware.info/?probe=a395c023bf) | Jan 10, 2021 |
| Dell          | Inspiron 5758               | [c096e37be5](https://bsd-hardware.info/?probe=c096e37be5) | Jan 03, 2021 |
| HP            | Laptop 14-dk0xxx            | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| Lenovo        | Yoga 2 13 20344             | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 42872VU       | [c843b5d271](https://bsd-hardware.info/?probe=c843b5d271) | Dec 10, 2020 |
| Acer          | Aspire 7540                 | [65d215a03b](https://bsd-hardware.info/?probe=65d215a03b) | Nov 17, 2020 |
| Apple         | MacBook6,1                  | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Acer          | Aspire E1-532               | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | Laptop 15-da0xxx            | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | [1d9786ac9f](https://bsd-hardware.info/?probe=1d9786ac9f) | Aug 31, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | [e505894bee](https://bsd-hardware.info/?probe=e505894bee) | Aug 29, 2020 |
| System76      | Lemur Pro                   | [0163d0f084](https://bsd-hardware.info/?probe=0163d0f084) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539JM      | [facf6fa0f8](https://bsd-hardware.info/?probe=facf6fa0f8) | Aug 27, 2020 |
| ASUSTek       | K53SD                       | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Sony          | VGN-SZ3VWP_X                | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| TUXEDO        | InfinityBook13V3            | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Dell          | Inspiron 3542               | [b89da90904](https://bsd-hardware.info/?probe=b89da90904) | Aug 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| MATE     | 47        | 81.03%  |
| XFCE     | 8         | 13.79%  |
| KDE5     | 1         | 1.72%   |
| GNOME    | 1         | 1.72%   |
| Cinnamon | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 57        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 57        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 23        | 38.98%  |
| Unknown | 16        | 27.12%  |
| C       | 8         | 13.56%  |
| de_DE   | 3         | 5.08%   |
| it_IT   | 2         | 3.39%   |
| zh_CN   | 1         | 1.69%   |
| ru_RU   | 1         | 1.69%   |
| pt_BR   | 1         | 1.69%   |
| es_ES   | 1         | 1.69%   |
| en_NZ   | 1         | 1.69%   |
| en_GB   | 1         | 1.69%   |
| el_GR   | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 37        | 64.91%  |
| BIOS | 20        | 35.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 54        | 93.1%   |
| Ufs  | 4         | 6.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 55        | 96.49%  |
| MBR  | 2         | 3.51%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 31.58%  |
| Dell                | 11        | 19.3%   |
| Acer                | 7         | 12.28%  |
| Hewlett-Packard     | 6         | 10.53%  |
| Apple               | 3         | 5.26%   |
| Sony                | 2         | 3.51%   |
| Samsung Electronics | 2         | 3.51%   |
| ASUSTek Computer    | 2         | 3.51%   |
| TUXEDO              | 1         | 1.75%   |
| Toshiba             | 1         | 1.75%   |
| System76            | 1         | 1.75%   |
| Panasonic           | 1         | 1.75%   |
| Notebook            | 1         | 1.75%   |
| GPU Company         | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 5.26%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 3.51%   |
| Dell Latitude E6420                      | 2         | 3.51%   |
| TUXEDO InfinityBook13V3                  | 1         | 1.75%   |
| Toshiba Satellite C855                   | 1         | 1.75%   |
| System76 Lemur Pro                       | 1         | 1.75%   |
| Sony VGN-SZ3VWP_X                        | 1         | 1.75%   |
| Sony SVP1322M1EBI                        | 1         | 1.75%   |
| Samsung 550P5C/550P7C                    | 1         | 1.75%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 1.75%   |
| Panasonic CF-19AHNC8FN                   | 1         | 1.75%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 1.75%   |
| Lenovo Yoga 2 13 20344                   | 1         | 1.75%   |
| Lenovo ThinkPad X250 20CM003WMS          | 1         | 1.75%   |
| Lenovo ThinkPad X220 42872VU             | 1         | 1.75%   |
| Lenovo ThinkPad T590 20N40016CD          | 1         | 1.75%   |
| Lenovo ThinkPad T530 239242U             | 1         | 1.75%   |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 1.75%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01    | 1         | 1.75%   |
| Lenovo ThinkPad T470 20HD000MUK          | 1         | 1.75%   |
| Lenovo ThinkPad T450 20BV0064US          | 1         | 1.75%   |
| Lenovo ThinkPad T440 20B7S1860W          | 1         | 1.75%   |
| Lenovo ThinkPad T430s 23539JM            | 1         | 1.75%   |
| Lenovo ThinkPad T430 2344C4U             | 1         | 1.75%   |
| Lenovo ThinkPad L512 44444XG             | 1         | 1.75%   |
| Lenovo Legion Y7000P 81LD                | 1         | 1.75%   |
| Lenovo IdeaPad S145-15API 81UT           | 1         | 1.75%   |
| Lenovo IdeaPad 520-15IKB 81BF            | 1         | 1.75%   |
| HP Pavilion g6                           | 1         | 1.75%   |
| HP OMEN by HP Laptop                     | 1         | 1.75%   |
| HP Laptop 15-db0xxx                      | 1         | 1.75%   |
| HP Laptop 15-da0xxx                      | 1         | 1.75%   |
| HP Laptop 14-dk0xxx                      | 1         | 1.75%   |
| HP 255 G7 Notebook PC                    | 1         | 1.75%   |
| GPU Company GWTN156-5                    | 1         | 1.75%   |
| Dell Latitude E6430                      | 1         | 1.75%   |
| Dell Latitude E5520                      | 1         | 1.75%   |
| Dell Latitude E5440                      | 1         | 1.75%   |
| Dell Latitude 5480                       | 1         | 1.75%   |
| Dell Latitude 5280                       | 1         | 1.75%   |
| Dell Inspiron 5758                       | 1         | 1.75%   |
| ASUS X550LC                              | 1         | 1.75%   |
| ASUS K53SD                               | 1         | 1.75%   |
| Apple MacBookPro5,5                      | 1         | 1.75%   |
| Apple MacBook6,1                         | 1         | 1.75%   |
| Apple MacBook5,1                         | 1         | 1.75%   |
| Acer Extensa 5635Z                       | 1         | 1.75%   |
| Acer Aspire F5-573G                      | 1         | 1.75%   |
| Acer Aspire E5-521G                      | 1         | 1.75%   |
| Acer Aspire E1-532                       | 1         | 1.75%   |
| Acer Aspire A315-42                      | 1         | 1.75%   |
| Acer Aspire 7540                         | 1         | 1.75%   |
| Acer Aspire 5750                         | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 14        | 24.56%  |
| Dell Latitude           | 7         | 12.28%  |
| Acer Aspire             | 6         | 10.53%  |
| Dell Inspiron           | 4         | 7.02%   |
| HP Laptop               | 3         | 5.26%   |
| Lenovo IdeaPad          | 2         | 3.51%   |
| TUXEDO InfinityBook13V3 | 1         | 1.75%   |
| Toshiba Satellite       | 1         | 1.75%   |
| System76 Lemur          | 1         | 1.75%   |
| Sony VGN-SZ3VWP         | 1         | 1.75%   |
| Sony SVP1322M1EBI       | 1         | 1.75%   |
| Samsung 550P5C          | 1         | 1.75%   |
| Samsung 3570R           | 1         | 1.75%   |
| Panasonic CF-19AHNC8FN  | 1         | 1.75%   |
| Notebook N85            | 1         | 1.75%   |
| Lenovo Yoga             | 1         | 1.75%   |
| Lenovo Legion           | 1         | 1.75%   |
| HP Pavilion             | 1         | 1.75%   |
| HP OMEN                 | 1         | 1.75%   |
| HP 255                  | 1         | 1.75%   |
| GPU Company GWTN156-5   | 1         | 1.75%   |
| ASUS X550LC             | 1         | 1.75%   |
| ASUS K53SD              | 1         | 1.75%   |
| Apple MacBookPro5       | 1         | 1.75%   |
| Apple MacBook6          | 1         | 1.75%   |
| Apple MacBook5          | 1         | 1.75%   |
| Acer Extensa            | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 13        | 22.81%  |
| 2019 | 11        | 19.3%   |
| 2009 | 5         | 8.77%   |
| 2018 | 4         | 7.02%   |
| 2017 | 4         | 7.02%   |
| 2014 | 4         | 7.02%   |
| 2012 | 4         | 7.02%   |
| 2016 | 3         | 5.26%   |
| 2013 | 3         | 5.26%   |
| 2011 | 3         | 5.26%   |
| 2015 | 1         | 1.75%   |
| 2010 | 1         | 1.75%   |
| 2007 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 98.25%  |
| Yes  | 1         | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 33        | 57.89%  |
| 16.01-24.0 | 11        | 19.3%   |
| 4.01-8.0   | 10        | 17.54%  |
| 24.01-32.0 | 2         | 3.51%   |
| 2.01-3.0   | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 27        | 46.55%  |
| 0.51-1.0 | 25        | 43.1%   |
| 2.01-3.0 | 5         | 8.62%   |
| 1.01-2.0 | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 75.44%  |
| 2      | 12        | 21.05%  |
| 0      | 2         | 3.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 59.65%  |
| Yes       | 23        | 40.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 91.23%  |
| No        | 5         | 8.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 70.18%  |
| No        | 17        | 29.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 13        | 22.81%  |
| France      | 5         | 8.77%   |
| Poland      | 4         | 7.02%   |
| Germany     | 4         | 7.02%   |
| UK          | 3         | 5.26%   |
| Spain       | 3         | 5.26%   |
| Russia      | 3         | 5.26%   |
| New Zealand | 3         | 5.26%   |
| Philippines | 2         | 3.51%   |
| Italy       | 2         | 3.51%   |
| Finland     | 2         | 3.51%   |
| Ukraine     | 1         | 1.75%   |
| Switzerland | 1         | 1.75%   |
| Sweden      | 1         | 1.75%   |
| Serbia      | 1         | 1.75%   |
| Portugal    | 1         | 1.75%   |
| Norway      | 1         | 1.75%   |
| Namibia     | 1         | 1.75%   |
| Japan       | 1         | 1.75%   |
| Hong Kong   | 1         | 1.75%   |
| Greece      | 1         | 1.75%   |
| Egypt       | 1         | 1.75%   |
| Brazil      | 1         | 1.75%   |
| Argentina   | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Franconville        | 3         | 5.17%   |
| Chrusty             | 3         | 5.17%   |
| Giessen             | 2         | 3.45%   |
| Clemmons            | 2         | 3.45%   |
| Yokohama            | 1         | 1.72%   |
| Yaroslavl           | 1         | 1.72%   |
| Whittier            | 1         | 1.72%   |
| Wenatchee           | 1         | 1.72%   |
| Taita               | 1         | 1.72%   |
| Stiring-Wendel      | 1         | 1.72%   |
| Sollentuna          | 1         | 1.72%   |
| Santo Tomas         | 1         | 1.72%   |
| Salem               | 1         | 1.72%   |
| Rochester           | 1         | 1.72%   |
| Richmond            | 1         | 1.72%   |
| Resistencia         | 1         | 1.72%   |
| Peoria              | 1         | 1.72%   |
| Oslo                | 1         | 1.72%   |
| Oshakati            | 1         | 1.72%   |
| Moscow              | 1         | 1.72%   |
| Milan               | 1         | 1.72%   |
| Marysville          | 1         | 1.72%   |
| Makati City         | 1         | 1.72%   |
| Lutz                | 1         | 1.72%   |
| London              | 1         | 1.72%   |
| Lenzburg            | 1         | 1.72%   |
| Kyiv                | 1         | 1.72%   |
| Krasnoyarsk         | 1         | 1.72%   |
| Jyväskylä         | 1         | 1.72%   |
| Huddersfield        | 1         | 1.72%   |
| Hamilton            | 1         | 1.72%   |
| Hamburg             | 1         | 1.72%   |
| Grajewo             | 1         | 1.72%   |
| Giza                | 1         | 1.72%   |
| Fiumicino           | 1         | 1.72%   |
| Estoril             | 1         | 1.72%   |
| Estacada            | 1         | 1.72%   |
| Espoo               | 1         | 1.72%   |
| Englewood           | 1         | 1.72%   |
| Clichy-sous-Bois    | 1         | 1.72%   |
| City of Westminster | 1         | 1.72%   |
| Christchurch        | 1         | 1.72%   |
| Central             | 1         | 1.72%   |
| Carcer              | 1         | 1.72%   |
| Cambre              | 1         | 1.72%   |
| Cairo               | 1         | 1.72%   |
| Bensheim            | 1         | 1.72%   |
| Beniarjo            | 1         | 1.72%   |
| Belgrade            | 1         | 1.72%   |
| Athens              | 1         | 1.72%   |
| Atascadero          | 1         | 1.72%   |
| Aracaju             | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 22     | 23.88%  |
| WDC                 | 9         | 9      | 13.43%  |
| Seagate             | 7         | 11     | 10.45%  |
| SanDisk             | 6         | 6      | 8.96%   |
| Kingston            | 4         | 4      | 5.97%   |
| Crucial             | 4         | 5      | 5.97%   |
| Toshiba             | 3         | 4      | 4.48%   |
| Hitachi             | 3         | 3      | 4.48%   |
| SK Hynix            | 2         | 2      | 2.99%   |
| PNY                 | 2         | 2      | 2.99%   |
| Micron Technology   | 2         | 2      | 2.99%   |
| PLEXTOR             | 1         | 1      | 1.49%   |
| Patriot             | 1         | 1      | 1.49%   |
| Netac               | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 1      | 1.49%   |
| KingSpec            | 1         | 1      | 1.49%   |
| HGST                | 1         | 1      | 1.49%   |
| GOODRAM             | 1         | 1      | 1.49%   |
| Gigabyte Technology | 1         | 1      | 1.49%   |
| Fujitsu             | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2.94%   |
| Samsung SSD 860 QVO 1TB              | 2         | 2.94%   |
| Samsung SSD 850 EVO 250GB            | 2         | 2.94%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 1.47%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 1.47%   |
| WDC WDS100T1B0A-00H9H0 1TB           | 1         | 1.47%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 1.47%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1.47%   |
| WDC WD3200LPVX-75V0TT0 320GB         | 1         | 1.47%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 1.47%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1.47%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 1.47%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 1.47%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.47%   |
| Toshiba MQ01ACF032 320GB             | 1         | 1.47%   |
| SK Hynix SC311 SATA 512GB            | 1         | 1.47%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 1.47%   |
| Seagate ST9250410AS 250GB            | 1         | 1.47%   |
| Seagate ST500LM030-2E717D 500GB      | 1         | 1.47%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1.47%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 1.47%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1.47%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 1.47%   |
| SanDisk SSD U110 16GB                | 1         | 1.47%   |
| SanDisk SSD PLUS 240GB               | 1         | 1.47%   |
| SanDisk SSD PLUS 1000GB              | 1         | 1.47%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 1.47%   |
| SanDisk SDSSDA240G 240GB             | 1         | 1.47%   |
| SanDisk SD8SNAT-128G-1006 128GB      | 1         | 1.47%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 1.47%   |
| Samsung SSD 970 EVO 250GB            | 1         | 1.47%   |
| Samsung SSD 950 PRO 512GB            | 1         | 1.47%   |
| Samsung SSD 860 PRO 512GB            | 1         | 1.47%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.47%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.47%   |
| Samsung SSD 850 PRO 1TB              | 1         | 1.47%   |
| Samsung PM981 NVMe 256GB             | 1         | 1.47%   |
| Samsung MZVLB256HAHQ-000L2 256GB     | 1         | 1.47%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 1         | 1.47%   |
| Samsung MZNLN256HAJQ-000L7 256GB     | 1         | 1.47%   |
| Samsung HM500JJ 500GB                | 1         | 1.47%   |
| PNY CS900 240GB SSD                  | 1         | 1.47%   |
| PNY CS1311 480GB SSD                 | 1         | 1.47%   |
| PLEXTOR PH6-CE240 240GB              | 1         | 1.47%   |
| Patriot Burst 240GB                  | 1         | 1.47%   |
| Netac SSD 256GB                      | 1         | 1.47%   |
| Micron MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1.47%   |
| Micron 1100 SATA 256GB               | 1         | 1.47%   |
| LITEONIT LGT-128M6G 128GB            | 1         | 1.47%   |
| Kingston SUV400S37240G 240GB         | 1         | 1.47%   |
| Kingston SUV400S37120G 120GB         | 1         | 1.47%   |
| Kingston SA400S37960G 960GB          | 1         | 1.47%   |
| Kingston SA400S37480G 480GB          | 1         | 1.47%   |
| KingSpec Q-720 720GB                 | 1         | 1.47%   |
| Hitachi HTS725050A7E630 500GB        | 1         | 1.47%   |
| Hitachi HTS545025B9SA02 250GB        | 1         | 1.47%   |
| Hitachi HTS543225L9A300 250GB        | 1         | 1.47%   |
| HGST HTS725050A7E630 500GB           | 1         | 1.47%   |
| GOODRAM SSDPR-CX400-256-G2 256GB     | 1         | 1.47%   |
| Gigabyte GP-GSM2NE3100TNTD 1TB       | 1         | 1.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 11     | 35%     |
| WDC                 | 5         | 5      | 25%     |
| Hitachi             | 3         | 3      | 15%     |
| Toshiba             | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 16     | 26.32%  |
| SanDisk             | 6         | 6      | 15.79%  |
| Kingston            | 4         | 4      | 10.53%  |
| Crucial             | 4         | 5      | 10.53%  |
| WDC                 | 3         | 3      | 7.89%   |
| PNY                 | 2         | 2      | 5.26%   |
| Micron Technology   | 2         | 2      | 5.26%   |
| SK Hynix            | 1         | 1      | 2.63%   |
| PLEXTOR             | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| Netac               | 1         | 1      | 2.63%   |
| LITEONIT            | 1         | 1      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| GOODRAM             | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 34        | 45     | 54.84%  |
| HDD  | 19        | 24     | 30.65%  |
| NVMe | 9         | 10     | 14.52%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 69     | 84.75%  |
| NVMe | 9         | 10     | 15.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 38     | 64.15%  |
| 0.51-1.0   | 17        | 28     | 32.08%  |
| 1.01-2.0   | 2         | 3      | 3.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 32.76%  |
| 1-20       | 12        | 20.69%  |
| 251-500    | 11        | 18.97%  |
| 501-1000   | 7         | 12.07%  |
| 51-100     | 5         | 8.62%   |
| Unknown    | 4         | 6.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 53        | 88.33%  |
| Unknown | 4         | 6.67%   |
| 21-50   | 3         | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 14.29%  |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 14.29%  |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 14.29%  |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 14.29%  |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 14.29%  |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 28.57%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 71.43%  |
| SSD  | 2         | 2      | 28.57%  |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 49        | 72     | 87.5%   |
| Malfunc | 7         | 7      | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 43        | 67.19%  |
| AMD                 | 9         | 14.06%  |
| Samsung Electronics | 5         | 7.81%   |
| Nvidia              | 3         | 4.69%   |
| Toshiba             | 1         | 1.56%   |
| SK Hynix            | 1         | 1.56%   |
| Sandisk             | 1         | 1.56%   |
| Phison Electronics  | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 8         | 12.31%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 8         | 12.31%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 7         | 10.77%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 7         | 10.77%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 6         | 9.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 6.15%   |
| Nvidia MCP79 AHCI Controller                                                 | 3         | 4.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 4.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 3.08%   |
| Toshiba XG4 NVMe SSD Controller                                              | 1         | 1.54%   |
| SK Hynix BC501 NVMe Solid State Drive                                        | 1         | 1.54%   |
| Sandisk PC SN520 NVMe SSD                                                    | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM951/PM951                                      | 1         | 1.54%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 1.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 1.54%   |
| AMD FCH SATA Controller [IDE mode]                                           | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 78.13%  |
| NVMe | 9         | 14.06%  |
| RAID | 3         | 4.69%   |
| IDE  | 2         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 84.21%  |
| AMD    | 9         | 15.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 5.26%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 3.51%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 3.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 3.51%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 3.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.51%   |
| Intel Core i5-2520M CPU @ 2.50GH              | 2         | 3.51%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 3.51%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 3.51%   |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 1.75%   |
| Intel Genuine CPU                             | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.75%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.75%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.75%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.75%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.75%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 1.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i5-2430M CPU @ 2.40GH              | 1         | 1.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.75%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.75%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.75%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.75%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz          | 1         | 1.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.75%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 1         | 1.75%   |
| Intel Core 2 CPU T7400 @ 2.16GHz              | 1         | 1.75%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.75%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.75%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 1         | 1.75%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.75%   |
| AMD New Processor Technology                  | 1         | 1.75%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 1.75%   |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 26        | 45.61%  |
| Intel Core i7    | 10        | 17.54%  |
| Intel Core 2 Duo | 5         | 8.77%   |
| Intel Core i3    | 3         | 5.26%   |
| AMD Ryzen 5      | 2         | 3.51%   |
| AMD A6           | 2         | 3.51%   |
| AMD A4           | 2         | 3.51%   |
| Other            | 1         | 1.75%   |
| Intel Pentium    | 1         | 1.75%   |
| Intel Genuine    | 1         | 1.75%   |
| Intel Core 2     | 1         | 1.75%   |
| Intel Celeron    | 1         | 1.75%   |
| AMD Ryzen 7      | 1         | 1.75%   |
| AMD Ryzen 3      | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 36        | 63.16%  |
| 4       | 13        | 22.81%  |
| Unknown | 5         | 8.77%   |
| 8       | 3         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 94.74%  |
| 2      | 3         | 5.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 39        | 68.42%  |
| 1       | 13        | 22.81%  |
| Unknown | 5         | 8.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 15.79%  |
| IvyBridge   | 9         | 15.79%  |
| Haswell     | 9         | 15.79%  |
| SandyBridge | 7         | 12.28%  |
| Penryn      | 5         | 8.77%   |
| Zen+        | 4         | 7.02%   |
| Skylake     | 4         | 7.02%   |
| Broadwell   | 3         | 5.26%   |
| Excavator   | 2         | 3.51%   |
| Westmere    | 1         | 1.75%   |
| Puma        | 1         | 1.75%   |
| K10 Llano   | 1         | 1.75%   |
| K10         | 1         | 1.75%   |
| Core        | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 63.77%  |
| Nvidia | 14        | 20.29%  |
| AMD    | 11        | 15.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 12.68%  |
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 12.68%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 9.86%   |
| AMD Picasso                                                                   | 4         | 5.63%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 4.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 4.23%   |
| Intel HD Graphics 620                                                         | 3         | 4.23%   |
| Intel HD Graphics 5500                                                        | 3         | 4.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 2         | 2.82%   |
| Intel UHD Graphics 620                                                        | 2         | 2.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 2.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.41%   |
| Nvidia GM206M [GeForce GTX 965M]                                              | 1         | 1.41%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 1.41%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 1.41%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.41%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 1         | 1.41%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.41%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.41%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.41%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.41%   |
| Intel HD Graphics 630                                                         | 1         | 1.41%   |
| Intel HD Graphics 530                                                         | 1         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.41%   |
| AMD Sumo [Radeon HD 6520G]                                                    | 1         | 1.41%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 1.41%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                       | 1         | 1.41%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 1         | 1.41%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 1         | 1.41%   |
| AMD Jet XT [Radeon R5 M240]                                                   | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 52.63%  |
| Intel + Nvidia | 11        | 19.3%   |
| 1 x AMD        | 9         | 15.79%  |
| 1 x Nvidia     | 3         | 5.26%   |
| 2 x Intel      | 2         | 3.51%   |
| 2 x AMD        | 1         | 1.75%   |
| Intel + AMD    | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 55        | 96.49%  |
| Proprietary | 2         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 87.72%  |
| 0.01-0.5   | 3         | 5.26%   |
| 1.01-2.0   | 2         | 3.51%   |
| 3.01-4.0   | 1         | 1.75%   |
| 0.51-1.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 10        | 19.61%  |
| AU Optronics        | 10        | 19.61%  |
| Chimei Innolux      | 9         | 17.65%  |
| Samsung Electronics | 8         | 15.69%  |
| BOE                 | 4         | 7.84%   |
| Philips             | 1         | 1.96%   |
| PANDA               | 1         | 1.96%   |
| Panasonic           | 1         | 1.96%   |
| Lenovo              | 1         | 1.96%   |
| InfoVision          | 1         | 1.96%   |
| IBM                 | 1         | 1.96%   |
| Hewlett-Packard     | 1         | 1.96%   |
| Dell                | 1         | 1.96%   |
| CSO                 | 1         | 1.96%   |
| BenQ                | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch          | 2         | 3.85%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 2         | 3.85%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 3.85%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch        | 2         | 3.85%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch | 1         | 1.92%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 310x170mm 13.9-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch | 1         | 1.92%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch            | 1         | 1.92%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch              | 1         | 1.92%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD0558 1920x1080 310x170mm 13.9-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch          | 1         | 1.92%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 1         | 1.92%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.92%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                | 1         | 1.92%   |
| Hewlett-Packard 22w HPN342E 1920x1080 480x270mm 21.7-inch            | 1         | 1.92%   |
| Dell U3818DW DELA0F0 3840x1600 880x370mm 37.6-inch                   | 1         | 1.92%   |
| CSO LCD Monitor CSO1501 3840x2160 340x190mm 15.3-inch                | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 310x170mm 13.9-inch     | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 310x170mm 13.9-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch     | 1         | 1.92%   |
| BOE LCD Monitor BOE06FB 1920x1080 340x190mm 15.3-inch                | 1         | 1.92%   |
| BOE LCD Monitor BOE06C6 1920x1080 340x190mm 15.3-inch                | 1         | 1.92%   |
| BOE LCD Monitor BOE06A5 1366x768 340x190mm 15.3-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE05F6 1366x768 310x170mm 13.9-inch                 | 1         | 1.92%   |
| BenQ RL2455 BNQ7F1C 1920x1080 530x300mm 24.0-inch                    | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 340x190mm 15.3-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO303E 1600x900 310x170mm 13.9-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO149E 1600x900 380x210mm 17.1-inch        | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 25        | 49.02%  |
| 1920x1080 (FHD)    | 12        | 23.53%  |
| 1600x900 (HD+)     | 7         | 13.73%  |
| 3840x2160 (4K)     | 2         | 3.92%   |
| 1680x1050 (WSXGA+) | 2         | 3.92%   |
| 3840x1600          | 1         | 1.96%   |
| 2880x1620          | 1         | 1.96%   |
| 1280x1024 (SXGA)   | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 50%     |
| 13     | 14        | 26.92%  |
| 17     | 4         | 7.69%   |
| 12     | 3         | 5.77%   |
| 39     | 1         | 1.92%   |
| 37     | 1         | 1.92%   |
| 24     | 1         | 1.92%   |
| 22     | 1         | 1.92%   |
| 21     | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 76.47%  |
| 201-300     | 4         | 7.84%   |
| 351-400     | 3         | 5.88%   |
| 801-900     | 2         | 3.92%   |
| 401-500     | 2         | 3.92%   |
| 501-600     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 89.8%   |
| 16/10 | 3         | 6.12%   |
| 5/4   | 1         | 2.04%   |
| 21/9  | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 44.23%  |
| 81-90          | 13        | 25%     |
| 61-70          | 3         | 5.77%   |
| 201-250        | 3         | 5.77%   |
| 121-130        | 3         | 5.77%   |
| 101-110        | 3         | 5.77%   |
| 501-1000       | 2         | 3.85%   |
| 71-80          | 1         | 1.92%   |
| 141-150        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 25        | 50%     |
| 121-160       | 16        | 32%     |
| 51-100        | 5         | 10%     |
| 161-240       | 3         | 6%      |
| More than 240 | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 77.19%  |
| 0     | 8         | 14.04%  |
| 2     | 5         | 8.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 32.63%  |
| Realtek Semiconductor             | 24        | 25.26%  |
| Qualcomm Atheros                  | 16        | 16.84%  |
| Broadcom                          | 8         | 8.42%   |
| TP-Link                           | 5         | 5.26%   |
| Nvidia                            | 3         | 3.16%   |
| Ericsson Business Mobile Networks | 3         | 3.16%   |
| Ralink                            | 1         | 1.05%   |
| Qualcomm                          | 1         | 1.05%   |
| Marvell Technology Group          | 1         | 1.05%   |
| Edimax Technology                 | 1         | 1.05%   |
| ASUSTek Computer                  | 1         | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 15        | 12.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 10        | 8.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 6         | 4.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 5         | 4.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 4         | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 4         | 3.31%   |
| Intel Wireless 8265 / 8275                                                  | 4         | 3.31%   |
| Intel Wireless 7260                                                         | 4         | 3.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 4         | 3.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3         | 2.48%   |
| Nvidia MCP79 Ethernet                                                       | 3         | 2.48%   |
| Intel Wireless 7265                                                         | 3         | 2.48%   |
| Intel Ethernet Connection (4) I219-LM                                       | 3         | 2.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 2         | 1.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 1.65%   |
| Intel Wireless 8260                                                         | 2         | 1.65%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 1.65%   |
| Intel Ethernet Connection (3) I218-LM                                       | 2         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 1.65%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 1.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 2         | 1.65%   |
| TP-Link TP-Link High Power Wireless USB Adapter                             | 1         | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 1         | 0.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 0.83%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 1         | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 1         | 0.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                       | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 1         | 0.83%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                  | 1         | 0.83%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 0.83%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                        | 1         | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 1         | 0.83%   |
| Intel Ethernet Connection I219-LM                                           | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                                        | 1         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 0.83%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 1         | 0.83%   |
| Intel Centrino Wireless-N 100                                               | 1         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 1         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                                    | 1         | 0.83%   |
| Ericsson Business Mobile Networks N5321 gw Mobile Broadband Serial Port III | 1         | 0.83%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module          | 1         | 0.83%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 0.83%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 1         | 0.83%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                           | 1         | 0.83%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                            | 1         | 0.83%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 1         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                             | 1         | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 0.83%   |
| ASUS ASUS Wireless USB adapter                                              | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 43.75%  |
| Qualcomm Atheros      | 14        | 21.88%  |
| Realtek Semiconductor | 9         | 14.06%  |
| TP-Link               | 5         | 7.81%   |
| Broadcom              | 5         | 7.81%   |
| Ralink                | 1         | 1.56%   |
| Edimax Technology     | 1         | 1.56%   |
| ASUSTek Computer      | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 9.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 6.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 6.15%   |
| Intel Wireless 8265 / 8275                                     | 4         | 6.15%   |
| Intel Wireless 7260                                            | 4         | 6.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 6.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 4.62%   |
| Intel Wireless 7265                                            | 3         | 4.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 3.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 3.08%   |
| Intel Wireless 8260                                            | 2         | 3.08%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 3.08%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 3.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 3.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.08%   |
| TP-Link TP-Link High Power Wireless USB Adapter                | 1         | 1.54%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.54%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 1.54%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.54%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.54%   |
| Intel Centrino Wireless-N 100                                  | 1         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.54%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 1.54%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.54%   |
| ASUS ASUS Wireless USB adapter                                 | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 38.46%  |
| Intel                    | 20        | 38.46%  |
| Broadcom                 | 4         | 7.69%   |
| Qualcomm Atheros         | 3         | 5.77%   |
| Nvidia                   | 3         | 5.77%   |
| Qualcomm                 | 1         | 1.92%   |
| Marvell Technology Group | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 28.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 18.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.43%   |
| Nvidia MCP79 Ethernet                                             | 3         | 5.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 5.66%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.77%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.89%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.89%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.89%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.89%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 51.33%  |
| Ethernet | 52        | 46.02%  |
| Modem    | 2         | 1.77%   |
| Unknown  | 1         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 51        | 52.58%  |
| WiFi     | 45        | 46.39%  |
| Modem    | 1         | 1.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 87.72%  |
| 1     | 6         | 10.53%  |
| 3     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 37.5%   |
| Qualcomm Atheros Communications | 6         | 15%     |
| Broadcom                        | 5         | 12.5%   |
| Realtek Semiconductor           | 4         | 10%     |
| Lite-On Technology              | 4         | 10%     |
| Apple                           | 3         | 7.5%    |
| Alps Electric                   | 2         | 5%      |
| Dell                            | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 10        | 25%     |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 7.5%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 7.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 7.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 7.5%    |
| Apple Bluetooth Host Controller                             | 3         | 7.5%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 5%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 5%      |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 5%      |
| Realtek  Bluetooth Adapter                                  | 1         | 2.5%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.5%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 2.5%    |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 2.5%    |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 45        | 77.59%  |
| AMD      | 9         | 15.52%  |
| Nvidia   | 3         | 5.17%   |
| Logitech | 1         | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 11.39%  |
| Intel 8 Series HD Audio Controller                                         | 9         | 11.39%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 11.39%  |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 10.13%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 8.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 5.06%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 5.06%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 3.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.8%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.53%   |
| AMD High Definition Audio Controller                                       | 2         | 2.53%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.53%   |
| Logitech H600 [Wireless Headset]                                           | 1         | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.27%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.27%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.27%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 29.33%  |
| SK Hynix            | 17        | 22.67%  |
| Unknown             | 6         | 8%      |
| Micron Technology   | 5         | 6.67%   |
| Kingston            | 5         | 6.67%   |
| Crucial             | 5         | 6.67%   |
| ELPIDA              | 3         | 4%      |
| G.Skill             | 2         | 2.67%   |
| A-DATA Technology   | 2         | 2.67%   |
| Team                | 1         | 1.33%   |
| Smart               | 1         | 1.33%   |
| Ramaxel Technology  | 1         | 1.33%   |
| Neo Forza           | 1         | 1.33%   |
| Nanya Technology    | 1         | 1.33%   |
| GOODRAM             | 1         | 1.33%   |
| Corsair             | 1         | 1.33%   |
| Apacer              | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 4         | 5.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 5.26%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 3.95%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 2         | 2.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 2.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 2         | 2.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 2.63%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                           | 1         | 1.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                 | 1         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                  | 1         | 1.32%   |
| Unknown RAM Module 1024MB SODIMM DDR                        | 1         | 1.32%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s        | 1         | 1.32%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s        | 1         | 1.32%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s       | 1         | 1.32%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                | 1         | 1.32%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s      | 1         | 1.32%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.32%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.32%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.32%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s       | 1         | 1.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 1.32%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s    | 1         | 1.32%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s       | 1         | 1.32%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.32%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.32%   |
| Neo Forza RAM NMSO480E82-2666E 8GB SODIMM DDR4 2667MT/s     | 1         | 1.32%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s        | 1         | 1.32%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.32%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.32%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s        | 1         | 1.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 1         | 1.32%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s       | 1         | 1.32%   |
| Kingston RAM ASU16D3LS1KBG/4G 4096MB SODIMM DDR3 1333MT/s   | 1         | 1.32%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s      | 1         | 1.32%   |
| Kingston RAM 9905630-025.A00G 8GB SODIMM DDR4 2400MT/s      | 1         | 1.32%   |
| Kingston RAM 9905624-007.A00G 8GB SODIMM DDR4 2133MT/s      | 1         | 1.32%   |
| Kingston RAM 9905469-157.A01LF 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.32%   |
| GOODRAM RAM GR2133S464L15/16G 16GB SODIMM DDR4 2133MT/s     | 1         | 1.32%   |
| G.Skill RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 1.32%   |
| G.Skill RAM F3-1600C11-8GSL 8GB SODIMM DDR3 1600MT/s        | 1         | 1.32%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.32%   |
| ELPIDA RAM EBJ81UG8BBU0-GN-F 8GB SODIMM DDR3 1600MT/s       | 1         | 1.32%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s       | 1         | 1.32%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1067MT/s              | 1         | 1.32%   |
| Crucial RAM CT8G4SFD824A.M16FB 8GB SODIMM DDR4 2133MT/s     | 1         | 1.32%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s     | 1         | 1.32%   |
| Crucial RAM CT204864BF160B.C16 16384MB SODIMM DDR3 1600MT/s | 1         | 1.32%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s  | 1         | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 37        | 63.79%  |
| DDR4    | 18        | 31.03%  |
| DDR2    | 1         | 1.72%   |
| DDR     | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 58        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 32        | 49.23%  |
| 8192  | 24        | 36.92%  |
| 16384 | 4         | 6.15%   |
| 2048  | 4         | 6.15%   |
| 1024  | 1         | 1.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 39.68%  |
| 2667    | 9         | 14.29%  |
| 2400    | 9         | 14.29%  |
| 1333    | 6         | 9.52%   |
| 1334    | 4         | 6.35%   |
| 2133    | 3         | 4.76%   |
| 1067    | 3         | 4.76%   |
| 800     | 2         | 3.17%   |
| Unknown | 2         | 3.17%   |

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
| Chicony Electronics                    | 12        | 25%     |
| Acer                                   | 7         | 14.58%  |
| Suyin                                  | 4         | 8.33%   |
| Sunplus Innovation Technology          | 4         | 8.33%   |
| Realtek Semiconductor                  | 4         | 8.33%   |
| Microdia                               | 4         | 8.33%   |
| Alcor Micro                            | 3         | 6.25%   |
| Silicon Motion                         | 2         | 4.17%   |
| Quanta                                 | 2         | 4.17%   |
| Lite-On Technology                     | 2         | 4.17%   |
| Lenovo                                 | 1         | 2.08%   |
| Importek                               | 1         | 2.08%   |
| IMC Networks                           | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer Integrated Camera                                         | 6         | 12.5%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 2         | 4.17%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 2         | 4.17%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 4.17%   |
| Microdia Integrated Webcam                                     | 2         | 4.17%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 4.17%   |
| Chicony Integrated Camera                                      | 2         | 4.17%   |
| Chicony HD WebCam                                              | 2         | 4.17%   |
| Chicony Chicony USB2.0 Camera                                  | 2         | 4.17%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 2.08%   |
| Suyin HD WebCam                                                | 1         | 2.08%   |
| Sunplus MTD camera                                             | 1         | 2.08%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 2.08%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 2.08%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 2.08%   |
| Realtek Realtek USB2.0 PC Camera                               | 1         | 2.08%   |
| Realtek Lenovo EasyCamera                                      | 1         | 2.08%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 2.08%   |
| Realtek Front Camera                                           | 1         | 2.08%   |
| Quanta VGA WebCam                                              | 1         | 2.08%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 2.08%   |
| Lite-On Integrated Camera                                      | 1         | 2.08%   |
| Lite-On HP TrueVision HD Camera                                | 1         | 2.08%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.08%   |
| Importek TOSHIBA Web Camera - HD                               | 1         | 2.08%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 2.08%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 2.08%   |
| Chicony Thinkpad T430 camera                                   | 1         | 2.08%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 2.08%   |
| Chicony Lenovo EasyCamera                                      | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.08%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 2.08%   |
| Alcor Micro HP WebCam-101                                      | 1         | 2.08%   |
| Alcor Micro Acer Integrated Webcam                             | 1         | 2.08%   |
| Acer ThinkPad Integrated Camera                                | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 4         | 40%     |
| Upek               | 2         | 20%     |
| Synaptics          | 2         | 20%     |
| STMicroelectronics | 1         | 10%     |
| Focal-systems.Corp | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors Synaptics WBDI                        | 1         | 10%     |
| Upek TCS5B Fingerprint sensor                          | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics  WBDI                                        | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 10%     |
| Focal-systems.Corp FocalTech Fingerprint reader        | 1         | 10%     |

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
| 2     | 20        | 33.33%  |
| 3     | 17        | 28.33%  |
| 4     | 9         | 15%     |
| 1     | 9         | 15%     |
| 0     | 4         | 6.67%   |
| 5     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 43        | 31.85%  |
| Bluetooth                | 34        | 25.19%  |
| Card reader              | 19        | 14.07%  |
| Net/wireless             | 17        | 12.59%  |
| Fingerprint reader       | 10        | 7.41%   |
| Storage                  | 4         | 2.96%   |
| Network                  | 4         | 2.96%   |
| Firewire controller      | 4         | 2.96%   |

