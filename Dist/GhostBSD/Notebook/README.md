GhostBSD - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for GhostBSD.

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

Total: 145

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| TUXEDO        | Aura 15 Gen1                | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d2334d7be3](https://bsd-hardware.info/?probe=d2334d7be3) | May 14, 2022 |
| Acer          | Aspire A715-42G             | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Dell          | Latitude 7490               | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell          | Precision 7730              | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| ASUSTek       | X550CC                      | [ece6d63cfb](https://bsd-hardware.info/?probe=ece6d63cfb) | Apr 25, 2022 |
| Dell          | Latitude E5450              | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Notebook      | N13xWU                      | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Dell          | Latitude E6500              | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [bc2860431e](https://bsd-hardware.info/?probe=bc2860431e) | Feb 17, 2022 |
| Jumper        | EZbook                      | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| Lenovo        | G500s 20245                 | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | Vostro 3550                 | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | [5b9c617dc8](https://bsd-hardware.info/?probe=5b9c617dc8) | Jan 22, 2022 |
| Apple         | MacBookPro11,4              | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Dell          | Latitude E6540              | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Jumper        | EZbook                      | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell          | Latitude 5510               | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell          | Inspiron N5110              | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Dell          | Latitude E5450              | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| ASUSTek       | X202E                       | [7f4e6f4541](https://bsd-hardware.info/?probe=7f4e6f4541) | Dec 05, 2021 |
| Fujitsu       | LIFEBOOK A555               | [c501c5c75e](https://bsd-hardware.info/?probe=c501c5c75e) | Dec 04, 2021 |
| Samsung       | 530XBB                      | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Alienware     | m15 R4                      | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Sony          | SVP13225SCBI                | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Dell          | Latitude 5510               | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer          | TravelMate B117-M           | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Toshiba       | Satellite C855-1U4          | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Dell          | Latitude D630               | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| Samsung       | 550P5C/550P7C               | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| HP            | Pavilion g6                 | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| MSI           | Modern 14 A10M              | [84838cd532](https://bsd-hardware.info/?probe=84838cd532) | Oct 07, 2021 |
| MSI           | Modern 14 A10M              | [db33045561](https://bsd-hardware.info/?probe=db33045561) | Oct 07, 2021 |
| Acer          | Aspire A315-56              | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| MSI           | Modern 14 A10M              | [277d8118da](https://bsd-hardware.info/?probe=277d8118da) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| MSI           | Modern 14 A10M              | [103ccaf452](https://bsd-hardware.info/?probe=103ccaf452) | Sep 25, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| HUAWEI        | HLY-WX9XX                   | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| HP            | EliteBook 8570p             | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [ecd69774c0](https://bsd-hardware.info/?probe=ecd69774c0) | Sep 06, 2021 |
| System76      | Kudu                        | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
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
| Sony          | VPCCB17FG                   | [d8a67b4a30](https://bsd-hardware.info/?probe=d8a67b4a30) | Dec 06, 2020 |
| Sony          | VPCCB17FG                   | [7fc23a57bb](https://bsd-hardware.info/?probe=7fc23a57bb) | Nov 25, 2020 |
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
| ASUSTek       | G750JS                      | [8214170523](https://bsd-hardware.info/?probe=8214170523) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | [60b904f003](https://bsd-hardware.info/?probe=60b904f003) | Aug 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |
| Dell          | Precision M4700             | [a7761ee829](https://bsd-hardware.info/?probe=a7761ee829) | May 25, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| GhostBSD 20.04.02    | 58        | 54.72%  |
| GhostBSD 21.08.27    | 28        | 26.42%  |
| GhostBSD 22.01.12    | 12        | 11.32%  |
| GhostBSD 22.05.13    | 1         | 0.94%   |
| GhostBSD 22.04.30    | 1         | 0.94%   |
| GhostBSD 22.04.22    | 1         | 0.94%   |
| GhostBSD 22.04.06    | 1         | 0.94%   |
| GhostBSD 21.12.29    | 1         | 0.94%   |
| GhostBSD 20.07.14    | 1         | 0.94%   |
| GhostBSD 20.03.01    | 1         | 0.94%   |
| GhostBSD 12.2-STABLE | 1         | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 104       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 104       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 82        | 78.1%   |
| XFCE         | 15        | 14.29%  |
| KDE5         | 3         | 2.86%   |
| Cinnamon     | 2         | 1.9%    |
| helloDesktop | 1         | 0.95%   |
| GNOME        | 1         | 0.95%   |
| Console      | 1         | 0.95%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 102       | 98.08%  |
| Wayland | 1         | 0.96%   |
| Console | 1         | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 102       | 98.08%  |
| SDDM    | 1         | 0.96%   |
| Console | 1         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 43        | 39.45%  |
| C       | 32        | 29.36%  |
| Unknown | 16        | 14.68%  |
| de_DE   | 5         | 4.59%   |
| pl_PL   | 2         | 1.83%   |
| it_IT   | 2         | 1.83%   |
| en_GB   | 2         | 1.83%   |
| zh_CN   | 1         | 0.92%   |
| sk_SK   | 1         | 0.92%   |
| ru_RU   | 1         | 0.92%   |
| pt_BR   | 1         | 0.92%   |
| es_ES   | 1         | 0.92%   |
| en_NZ   | 1         | 0.92%   |
| el_GR   | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 79        | 75.96%  |
| BIOS | 25        | 24.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 97        | 91.51%  |
| Ufs  | 9         | 8.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 102       | 98.08%  |
| MBR  | 2         | 1.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 26.92%  |
| Dell                | 22        | 21.15%  |
| Acer                | 9         | 8.65%   |
| Hewlett-Packard     | 8         | 7.69%   |
| ASUSTek Computer    | 7         | 6.73%   |
| Sony                | 4         | 3.85%   |
| Notebook            | 4         | 3.85%   |
| MSI                 | 4         | 3.85%   |
| Apple               | 4         | 3.85%   |
| Toshiba             | 2         | 1.92%   |
| System76            | 2         | 1.92%   |
| Samsung Electronics | 2         | 1.92%   |
| Fujitsu             | 2         | 1.92%   |
| TUXEDO              | 1         | 0.96%   |
| Panasonic           | 1         | 0.96%   |
| Jumper              | 1         | 0.96%   |
| HUAWEI              | 1         | 0.96%   |
| GPU Company         | 1         | 0.96%   |
| Alienware           | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 2.88%   |
| MSI Modern 14 A10M                       | 2         | 1.92%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 1.92%   |
| Dell Latitude E6420                      | 2         | 1.92%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.96%   |
| Toshiba Satellite C855-1U4               | 1         | 0.96%   |
| Toshiba Satellite C855                   | 1         | 0.96%   |
| System76 Lemur Pro                       | 1         | 0.96%   |
| System76 Kudu                            | 1         | 0.96%   |
| Sony VPCCB17FG                           | 1         | 0.96%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.96%   |
| Sony SVP1322M1EBI                        | 1         | 0.96%   |
| Sony SVP13225SCBI                        | 1         | 0.96%   |
| Samsung 550P5C/550P7C                    | 1         | 0.96%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.96%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.96%   |
| Notebook N8xEJEK                         | 1         | 0.96%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.96%   |
| Notebook N7x0WU                          | 1         | 0.96%   |
| Notebook N13xWU                          | 1         | 0.96%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.96%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.96%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.96%   |
| Lenovo Yoga 2 13 20344                   | 1         | 0.96%   |
| Lenovo ThinkPad X250 20CM003WMS          | 1         | 0.96%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 0.96%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.96%   |
| Lenovo ThinkPad X220 42872VU             | 1         | 0.96%   |
| Lenovo ThinkPad X201 32492EU             | 1         | 0.96%   |
| Lenovo ThinkPad T590 20N40016CD          | 1         | 0.96%   |
| Lenovo ThinkPad T530 239242U             | 1         | 0.96%   |
| Lenovo ThinkPad T520 4243E51             | 1         | 0.96%   |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 0.96%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01    | 1         | 0.96%   |
| Lenovo ThinkPad T470 20HD000MUK          | 1         | 0.96%   |
| Lenovo ThinkPad T450 20BV0064US          | 1         | 0.96%   |
| Lenovo ThinkPad T450 20BUS0VH08          | 1         | 0.96%   |
| Lenovo ThinkPad T440 20B7S1860W          | 1         | 0.96%   |
| Lenovo ThinkPad T430s 23539JM            | 1         | 0.96%   |
| Lenovo ThinkPad T430 2344C4U             | 1         | 0.96%   |
| Lenovo ThinkPad T400 6474E18             | 1         | 0.96%   |
| Lenovo ThinkPad L512 44444XG             | 1         | 0.96%   |
| Lenovo ThinkPad E14 Gen 2 20TA004FUS     | 1         | 0.96%   |
| Lenovo Legion Y7000P 81LD                | 1         | 0.96%   |
| Lenovo IdeaPad S145-15API 81UT           | 1         | 0.96%   |
| Lenovo IdeaPad 520-15IKB 81BF            | 1         | 0.96%   |
| Lenovo G500s 20245                       | 1         | 0.96%   |
| Lenovo Flex 2-15 20405                   | 1         | 0.96%   |
| Jumper EZbook                            | 1         | 0.96%   |
| HUAWEI HLY-WX9XX                         | 1         | 0.96%   |
| HP Pavilion g6                           | 1         | 0.96%   |
| HP OMEN by HP Laptop                     | 1         | 0.96%   |
| HP Laptop 15-dw2xxx                      | 1         | 0.96%   |
| HP Laptop 15-db0xxx                      | 1         | 0.96%   |
| HP Laptop 15-da0xxx                      | 1         | 0.96%   |
| HP Laptop 14-dk0xxx                      | 1         | 0.96%   |
| HP EliteBook Folio 1040 G3               | 1         | 0.96%   |
| HP 255 G7 Notebook PC                    | 1         | 0.96%   |
| GPU Company GWTN156-5                    | 1         | 0.96%   |
| Fujitsu LIFEBOOK A555                    | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 21        | 20.19%  |
| Dell Latitude           | 15        | 14.42%  |
| Acer Aspire             | 7         | 6.73%   |
| Dell Inspiron           | 5         | 4.81%   |
| HP Laptop               | 4         | 3.85%   |
| Toshiba Satellite       | 2         | 1.92%   |
| MSI Modern              | 2         | 1.92%   |
| Lenovo Yoga             | 2         | 1.92%   |
| Lenovo IdeaPad          | 2         | 1.92%   |
| Dell Precision          | 2         | 1.92%   |
| TUXEDO InfinityBook13V3 | 1         | 0.96%   |
| System76 Lemur          | 1         | 0.96%   |
| System76 Kudu           | 1         | 0.96%   |
| Sony VPCCB17FG          | 1         | 0.96%   |
| Sony VGN-SZ3VWP         | 1         | 0.96%   |
| Sony SVP1322M1EBI       | 1         | 0.96%   |
| Sony SVP13225SCBI       | 1         | 0.96%   |
| Samsung 550P5C          | 1         | 0.96%   |
| Samsung 3570R           | 1         | 0.96%   |
| Panasonic CF-19AHNC8FN  | 1         | 0.96%   |
| Notebook N8xEJEK        | 1         | 0.96%   |
| Notebook N85            | 1         | 0.96%   |
| Notebook N7x0WU         | 1         | 0.96%   |
| Notebook N13xWU         | 1         | 0.96%   |
| MSI GF63                | 1         | 0.96%   |
| MSI GE75                | 1         | 0.96%   |
| Lenovo Legion           | 1         | 0.96%   |
| Lenovo G500s            | 1         | 0.96%   |
| Lenovo Flex             | 1         | 0.96%   |
| Jumper EZbook           | 1         | 0.96%   |
| HUAWEI HLY-WX9XX        | 1         | 0.96%   |
| HP Pavilion             | 1         | 0.96%   |
| HP OMEN                 | 1         | 0.96%   |
| HP EliteBook            | 1         | 0.96%   |
| HP 255                  | 1         | 0.96%   |
| GPU Company GWTN156-5   | 1         | 0.96%   |
| Fujitsu LIFEBOOK        | 1         | 0.96%   |
| Fujitsu CELSIUS         | 1         | 0.96%   |
| ASUS X550LC             | 1         | 0.96%   |
| ASUS X550CC             | 1         | 0.96%   |
| ASUS X202E              | 1         | 0.96%   |
| ASUS VivoBook           | 1         | 0.96%   |
| ASUS TUF                | 1         | 0.96%   |
| ASUS K53SD              | 1         | 0.96%   |
| ASUS G750JS             | 1         | 0.96%   |
| Apple MacBookPro5       | 1         | 0.96%   |
| Apple MacBookPro11      | 1         | 0.96%   |
| Apple MacBook6          | 1         | 0.96%   |
| Apple MacBook5          | 1         | 0.96%   |
| Alienware m15           | 1         | 0.96%   |
| Acer TravelMate         | 1         | 0.96%   |
| Acer Extensa            | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 19        | 18.27%  |
| 2013 | 14        | 13.46%  |
| 2014 | 10        | 9.62%   |
| 2018 | 8         | 7.69%   |
| 2011 | 8         | 7.69%   |
| 2015 | 7         | 6.73%   |
| 2021 | 6         | 5.77%   |
| 2012 | 6         | 5.77%   |
| 2019 | 5         | 4.81%   |
| 2017 | 5         | 4.81%   |
| 2009 | 5         | 4.81%   |
| 2010 | 4         | 3.85%   |
| 2016 | 3         | 2.88%   |
| 2008 | 2         | 1.92%   |
| 2022 | 1         | 0.96%   |
| 2007 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 99.04%  |
| Yes  | 1         | 0.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 58        | 55.77%  |
| 16.01-24.0 | 23        | 22.12%  |
| 4.01-8.0   | 18        | 17.31%  |
| 32.01-64.0 | 2         | 1.92%   |
| 24.01-32.0 | 2         | 1.92%   |
| 2.01-3.0   | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 53        | 50%     |
| 0.51-1.0   | 41        | 38.68%  |
| 2.01-3.0   | 6         | 5.66%   |
| 1.01-2.0   | 4         | 3.77%   |
| 4.01-8.0   | 1         | 0.94%   |
| 24.01-32.0 | 1         | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 73.58%  |
| 2      | 21        | 19.81%  |
| 0      | 7         | 6.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 60.58%  |
| Yes       | 41        | 39.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 86.54%  |
| No        | 14        | 13.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 74.04%  |
| No        | 27        | 25.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 21        | 20.19%  |
| Germany      | 15        | 14.42%  |
| France       | 9         | 8.65%   |
| Poland       | 6         | 5.77%   |
| UK           | 4         | 3.85%   |
| Spain        | 4         | 3.85%   |
| Russia       | 4         | 3.85%   |
| Italy        | 4         | 3.85%   |
| New Zealand  | 3         | 2.88%   |
| Switzerland  | 2         | 1.92%   |
| Sweden       | 2         | 1.92%   |
| Portugal     | 2         | 1.92%   |
| Philippines  | 2         | 1.92%   |
| Japan        | 2         | 1.92%   |
| India        | 2         | 1.92%   |
| Hong Kong    | 2         | 1.92%   |
| Finland      | 2         | 1.92%   |
| China        | 2         | 1.92%   |
| Belgium      | 2         | 1.92%   |
| Ukraine      | 1         | 0.96%   |
| Uganda       | 1         | 0.96%   |
| South Africa | 1         | 0.96%   |
| Slovakia     | 1         | 0.96%   |
| Serbia       | 1         | 0.96%   |
| Norway       | 1         | 0.96%   |
| Namibia      | 1         | 0.96%   |
| Indonesia    | 1         | 0.96%   |
| Hungary      | 1         | 0.96%   |
| Greece       | 1         | 0.96%   |
| Egypt        | 1         | 0.96%   |
| Canada       | 1         | 0.96%   |
| Brazil       | 1         | 0.96%   |
| Argentina    | 1         | 0.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Bedburg            | 6         | 5.61%   |
| Franconville       | 3         | 2.8%    |
| Chrusty            | 3         | 2.8%    |
| Bonn               | 3         | 2.8%    |
| Yokohama           | 2         | 1.87%   |
| Whittier           | 2         | 1.87%   |
| Wezeren            | 2         | 1.87%   |
| Stiring-Wendel     | 2         | 1.87%   |
| Rome               | 2         | 1.87%   |
| Paris              | 2         | 1.87%   |
| London             | 2         | 1.87%   |
| Giessen            | 2         | 1.87%   |
| Clemmons           | 2         | 1.87%   |
| Asnieres-sur-Seine | 2         | 1.87%   |
| Zurich             | 1         | 0.93%   |
| Yaroslavl          | 1         | 0.93%   |
| Witbank            | 1         | 0.93%   |
| Wenatchee          | 1         | 0.93%   |
| Valencia           | 1         | 0.93%   |
| Toronto            | 1         | 0.93%   |
| Taita              | 1         | 0.93%   |
| Staffanstorp       | 1         | 0.93%   |
| St Petersburg      | 1         | 0.93%   |
| Sollentuna         | 1         | 0.93%   |
| Santo Tomas        | 1         | 0.93%   |
| Salem              | 1         | 0.93%   |
| Rochester          | 1         | 0.93%   |
| Richmond           | 1         | 0.93%   |
| Resistencia        | 1         | 0.93%   |
| Portland           | 1         | 0.93%   |
| Peoria             | 1         | 0.93%   |
| Oslo               | 1         | 0.93%   |
| Oshakati           | 1         | 0.93%   |
| New Delhi          | 1         | 0.93%   |
| Nanjing            | 1         | 0.93%   |
| Mystic             | 1         | 0.93%   |
| Murfreesboro       | 1         | 0.93%   |
| Moscow             | 1         | 0.93%   |
| Milan              | 1         | 0.93%   |
| Marysville         | 1         | 0.93%   |
| Makati City        | 1         | 0.93%   |
| Madrid             | 1         | 0.93%   |
| Lutz               | 1         | 0.93%   |
| Lisbon             | 1         | 0.93%   |
| Lingen             | 1         | 0.93%   |
| Lenzburg           | 1         | 0.93%   |
| Kyiv               | 1         | 0.93%   |
| Krasnoyarsk        | 1         | 0.93%   |
| Knoxville          | 1         | 0.93%   |
| Kampala            | 1         | 0.93%   |
| JyvГ¤skylГ¤    | 1         | 0.93%   |
| JarosÅ‚aw       | 1         | 0.93%   |
| Jakarta            | 1         | 0.93%   |
| Hyderabad          | 1         | 0.93%   |
| Huddersfield       | 1         | 0.93%   |
| Hamilton           | 1         | 0.93%   |
| Hamburg            | 1         | 0.93%   |
| Grajewo            | 1         | 0.93%   |
| Giza               | 1         | 0.93%   |
| Fiumicino          | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 42     | 27.5%   |
| WDC                 | 14        | 14     | 11.67%  |
| Seagate             | 12        | 16     | 10%     |
| Kingston            | 12        | 12     | 10%     |
| Crucial             | 8         | 9      | 6.67%   |
| Toshiba             | 6         | 8      | 5%      |
| SanDisk             | 6         | 6      | 5%      |
| SK Hynix            | 3         | 3      | 2.5%    |
| Hitachi             | 3         | 3      | 2.5%    |
| PNY                 | 2         | 2      | 1.67%   |
| Phison              | 2         | 3      | 1.67%   |
| Micron Technology   | 2         | 2      | 1.67%   |
| KingSpec            | 2         | 2      | 1.67%   |
| Intel               | 2         | 2      | 1.67%   |
| HGST                | 2         | 2      | 1.67%   |
| GOODRAM             | 2         | 2      | 1.67%   |
| Fujitsu             | 2         | 2      | 1.67%   |
| PLEXTOR             | 1         | 1      | 0.83%   |
| Patriot             | 1         | 1      | 0.83%   |
| Netac               | 1         | 1      | 0.83%   |
| LITEONIT            | 1         | 1      | 0.83%   |
| Gigabyte Technology | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| A-DATA Technology   | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 3         | 2.46%   |
| Samsung SSD 850 EVO 250GB            | 3         | 2.46%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.64%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.64%   |
| Samsung PM981 NVMe 256GB             | 2         | 1.64%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 2         | 1.64%   |
| Kingston RBUSNS8154P3512GJ 512GB     | 2         | 1.64%   |
| KingSpec Q-720 720GB                 | 2         | 1.64%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.82%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.82%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.82%   |
| WDC WDS100T1B0A-00H9H0 1TB           | 1         | 0.82%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.82%   |
| WDC WD7500BPKX-80HPJT0 752GB         | 1         | 0.82%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.82%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.82%   |
| WDC WD5000BPVT-00HXZT3 500GB         | 1         | 0.82%   |
| WDC WD3200LPVX-75V0TT0 320GB         | 1         | 0.82%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.82%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.82%   |
| WDC WD10JMVW-11AJGS1 1TB             | 1         | 0.82%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.82%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 0.82%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.82%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.82%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.82%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 1         | 0.82%   |
| Toshiba KBG30ZMV512G 512GB           | 1         | 0.82%   |
| SK Hynix SC311 SATA 512GB            | 1         | 0.82%   |
| SK Hynix SC311 SATA 256GB            | 1         | 0.82%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.82%   |
| Seagate ST9250827AS 250GB            | 1         | 0.82%   |
| Seagate ST9250410AS 250GB            | 1         | 0.82%   |
| Seagate ST9160411ASG 160GB           | 1         | 0.82%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 0.82%   |
| Seagate ST500LM030-2E717D 500GB      | 1         | 0.82%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.82%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 0.82%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.82%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 0.82%   |
| SanDisk SSD U110 16GB                | 1         | 0.82%   |
| SanDisk SSD PLUS 240GB               | 1         | 0.82%   |
| SanDisk SSD PLUS 1000GB              | 1         | 0.82%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 0.82%   |
| SanDisk SDSSDA240G 240GB             | 1         | 0.82%   |
| SanDisk SD8SNAT-128G-1006 128GB      | 1         | 0.82%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 0.82%   |
| Samsung SSD 970 EVO 250GB            | 1         | 0.82%   |
| Samsung SSD 950 PRO 512GB            | 1         | 0.82%   |
| Samsung SSD 860 PRO 512GB            | 1         | 0.82%   |
| Samsung SSD 860 EVO M.2 500GB        | 1         | 0.82%   |
| Samsung SSD 860 EVO M.2 250GB        | 1         | 0.82%   |
| Samsung SSD 860 EVO M.2 1TB          | 1         | 0.82%   |
| Samsung SSD 860 EVO 1TB              | 1         | 0.82%   |
| Samsung SSD 850 PRO 1TB              | 1         | 0.82%   |
| Samsung SSD 840 PRO Series 256GB     | 1         | 0.82%   |
| Samsung SSD 840 EVO 500GB            | 1         | 0.82%   |
| Samsung PM9A1 NVMe 512GB             | 1         | 0.82%   |
| Samsung MZVLQ512HALU-00000 512GB     | 1         | 0.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 16     | 37.5%   |
| WDC                 | 9         | 9      | 28.13%  |
| Toshiba             | 3         | 3      | 9.38%   |
| Hitachi             | 3         | 3      | 9.38%   |
| HGST                | 2         | 2      | 6.25%   |
| Fujitsu             | 2         | 2      | 6.25%   |
| Samsung Electronics | 1         | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 29     | 31.82%  |
| Kingston            | 9         | 9      | 13.64%  |
| Crucial             | 7         | 8      | 10.61%  |
| SanDisk             | 6         | 6      | 9.09%   |
| WDC                 | 4         | 4      | 6.06%   |
| SK Hynix            | 2         | 2      | 3.03%   |
| PNY                 | 2         | 2      | 3.03%   |
| Micron Technology   | 2         | 2      | 3.03%   |
| KingSpec            | 2         | 2      | 3.03%   |
| GOODRAM             | 2         | 2      | 3.03%   |
| Toshiba             | 1         | 2      | 1.52%   |
| PLEXTOR             | 1         | 1      | 1.52%   |
| Phison              | 1         | 1      | 1.52%   |
| Patriot             | 1         | 1      | 1.52%   |
| Netac               | 1         | 1      | 1.52%   |
| LITEONIT            | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| Apple               | 1         | 1      | 1.52%   |
| A-DATA Technology   | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 59        | 76     | 53.15%  |
| HDD  | 30        | 36     | 27.03%  |
| NVMe | 22        | 25     | 19.82%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 112    | 79.44%  |
| NVMe | 22        | 25     | 20.56%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 72     | 68.89%  |
| 0.51-1.0   | 24        | 35     | 26.67%  |
| 1.01-2.0   | 4         | 5      | 4.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 34        | 31.48%  |
| 101-250    | 27        | 25%     |
| 251-500    | 16        | 14.81%  |
| 501-1000   | 12        | 11.11%  |
| 51-100     | 9         | 8.33%   |
| Unknown    | 8         | 7.41%   |
| 1001-2000  | 2         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 95        | 87.16%  |
| Unknown | 8         | 7.34%   |
| 21-50   | 5         | 4.59%   |
| 101-250 | 1         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 8.33%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 8.33%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 8.33%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 8.33%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1      | 8.33%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 8.33%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 8.33%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 8.33%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 25%     |
| WDC                 | 2         | 2      | 16.67%  |
| Samsung Electronics | 2         | 2      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 66.67%  |
| SSD  | 4         | 4      | 33.33%  |

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
| Works   | 90        | 125    | 88.24%  |
| Malfunc | 12        | 12     | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 82        | 70.09%  |
| Samsung Electronics         | 12        | 10.26%  |
| AMD                         | 10        | 8.55%   |
| Nvidia                      | 3         | 2.56%   |
| Kingston Technology Company | 3         | 2.56%   |
| Toshiba                     | 2         | 1.71%   |
| Phison Electronics          | 2         | 1.71%   |
| SK Hynix                    | 1         | 0.85%   |
| Sandisk                     | 1         | 0.85%   |
| Micron/Crucial Technology   | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 11.67%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 9.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 7.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 7.5%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 5.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 5%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 3.33%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 2.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.5%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.67%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.67%   |
| Unknown                                                                          | 2         | 1.67%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.83%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.83%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.83%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.83%   |
| Samsung SM951 AHCI                                                               | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.83%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.83%   |
| Intel SSD 660P Series                                                            | 1         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.83%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 85        | 71.43%  |
| NVMe | 22        | 18.49%  |
| RAID | 9         | 7.56%   |
| IDE  | 3         | 2.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 92        | 88.46%  |
| AMD    | 12        | 11.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz            | 5         | 4.81%   |
| Intel Core i7-3520M CPU @ 2.90GHz            | 3         | 2.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz            | 3         | 2.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 3         | 2.88%   |
| Intel Core i9-10980HK CPU @ 2.40GHz          | 2         | 1.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 2         | 1.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.92%   |
| Intel Core i7-2620M CPU @ 2.70GHz            | 2         | 1.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.92%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 2         | 1.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 2         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 2         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 2         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GH             | 2         | 1.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz           | 2         | 1.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 2         | 1.92%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz         | 2         | 1.92%   |
| Intel Core 2 Duo                             | 2         | 1.92%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 2         | 1.92%   |
| Intel Pentium 3558U @ 1.70GHz                | 1         | 0.96%   |
| Intel Genuine CPU                            | 1         | 0.96%   |
| Intel Core i7-8850H CPU @ 2.60GHz            | 1         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 0.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.96%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 1         | 0.96%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz           | 1         | 0.96%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i7-4500U CPU @ 1.80GHz            | 1         | 0.96%   |
| Intel Core i7-3740QM CPU @ 2.70GHz           | 1         | 0.96%   |
| Intel Core i7-3720QM CPU @ 2.60GHz           | 1         | 0.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 1         | 0.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 1         | 0.96%   |
| Intel Core i7 CPU M 620 @ 2.67GH             | 1         | 0.96%   |
| Intel Core i5-8400H CPU @ 2.50GHz            | 1         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz            | 1         | 0.96%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz           | 1         | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 0.96%   |
| Intel Core i5-4310U CPU @ 2.00GHz            | 1         | 0.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.96%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 1         | 0.96%   |
| Intel Core i5-3337U CPU @ 1.80GHz            | 1         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 1         | 0.96%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 0.96%   |
| Intel Core i5-2430M CPU @ 2.40GH             | 1         | 0.96%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.96%   |
| Intel Core i5-10310U CPU @ 1.70GHz           | 1         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 0.96%   |
| Intel Core i5 CPU M 540 @ 2.53GHz            | 1         | 0.96%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 0.96%   |
| Intel Core i3-4030U CPU @ 1.90GHz            | 1         | 0.96%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 0.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 0.96%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 1         | 0.96%   |
| Intel Core i3-3110M CPU @ 2.40GHz            | 1         | 0.96%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 1         | 0.96%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz         | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 42        | 40.38%  |
| Intel Core i7    | 26        | 25%     |
| Intel Core 2 Duo | 8         | 7.69%   |
| Intel Core i3    | 7         | 6.73%   |
| AMD Ryzen 5      | 4         | 3.85%   |
| Intel Celeron    | 3         | 2.88%   |
| Other            | 2         | 1.92%   |
| Intel Core i9    | 2         | 1.92%   |
| AMD Ryzen 7      | 2         | 1.92%   |
| AMD A6           | 2         | 1.92%   |
| AMD A4           | 2         | 1.92%   |
| Intel Pentium    | 1         | 0.96%   |
| Intel Genuine    | 1         | 0.96%   |
| Intel Core 2     | 1         | 0.96%   |
| AMD Ryzen 3      | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 59        | 56.73%  |
| 4       | 27        | 25.96%  |
| 8       | 6         | 5.77%   |
| Unknown | 6         | 5.77%   |
| 6       | 4         | 3.85%   |
| 16      | 1         | 0.96%   |
| 12      | 1         | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 97.12%  |
| 2      | 3         | 2.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 75%     |
| 1       | 20        | 19.23%  |
| Unknown | 6         | 5.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 19        | 18.27%  |
| IvyBridge   | 15        | 14.42%  |
| Haswell     | 14        | 13.46%  |
| SandyBridge | 11        | 10.58%  |
| Penryn      | 7         | 6.73%   |
| Broadwell   | 7         | 6.73%   |
| Skylake     | 6         | 5.77%   |
| Zen+        | 5         | 4.81%   |
| Westmere    | 3         | 2.88%   |
| CometLake   | 3         | 2.88%   |
| IceLake     | 2         | 1.92%   |
| Excavator   | 2         | 1.92%   |
| Core        | 2         | 1.92%   |
| Zen 3       | 1         | 0.96%   |
| TigerLake   | 1         | 0.96%   |
| Silvermont  | 1         | 0.96%   |
| Puma        | 1         | 0.96%   |
| K10 Llano   | 1         | 0.96%   |
| K10         | 1         | 0.96%   |
| Goldmont    | 1         | 0.96%   |
| Unknown     | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 84        | 64.12%  |
| Nvidia | 29        | 22.14%  |
| AMD    | 18        | 13.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 9.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 8.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 8.21%   |
| Intel HD Graphics 5500                                                                   | 7         | 5.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 3.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.99%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.99%   |
| Intel HD Graphics 620                                                                    | 4         | 2.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 2.24%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 2.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.24%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 1.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.49%   |
| Intel HD Graphics 530                                                                    | 2         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.75%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.75%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.75%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.75%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 0.75%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.75%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.75%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.75%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.75%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.75%   |
| Nvidia GK104M [GeForce GTX 870M]                                                         | 1         | 0.75%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.75%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.75%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.75%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.75%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 1         | 0.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.75%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.75%   |
| Intel HD Graphics 630                                                                    | 1         | 0.75%   |
| Intel HD Graphics 500                                                                    | 1         | 0.75%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.75%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.75%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                                  | 1         | 0.75%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.75%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.75%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 0.75%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 0.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 0.75%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 0.75%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 0.75%   |
| AMD Lucienne                                                                             | 1         | 0.75%   |
| AMD Jet XT [Radeon R5 M240]                                                              | 1         | 0.75%   |
| AMD Cezanne                                                                              | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 51.92%  |
| Intel + Nvidia | 23        | 22.12%  |
| 1 x AMD        | 13        | 12.5%   |
| 1 x Nvidia     | 6         | 5.77%   |
| 2 x Intel      | 4         | 3.85%   |
| Intel + AMD    | 3         | 2.88%   |
| 2 x AMD        | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 98        | 94.23%  |
| Proprietary | 6         | 5.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 91.35%  |
| 1.01-2.0   | 3         | 2.88%   |
| 0.01-0.5   | 3         | 2.88%   |
| 0.51-1.0   | 2         | 1.92%   |
| 3.01-4.0   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 21        | 22.34%  |
| Chimei Innolux      | 19        | 20.21%  |
| AU Optronics        | 19        | 20.21%  |
| Samsung Electronics | 9         | 9.57%   |
| BOE                 | 5         | 5.32%   |
| Lenovo              | 4         | 4.26%   |
| Philips             | 3         | 3.19%   |
| Panasonic           | 2         | 2.13%   |
| Dell                | 2         | 2.13%   |
| ___                 | 1         | 1.06%   |
| PANDA               | 1         | 1.06%   |
| InfoVision          | 1         | 1.06%   |
| Iiyama              | 1         | 1.06%   |
| IBM                 | 1         | 1.06%   |
| Hewlett-Packard     | 1         | 1.06%   |
| Fujitsu Siemens     | 1         | 1.06%   |
| CSO                 | 1         | 1.06%   |
| BenQ                | 1         | 1.06%   |
| Apple               | 1         | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch             | 2         | 2.11%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 2         | 2.11%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch          | 2         | 2.11%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 2         | 2.11%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 2         | 2.11%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 2         | 2.11%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 2         | 2.11%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 2.11%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch      | 2         | 2.11%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch        | 2         | 2.11%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 1.05%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch | 1         | 1.05%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch | 1         | 1.05%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch            | 1         | 1.05%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD0558 1920x1080 310x170mm 13.9-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD04D5 1920x1080 340x190mm 15.3-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch         | 1         | 1.05%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch          | 1         | 1.05%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 1         | 1.05%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 1         | 1.05%   |
| Lenovo LCD Monitor LEN4031 1280x800 290x180mm 13.4-inch              | 1         | 1.05%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 1         | 1.05%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.05%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 1.05%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                | 1         | 1.05%   |
| Hewlett-Packard 22w HPN342E 1920x1080 480x270mm 21.7-inch            | 1         | 1.05%   |
| Fujitsu Siemens P27T-6 IPS FUS07EF 2560x1440 600x340mm 27.2-inch     | 1         | 1.05%   |
| Dell U3818DW DELA0F0 3840x1600 880x370mm 37.6-inch                   | 1         | 1.05%   |
| Dell U2312HM DEL4073 1920x1080 510x290mm 23.1-inch                   | 1         | 1.05%   |
| CSO LCD Monitor CSO1501 3840x2160 340x190mm 15.3-inch                | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 380x210mm 17.1-inch     | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch      | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch     | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch     | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch      | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 310x170mm 13.9-inch     | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 310x170mm 13.9-inch      | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 310x170mm 13.9-inch      | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1372 1920x1080 290x170mm 13.2-inch     | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch     | 1         | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 36        | 39.13%  |
| 1920x1080 (FHD)    | 34        | 36.96%  |
| 1600x900 (HD+)     | 8         | 8.7%    |
| 3840x2160 (4K)     | 2         | 2.17%   |
| 2880x1620          | 2         | 2.17%   |
| 2560x1440 (QHD)    | 2         | 2.17%   |
| 1680x1050 (WSXGA+) | 2         | 2.17%   |
| 1280x800 (WXGA)    | 2         | 2.17%   |
| 3840x1600          | 1         | 1.09%   |
| 2880x1800          | 1         | 1.09%   |
| 1440x900 (WXGA+)   | 1         | 1.09%   |
| 1280x1024 (SXGA)   | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 44        | 46.32%  |
| 13      | 21        | 22.11%  |
| 17      | 7         | 7.37%   |
| 12      | 6         | 6.32%   |
| 24      | 3         | 3.16%   |
| 14      | 3         | 3.16%   |
| 23      | 2         | 2.11%   |
| 11      | 2         | 2.11%   |
| 39      | 1         | 1.05%   |
| 37      | 1         | 1.05%   |
| 27      | 1         | 1.05%   |
| 22      | 1         | 1.05%   |
| 21      | 1         | 1.05%   |
| 16      | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 67.02%  |
| 201-300     | 13        | 13.83%  |
| 351-400     | 7         | 7.45%   |
| 501-600     | 6         | 6.38%   |
| 801-900     | 2         | 2.13%   |
| 401-500     | 2         | 2.13%   |
| Unknown     | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 77        | 88.51%  |
| 16/10 | 8         | 9.2%    |
| 5/4   | 1         | 1.15%   |
| 21/9  | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 36        | 37.89%  |
| 81-90          | 22        | 23.16%  |
| 101-110        | 8         | 8.42%   |
| 201-250        | 7         | 7.37%   |
| 61-70          | 6         | 6.32%   |
| 121-130        | 6         | 6.32%   |
| 71-80          | 2         | 2.11%   |
| 51-60          | 2         | 2.11%   |
| 501-1000       | 2         | 2.11%   |
| 301-350        | 1         | 1.05%   |
| 141-150        | 1         | 1.05%   |
| 111-120        | 1         | 1.05%   |
| Unknown        | 1         | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 41        | 44.09%  |
| 101-120       | 31        | 33.33%  |
| 51-100        | 12        | 12.9%   |
| 161-240       | 7         | 7.53%   |
| More than 240 | 1         | 1.08%   |
| Unknown       | 1         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 78        | 73.58%  |
| 0     | 17        | 16.04%  |
| 2     | 11        | 10.38%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 66        | 39.76%  |
| Realtek Semiconductor             | 40        | 24.1%   |
| Qualcomm Atheros                  | 26        | 15.66%  |
| Broadcom                          | 11        | 6.63%   |
| TP-Link                           | 5         | 3.01%   |
| Ericsson Business Mobile Networks | 4         | 2.41%   |
| Nvidia                            | 3         | 1.81%   |
| ASUSTek Computer                  | 3         | 1.81%   |
| Edimax Technology                 | 2         | 1.2%    |
| Sierra Wireless                   | 1         | 0.6%    |
| Ralink                            | 1         | 0.6%    |
| Qualcomm                          | 1         | 0.6%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.6%    |
| Marvell Technology Group          | 1         | 0.6%    |
| Hewlett-Packard                   | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 27        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 15        | 6.94%   |
| Intel Wireless 7265                                                         | 8         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 8         | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 7         | 3.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 6         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 6         | 2.78%   |
| Intel Wireless 8265 / 8275                                                  | 5         | 2.31%   |
| Intel Wireless 7260                                                         | 5         | 2.31%   |
| Intel Ethernet Connection (3) I218-LM                                       | 5         | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 4         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 1.85%   |
| Intel Wireless 8260                                                         | 4         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                       | 4         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 4         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                              | 4         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 4         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3         | 1.39%   |
| Nvidia MCP79 Ethernet                                                       | 3         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                                    | 3         | 1.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 2         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                       | 2         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 2         | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 2         | 0.93%   |
| Intel Ethernet Connection I219-LM                                           | 2         | 0.93%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                       | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 2         | 0.93%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 0.93%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 0.93%   |
| Ericsson Business Mobile Networks N5321 gw Mobile Broadband Serial Port III | 2         | 0.93%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 2         | 0.93%   |
| TP-Link TP-Link High Power Wireless USB Adapter                             | 1         | 0.46%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 1         | 0.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1         | 0.46%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                               | 1         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 0.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 0.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 0.46%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 0.46%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 1         | 0.46%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                      | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                   | 1         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                   | 1         | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 1         | 0.46%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                  | 1         | 0.46%   |
| OnePlus (Shenzhen) IN2025 RNDIS Control RNDIS Ethernet Data                 | 1         | 0.46%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 0.46%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                        | 1         | 0.46%   |
| Intel Wireless-AC 9260                                                      | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 53.85%  |
| Qualcomm Atheros      | 21        | 17.95%  |
| Realtek Semiconductor | 14        | 11.97%  |
| Broadcom              | 7         | 5.98%   |
| TP-Link               | 5         | 4.27%   |
| ASUSTek Computer      | 3         | 2.56%   |
| Edimax Technology     | 2         | 1.71%   |
| Sierra Wireless       | 1         | 0.85%   |
| Ralink                | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                | 8         | 6.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 8         | 6.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 6         | 5.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 6         | 5.08%   |
| Intel Wireless 8265 / 8275                                         | 5         | 4.24%   |
| Intel Wireless 7260                                                | 5         | 4.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 4         | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 4         | 3.39%   |
| Intel Wireless 8260                                                | 4         | 3.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 4         | 3.39%   |
| Intel Centrino Ultimate-N 6300                                     | 4         | 3.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4         | 3.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 3         | 2.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 2         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 2         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 2         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection            | 2         | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 2         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 2         | 1.69%   |
| Intel Centrino Advanced-N 6235                                     | 2         | 1.69%   |
| Intel Centrino Advanced-N 6200                                     | 2         | 1.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller             | 2         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                | 2         | 1.69%   |
| TP-Link TP-Link High Power Wireless USB Adapter                    | 1         | 0.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 1         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 1         | 0.85%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                      | 1         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 0.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                    | 1         | 0.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1         | 0.85%   |
| Realtek Realtek Bluetooth 4.2 Adapter                              | 1         | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 1         | 0.85%   |
| Intel Wireless-AC 9260                                             | 1         | 0.85%   |
| Intel Wireless 3165                                                | 1         | 0.85%   |
| Intel Wi-Fi 6 AX201                                                | 1         | 0.85%   |
| Intel Wi-Fi 6 AX200                                                | 1         | 0.85%   |
| Intel Ultimate N WiFi Link 5300                                    | 1         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection              | 1         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 0.85%   |
| Intel Centrino Wireless-N 135                                      | 1         | 0.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                       | 1         | 0.85%   |
| Intel Centrino Wireless-N 100                                      | 1         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 1         | 0.85%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]     | 1         | 0.85%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]  | 1         | 0.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 0.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                 | 1         | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                    | 1         | 0.85%   |
| ASUS WL-167G v1 802.11g Adapter [Ralink RT2571]                    | 1         | 0.85%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 1         | 0.85%   |
| ASUS ASUS Wireless USB adapter                                     | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 39        | 42.39%  |
| Realtek Semiconductor         | 34        | 36.96%  |
| Qualcomm Atheros              | 8         | 8.7%    |
| Broadcom                      | 5         | 5.43%   |
| Nvidia                        | 3         | 3.26%   |
| Qualcomm                      | 1         | 1.09%   |
| OnePlus Technology (Shenzhen) | 1         | 1.09%   |
| Marvell Technology Group      | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 29.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 16.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 5.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 4.3%    |
| Nvidia MCP79 Ethernet                                             | 3         | 3.23%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 3.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.15%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.15%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.15%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.15%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.15%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.08%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.08%   |
| OnePlus (Shenzhen) IN2025 RNDIS Control RNDIS Ethernet Data       | 1         | 1.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.08%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.08%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.08%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.08%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.08%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.08%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.08%   |
| Unknown                                                           | 1         | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 52.22%  |
| Ethernet | 92        | 45.32%  |
| Modem    | 4         | 1.97%   |
| Unknown  | 1         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 52.15%  |
| WiFi     | 75        | 46.01%  |
| Modem    | 3         | 1.84%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 88        | 84.62%  |
| 1     | 15        | 14.42%  |
| 3     | 1         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 50.65%  |
| Realtek Semiconductor           | 6         | 7.79%   |
| Qualcomm Atheros Communications | 6         | 7.79%   |
| Broadcom                        | 6         | 7.79%   |
| Lite-On Technology              | 5         | 6.49%   |
| IMC Networks                    | 4         | 5.19%   |
| Dell                            | 4         | 5.19%   |
| Apple                           | 4         | 5.19%   |
| Alps Electric                   | 2         | 2.6%    |
| Toshiba                         | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 20        | 25.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 10.39%  |
| Intel AX201 Bluetooth                                       | 5         | 6.49%   |
| Apple Bluetooth Host Controller                             | 4         | 5.19%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 3.9%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 3.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 3.9%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 3         | 3.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 3.9%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 2.6%    |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.6%    |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 2.6%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2.6%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.6%    |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.3%    |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.3%    |
| Realtek  Bluetooth Adapter                                  | 1         | 1.3%    |
| Realtek Bluetooth Radio                                     | 1         | 1.3%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.3%    |
| Intel AX200 Bluetooth                                       | 1         | 1.3%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.3%    |
| IMC Networks Bluetooth Module                               | 1         | 1.3%    |
| Dell DW375 Bluetooth Module                                 | 1         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.3%    |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.3%    |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 90        | 78.26%  |
| AMD      | 14        | 12.17%  |
| Nvidia   | 9         | 7.83%   |
| Logitech | 1         | 0.87%   |
| DSEA A/S | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 10.81%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 8.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 7.43%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 7.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 7.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 4.73%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 4.73%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 4.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.7%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 2.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.35%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.35%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.35%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.68%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.68%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.68%   |
| DSEA A/S EPOS BTD 800                                                                             | 1         | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.68%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 32.12%  |
| SK Hynix            | 36        | 26.28%  |
| Micron Technology   | 9         | 6.57%   |
| Unknown             | 8         | 5.84%   |
| Kingston            | 8         | 5.84%   |
| Crucial             | 7         | 5.11%   |
| Elpida              | 5         | 3.65%   |
| Corsair             | 3         | 2.19%   |
| Unknown (ABCD)      | 2         | 1.46%   |
| GOODRAM             | 2         | 1.46%   |
| G.Skill             | 2         | 1.46%   |
| A-DATA Technology   | 2         | 1.46%   |
| Transcend           | 1         | 0.73%   |
| Team                | 1         | 0.73%   |
| Smart               | 1         | 0.73%   |
| Ramaxel Technology  | 1         | 0.73%   |
| Neo Forza           | 1         | 0.73%   |
| Nanya Technology    | 1         | 0.73%   |
| Apacer              | 1         | 0.73%   |
| 09490000802C        | 1         | 0.73%   |
| Unknown             | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 6.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 5%      |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 3.57%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 3.57%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 5         | 3.57%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.86%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 2.14%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.43%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 2         | 1.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.43%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.43%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.43%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.43%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s            | 2         | 1.43%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 1.43%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.71%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s             | 1         | 0.71%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                 | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.71%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 1         | 0.71%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.71%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.71%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 1         | 0.71%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s    | 1         | 0.71%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 0.71%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.71%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.71%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 0.71%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 1         | 0.71%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 0.71%   |
| Neo Forza RAM NMSO480E82-2666E 8GB SODIMM DDR4 2667MT/s          | 1         | 0.71%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 0.71%   |
| Micron RAM Module 4GB SODIMM DDR4 2133MT/s                       | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 63        | 57.8%   |
| DDR4    | 38        | 34.86%  |
| DDR2    | 3         | 2.75%   |
| LPDDR4  | 2         | 1.83%   |
| DDR     | 2         | 1.83%   |
| Unknown | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 97.22%  |
| Row Of Chips | 3         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 59        | 49.58%  |
| 8192  | 43        | 36.13%  |
| 16384 | 8         | 6.72%   |
| 2048  | 8         | 6.72%   |
| 1024  | 1         | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 41        | 35.65%  |
| 2667    | 21        | 18.26%  |
| 2400    | 12        | 10.43%  |
| 1334    | 10        | 8.7%    |
| 1333    | 8         | 6.96%   |
| 2133    | 7         | 6.09%   |
| 3200    | 4         | 3.48%   |
| Unknown | 4         | 3.48%   |
| 1067    | 3         | 2.61%   |
| 800     | 3         | 2.61%   |
| 1867    | 1         | 0.87%   |
| 667     | 1         | 0.87%   |

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
| Chicony Electronics                    | 20        | 25.32%  |
| Realtek Semiconductor                  | 9         | 11.39%  |
| Microdia                               | 9         | 11.39%  |
| Acer                                   | 9         | 11.39%  |
| Suyin                                  | 5         | 6.33%   |
| Quanta                                 | 5         | 6.33%   |
| Sunplus Innovation Technology          | 4         | 5.06%   |
| IMC Networks                           | 4         | 5.06%   |
| Alcor Micro                            | 4         | 5.06%   |
| Silicon Motion                         | 2         | 2.53%   |
| Ricoh                                  | 2         | 2.53%   |
| Lite-On Technology                     | 2         | 2.53%   |
| Luxvisions Innotech Limited            | 1         | 1.27%   |
| Lenovo                                 | 1         | 1.27%   |
| Importek                               | 1         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer Integrated Camera                                         | 7         | 8.86%   |
| Microdia Integrated Webcam                                     | 4         | 5.06%   |
| Chicony Integrated Camera                                      | 4         | 5.06%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 3.8%    |
| Microdia Integrated_Webcam_HD                                  | 3         | 3.8%    |
| Chicony USB2.0 HD UVC WebCam                                   | 3         | 3.8%    |
| Chicony HD WebCam                                              | 3         | 3.8%    |
| Chicony Chicony USB2.0 Camera                                  | 3         | 3.8%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 2         | 2.53%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 2         | 2.53%   |
| Realtek Lenovo EasyCamera                                      | 2         | 2.53%   |
| Realtek Front Camera                                           | 2         | 2.53%   |
| Quanta VGA WebCam                                              | 2         | 2.53%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.53%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 2.53%   |
| Suyin RGBIR Camera                                             | 1         | 1.27%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.27%   |
| Suyin HD WebCam                                                | 1         | 1.27%   |
| Sunplus MTD camera                                             | 1         | 1.27%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.27%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 1.27%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.27%   |
| Ricoh USB2.0 Camera                                            | 1         | 1.27%   |
| Ricoh HD Webcam                                                | 1         | 1.27%   |
| Realtek Realtek USB2.0 PC Camera                               | 1         | 1.27%   |
| Realtek Integrated Webcam HD                                   | 1         | 1.27%   |
| Quanta USB2.0 HD UVC WebCam                                    | 1         | 1.27%   |
| Microdia Sonix Integrated Webcam                               | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.27%   |
| Luxvisions Innotech Limited Integrated Camera                  | 1         | 1.27%   |
| Lite-On Integrated Camera                                      | 1         | 1.27%   |
| Lite-On HP TrueVision HD Camera                                | 1         | 1.27%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.27%   |
| Importek TOSHIBA Web Camera - HD                               | 1         | 1.27%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 1.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 1.27%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.27%   |
| IMC Networks Integrated Camera                                 | 1         | 1.27%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.27%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 1.27%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.27%   |
| Chicony Integrated HP HD Webcam                                | 1         | 1.27%   |
| Chicony HP HD Camera                                           | 1         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.27%   |
| Alcor Micro USB 2.0 Web Camera                                 | 1         | 1.27%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.27%   |
| Alcor Micro HP WebCam-101                                      | 1         | 1.27%   |
| Alcor Micro Acer Integrated Webcam                             | 1         | 1.27%   |
| Acer ThinkPad Integrated Camera                                | 1         | 1.27%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 33.33%  |
| Upek                  | 3         | 20%     |
| Synaptics             | 2         | 13.33%  |
| STMicroelectronics    | 1         | 6.67%   |
| Next Biometrics       | 1         | 6.67%   |
| LighTuning Technology | 1         | 6.67%   |
| Focal-systems.Corp    | 1         | 6.67%   |
| Broadcom              | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.67%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 6.67%   |
| Synaptics  WBDI                                                              | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 6.67%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 6.67%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |

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
| 2     | 38        | 35.51%  |
| 3     | 26        | 24.3%   |
| 1     | 22        | 20.56%  |
| 4     | 14        | 13.08%  |
| 0     | 5         | 4.67%   |
| 5     | 2         | 1.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 83        | 35.32%  |
| Bluetooth                | 59        | 25.11%  |
| Net/wireless             | 33        | 14.04%  |
| Card reader              | 28        | 11.91%  |
| Fingerprint reader       | 17        | 7.23%   |
| Firewire controller      | 7         | 2.98%   |
| Storage                  | 4         | 1.7%    |
| Network                  | 4         | 1.7%    |

