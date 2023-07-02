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

Total: 164

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 140       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 139       | 99.29%  |
| GNOME        | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 140       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 140       | 99.29%  |
| SDDM | 1         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 74        | 52.48%  |
| fr_FR   | 18        | 12.77%  |
| ru_RU   | 11        | 7.8%    |
| de_DE   | 9         | 6.38%   |
| pl_PL   | 6         | 4.26%   |
| es_ES   | 6         | 4.26%   |
| pt_BR   | 4         | 2.84%   |
| Unknown | 4         | 2.84%   |
| nl_NL   | 2         | 1.42%   |
| it_IT   | 2         | 1.42%   |
| zh_CN   | 1         | 0.71%   |
| pt      | 1         | 0.71%   |
| ko_KR   | 1         | 0.71%   |
| fi_FI   | 1         | 0.71%   |
| en      | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 140       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 71        | 50.71%  |
| Cd9660 | 69        | 49.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 140       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 46        | 32.86%  |
| Hewlett-Packard     | 19        | 13.57%  |
| Dell                | 17        | 12.14%  |
| ASUSTek Computer    | 8         | 5.71%   |
| Toshiba             | 7         | 5%      |
| Acer                | 7         | 5%      |
| Samsung Electronics | 6         | 4.29%   |
| Apple               | 5         | 3.57%   |
| Fujitsu             | 4         | 2.86%   |
| Sony                | 3         | 2.14%   |
| Google              | 3         | 2.14%   |
| Packard Bell        | 2         | 1.43%   |
| TUXEDO              | 1         | 0.71%   |
| Timi                | 1         | 0.71%   |
| Plaisio             | 1         | 0.71%   |
| Panasonic           | 1         | 0.71%   |
| MSI                 | 1         | 0.71%   |
| Medion              | 1         | 0.71%   |
| LG Electronics      | 1         | 0.71%   |
| Irbis               | 1         | 0.71%   |
| Intel               | 1         | 0.71%   |
| IGEL Technology     | 1         | 0.71%   |
| HUAWEI              | 1         | 0.71%   |
| Dynabook Europe     | 1         | 0.71%   |
| DNS                 | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Laptop 14-bs0xx                    | 2         | 1.43%   |
| Unknown                               | 2         | 1.43%   |
| TUXEDO Aura 15 Gen1                   | 1         | 0.71%   |
| Toshiba Satellite P300                | 1         | 0.71%   |
| Toshiba Satellite L675D               | 1         | 0.71%   |
| Toshiba Satellite L50-B               | 1         | 0.71%   |
| Toshiba Satellite L40                 | 1         | 0.71%   |
| Toshiba Satellite C845                | 1         | 0.71%   |
| Toshiba Satellite A200                | 1         | 0.71%   |
| Toshiba PORTEGE R700                  | 1         | 0.71%   |
| Timi TM1701                           | 1         | 0.71%   |
| Sony VPCEG15FB                        | 1         | 0.71%   |
| Sony VGN-FZ19VN                       | 1         | 0.71%   |
| Sony SVF14A15CBB                      | 1         | 0.71%   |
| Samsung R530/R730/R540                | 1         | 0.71%   |
| Samsung R520/R522/R620                | 1         | 0.71%   |
| Samsung R468/R418                     | 1         | 0.71%   |
| Samsung 370E4K                        | 1         | 0.71%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.71%   |
| Samsung 275E4E/275E5E                 | 1         | 0.71%   |
| Plaisio Turbo X                       | 1         | 0.71%   |
| Panasonic CF-NX1GDHYS                 | 1         | 0.71%   |
| Packard Bell EasyNote LJ65            | 1         | 0.71%   |
| Packard Bell DOT SE                   | 1         | 0.71%   |
| MSI GE63 Raider RGB 8RE               | 1         | 0.71%   |
| Medion E15302                         | 1         | 0.71%   |
| LG E500-L.A2M4A2                      | 1         | 0.71%   |
| Lenovo ZIUS6                          | 1         | 0.71%   |
| Lenovo Yoga Slim 7 14ITL05 82A3       | 1         | 0.71%   |
| Lenovo ThinkPad X61s 7667WQS          | 1         | 0.71%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05 | 1         | 0.71%   |
| Lenovo ThinkPad X270 20HMS06Q1D       | 1         | 0.71%   |
| Lenovo ThinkPad X230 Tablet 34352TU   | 1         | 0.71%   |
| Lenovo ThinkPad X230 232578G          | 1         | 0.71%   |
| Lenovo ThinkPad X220 4291AN9          | 1         | 0.71%   |
| Lenovo ThinkPad X220 4290DK6          | 1         | 0.71%   |
| Lenovo ThinkPad X220 4286CTO          | 1         | 0.71%   |
| Lenovo ThinkPad X201 36801T6          | 1         | 0.71%   |
| Lenovo ThinkPad X200 74591P0          | 1         | 0.71%   |
| Lenovo ThinkPad X200 2024AY7          | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 32        | 22.86%  |
| Dell Latitude         | 10        | 7.14%   |
| Toshiba Satellite     | 6         | 4.29%   |
| HP Pavilion           | 6         | 4.29%   |
| HP Laptop             | 6         | 4.29%   |
| Dell Inspiron         | 6         | 4.29%   |
| Lenovo IdeaPad        | 5         | 3.57%   |
| HP EliteBook          | 3         | 2.14%   |
| Acer Aspire           | 3         | 2.14%   |
| HP Compaq             | 2         | 1.43%   |
| Fujitsu LIFEBOOK      | 2         | 1.43%   |
| ASUS VivoBook         | 2         | 1.43%   |
| Unknown               | 2         | 1.43%   |
| TUXEDO Aura           | 1         | 0.71%   |
| Toshiba PORTEGE       | 1         | 0.71%   |
| Timi TM1701           | 1         | 0.71%   |
| Sony VPCEG15FB        | 1         | 0.71%   |
| Sony VGN-FZ19VN       | 1         | 0.71%   |
| Sony SVF14A15CBB      | 1         | 0.71%   |
| Samsung R530          | 1         | 0.71%   |
| Samsung R520          | 1         | 0.71%   |
| Samsung R468          | 1         | 0.71%   |
| Samsung 370E4K        | 1         | 0.71%   |
| Samsung 305E4A        | 1         | 0.71%   |
| Samsung 275E4E        | 1         | 0.71%   |
| Plaisio Turbo         | 1         | 0.71%   |
| Panasonic CF-NX1GDHYS | 1         | 0.71%   |
| Packard Bell EasyNote | 1         | 0.71%   |
| Packard Bell DOT      | 1         | 0.71%   |
| MSI GE63              | 1         | 0.71%   |
| Medion E15302         | 1         | 0.71%   |
| LG E500-L.A2M4A2      | 1         | 0.71%   |
| Lenovo ZIUS6          | 1         | 0.71%   |
| Lenovo Yoga           | 1         | 0.71%   |
| Lenovo ThinkBook      | 1         | 0.71%   |
| Lenovo S10-3          | 1         | 0.71%   |
| Lenovo Legion         | 1         | 0.71%   |
| Lenovo G570           | 1         | 0.71%   |
| Lenovo G500           | 1         | 0.71%   |
| Lenovo Flex           | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 16        | 11.43%  |
| 2022 | 13        | 9.29%   |
| 2013 | 12        | 8.57%   |
| 2012 | 12        | 8.57%   |
| 2020 | 9         | 6.43%   |
| 2019 | 9         | 6.43%   |
| 2017 | 9         | 6.43%   |
| 2008 | 9         | 6.43%   |
| 2016 | 7         | 5%      |
| 2010 | 7         | 5%      |
| 2009 | 7         | 5%      |
| 2021 | 6         | 4.29%   |
| 2014 | 6         | 4.29%   |
| 2018 | 5         | 3.57%   |
| 2015 | 5         | 3.57%   |
| 2007 | 5         | 3.57%   |
| 2023 | 2         | 1.43%   |
| 2006 | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 140       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 96.43%  |
| Yes  | 5         | 3.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 50        | 35.71%  |
| 4.01-8.0    | 46        | 32.86%  |
| 16.01-24.0  | 24        | 17.14%  |
| 2.01-3.0    | 13        | 9.29%   |
| 32.01-64.0  | 4         | 2.86%   |
| 3.01-4.0    | 2         | 1.43%   |
| 64.01-256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 90        | 64.29%  |
| 0.51-1.0 | 39        | 27.86%  |
| 1.01-2.0 | 9         | 6.43%   |
| 2.01-3.0 | 2         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 75.18%  |
| 2      | 19        | 13.48%  |
| 0      | 11        | 7.8%    |
| 3      | 5         | 3.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 65%     |
| Yes       | 49        | 35%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 87.86%  |
| No        | 17        | 12.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 96.43%  |
| No        | 5         | 3.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 67.86%  |
| No        | 45        | 32.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 23        | 16.43%  |
| Brazil      | 13        | 9.29%   |
| Russia      | 12        | 8.57%   |
| Poland      | 12        | 8.57%   |
| Germany     | 12        | 8.57%   |
| Indonesia   | 6         | 4.29%   |
| Spain       | 5         | 3.57%   |
| Italy       | 5         | 3.57%   |
| UK          | 4         | 2.86%   |
| Romania     | 4         | 2.86%   |
| France      | 4         | 2.86%   |
| Canada      | 4         | 2.86%   |
| Turkey      | 3         | 2.14%   |
| India       | 3         | 2.14%   |
| Australia   | 3         | 2.14%   |
| Netherlands | 2         | 1.43%   |
| Mexico      | 2         | 1.43%   |
| Israel      | 2         | 1.43%   |
| Hungary     | 2         | 1.43%   |
| China       | 2         | 1.43%   |
| Bulgaria    | 2         | 1.43%   |
| Syria       | 1         | 0.71%   |
| Switzerland | 1         | 0.71%   |
| South Korea | 1         | 0.71%   |
| Slovenia    | 1         | 0.71%   |
| Slovakia    | 1         | 0.71%   |
| Portugal    | 1         | 0.71%   |
| Philippines | 1         | 0.71%   |
| Lithuania   | 1         | 0.71%   |
| Ireland     | 1         | 0.71%   |
| Finland     | 1         | 0.71%   |
| Czechia     | 1         | 0.71%   |
| Colombia    | 1         | 0.71%   |
| Chile       | 1         | 0.71%   |
| Bolivia     | 1         | 0.71%   |
| Belarus     | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 4         | 2.84%   |
| Berlin             | 3         | 2.13%   |
| Wroclaw            | 2         | 1.42%   |
| Warsaw             | 2         | 1.42%   |
| Valencia           | 2         | 1.42%   |
| Sydney             | 2         | 1.42%   |
| Montreal           | 2         | 1.42%   |
| Milan              | 2         | 1.42%   |
| Irkutsk            | 2         | 1.42%   |
| Yeosu              | 1         | 0.71%   |
| Yekaterinburg      | 1         | 0.71%   |
| Woodbridge         | 1         | 0.71%   |
| West Plains        | 1         | 0.71%   |
| Wausau             | 1         | 0.71%   |
| Vitória           | 1         | 0.71%   |
| Vitebsk            | 1         | 0.71%   |
| Vilnius            | 1         | 0.71%   |
| Villemomble        | 1         | 0.71%   |
| Villefontaine      | 1         | 0.71%   |
| Victoria           | 1         | 0.71%   |
| Ulyanovsk          | 1         | 0.71%   |
| Twinsburg          | 1         | 0.71%   |
| Trindade           | 1         | 0.71%   |
| Tomasikovo         | 1         | 0.71%   |
| Tolyatti           | 1         | 0.71%   |
| Tata               | 1         | 0.71%   |
| Targoviste         | 1         | 0.71%   |
| Surabaya           | 1         | 0.71%   |
| St. Jean Baptiste  | 1         | 0.71%   |
| St Petersburg      | 1         | 0.71%   |
| South Goa          | 1         | 0.71%   |
| Sofia              | 1         | 0.71%   |
| Sobral             | 1         | 0.71%   |
| Shenzhen           | 1         | 0.71%   |
| Seville            | 1         | 0.71%   |
| Sete Lagoas        | 1         | 0.71%   |
| Sesto San Giovanni | 1         | 0.71%   |
| Selma              | 1         | 0.71%   |
| Schneverdingen     | 1         | 0.71%   |
| Santiago           | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 24     | 15.03%  |
| Seagate             | 17        | 18     | 11.11%  |
| Toshiba             | 16        | 17     | 10.46%  |
| WDC                 | 13        | 14     | 8.5%    |
| Hitachi             | 11        | 11     | 7.19%   |
| SanDisk             | 10        | 10     | 6.54%   |
| Kingston            | 9         | 9      | 5.88%   |
| Crucial             | 7         | 9      | 4.58%   |
| HGST                | 6         | 9      | 3.92%   |
| Intel               | 5         | 5      | 3.27%   |
| SK hynix            | 3         | 3      | 1.96%   |
| Micron Technology   | 3         | 3      | 1.96%   |
| China               | 3         | 3      | 1.96%   |
| A-DATA Technology   | 3         | 3      | 1.96%   |
| Transcend           | 2         | 2      | 1.31%   |
| OCZ                 | 2         | 2      | 1.31%   |
| Gigabyte Technology | 2         | 2      | 1.31%   |
| Verbatim            | 1         | 1      | 0.65%   |
| V-GeN               | 1         | 1      | 0.65%   |
| SPCC                | 1         | 1      | 0.65%   |
| PNY                 | 1         | 1      | 0.65%   |
| Plextor             | 1         | 1      | 0.65%   |
| Phison              | 1         | 1      | 0.65%   |
| Patriot             | 1         | 1      | 0.65%   |
| Netac               | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| Kingmax             | 1         | 1      | 0.65%   |
| Intenso             | 1         | 1      | 0.65%   |
| GOODRAM             | 1         | 1      | 0.65%   |
| Goldenfir           | 1         | 1      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |
| Dogfish             | 1         | 1      | 0.65%   |
| Biostar             | 1         | 1      | 0.65%   |
| BHT                 | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 3         | 1.92%   |
| Crucial CT480BX500SSD1 480GB         | 3         | 1.92%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.28%   |
| Seagate ST9500325AS 500GB            | 2         | 1.28%   |
| Seagate ST9250410AS 250GB            | 2         | 1.28%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.28%   |
| Samsung HM321HI 320GB                | 2         | 1.28%   |
| Kingston SV300S37A60G 64GB           | 2         | 1.28%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 1.28%   |
| Hitachi HTS542525K9A300 250GB        | 2         | 1.28%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.28%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 2         | 1.28%   |
| WDC WDS500G2B0B-00YS70 500GB         | 1         | 0.64%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.64%   |
| WDC WDS100T2G0A-00JH30 1TB           | 1         | 0.64%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.64%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.64%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.64%   |
| WDC WD30PURZ-85AKKY0 3TB             | 1         | 0.64%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.64%   |
| WDC WD1600BEVT-60ZCT0 160GB          | 1         | 0.64%   |
| WDC WD1600BEVS-22VAT0 160GB          | 1         | 0.64%   |
| WDC WD10JPVX-80JC3T0 1TB             | 1         | 0.64%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.64%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.64%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.64%   |
| Verbatim Vi550 S3 SSD 512GB          | 1         | 0.64%   |
| V-GeN V-GEN08SM22AR256SDK 256GB      | 1         | 0.64%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.64%   |
| Transcend TS120GMTS420S 120GB        | 1         | 0.64%   |
| Toshiba THNSNJ256G8NY 256GB          | 1         | 0.64%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.64%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.64%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.64%   |
| Toshiba MK8034GSX 80GB               | 1         | 0.64%   |
| Toshiba MK6461GSYN 640GB             | 1         | 0.64%   |
| Toshiba MK5065GSXF 500GB             | 1         | 0.64%   |
| Toshiba MK5059GSXP 500GB             | 1         | 0.64%   |
| Toshiba MK3263GSXN 320GB             | 1         | 0.64%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 27.42%  |
| Toshiba             | 14        | 15     | 22.58%  |
| Hitachi             | 11        | 11     | 17.74%  |
| WDC                 | 9         | 9      | 14.52%  |
| HGST                | 6         | 9      | 9.68%   |
| Samsung Electronics | 4         | 5      | 6.45%   |
| Fujitsu             | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 10        | 10     | 14.08%  |
| Samsung Electronics | 10        | 10     | 14.08%  |
| Kingston            | 8         | 8      | 11.27%  |
| Crucial             | 7         | 9      | 9.86%   |
| Intel               | 4         | 4      | 5.63%   |
| China               | 3         | 3      | 4.23%   |
| WDC                 | 2         | 3      | 2.82%   |
| OCZ                 | 2         | 2      | 2.82%   |
| Micron Technology   | 2         | 2      | 2.82%   |
| Gigabyte Technology | 2         | 2      | 2.82%   |
| A-DATA Technology   | 2         | 2      | 2.82%   |
| Verbatim            | 1         | 1      | 1.41%   |
| V-GeN               | 1         | 1      | 1.41%   |
| Transcend           | 1         | 1      | 1.41%   |
| Toshiba             | 1         | 1      | 1.41%   |
| SPCC                | 1         | 1      | 1.41%   |
| SK hynix            | 1         | 1      | 1.41%   |
| PNY                 | 1         | 1      | 1.41%   |
| Plextor             | 1         | 1      | 1.41%   |
| Patriot             | 1         | 1      | 1.41%   |
| Netac               | 1         | 1      | 1.41%   |
| KingSpec            | 1         | 1      | 1.41%   |
| Kingmax             | 1         | 1      | 1.41%   |
| Intenso             | 1         | 1      | 1.41%   |
| GOODRAM             | 1         | 1      | 1.41%   |
| Goldenfir           | 1         | 1      | 1.41%   |
| Dogfish             | 1         | 1      | 1.41%   |
| Biostar             | 1         | 1      | 1.41%   |
| BHT                 | 1         | 1      | 1.41%   |
| Apple               | 1         | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 65        | 74     | 45.14%  |
| HDD  | 60        | 68     | 41.67%  |
| NVMe | 19        | 20     | 13.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 142    | 85.71%  |
| NVMe | 19        | 20     | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 101       | 116    | 82.79%  |
| 0.51-1.0   | 19        | 24     | 15.57%  |
| 2.01-3.0   | 1         | 1      | 0.82%   |
| 1.01-2.0   | 1         | 1      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 67        | 47.86%  |
| 101-250    | 27        | 19.29%  |
| 251-500    | 20        | 14.29%  |
| 51-100     | 16        | 11.43%  |
| 501-1000   | 6         | 4.29%   |
| 21-50      | 3         | 2.14%   |
| Unknown    | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 137       | 97.86%  |
| 21-50   | 1         | 0.71%   |
| 101-250 | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 2         | 2      | 5.71%   |
| Hitachi HTS542525K9A300 250GB       | 2         | 2      | 5.71%   |
| WDC WD30PURZ-85AKKY0 3TB            | 1         | 1      | 2.86%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 2.86%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 2.86%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 2.86%   |
| Toshiba MK1229GSG 120GB             | 1         | 1      | 2.86%   |
| SK hynix SC210 mSATA 256GB          | 1         | 1      | 2.86%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 2.86%   |
| Seagate ST9160827AS 160GB           | 1         | 1      | 2.86%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 2.86%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 2.86%   |
| Seagate ST500LM000-SSHD-8GB         | 1         | 1      | 2.86%   |
| Seagate ST500LM000-1EJ162 500GB     | 1         | 1      | 2.86%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 2.86%   |
| Seagate ST320LT012-9WS14C 320GB     | 1         | 2      | 2.86%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 2.86%   |
| OCZ AGILITY3 120GB                  | 1         | 1      | 2.86%   |
| Kingston SV300S37A60G 64GB          | 1         | 1      | 2.86%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 2.86%   |
| Hitachi HTS727550A9E364 500GB       | 1         | 1      | 2.86%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 2.86%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 2.86%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 2.86%   |
| Hitachi HTS541616J9SA00 160GB       | 1         | 1      | 2.86%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.86%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.86%   |
| HGST HTS541075A7E630 752GB          | 1         | 1      | 2.86%   |
| HGST HTS541010A9E680 1TB            | 1         | 2      | 2.86%   |
| Crucial M4-CT256M4SSD3 256GB        | 1         | 1      | 2.86%   |
| Crucial CT500MX500SSD1 500GB        | 1         | 2      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 28.57%  |
| Hitachi             | 7         | 7      | 20%     |
| Toshiba             | 5         | 5      | 14.29%  |
| HGST                | 4         | 5      | 11.43%  |
| WDC                 | 2         | 2      | 5.71%   |
| Crucial             | 2         | 3      | 5.71%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| OCZ                 | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 34.48%  |
| Hitachi             | 7         | 7      | 24.14%  |
| Toshiba             | 5         | 5      | 17.24%  |
| HGST                | 4         | 5      | 13.79%  |
| WDC                 | 2         | 2      | 6.9%    |
| Samsung Electronics | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 31     | 82.35%  |
| SSD  | 6         | 7      | 17.65%  |

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
| Works   | 101       | 123    | 74.26%  |
| Malfunc | 34        | 38     | 25%     |
| Failed  | 1         | 1      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 111       | 75.51%  |
| AMD                              | 11        | 7.48%   |
| Samsung Electronics              | 8         | 5.44%   |
| SanDisk                          | 5         | 3.4%    |
| Nvidia                           | 3         | 2.04%   |
| SK hynix                         | 2         | 1.36%   |
| Toshiba                          | 1         | 0.68%   |
| Silicon Motion                   | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| Phison Electronics               | 1         | 0.68%   |
| Micron Technology                | 1         | 0.68%   |
| Kingston Technology Company      | 1         | 0.68%   |
| ADATA Technology                 | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 10.56%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 8.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 8.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 6.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 4.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 3.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 3.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 2.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.48%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.86%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 2         | 1.24%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.24%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.24%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.24%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.62%   |
| SK hynix hynix unknown                                                           | 1         | 0.62%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.62%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.62%   |
| Sandisk WD Black SN770 NVMe SSD                                                  | 1         | 0.62%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.62%   |
| SanDisk PC SN530 NVMe SSD                                                        | 1         | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.62%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.62%   |
| Micron 2200S NVMe SSD                                                            | 1         | 0.62%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 114       | 74.03%  |
| NVMe | 18        | 11.69%  |
| IDE  | 18        | 11.69%  |
| RAID | 4         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 89.29%  |
| AMD    | 15        | 10.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 4.29%   |
| Intel CPU Version                           | 5         | 3.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 3.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 2.86%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 2.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 2.14%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 2.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.43%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.43%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.43%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.43%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 1.43%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz        | 2         | 1.43%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.43%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 1.43%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.43%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.71%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.71%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 1         | 0.71%   |
| Intel Genuine CPU                           | 1         | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.71%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.71%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.71%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.71%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.71%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.71%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 0.71%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 0.71%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 1         | 0.71%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 30.71%  |
| Intel Core i7           | 25        | 17.86%  |
| Intel Celeron           | 16        | 11.43%  |
| Intel Core 2 Duo        | 14        | 10%     |
| Other                   | 9         | 6.43%   |
| Intel Core i3           | 8         | 5.71%   |
| AMD Ryzen 7             | 5         | 3.57%   |
| Intel Atom              | 4         | 2.86%   |
| Intel Genuine           | 2         | 1.43%   |
| AMD Ryzen 5             | 2         | 1.43%   |
| Intel Pentium Dual-Core | 1         | 0.71%   |
| Intel Pentium Dual      | 1         | 0.71%   |
| Intel Pentium           | 1         | 0.71%   |
| Intel Core 2            | 1         | 0.71%   |
| Intel Celeron D         | 1         | 0.71%   |
| AMD Ryzen Embedded      | 1         | 0.71%   |
| AMD Phenom II           | 1         | 0.71%   |
| AMD E1                  | 1         | 0.71%   |
| AMD E                   | 1         | 0.71%   |
| AMD Athlon              | 1         | 0.71%   |
| AMD A8                  | 1         | 0.71%   |
| AMD A4                  | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 86        | 61.43%  |
| 4       | 26        | 18.57%  |
| Unknown | 16        | 11.43%  |
| 8       | 4         | 2.86%   |
| 1       | 4         | 2.86%   |
| 16      | 2         | 1.43%   |
| 12      | 1         | 0.71%   |
| 6       | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 136       | 97.14%  |
| 2      | 4         | 2.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 84        | 60%     |
| 1       | 37        | 26.43%  |
| Unknown | 19        | 13.57%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 18        | 12.86%  |
| SandyBridge   | 16        | 11.43%  |
| IvyBridge     | 16        | 11.43%  |
| Core          | 14        | 10%     |
| Haswell       | 11        | 7.86%   |
| Penryn        | 10        | 7.14%   |
| Skylake       | 9         | 6.43%   |
| Westmere      | 7         | 5%      |
| Broadwell     | 7         | 5%      |
| Silvermont    | 6         | 4.29%   |
| Bonnell       | 5         | 3.57%   |
| Zen+          | 3         | 2.14%   |
| TigerLake     | 3         | 2.14%   |
| Zen 3         | 2         | 1.43%   |
| Zen 2         | 2         | 1.43%   |
| Goldmont plus | 2         | 1.43%   |
| Excavator     | 2         | 1.43%   |
| Bobcat        | 2         | 1.43%   |
| Zen           | 1         | 0.71%   |
| K10 Llano     | 1         | 0.71%   |
| K10           | 1         | 0.71%   |
| Goldmont      | 1         | 0.71%   |
| Unknown       | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 113       | 70.19%  |
| AMD                              | 24        | 14.91%  |
| Nvidia                           | 23        | 14.29%  |
| Silicon Integrated Systems [SiS] | 1         | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 9.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 8.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 5.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 5.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 4.07%   |
| Intel HD Graphics 5500                                                                   | 7         | 4.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 4.07%   |
| Intel UHD Graphics 620                                                                   | 6         | 3.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.91%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 2.33%   |
| Intel HD Graphics 620                                                                    | 3         | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.16%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.16%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.16%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.16%   |
| AMD Renoir                                                                               | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.58%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.58%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.58%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.58%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.58%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.58%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.58%   |
| Nvidia GK208M [GeForce GT 735M]                                                          | 1         | 0.58%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.58%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 0.58%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 53.57%  |
| 2 x Intel      | 18        | 12.86%  |
| 1 x AMD        | 17        | 12.14%  |
| Intel + Nvidia | 15        | 10.71%  |
| 1 x Nvidia     | 6         | 4.29%   |
| Intel + AMD    | 5         | 3.57%   |
| 2 x Nvidia     | 1         | 0.71%   |
| 2 x AMD        | 1         | 0.71%   |
| 1 x SiS        | 1         | 0.71%   |
| AMD + Nvidia   | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 128       | 91.43%  |
| Proprietary | 7         | 5%      |
| Unknown     | 5         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 90%     |
| 0.01-0.5   | 10        | 7.14%   |
| 0.51-1.0   | 3         | 2.14%   |
| 7.01-8.0   | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 31.25%  |
| Samsung Electronics     | 4         | 12.5%   |
| Chimei Innolux          | 4         | 12.5%   |
| LG Display              | 3         | 9.38%   |
| BOE                     | 2         | 6.25%   |
| LG Philips              | 1         | 3.13%   |
| Lenovo                  | 1         | 3.13%   |
| InfoVision              | 1         | 3.13%   |
| Goldstar                | 1         | 3.13%   |
| CPT                     | 1         | 3.13%   |
| Chi Mei Optoelectronics | 1         | 3.13%   |
| Apple                   | 1         | 3.13%   |
| AOC                     | 1         | 3.13%   |
| Unknown                 | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch      | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch     | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 3.13%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch        | 1         | 3.13%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch            | 1         | 3.13%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch              | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch                 | 1         | 3.13%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch              | 1         | 3.13%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1         | 3.13%   |
| CPT LCD Monitor CPT1BC0 1024x600 220x120mm 9.9-inch                      | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch         | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 3.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1465 1366x768 310x180mm 14.1-inch | 1         | 3.13%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                    | 1         | 3.13%   |
| BOE LCD Monitor BOE0696 1366x768 310x170mm 13.9-inch                     | 1         | 3.13%   |
| AU Optronics LCD Monitor AUOB78F 1920x1080 340x190mm 15.3-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO33ED 1920x1080 340x190mm 15.3-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO333C 1366x768 310x170mm 13.9-inch            | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO323E 1600x900 310x170mm 13.9-inch            | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch            | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 340x190mm 15.3-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch            | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 380x210mm 17.1-inch           | 1         | 3.13%   |
| Apple Color LCD APPA014 2560x1600 290x180mm 13.4-inch                    | 1         | 3.13%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                        | 1         | 3.13%   |
| Unknown                                                                  | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 13        | 41.94%  |
| 1920x1080 (FHD) | 10        | 32.26%  |
| 2560x1600       | 2         | 6.45%   |
| 1600x900 (HD+)  | 2         | 6.45%   |
| 2560x1440 (QHD) | 1         | 3.23%   |
| 1400x1050       | 1         | 3.23%   |
| 1280x800 (WXGA) | 1         | 3.23%   |
| 1024x600        | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 12        | 37.5%   |
| 13      | 11        | 34.38%  |
| 21      | 2         | 6.25%   |
| 14      | 2         | 6.25%   |
| 31      | 1         | 3.13%   |
| 19      | 1         | 3.13%   |
| 17      | 1         | 3.13%   |
| 9       | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 62.5%   |
| 201-300     | 6         | 18.75%  |
| 401-500     | 3         | 9.38%   |
| 601-700     | 1         | 3.13%   |
| 351-400     | 1         | 3.13%   |
| Unknown     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 25        | 86.21%  |
| 16/10   | 2         | 6.9%    |
| 4/3     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 12        | 37.5%   |
| 81-90          | 9         | 28.13%  |
| 71-80          | 3         | 9.38%   |
| 201-250        | 2         | 6.25%   |
| 351-500        | 1         | 3.13%   |
| 41-50          | 1         | 3.13%   |
| 151-200        | 1         | 3.13%   |
| 121-130        | 1         | 3.13%   |
| 101-110        | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 46.88%  |
| 121-160 | 12        | 37.5%   |
| 51-100  | 3         | 9.38%   |
| 161-240 | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 125       | 89.29%  |
| 0     | 8         | 5.71%   |
| 2     | 7         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 37.09%  |
| Realtek Semiconductor             | 57        | 26.76%  |
| Qualcomm Atheros                  | 36        | 16.9%   |
| Broadcom                          | 12        | 5.63%   |
| Marvell Technology Group          | 7         | 3.29%   |
| Sierra Wireless                   | 4         | 1.88%   |
| Xiaomi                            | 3         | 1.41%   |
| Samsung Electronics               | 3         | 1.41%   |
| Ericsson Business Mobile Networks | 3         | 1.41%   |
| Nvidia                            | 2         | 0.94%   |
| MediaTek                          | 2         | 0.94%   |
| TP-Link                           | 1         | 0.47%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.47%   |
| Qualcomm                          | 1         | 0.47%   |
| JMicron Technology                | 1         | 0.47%   |
| Edimax Technology                 | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 32        | 11.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 5.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 4.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 3.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 3.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.89%   |
| Intel Wireless 8260                                                     | 7         | 2.53%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.17%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 1.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.81%   |
| Intel Wireless 7265                                                     | 5         | 1.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.44%   |
| Intel Wireless 7260                                                     | 4         | 1.44%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.08%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.08%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 1.08%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 1.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.08%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.72%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.72%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 52.45%  |
| Qualcomm Atheros      | 31        | 21.68%  |
| Realtek Semiconductor | 21        | 14.69%  |
| Broadcom              | 10        | 6.99%   |
| Sierra Wireless       | 3         | 2.1%    |
| TP-Link               | 1         | 0.7%    |
| MediaTek              | 1         | 0.7%    |
| Edimax Technology     | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 7.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 6.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 5.48%   |
| Intel Wireless 8260                                                     | 7         | 4.79%   |
| Intel Wireless 8265 / 8275                                              | 6         | 4.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 3.42%   |
| Intel Wireless 7265                                                     | 5         | 3.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.74%   |
| Intel Wireless 7260                                                     | 4         | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.05%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.05%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 2.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 2.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 2.05%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2.05%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 1.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.37%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 1.37%   |
| Intel Wireless 3165                                                     | 2         | 1.37%   |
| Intel WiFi Link 5100                                                    | 2         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.37%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.37%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.68%   |
| Sierra Wireless EM7455                                                  | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.68%   |
| Realtek Bluetooth Adapter                                               | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 47        | 37.3%   |
| Intel                            | 46        | 36.51%  |
| Qualcomm Atheros                 | 11        | 8.73%   |
| Marvell Technology Group         | 7         | 5.56%   |
| Xiaomi                           | 3         | 2.38%   |
| Samsung Electronics              | 3         | 2.38%   |
| Broadcom                         | 3         | 2.38%   |
| Nvidia                           | 2         | 1.59%   |
| Silicon Integrated Systems [SiS] | 1         | 0.79%   |
| Qualcomm                         | 1         | 0.79%   |
| MediaTek                         | 1         | 0.79%   |
| JMicron Technology               | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 25.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 10.32%  |
| Intel Ethernet Connection I219-LM                                 | 6         | 4.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 3.97%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 2.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.38%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.38%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 2.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.59%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.79%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.79%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.79%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.79%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 51.33%  |
| Ethernet | 123       | 46.77%  |
| Unknown  | 4         | 1.52%   |
| Modem    | 1         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 59.06%  |
| Ethernet | 52        | 40.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 113       | 80.71%  |
| 1     | 25        | 17.86%  |
| 0     | 2         | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 128       | 90.78%  |
| Yes  | 13        | 9.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 45.26%  |
| Qualcomm Atheros Communications | 11        | 11.58%  |
| Broadcom                        | 9         | 9.47%   |
| Realtek Semiconductor           | 7         | 7.37%   |
| Foxconn / Hon Hai               | 6         | 6.32%   |
| Apple                           | 5         | 5.26%   |
| IMC Networks                    | 3         | 3.16%   |
| ASUSTek Computer                | 3         | 3.16%   |
| Hewlett-Packard                 | 2         | 2.11%   |
| Dell                            | 2         | 2.11%   |
| Lite-On Technology              | 1         | 1.05%   |
| Cambridge Silicon Radio         | 1         | 1.05%   |
| Askey Computer                  | 1         | 1.05%   |
| Alps Electric                   | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 26.32%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 5         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 3.16%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 3.16%   |
| Intel AX201 Bluetooth                                       | 3         | 3.16%   |
| Intel AX200 Bluetooth                                       | 3         | 3.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 3.16%   |
| Apple Bluetooth Host Controller                             | 3         | 3.16%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 2.11%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 2.11%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 2.11%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 2.11%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 2         | 2.11%   |
| ASUS BT-270 Bluetooth Adapter                               | 2         | 2.11%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.05%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 1.05%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 1.05%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.05%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 1.05%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.05%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 1.05%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.05%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.05%   |
| IMC Networks Bluetooth module                               | 1         | 1.05%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 1.05%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.05%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.05%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.05%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 121       | 79.61%  |
| AMD                               | 18        | 11.84%  |
| Nvidia                            | 7         | 4.61%   |
| Texas Instruments                 | 1         | 0.66%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.66%   |
| Phison Electronics                | 1         | 0.66%   |
| Generalplus Technology            | 1         | 0.66%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.66%   |
| Conexant Systems                  | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 9.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 9.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 7.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 5.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 5.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.95%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.3%    |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.2%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.1%    |
| AMD High Definition Audio Controller                                                              | 2         | 1.1%    |
| AMD FCH Azalia Controller                                                                         | 2         | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.1%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.55%   |
| Phison Electronics SoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoun                   | 1         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.55%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.55%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.55%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                                          | 1         | 0.55%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 27.22%  |
| SK hynix            | 30        | 18.99%  |
| Unknown             | 17        | 10.76%  |
| Micron Technology   | 14        | 8.86%   |
| Unknown             | 10        | 6.33%   |
| Kingston            | 8         | 5.06%   |
| Crucial             | 6         | 3.8%    |
| Nanya Technology    | 5         | 3.16%   |
| Smart               | 3         | 1.9%    |
| Ramaxel Technology  | 3         | 1.9%    |
| Elpida              | 3         | 1.9%    |
| Corsair             | 3         | 1.9%    |
| A-DATA Technology   | 3         | 1.9%    |
| Unknown (ABCD)      | 2         | 1.27%   |
| Transcend           | 2         | 1.27%   |
| Swissbit            | 1         | 0.63%   |
| Silicon Power       | 1         | 0.63%   |
| SHARETRONIC         | 1         | 0.63%   |
| Multilaser          | 1         | 0.63%   |
| G.Skill             | 1         | 0.63%   |
| ASint Technology    | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 10        | 6.02%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 3.01%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 2.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 2.41%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 1.81%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.81%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.81%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.2%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 2         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 1.2%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.2%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.2%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.2%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.2%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s            | 2         | 1.2%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.2%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.2%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.6%    |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 1         | 0.6%    |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 1         | 0.6%    |
| Swissbit RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.6%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.6%    |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.6%    |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 667MT/s             | 1         | 0.6%    |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.6%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.6%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.6%    |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.6%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 70        | 51.09%  |
| DDR4    | 38        | 27.74%  |
| DDR2    | 17        | 12.41%  |
| Unknown | 4         | 2.92%   |
| SDRAM   | 3         | 2.19%   |
| LPDDR4  | 3         | 2.19%   |
| LPDDR3  | 2         | 1.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 127       | 92.03%  |
| Chip         | 4         | 2.9%    |
| Unknown      | 4         | 2.9%    |
| Row Of Chips | 2         | 1.45%   |
| DIMM         | 1         | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 51        | 33.77%  |
| 8192  | 43        | 28.48%  |
| 2048  | 38        | 25.17%  |
| 16384 | 9         | 5.96%   |
| 1024  | 9         | 5.96%   |
| 32768 | 1         | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 37        | 25.17%  |
| 2400    | 17        | 11.56%  |
| 667     | 15        | 10.2%   |
| 1333    | 12        | 8.16%   |
| 2667    | 11        | 7.48%   |
| 3200    | 9         | 6.12%   |
| 1067    | 9         | 6.12%   |
| 2133    | 8         | 5.44%   |
| 1334    | 8         | 5.44%   |
| 800     | 6         | 4.08%   |
| Unknown | 6         | 4.08%   |
| 1867    | 4         | 2.72%   |
| 2048    | 2         | 1.36%   |
| 3733    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| 533     | 1         | 0.68%   |

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
| Chicony Electronics                    | 25        | 25.77%  |
| Bison Electronics                      | 15        | 15.46%  |
| Microdia                               | 9         | 9.28%   |
| Realtek Semiconductor                  | 7         | 7.22%   |
| Sunplus Innovation Technology          | 6         | 6.19%   |
| IMC Networks                           | 5         | 5.15%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.15%   |
| Quanta                                 | 4         | 4.12%   |
| Lite-On Technology                     | 4         | 4.12%   |
| Silicon Motion                         | 3         | 3.09%   |
| Syntek                                 | 2         | 2.06%   |
| Suyin                                  | 2         | 2.06%   |
| Lenovo                                 | 2         | 2.06%   |
| Z-Star Microelectronics                | 1         | 1.03%   |
| Y Media                                | 1         | 1.03%   |
| Supreme Electronics                    | 1         | 1.03%   |
| Luxvisions Innotech Limited            | 1         | 1.03%   |
| DigiTech                               | 1         | 1.03%   |
| Apple                                  | 1         | 1.03%   |
| ALi                                    | 1         | 1.03%   |
| Alcor Micro                            | 1         | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 8         | 8.25%   |
| Chicony Integrated Camera                                   | 6         | 6.19%   |
| Microdia Integrated_Webcam_HD                               | 5         | 5.15%   |
| Realtek Integrated_Webcam_HD                                | 4         | 4.12%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 3.09%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 2.06%   |
| Lite-On Integrated Camera                                   | 2         | 2.06%   |
| Lenovo Integrated Webcam                                    | 2         | 2.06%   |
| IMC Networks Integrated Webcam                              | 2         | 2.06%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.06%   |
| Chicony FJ Camera                                           | 2         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 2         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 2.06%   |
| Bison Lenovo EasyCamera                                     | 2         | 2.06%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 1.03%   |
| Y Media USB Camera                                          | 1         | 1.03%   |
| Syntek HP Webcam                                            | 1         | 1.03%   |
| Syntek EasyCamera                                           | 1         | 1.03%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.03%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.03%   |
| Supreme Integrated Camera                                   | 1         | 1.03%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.03%   |
| Sunplus Integrated Camera                                   | 1         | 1.03%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.03%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 1.03%   |
| Silicon Motion WebCam SCX Series                            | 1         | 1.03%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 1.03%   |
| Silicon Motion ATIV VGA Camera                              | 1         | 1.03%   |
| Realtek USB 2.0 PC Camera                                   | 1         | 1.03%   |
| Realtek Integrated Webcam HD                                | 1         | 1.03%   |
| Realtek Dell EasyCamera                                     | 1         | 1.03%   |
| Quanta Realtek PC Camera                                    | 1         | 1.03%   |
| Quanta Realtek DMFT RGB                                     | 1         | 1.03%   |
| Quanta HD WebCam                                            | 1         | 1.03%   |
| Quanta HD Camera                                            | 1         | 1.03%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.03%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.03%   |
| Microdia Integrated Webcam                                  | 1         | 1.03%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.03%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 35.29%  |
| Elan Microelectronics      | 3         | 17.65%  |
| AuthenTec                  | 3         | 17.65%  |
| Upek                       | 2         | 11.76%  |
| STMicroelectronics         | 1         | 5.88%   |
| Shenzhen Goodix Technology | 1         | 5.88%   |
| LighTuning Technology      | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan Fingerprint Sensor                                | 3         | 17.65%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 11.76%  |
| Validity Sensors Synaptics WBDI                        | 2         | 11.76%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 11.76%  |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.88%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.88%   |
| AuthenTec AES2810                                      | 1         | 5.88%   |
| AuthenTec AES2660                                      | 1         | 5.88%   |
| AuthenTec AES1660                                      | 1         | 5.88%   |

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
| 1     | 66        | 47.14%  |
| 2     | 34        | 24.29%  |
| 0     | 25        | 17.86%  |
| 3     | 14        | 10%     |
| 4     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 91        | 55.49%  |
| Net/wireless             | 22        | 13.41%  |
| Fingerprint reader       | 17        | 10.37%  |
| Card reader              | 17        | 10.37%  |
| Bluetooth                | 11        | 6.71%   |
| Storage                  | 4         | 2.44%   |
| Network                  | 1         | 0.61%   |
| Net/ethernet             | 1         | 0.61%   |

