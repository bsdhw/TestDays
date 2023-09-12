helloSystem 0.8.1 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.1.

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

Total: 202

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| HP            | 2000                        | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| HP            | Pavilion dv3500             | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| NVN-ED01      | Unknown                     | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| ASUSTek       | X553MA                      | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Acer          | Aspire V3-371               | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| Compaq        | Presario CQ-17              | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| HP            | EliteBook 840 G5            | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| Dell          | Latitude 5480               | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| ASUSTek       | X541UVK                     | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| HP            | Compaq Presario CQ61        | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Acer          | Aspire 5749                 | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Lenovo        | S10-3                       | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Panasonic     | CF-NX1GDHYS                 | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Pavilion Notebook           | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Apple         | MacBookPro10,2              | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| Fujitsu       | Unknown                     | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| ASUSTek       | K42Jc                       | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Google        | Sentry                      | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| Sony          | VPCEG15FB                   | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Packard Be... | EasyNote LJ65               | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| Sony          | SVF14A15CBB                 | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| HP            | Laptop 14-bs0xx             | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Lenovo        | Flex 2-15 20405             | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell          | Inspiron 3421               | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [93b498fb0c](https://bsd-hardware.info/?probe=93b498fb0c) | Apr 21, 2023 |
| Packard Be... | DOT SE                      | [f456e964db](https://bsd-hardware.info/?probe=f456e964db) | Apr 19, 2023 |
| Dell          | Latitude 7410               | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Acer          | V5-131                      | [4c2332c3b8](https://bsd-hardware.info/?probe=4c2332c3b8) | Apr 19, 2023 |
| Medion        | E15302                      | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Toshiba       | PORTEGE R700                | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| Google        | Terra                       | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| Samsung       | 370E4K                      | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [c7e40ee8ea](https://bsd-hardware.info/?probe=c7e40ee8ea) | Apr 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [52aac5fc6f](https://bsd-hardware.info/?probe=52aac5fc6f) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| Google        | Wolf                        | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| ASUSTek       | X58C                        | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| Dell          | Latitude 5500               | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Apple         | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Lenovo        | ThinkPad T440p              | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Acer          | TravelMate P249-G2-M        | [090f37a821](https://bsd-hardware.info/?probe=090f37a821) | Mar 14, 2023 |
| Dell          | Latitude D630               | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| HP            | Laptop 14-bs0xx             | [cd76713b75](https://bsd-hardware.info/?probe=cd76713b75) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Toshiba       | Satellite L50-B             | [7052b38ba8](https://bsd-hardware.info/?probe=7052b38ba8) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Toshiba       | Satellite A200              | [c49985d00b](https://bsd-hardware.info/?probe=c49985d00b) | Mar 13, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Fujitsu       | LIFEBOOK E736               | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| HP            | Laptop 15-bs1xx             | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| ASUSTek       | 1201N                       | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Dell          | Inspiron 15 3515            | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Plaisio       | Turbo X                     | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 174       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 172       | 98.85%  |
| JWM          | 1         | 0.57%   |
| GNOME        | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 174       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 174       | 99.43%  |
| SDDM | 1         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 87        | 49.71%  |
| fr_FR   | 22        | 12.57%  |
| ru_RU   | 12        | 6.86%   |
| de_DE   | 12        | 6.86%   |
| es_ES   | 8         | 4.57%   |
| Unknown | 8         | 4.57%   |
| pl_PL   | 7         | 4%      |
| pt_BR   | 5         | 2.86%   |
| nl_NL   | 3         | 1.71%   |
| it_IT   | 3         | 1.71%   |
| zh_CN   | 2         | 1.14%   |
| pt_PT   | 1         | 0.57%   |
| pt      | 1         | 0.57%   |
| ko_KR   | 1         | 0.57%   |
| jp_JP   | 1         | 0.57%   |
| fi_FI   | 1         | 0.57%   |
| en      | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 174       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 87        | 50%     |
| Cd9660 | 87        | 50%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 174       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 58        | 33.33%  |
| Hewlett-Packard     | 26        | 14.94%  |
| Dell                | 18        | 10.34%  |
| ASUSTek Computer    | 13        | 7.47%   |
| Acer                | 9         | 5.17%   |
| Toshiba             | 8         | 4.6%    |
| Samsung Electronics | 8         | 4.6%    |
| Apple               | 6         | 3.45%   |
| Fujitsu             | 5         | 2.87%   |
| Sony                | 3         | 1.72%   |
| Google              | 3         | 1.72%   |
| Packard Bell        | 2         | 1.15%   |
| TUXEDO              | 1         | 0.57%   |
| Timi                | 1         | 0.57%   |
| Plaisio             | 1         | 0.57%   |
| Panasonic           | 1         | 0.57%   |
| NVN-ED01            | 1         | 0.57%   |
| MSI                 | 1         | 0.57%   |
| Medion              | 1         | 0.57%   |
| LG Electronics      | 1         | 0.57%   |
| Irbis               | 1         | 0.57%   |
| Intel               | 1         | 0.57%   |
| IGEL Technology     | 1         | 0.57%   |
| HUAWEI              | 1         | 0.57%   |
| Dynabook Europe     | 1         | 0.57%   |
| DNS                 | 1         | 0.57%   |
| Compaq              | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 3         | 1.72%   |
| HP Laptop 14-bs0xx                    | 2         | 1.15%   |
| TUXEDO Aura 15 Gen1                   | 1         | 0.57%   |
| Toshiba Satellite P300                | 1         | 0.57%   |
| Toshiba Satellite L675D               | 1         | 0.57%   |
| Toshiba Satellite L50-B               | 1         | 0.57%   |
| Toshiba Satellite L40                 | 1         | 0.57%   |
| Toshiba Satellite C845                | 1         | 0.57%   |
| Toshiba Satellite A200                | 1         | 0.57%   |
| Toshiba QOSMIO X775                   | 1         | 0.57%   |
| Toshiba PORTEGE R700                  | 1         | 0.57%   |
| Timi TM1701                           | 1         | 0.57%   |
| Sony VPCEG15FB                        | 1         | 0.57%   |
| Sony VGN-FZ19VN                       | 1         | 0.57%   |
| Sony SVF14A15CBB                      | 1         | 0.57%   |
| Samsung RC530/RC730                   | 1         | 0.57%   |
| Samsung R530/R730/R540                | 1         | 0.57%   |
| Samsung R520/R522/R620                | 1         | 0.57%   |
| Samsung R468/R418                     | 1         | 0.57%   |
| Samsung 370E4K                        | 1         | 0.57%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.57%   |
| Samsung 275E4E/275E5E                 | 1         | 0.57%   |
| Samsung 270E5J/2570EJ                 | 1         | 0.57%   |
| Plaisio Turbo X                       | 1         | 0.57%   |
| Panasonic CF-NX1GDHYS                 | 1         | 0.57%   |
| Packard Bell EasyNote LJ65            | 1         | 0.57%   |
| Packard Bell DOT SE                   | 1         | 0.57%   |
| MSI GE63 Raider RGB 8RE               | 1         | 0.57%   |
| Medion E15302                         | 1         | 0.57%   |
| LG E500-L.A2M4A2                      | 1         | 0.57%   |
| Lenovo ZIUS6                          | 1         | 0.57%   |
| Lenovo Yoga Slim 7 14ITL05 82A3       | 1         | 0.57%   |
| Lenovo ThinkPad X61s 7667WQS          | 1         | 0.57%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05 | 1         | 0.57%   |
| Lenovo ThinkPad X270 20HNA04GCD       | 1         | 0.57%   |
| Lenovo ThinkPad X270 20HMS06Q1D       | 1         | 0.57%   |
| Lenovo ThinkPad X240 20AMA1Y3UK       | 1         | 0.57%   |
| Lenovo ThinkPad X230 Tablet 34352TU   | 1         | 0.57%   |
| Lenovo ThinkPad X230 232578G          | 1         | 0.57%   |
| Lenovo ThinkPad X230 23202DG          | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 39        | 22.41%  |
| Dell Latitude         | 11        | 6.32%   |
| Lenovo IdeaPad        | 9         | 5.17%   |
| HP Pavilion           | 8         | 4.6%    |
| Toshiba Satellite     | 6         | 3.45%   |
| HP Laptop             | 6         | 3.45%   |
| Dell Inspiron         | 6         | 3.45%   |
| Acer Aspire           | 5         | 2.87%   |
| HP EliteBook          | 4         | 2.3%    |
| HP Compaq             | 3         | 1.72%   |
| Fujitsu LIFEBOOK      | 3         | 1.72%   |
| Unknown               | 3         | 1.72%   |
| Lenovo Legion         | 2         | 1.15%   |
| ASUS VivoBook         | 2         | 1.15%   |
| TUXEDO Aura           | 1         | 0.57%   |
| Toshiba QOSMIO        | 1         | 0.57%   |
| Toshiba PORTEGE       | 1         | 0.57%   |
| Timi TM1701           | 1         | 0.57%   |
| Sony VPCEG15FB        | 1         | 0.57%   |
| Sony VGN-FZ19VN       | 1         | 0.57%   |
| Sony SVF14A15CBB      | 1         | 0.57%   |
| Samsung RC530         | 1         | 0.57%   |
| Samsung R530          | 1         | 0.57%   |
| Samsung R520          | 1         | 0.57%   |
| Samsung R468          | 1         | 0.57%   |
| Samsung 370E4K        | 1         | 0.57%   |
| Samsung 305E4A        | 1         | 0.57%   |
| Samsung 275E4E        | 1         | 0.57%   |
| Samsung 270E5J        | 1         | 0.57%   |
| Plaisio Turbo         | 1         | 0.57%   |
| Panasonic CF-NX1GDHYS | 1         | 0.57%   |
| Packard Bell EasyNote | 1         | 0.57%   |
| Packard Bell DOT      | 1         | 0.57%   |
| MSI GE63              | 1         | 0.57%   |
| Medion E15302         | 1         | 0.57%   |
| LG E500-L.A2M4A2      | 1         | 0.57%   |
| Lenovo ZIUS6          | 1         | 0.57%   |
| Lenovo Yoga           | 1         | 0.57%   |
| Lenovo ThinkBook      | 1         | 0.57%   |
| Lenovo S10-3          | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 18        | 10.34%  |
| 2012 | 16        | 9.2%    |
| 2013 | 14        | 8.05%   |
| 2022 | 13        | 7.47%   |
| 2017 | 12        | 6.9%    |
| 2020 | 11        | 6.32%   |
| 2019 | 11        | 6.32%   |
| 2016 | 11        | 6.32%   |
| 2010 | 10        | 5.75%   |
| 2009 | 10        | 5.75%   |
| 2008 | 9         | 5.17%   |
| 2021 | 8         | 4.6%    |
| 2014 | 8         | 4.6%    |
| 2015 | 7         | 4.02%   |
| 2018 | 6         | 3.45%   |
| 2007 | 5         | 2.87%   |
| 2023 | 3         | 1.72%   |
| 2006 | 2         | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 174       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 169       | 97.13%  |
| Yes  | 5         | 2.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 63        | 36.21%  |
| 4.01-8.0    | 55        | 31.61%  |
| 16.01-24.0  | 31        | 17.82%  |
| 2.01-3.0    | 14        | 8.05%   |
| 32.01-64.0  | 5         | 2.87%   |
| 3.01-4.0    | 5         | 2.87%   |
| 64.01-256.0 | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 111       | 63.79%  |
| 0.51-1.0 | 49        | 28.16%  |
| 1.01-2.0 | 11        | 6.32%   |
| 2.01-3.0 | 3         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 74.29%  |
| 2      | 27        | 15.43%  |
| 0      | 13        | 7.43%   |
| 3      | 5         | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 64.37%  |
| Yes       | 62        | 35.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 88.51%  |
| No        | 20        | 11.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 96.55%  |
| No        | 6         | 3.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 70.11%  |
| No        | 52        | 29.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 26        | 14.94%  |
| Germany     | 15        | 8.62%   |
| Russia      | 14        | 8.05%   |
| Poland      | 14        | 8.05%   |
| Brazil      | 14        | 8.05%   |
| Indonesia   | 8         | 4.6%    |
| UK          | 7         | 4.02%   |
| Spain       | 6         | 3.45%   |
| Italy       | 6         | 3.45%   |
| France      | 5         | 2.87%   |
| Canada      | 5         | 2.87%   |
| Romania     | 4         | 2.3%    |
| China       | 4         | 2.3%    |
| Australia   | 4         | 2.3%    |
| Turkey      | 3         | 1.72%   |
| Netherlands | 3         | 1.72%   |
| Mexico      | 3         | 1.72%   |
| India       | 3         | 1.72%   |
| Hungary     | 3         | 1.72%   |
| Ukraine     | 2         | 1.15%   |
| South Korea | 2         | 1.15%   |
| Portugal    | 2         | 1.15%   |
| Israel      | 2         | 1.15%   |
| Bulgaria    | 2         | 1.15%   |
| Syria       | 1         | 0.57%   |
| Switzerland | 1         | 0.57%   |
| Slovenia    | 1         | 0.57%   |
| Slovakia    | 1         | 0.57%   |
| Philippines | 1         | 0.57%   |
| Lithuania   | 1         | 0.57%   |
| Jamaica     | 1         | 0.57%   |
| Ireland     | 1         | 0.57%   |
| Greece      | 1         | 0.57%   |
| Finland     | 1         | 0.57%   |
| Czechia     | 1         | 0.57%   |
| Cyprus      | 1         | 0.57%   |
| Colombia    | 1         | 0.57%   |
| Chile       | 1         | 0.57%   |
| Bolivia     | 1         | 0.57%   |
| Belarus     | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Sao Paulo     | 4         | 2.29%   |
| Wroclaw       | 3         | 1.71%   |
| Berlin        | 3         | 1.71%   |
| Warsaw        | 2         | 1.14%   |
| Valencia      | 2         | 1.14%   |
| Sydney        | 2         | 1.14%   |
| St Petersburg | 2         | 1.14%   |
| Shenzhen      | 2         | 1.14%   |
| Moscow        | 2         | 1.14%   |
| Montreal      | 2         | 1.14%   |
| Milan         | 2         | 1.14%   |
| Lisbon        | 2         | 1.14%   |
| Irkutsk       | 2         | 1.14%   |
| Budapest      | 2         | 1.14%   |
| Zarautz       | 1         | 0.57%   |
| Yuseong-gu    | 1         | 0.57%   |
| Yogyakarta    | 1         | 0.57%   |
| Yeosu         | 1         | 0.57%   |
| Yekaterinburg | 1         | 0.57%   |
| Woodbridge    | 1         | 0.57%   |
| Whitby        | 1         | 0.57%   |
| West Plains   | 1         | 0.57%   |
| Wausau        | 1         | 0.57%   |
| Vitória      | 1         | 0.57%   |
| Vitebsk       | 1         | 0.57%   |
| Vilnius       | 1         | 0.57%   |
| Villemomble   | 1         | 0.57%   |
| Villefontaine | 1         | 0.57%   |
| Victoria      | 1         | 0.57%   |
| Ulyanovsk     | 1         | 0.57%   |
| Twinsburg     | 1         | 0.57%   |
| Trindade      | 1         | 0.57%   |
| Tomasikovo    | 1         | 0.57%   |
| Tolyatti      | 1         | 0.57%   |
| Thessaloniki  | 1         | 0.57%   |
| Teaneck       | 1         | 0.57%   |
| Tata          | 1         | 0.57%   |
| Targoviste    | 1         | 0.57%   |
| Swindon       | 1         | 0.57%   |
| Surabaya      | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 32     | 16.15%  |
| Toshiba             | 20        | 22     | 10.42%  |
| Seagate             | 20        | 21     | 10.42%  |
| WDC                 | 16        | 17     | 8.33%   |
| Hitachi             | 15        | 15     | 7.81%   |
| SanDisk             | 14        | 14     | 7.29%   |
| Kingston            | 12        | 12     | 6.25%   |
| Crucial             | 9         | 11     | 4.69%   |
| HGST                | 6         | 9      | 3.13%   |
| Intel               | 5         | 5      | 2.6%    |
| Micron Technology   | 4         | 4      | 2.08%   |
| SK hynix            | 3         | 3      | 1.56%   |
| China               | 3         | 3      | 1.56%   |
| A-DATA Technology   | 3         | 3      | 1.56%   |
| Transcend           | 2         | 2      | 1.04%   |
| OCZ                 | 2         | 2      | 1.04%   |
| Intenso             | 2         | 2      | 1.04%   |
| GOODRAM             | 2         | 2      | 1.04%   |
| Gigabyte Technology | 2         | 2      | 1.04%   |
| Fujitsu             | 2         | 2      | 1.04%   |
| BHT                 | 2         | 2      | 1.04%   |
| Verbatim            | 1         | 1      | 0.52%   |
| V-GeN               | 1         | 1      | 0.52%   |
| UMIS                | 1         | 1      | 0.52%   |
| Team                | 1         | 1      | 0.52%   |
| SPCC                | 1         | 1      | 0.52%   |
| PNY                 | 1         | 1      | 0.52%   |
| Plextor             | 1         | 1      | 0.52%   |
| Phison              | 1         | 1      | 0.52%   |
| Patriot             | 1         | 1      | 0.52%   |
| Netac               | 1         | 1      | 0.52%   |
| MidasForce          | 1         | 1      | 0.52%   |
| KingSpec            | 1         | 1      | 0.52%   |
| Kingmax             | 1         | 1      | 0.52%   |
| Goldenfir           | 1         | 1      | 0.52%   |
| Dogfish             | 1         | 1      | 0.52%   |
| Biostar             | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 4         | 2.05%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 2.05%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.54%   |
| Kingston SA400S37240G 240GB          | 3         | 1.54%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.03%   |
| Seagate ST9500325AS 500GB            | 2         | 1.03%   |
| Seagate ST9250410AS 250GB            | 2         | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.03%   |
| Samsung HM321HI 320GB                | 2         | 1.03%   |
| Kingston SV300S37A60G 64GB           | 2         | 1.03%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 1.03%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 1.03%   |
| Hitachi HTS542525K9A300 250GB        | 2         | 1.03%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.03%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 2         | 1.03%   |
| WDC WDS500G2B0B-00YS70 500GB         | 1         | 0.51%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.51%   |
| WDC WDS100T2G0A-00JH30 1TB           | 1         | 0.51%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.51%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.51%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.51%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 1         | 0.51%   |
| WDC WD30PURZ-85AKKY0 3TB             | 1         | 0.51%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.51%   |
| WDC WD1600BEVT-60ZCT0 160GB          | 1         | 0.51%   |
| WDC WD1600BEVS-22VAT0 160GB          | 1         | 0.51%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10JPVX-80JC3T0 1TB             | 1         | 0.51%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.51%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.51%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.51%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.51%   |
| Verbatim Vi550 S3 SSD 256GB          | 1         | 0.51%   |
| V-GeN V-GEN08SM22AR256SDK 256GB      | 1         | 0.51%   |
| UMIS RPJYJ512MKN1QWQ 512GB           | 1         | 0.51%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.51%   |
| Transcend TS120GMTS420S 120GB        | 1         | 0.51%   |
| Toshiba THNSNJ256G8NY 256GB          | 1         | 0.51%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.51%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 21     | 26.32%  |
| Toshiba             | 18        | 20     | 23.68%  |
| Hitachi             | 15        | 15     | 19.74%  |
| WDC                 | 11        | 11     | 14.47%  |
| HGST                | 6         | 9      | 7.89%   |
| Samsung Electronics | 4         | 5      | 5.26%   |
| Fujitsu             | 2         | 2      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 14        | 14     | 15.73%  |
| Samsung Electronics | 14        | 14     | 15.73%  |
| Kingston            | 11        | 11     | 12.36%  |
| Crucial             | 9         | 11     | 10.11%  |
| Intel               | 4         | 4      | 4.49%   |
| China               | 3         | 3      | 3.37%   |
| WDC                 | 2         | 3      | 2.25%   |
| OCZ                 | 2         | 2      | 2.25%   |
| Micron Technology   | 2         | 2      | 2.25%   |
| Intenso             | 2         | 2      | 2.25%   |
| GOODRAM             | 2         | 2      | 2.25%   |
| Gigabyte Technology | 2         | 2      | 2.25%   |
| BHT                 | 2         | 2      | 2.25%   |
| A-DATA Technology   | 2         | 2      | 2.25%   |
| Verbatim            | 1         | 1      | 1.12%   |
| V-GeN               | 1         | 1      | 1.12%   |
| Transcend           | 1         | 1      | 1.12%   |
| Toshiba             | 1         | 1      | 1.12%   |
| Team                | 1         | 1      | 1.12%   |
| SPCC                | 1         | 1      | 1.12%   |
| SK hynix            | 1         | 1      | 1.12%   |
| PNY                 | 1         | 1      | 1.12%   |
| Plextor             | 1         | 1      | 1.12%   |
| Patriot             | 1         | 1      | 1.12%   |
| Netac               | 1         | 1      | 1.12%   |
| MidasForce          | 1         | 1      | 1.12%   |
| KingSpec            | 1         | 1      | 1.12%   |
| Kingmax             | 1         | 1      | 1.12%   |
| Goldenfir           | 1         | 1      | 1.12%   |
| Dogfish             | 1         | 1      | 1.12%   |
| Biostar             | 1         | 1      | 1.12%   |
| Apple               | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 82        | 92     | 45.81%  |
| HDD  | 72        | 83     | 40.22%  |
| NVMe | 25        | 27     | 13.97%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 140       | 175    | 84.85%  |
| NVMe | 25        | 27     | 15.15%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 125       | 145    | 83.33%  |
| 0.51-1.0   | 23        | 28     | 15.33%  |
| 2.01-3.0   | 1         | 1      | 0.67%   |
| 1.01-2.0   | 1         | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 82        | 47.13%  |
| 101-250    | 29        | 16.67%  |
| 251-500    | 26        | 14.94%  |
| 51-100     | 22        | 12.64%  |
| 21-50      | 7         | 4.02%   |
| 501-1000   | 7         | 4.02%   |
| Unknown    | 1         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 171       | 98.28%  |
| 21-50   | 1         | 0.57%   |
| 101-250 | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 2         | 2      | 4.88%   |
| Hitachi HTS542525K9A300 250GB       | 2         | 2      | 4.88%   |
| WDC WD30PURZ-85AKKY0 3TB            | 1         | 1      | 2.44%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 2.44%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 2.44%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 2.44%   |
| Toshiba MK1229GSG 120GB             | 1         | 1      | 2.44%   |
| SK hynix SC210 mSATA 256GB          | 1         | 1      | 2.44%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 2.44%   |
| Seagate ST9160827AS 160GB           | 1         | 1      | 2.44%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 2.44%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 2.44%   |
| Seagate ST500LM000-SSHD-8GB         | 1         | 1      | 2.44%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB  | 1         | 1      | 2.44%   |
| Seagate ST500LM000-1EJ162 500GB     | 1         | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 2.44%   |
| Seagate ST320LT012-9WS14C 320GB     | 1         | 2      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 2.44%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 2.44%   |
| OCZ AGILITY3 120GB                  | 1         | 1      | 2.44%   |
| Kingston SV300S37A60G 64GB          | 1         | 1      | 2.44%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 2.44%   |
| Hitachi HTS727550A9E364 500GB       | 1         | 1      | 2.44%   |
| Hitachi HTS721060G9SA00 64GB        | 1         | 1      | 2.44%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 2.44%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 2.44%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 2.44%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 2.44%   |
| Hitachi HTS541616J9SA00 160GB       | 1         | 1      | 2.44%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.44%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.44%   |
| HGST HTS541075A7E630 752GB          | 1         | 1      | 2.44%   |
| HGST HTS541010A9E680 1TB            | 1         | 2      | 2.44%   |
| Crucial M4-CT256M4SSD3 256GB        | 1         | 1      | 2.44%   |
| Crucial CT500MX500SSD1 500GB        | 1         | 2      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 29.27%  |
| Hitachi             | 10        | 10     | 24.39%  |
| Toshiba             | 6         | 6      | 14.63%  |
| HGST                | 4         | 5      | 9.76%   |
| WDC                 | 2         | 2      | 4.88%   |
| Crucial             | 2         | 3      | 4.88%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Samsung Electronics | 1         | 1      | 2.44%   |
| OCZ                 | 1         | 1      | 2.44%   |
| Kingston            | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 34.29%  |
| Hitachi             | 10        | 10     | 28.57%  |
| Toshiba             | 6         | 6      | 17.14%  |
| HGST                | 4         | 5      | 11.43%  |
| WDC                 | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 37     | 84.62%  |
| SSD  | 6         | 7      | 15.38%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 130       | 157    | 76.47%  |
| Malfunc | 39        | 44     | 22.94%  |
| Failed  | 1         | 1      | 0.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 140       | 75.27%  |
| AMD                                     | 14        | 7.53%   |
| Samsung Electronics                     | 12        | 6.45%   |
| Sandisk                                 | 6         | 3.23%   |
| Nvidia                                  | 3         | 1.61%   |
| SK hynix                                | 2         | 1.08%   |
| Micron Technology                       | 2         | 1.08%   |
| Toshiba                                 | 1         | 0.54%   |
| Silicon Motion                          | 1         | 0.54%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.54%   |
| Shenzhen Unionmemory Information System | 1         | 0.54%   |
| Phison Electronics                      | 1         | 0.54%   |
| Kingston Technology Company             | 1         | 0.54%   |
| ADATA Technology                        | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 10.34%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 8.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 15        | 7.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 6.9%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 5.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 4.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 3.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 2.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.46%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.97%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.48%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 2         | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.99%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.99%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.99%   |
| Unknown                                                                          | 2         | 0.99%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.49%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.49%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.49%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.49%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 144       | 74.23%  |
| NVMe | 24        | 12.37%  |
| IDE  | 20        | 10.31%  |
| RAID | 6         | 3.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 156       | 89.66%  |
| AMD    | 18        | 10.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 3.45%   |
| Intel CPU Version                           | 5         | 2.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 2.87%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 5         | 2.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 2.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.72%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.72%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 1.72%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 1.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 1.15%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 1.15%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.15%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.15%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.15%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.15%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.15%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 1.15%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz        | 2         | 1.15%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 2         | 1.15%   |
| Intel Core 2 CPU                            | 2         | 1.15%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 2         | 1.15%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.15%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.15%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 1.15%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.15%   |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz        | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.57%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.57%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.57%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.57%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.57%   |
| Intel Pentium 3558U @ 1.70GHz               | 1         | 0.57%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 1         | 0.57%   |
| Intel Genuine CPU                           | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 52        | 29.89%  |
| Intel Core i7           | 29        | 16.67%  |
| Intel Celeron           | 20        | 11.49%  |
| Intel Core 2 Duo        | 16        | 9.2%    |
| Other                   | 11        | 6.32%   |
| Intel Core i3           | 11        | 6.32%   |
| AMD Ryzen 7             | 5         | 2.87%   |
| Intel Pentium           | 4         | 2.3%    |
| Intel Atom              | 4         | 2.3%    |
| Intel Pentium Dual-Core | 3         | 1.72%   |
| AMD Ryzen 5             | 3         | 1.72%   |
| Intel Genuine           | 2         | 1.15%   |
| Intel Core 2            | 2         | 1.15%   |
| Intel Xeon              | 1         | 0.57%   |
| Intel Pentium Dual      | 1         | 0.57%   |
| Intel Celeron D         | 1         | 0.57%   |
| AMD Ryzen Embedded      | 1         | 0.57%   |
| AMD Phenom II           | 1         | 0.57%   |
| AMD E2                  | 1         | 0.57%   |
| AMD E1                  | 1         | 0.57%   |
| AMD E                   | 1         | 0.57%   |
| AMD Athlon              | 1         | 0.57%   |
| AMD A8                  | 1         | 0.57%   |
| AMD A4                  | 1         | 0.57%   |
| AMD A10                 | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 105       | 60.34%  |
| 4       | 34        | 19.54%  |
| Unknown | 21        | 12.07%  |
| 8       | 4         | 2.3%    |
| 1       | 4         | 2.3%    |
| 16      | 3         | 1.72%   |
| 12      | 2         | 1.15%   |
| 6       | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 170       | 97.7%   |
| 2      | 4         | 2.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 102       | 58.62%  |
| 1       | 48        | 27.59%  |
| Unknown | 24        | 13.79%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 13.79%  |
| SandyBridge   | 19        | 10.92%  |
| IvyBridge     | 19        | 10.92%  |
| Core          | 15        | 8.62%   |
| Penryn        | 14        | 8.05%   |
| Haswell       | 14        | 8.05%   |
| Skylake       | 10        | 5.75%   |
| Westmere      | 9         | 5.17%   |
| Silvermont    | 8         | 4.6%    |
| Broadwell     | 8         | 4.6%    |
| Bonnell       | 5         | 2.87%   |
| TigerLake     | 4         | 2.3%    |
| Zen+          | 3         | 1.72%   |
| Goldmont plus | 3         | 1.72%   |
| Bobcat        | 3         | 1.72%   |
| Unknown       | 3         | 1.72%   |
| Zen 3         | 2         | 1.15%   |
| Zen 2         | 2         | 1.15%   |
| Goldmont      | 2         | 1.15%   |
| Excavator     | 2         | 1.15%   |
| Zen           | 1         | 0.57%   |
| Piledriver    | 1         | 0.57%   |
| K10 Llano     | 1         | 0.57%   |
| K10           | 1         | 0.57%   |
| CometLake     | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 142       | 69.95%  |
| Nvidia                           | 30        | 14.78%  |
| AMD                              | 30        | 14.78%  |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 8.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 8.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 4.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 4.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 4.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 3.72%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.72%   |
| Intel UHD Graphics 620                                                                   | 7         | 3.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.26%   |
| Intel HD Graphics 620                                                                    | 7         | 3.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.33%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.93%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 2         | 0.93%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.93%   |
| Intel HD Graphics 630                                                                    | 2         | 0.93%   |
| Intel HD Graphics 500                                                                    | 2         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.93%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.93%   |
| AMD Renoir                                                                               | 2         | 0.93%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.93%   |
| AMD Lucienne                                                                             | 2         | 0.93%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.47%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.47%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.47%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.47%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.47%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.47%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 92        | 52.87%  |
| 2 x Intel      | 22        | 12.64%  |
| Intel + Nvidia | 21        | 12.07%  |
| 1 x AMD        | 21        | 12.07%  |
| 1 x Nvidia     | 7         | 4.02%   |
| Intel + AMD    | 7         | 4.02%   |
| 2 x Nvidia     | 1         | 0.57%   |
| 2 x AMD        | 1         | 0.57%   |
| 1 x SiS        | 1         | 0.57%   |
| AMD + Nvidia   | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 160       | 91.95%  |
| Proprietary | 8         | 4.6%    |
| Unknown     | 6         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 89.66%  |
| 0.01-0.5   | 12        | 6.9%    |
| 0.51-1.0   | 4         | 2.3%    |
| 7.01-8.0   | 1         | 0.57%   |
| 1.01-2.0   | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 30.16%  |
| Samsung Electronics     | 8         | 12.7%   |
| BOE                     | 8         | 12.7%   |
| LG Display              | 5         | 7.94%   |
| Chimei Innolux          | 5         | 7.94%   |
| Lenovo                  | 3         | 4.76%   |
| Chi Mei Optoelectronics | 3         | 4.76%   |
| Sharp                   | 2         | 3.17%   |
| InfoVision              | 2         | 3.17%   |
| Goldstar                | 2         | 3.17%   |
| Apple                   | 2         | 3.17%   |
| LG Philips              | 1         | 1.59%   |
| CPT                     | 1         | 1.59%   |
| AOC                     | 1         | 1.59%   |
| Unknown                 | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 2         | 3.17%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch                 | 2         | 3.17%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 3.17%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 1.59%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                  | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch      | 1         | 1.59%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch     | 1         | 1.59%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch        | 1         | 1.59%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch            | 1         | 1.59%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch              | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 1.59%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch              | 1         | 1.59%   |
| InfoVision LCD Monitor IVO048E 1366x768 260x140mm 11.6-inch              | 1         | 1.59%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1         | 1.59%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1         | 1.59%   |
| CPT LCD Monitor CPT1BC0 1024x600 220x120mm 9.9-inch                      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 380x210mm 17.1-inch         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 350x190mm 15.7-inch | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1465 1366x768 310x180mm 14.1-inch | 1         | 1.59%   |
| BOE LCD Monitor BOE0A81 1920x1080 340x190mm 15.3-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE072C 1920x1080 310x170mm 13.9-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE06E2 1920x1080 310x170mm 13.9-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE0696 1366x768 310x170mm 13.9-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE0610 1920x1080 340x190mm 15.3-inch                    | 1         | 1.59%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch           | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 28        | 45.9%   |
| 1920x1080 (FHD) | 20        | 32.79%  |
| 1600x900 (HD+)  | 3         | 4.92%   |
| 1280x800 (WXGA) | 3         | 4.92%   |
| 2560x1600       | 2         | 3.28%   |
| 1400x1050       | 2         | 3.28%   |
| 3840x2160 (4K)  | 1         | 1.64%   |
| 2560x1440 (QHD) | 1         | 1.64%   |
| 1024x600        | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 24        | 38.1%   |
| 13      | 17        | 26.98%  |
| 17      | 4         | 6.35%   |
| 14      | 4         | 6.35%   |
| 12      | 4         | 6.35%   |
| 21      | 3         | 4.76%   |
| 11      | 2         | 3.17%   |
| 31      | 1         | 1.59%   |
| 27      | 1         | 1.59%   |
| 19      | 1         | 1.59%   |
| 9       | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 57.14%  |
| 201-300     | 16        | 25.4%   |
| 401-500     | 4         | 6.35%   |
| 351-400     | 4         | 6.35%   |
| 601-700     | 1         | 1.59%   |
| 501-600     | 1         | 1.59%   |
| Unknown     | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 88.14%  |
| 16/10   | 4         | 6.78%   |
| 4/3     | 2         | 3.39%   |
| Unknown | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 36.51%  |
| 81-90          | 13        | 20.63%  |
| 71-80          | 5         | 7.94%   |
| 61-70          | 4         | 6.35%   |
| 121-130        | 4         | 6.35%   |
| 101-110        | 4         | 6.35%   |
| 201-250        | 3         | 4.76%   |
| 51-60          | 2         | 3.17%   |
| 351-500        | 1         | 1.59%   |
| 41-50          | 1         | 1.59%   |
| 301-350        | 1         | 1.59%   |
| 151-200        | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 44.44%  |
| 101-120       | 25        | 39.68%  |
| 51-100        | 6         | 9.52%   |
| 161-240       | 2         | 3.17%   |
| More than 240 | 1         | 1.59%   |
| Unknown       | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 153       | 87.93%  |
| 0     | 11        | 6.32%   |
| 2     | 10        | 5.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 96        | 35.96%  |
| Realtek Semiconductor             | 73        | 27.34%  |
| Qualcomm Atheros                  | 49        | 18.35%  |
| Broadcom                          | 14        | 5.24%   |
| Marvell Technology Group          | 7         | 2.62%   |
| Sierra Wireless                   | 5         | 1.87%   |
| Xiaomi                            | 4         | 1.5%    |
| Samsung Electronics               | 4         | 1.5%    |
| MediaTek                          | 3         | 1.12%   |
| Ericsson Business Mobile Networks | 3         | 1.12%   |
| Nvidia                            | 2         | 0.75%   |
| JMicron Technology                | 2         | 0.75%   |
| TP-Link                           | 1         | 0.37%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.37%   |
| Ralink                            | 1         | 0.37%   |
| Qualcomm                          | 1         | 0.37%   |
| Edimax Technology                 | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 39        | 11.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 23        | 6.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 14        | 4.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 3.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 3.5%    |
| Intel Wireless 8265 / 8275                                              | 9         | 2.62%   |
| Intel Wireless 8260                                                     | 8         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.04%   |
| Intel Wireless 7265                                                     | 7         | 2.04%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 1.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.46%   |
| Intel Wireless 7260                                                     | 5         | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.17%   |
| Intel Wireless 3165                                                     | 4         | 1.17%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 1.17%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 1.17%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.87%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.87%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.87%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 0.87%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.87%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.58%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 51.7%   |
| Qualcomm Atheros      | 43        | 24.43%  |
| Realtek Semiconductor | 22        | 12.5%   |
| Broadcom              | 12        | 6.82%   |
| Sierra Wireless       | 3         | 1.7%    |
| MediaTek              | 2         | 1.14%   |
| TP-Link               | 1         | 0.57%   |
| Ralink                | 1         | 0.57%   |
| Edimax Technology     | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 7.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 6.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 6.7%    |
| Intel Wireless 8265 / 8275                                              | 9         | 5.03%   |
| Intel Wireless 8260                                                     | 8         | 4.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.91%   |
| Intel Wireless 7265                                                     | 7         | 3.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 2.79%   |
| Intel Wireless 7260                                                     | 5         | 2.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.23%   |
| Intel Wireless 3165                                                     | 4         | 2.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.68%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.68%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.68%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.68%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.68%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.12%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.12%   |
| Intel WiFi Link 5100                                                    | 2         | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.12%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.12%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.12%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.56%   |
| Sierra Wireless EM7455                                                  | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 63        | 39.87%  |
| Intel                            | 56        | 35.44%  |
| Qualcomm Atheros                 | 13        | 8.23%   |
| Marvell Technology Group         | 7         | 4.43%   |
| Xiaomi                           | 4         | 2.53%   |
| Samsung Electronics              | 4         | 2.53%   |
| Broadcom                         | 4         | 2.53%   |
| Nvidia                           | 2         | 1.27%   |
| JMicron Technology               | 2         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |
| Qualcomm                         | 1         | 0.63%   |
| MediaTek                         | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 24.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 14.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 8.86%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 3.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 3.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 2.53%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.53%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.9%    |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.27%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.27%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 1.27%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.63%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.63%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.63%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.63%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 51.22%  |
| Ethernet | 154       | 46.95%  |
| Unknown  | 5         | 1.52%   |
| Modem    | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 57.59%  |
| Ethernet | 67        | 42.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 142       | 81.61%  |
| 1     | 30        | 17.24%  |
| 0     | 2         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 158       | 90.29%  |
| Yes  | 17        | 9.71%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 45.9%   |
| Qualcomm Atheros Communications | 14        | 11.48%  |
| Broadcom                        | 11        | 9.02%   |
| Realtek Semiconductor           | 8         | 6.56%   |
| Foxconn / Hon Hai               | 7         | 5.74%   |
| Apple                           | 6         | 4.92%   |
| IMC Networks                    | 4         | 3.28%   |
| ASUSTek Computer                | 4         | 3.28%   |
| Lite-On Technology              | 3         | 2.46%   |
| Hewlett-Packard                 | 3         | 2.46%   |
| Dell                            | 2         | 1.64%   |
| Cambridge Silicon Radio         | 2         | 1.64%   |
| Askey Computer                  | 1         | 0.82%   |
| Alps Electric                   | 1         | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 35        | 28.69%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 5.74%   |
| Intel AX201 Bluetooth                                       | 6         | 4.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 4.1%    |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 2.46%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 2.46%   |
| Intel AX200 Bluetooth                                       | 3         | 2.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 2.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 2.46%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 2.46%   |
| ASUS BT-270 Bluetooth Adapter                               | 3         | 2.46%   |
| Apple Bluetooth Host Controller                             | 3         | 2.46%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.64%   |
| Realtek Bluetooth Adapter                                   | 2         | 1.64%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 1.64%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 1.64%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 1.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 2         | 1.64%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 1.64%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.82%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.82%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.82%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.82%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.82%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 0.82%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.82%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.82%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.82%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.82%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.82%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS     | 1         | 0.82%   |
| IMC Networks Bluetooth module                               | 1         | 0.82%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 0.82%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 152       | 80.42%  |
| AMD                               | 23        | 12.17%  |
| Nvidia                            | 8         | 4.23%   |
| Texas Instruments                 | 1         | 0.53%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.53%   |
| Phison Electronics                | 1         | 0.53%   |
| Generalplus Technology            | 1         | 0.53%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.53%   |
| Conexant Systems                  | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 10.18%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 9.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 7.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 6.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 4.42%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 4.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.98%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.98%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 3.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.77%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.33%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.88%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.88%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.88%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.44%   |
| Phison Electronics SoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoun                   | 1         | 0.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.44%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.44%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.44%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 28.64%  |
| SK hynix            | 39        | 19.6%   |
| Unknown             | 20        | 10.05%  |
| Micron Technology   | 19        | 9.55%   |
| Unknown             | 10        | 5.03%   |
| Kingston            | 9         | 4.52%   |
| Crucial             | 6         | 3.02%   |
| Nanya Technology    | 5         | 2.51%   |
| Elpida              | 5         | 2.51%   |
| A-DATA Technology   | 4         | 2.01%   |
| Unknown (ABCD)      | 3         | 1.51%   |
| Transcend           | 3         | 1.51%   |
| Smart               | 3         | 1.51%   |
| Ramaxel Technology  | 3         | 1.51%   |
| Corsair             | 3         | 1.51%   |
| SHARETRONIC         | 2         | 1.01%   |
| Multilaser          | 2         | 1.01%   |
| Team                | 1         | 0.5%    |
| Swissbit            | 1         | 0.5%    |
| Silicon Power       | 1         | 0.5%    |
| Lenovo              | 1         | 0.5%    |
| G.Skill             | 1         | 0.5%    |
| ASint Technology    | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 10        | 4.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 2.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 2.39%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 1.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 1.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.91%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 1.91%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 1.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.44%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.96%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.96%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 0.96%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                 | 2         | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.96%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.96%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.96%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.96%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.96%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.96%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.96%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 89        | 51.74%  |
| DDR4    | 49        | 28.49%  |
| DDR2    | 20        | 11.63%  |
| Unknown | 5         | 2.91%   |
| LPDDR4  | 4         | 2.33%   |
| SDRAM   | 3         | 1.74%   |
| LPDDR3  | 2         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 92.44%  |
| Chip         | 4         | 2.33%   |
| Unknown      | 4         | 2.33%   |
| Row Of Chips | 3         | 1.74%   |
| DIMM         | 2         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 67        | 35.08%  |
| 8192  | 55        | 28.8%   |
| 2048  | 45        | 23.56%  |
| 1024  | 12        | 6.28%   |
| 16384 | 10        | 5.24%   |
| 32768 | 2         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 50        | 26.88%  |
| 2400    | 23        | 12.37%  |
| 667     | 17        | 9.14%   |
| 1333    | 16        | 8.6%    |
| 2667    | 14        | 7.53%   |
| 3200    | 13        | 6.99%   |
| 1067    | 11        | 5.91%   |
| 2133    | 9         | 4.84%   |
| 1334    | 9         | 4.84%   |
| 800     | 7         | 3.76%   |
| Unknown | 7         | 3.76%   |
| 1867    | 4         | 2.15%   |
| 2048    | 2         | 1.08%   |
| 1066    | 2         | 1.08%   |
| 3733    | 1         | 0.54%   |
| 533     | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1020 | 1         | 100%    |

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
| Chicony Electronics                    | 35        | 27.78%  |
| Bison Electronics                      | 18        | 14.29%  |
| Microdia                               | 10        | 7.94%   |
| Realtek Semiconductor                  | 9         | 7.14%   |
| IMC Networks                           | 8         | 6.35%   |
| Sunplus Innovation Technology          | 7         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.76%   |
| Silicon Motion                         | 4         | 3.17%   |
| Quanta                                 | 4         | 3.17%   |
| Lite-On Technology                     | 4         | 3.17%   |
| Alcor Micro                            | 4         | 3.17%   |
| Syntek                                 | 3         | 2.38%   |
| Suyin                                  | 3         | 2.38%   |
| Lenovo                                 | 2         | 1.59%   |
| Apple                                  | 2         | 1.59%   |
| Z-Star Microelectronics                | 1         | 0.79%   |
| Y Media                                | 1         | 0.79%   |
| Supreme Electronics                    | 1         | 0.79%   |
| Luxvisions Innotech Limited            | 1         | 0.79%   |
| Importek                               | 1         | 0.79%   |
| DigiTech                               | 1         | 0.79%   |
| ALi                                    | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 11        | 8.73%   |
| Bison Integrated Camera                                     | 8         | 6.35%   |
| Microdia Integrated_Webcam_HD                               | 5         | 3.97%   |
| Realtek Integrated_Webcam_HD                                | 4         | 3.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 2.38%   |
| Chicony FJ Camera                                           | 3         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 3         | 2.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 2         | 1.59%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 1.59%   |
| Realtek USB Camera                                          | 2         | 1.59%   |
| Lite-On Integrated Camera                                   | 2         | 1.59%   |
| Lenovo Integrated Webcam                                    | 2         | 1.59%   |
| IMC Networks Integrated Webcam                              | 2         | 1.59%   |
| IMC Networks Integrated Camera                              | 2         | 1.59%   |
| Chicony USB 2.0 Camera                                      | 2         | 1.59%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.59%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.59%   |
| Bison HP Webcam-101                                         | 2         | 1.59%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.59%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.79%   |
| Y Media USB Camera                                          | 1         | 0.79%   |
| Syntek Integrated Camera                                    | 1         | 0.79%   |
| Syntek HP Webcam                                            | 1         | 0.79%   |
| Syntek EasyCamera                                           | 1         | 0.79%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.79%   |
| Supreme Integrated Camera                                   | 1         | 0.79%   |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 0.79%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.79%   |
| Sunplus Integrated Camera                                   | 1         | 0.79%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.79%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.79%   |
| Silicon Motion WebCam SCX Series                            | 1         | 0.79%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 0.79%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 0.79%   |
| Silicon Motion ATIV VGA Camera                              | 1         | 0.79%   |
| Realtek USB 2.0 PC Camera                                   | 1         | 0.79%   |
| Realtek Integrated Webcam HD                                | 1         | 0.79%   |
| Realtek Dell EasyCamera                                     | 1         | 0.79%   |
| Quanta Realtek PC Camera                                    | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 45.45%  |
| Elan Microelectronics      | 3         | 13.64%  |
| AuthenTec                  | 3         | 13.64%  |
| Upek                       | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| Shenzhen Goodix Technology | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Fingerprint Cards          | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 13.64%  |
| Validity Sensors Synaptics WBDI                        | 3         | 13.64%  |
| Elan Fingerprint Sensor                                | 3         | 13.64%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.55%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.55%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.55%   |
| Fingerprint Cards FPC Fingerprint Reader               | 1         | 4.55%   |
| AuthenTec AES2810                                      | 1         | 4.55%   |
| AuthenTec AES2660                                      | 1         | 4.55%   |
| AuthenTec AES1660                                      | 1         | 4.55%   |

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
| 1     | 81        | 46.55%  |
| 2     | 43        | 24.71%  |
| 0     | 31        | 17.82%  |
| 3     | 17        | 9.77%   |
| 4     | 2         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 116       | 55.24%  |
| Net/wireless             | 26        | 12.38%  |
| Card reader              | 24        | 11.43%  |
| Fingerprint reader       | 22        | 10.48%  |
| Bluetooth                | 14        | 6.67%   |
| Storage                  | 4         | 1.9%    |
| Sound                    | 2         | 0.95%   |
| Network                  | 1         | 0.48%   |
| Net/ethernet             | 1         | 0.48%   |

