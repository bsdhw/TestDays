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

Total: 148

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 126       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 125       | 99.21%  |
| GNOME        | 1         | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 126       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 126       | 99.21%  |
| SDDM | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 67        | 52.76%  |
| fr_FR   | 16        | 12.6%   |
| ru_RU   | 11        | 8.66%   |
| de_DE   | 9         | 7.09%   |
| es_ES   | 5         | 3.94%   |
| pt_BR   | 4         | 3.15%   |
| pl_PL   | 4         | 3.15%   |
| Unknown | 4         | 3.15%   |
| zh_CN   | 1         | 0.79%   |
| pt      | 1         | 0.79%   |
| nl_NL   | 1         | 0.79%   |
| ko_KR   | 1         | 0.79%   |
| it_IT   | 1         | 0.79%   |
| fi_FI   | 1         | 0.79%   |
| en      | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 126       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 63        | 50%     |
| Cd9660 | 63        | 50%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 126       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 43        | 34.13%  |
| Dell                | 15        | 11.9%   |
| Hewlett-Packard     | 14        | 11.11%  |
| ASUSTek Computer    | 8         | 6.35%   |
| Toshiba             | 7         | 5.56%   |
| Acer                | 6         | 4.76%   |
| Samsung Electronics | 5         | 3.97%   |
| Apple               | 5         | 3.97%   |
| Fujitsu             | 4         | 3.17%   |
| Sony                | 3         | 2.38%   |
| Google              | 3         | 2.38%   |
| Packard Bell        | 2         | 1.59%   |
| TUXEDO              | 1         | 0.79%   |
| Timi                | 1         | 0.79%   |
| Plaisio             | 1         | 0.79%   |
| Panasonic           | 1         | 0.79%   |
| Medion              | 1         | 0.79%   |
| LG Electronics      | 1         | 0.79%   |
| Irbis               | 1         | 0.79%   |
| Intel               | 1         | 0.79%   |
| IGEL Technology     | 1         | 0.79%   |
| Dynabook Europe     | 1         | 0.79%   |
| DNS                 | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Laptop 14-bs0xx                    | 2         | 1.59%   |
| Unknown                               | 2         | 1.59%   |
| TUXEDO Aura 15 Gen1                   | 1         | 0.79%   |
| Toshiba Satellite P300                | 1         | 0.79%   |
| Toshiba Satellite L675D               | 1         | 0.79%   |
| Toshiba Satellite L50-B               | 1         | 0.79%   |
| Toshiba Satellite L40                 | 1         | 0.79%   |
| Toshiba Satellite C845                | 1         | 0.79%   |
| Toshiba Satellite A200                | 1         | 0.79%   |
| Toshiba PORTEGE R700                  | 1         | 0.79%   |
| Timi TM1701                           | 1         | 0.79%   |
| Sony VPCEG15FB                        | 1         | 0.79%   |
| Sony VGN-FZ19VN                       | 1         | 0.79%   |
| Sony SVF14A15CBB                      | 1         | 0.79%   |
| Samsung R520/R522/R620                | 1         | 0.79%   |
| Samsung R468/R418                     | 1         | 0.79%   |
| Samsung 370E4K                        | 1         | 0.79%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.79%   |
| Samsung 275E4E/275E5E                 | 1         | 0.79%   |
| Plaisio Turbo X                       | 1         | 0.79%   |
| Panasonic CF-NX1GDHYS                 | 1         | 0.79%   |
| Packard Bell EasyNote LJ65            | 1         | 0.79%   |
| Packard Bell DOT SE                   | 1         | 0.79%   |
| Medion E15302                         | 1         | 0.79%   |
| LG E500-L.A2M4A2                      | 1         | 0.79%   |
| Lenovo ZIUS6                          | 1         | 0.79%   |
| Lenovo Yoga Slim 7 14ITL05 82A3       | 1         | 0.79%   |
| Lenovo ThinkPad X61s 7667WQS          | 1         | 0.79%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05 | 1         | 0.79%   |
| Lenovo ThinkPad X270 20HMS06Q1D       | 1         | 0.79%   |
| Lenovo ThinkPad X230 Tablet 34352TU   | 1         | 0.79%   |
| Lenovo ThinkPad X230 232578G          | 1         | 0.79%   |
| Lenovo ThinkPad X220 4291AN9          | 1         | 0.79%   |
| Lenovo ThinkPad X220 4290DK6          | 1         | 0.79%   |
| Lenovo ThinkPad X220 4286CTO          | 1         | 0.79%   |
| Lenovo ThinkPad X201 36801T6          | 1         | 0.79%   |
| Lenovo ThinkPad X200 74591P0          | 1         | 0.79%   |
| Lenovo ThinkPad X200 2024AY7          | 1         | 0.79%   |
| Lenovo ThinkPad X1 Carbon 3448AWU     | 1         | 0.79%   |
| Lenovo ThinkPad X1 Carbon 34487SM     | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 30        | 23.81%  |
| Dell Latitude         | 8         | 6.35%   |
| Toshiba Satellite     | 6         | 4.76%   |
| Dell Inspiron         | 6         | 4.76%   |
| HP Pavilion           | 5         | 3.97%   |
| HP Laptop             | 5         | 3.97%   |
| Lenovo IdeaPad        | 4         | 3.17%   |
| HP EliteBook          | 2         | 1.59%   |
| Fujitsu LIFEBOOK      | 2         | 1.59%   |
| ASUS VivoBook         | 2         | 1.59%   |
| Acer Aspire           | 2         | 1.59%   |
| Unknown               | 2         | 1.59%   |
| TUXEDO Aura           | 1         | 0.79%   |
| Toshiba PORTEGE       | 1         | 0.79%   |
| Timi TM1701           | 1         | 0.79%   |
| Sony VPCEG15FB        | 1         | 0.79%   |
| Sony VGN-FZ19VN       | 1         | 0.79%   |
| Sony SVF14A15CBB      | 1         | 0.79%   |
| Samsung R520          | 1         | 0.79%   |
| Samsung R468          | 1         | 0.79%   |
| Samsung 370E4K        | 1         | 0.79%   |
| Samsung 305E4A        | 1         | 0.79%   |
| Samsung 275E4E        | 1         | 0.79%   |
| Plaisio Turbo         | 1         | 0.79%   |
| Panasonic CF-NX1GDHYS | 1         | 0.79%   |
| Packard Bell EasyNote | 1         | 0.79%   |
| Packard Bell DOT      | 1         | 0.79%   |
| Medion E15302         | 1         | 0.79%   |
| LG E500-L.A2M4A2      | 1         | 0.79%   |
| Lenovo ZIUS6          | 1         | 0.79%   |
| Lenovo Yoga           | 1         | 0.79%   |
| Lenovo ThinkBook      | 1         | 0.79%   |
| Lenovo S10-3          | 1         | 0.79%   |
| Lenovo Legion         | 1         | 0.79%   |
| Lenovo G570           | 1         | 0.79%   |
| Lenovo G500           | 1         | 0.79%   |
| Lenovo Flex           | 1         | 0.79%   |
| Lenovo B570e          | 1         | 0.79%   |
| Irbis NB78            | 1         | 0.79%   |
| Intel Intel           | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 15        | 11.9%   |
| 2012 | 12        | 9.52%   |
| 2013 | 11        | 8.73%   |
| 2022 | 10        | 7.94%   |
| 2020 | 9         | 7.14%   |
| 2019 | 9         | 7.14%   |
| 2017 | 8         | 6.35%   |
| 2008 | 8         | 6.35%   |
| 2009 | 7         | 5.56%   |
| 2021 | 6         | 4.76%   |
| 2014 | 6         | 4.76%   |
| 2016 | 5         | 3.97%   |
| 2015 | 5         | 3.97%   |
| 2010 | 5         | 3.97%   |
| 2007 | 5         | 3.97%   |
| 2018 | 3         | 2.38%   |
| 2023 | 2         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 126       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 96.03%  |
| Yes  | 5         | 3.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 46        | 36.51%  |
| 4.01-8.0    | 40        | 31.75%  |
| 16.01-24.0  | 21        | 16.67%  |
| 2.01-3.0    | 13        | 10.32%  |
| 32.01-64.0  | 4         | 3.17%   |
| 3.01-4.0    | 1         | 0.79%   |
| 64.01-256.0 | 1         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 82        | 65.08%  |
| 0.51-1.0 | 34        | 26.98%  |
| 1.01-2.0 | 8         | 6.35%   |
| 2.01-3.0 | 2         | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 74.02%  |
| 2      | 17        | 13.39%  |
| 0      | 11        | 8.66%   |
| 3      | 5         | 3.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 66.67%  |
| Yes       | 42        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 86.51%  |
| No        | 17        | 13.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 96.03%  |
| No        | 5         | 3.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 66.67%  |
| No        | 42        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 21        | 16.67%  |
| Russia      | 12        | 9.52%   |
| Germany     | 12        | 9.52%   |
| Brazil      | 12        | 9.52%   |
| Poland      | 10        | 7.94%   |
| Indonesia   | 6         | 4.76%   |
| Spain       | 4         | 3.17%   |
| Romania     | 4         | 3.17%   |
| Italy       | 4         | 3.17%   |
| Canada      | 4         | 3.17%   |
| UK          | 3         | 2.38%   |
| Turkey      | 3         | 2.38%   |
| India       | 3         | 2.38%   |
| France      | 3         | 2.38%   |
| Mexico      | 2         | 1.59%   |
| China       | 2         | 1.59%   |
| Bulgaria    | 2         | 1.59%   |
| Australia   | 2         | 1.59%   |
| Switzerland | 1         | 0.79%   |
| South Korea | 1         | 0.79%   |
| Slovenia    | 1         | 0.79%   |
| Slovakia    | 1         | 0.79%   |
| Portugal    | 1         | 0.79%   |
| Philippines | 1         | 0.79%   |
| Netherlands | 1         | 0.79%   |
| Lithuania   | 1         | 0.79%   |
| Israel      | 1         | 0.79%   |
| Ireland     | 1         | 0.79%   |
| Hungary     | 1         | 0.79%   |
| Finland     | 1         | 0.79%   |
| Czechia     | 1         | 0.79%   |
| Colombia    | 1         | 0.79%   |
| Chile       | 1         | 0.79%   |
| Bolivia     | 1         | 0.79%   |
| Belarus     | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 4         | 3.15%   |
| Berlin            | 3         | 2.36%   |
| Wroclaw           | 2         | 1.57%   |
| Warsaw            | 2         | 1.57%   |
| Valencia          | 2         | 1.57%   |
| Sydney            | 2         | 1.57%   |
| Montreal          | 2         | 1.57%   |
| Milan             | 2         | 1.57%   |
| Irkutsk           | 2         | 1.57%   |
| Yeosu             | 1         | 0.79%   |
| Yekaterinburg     | 1         | 0.79%   |
| Woodbridge        | 1         | 0.79%   |
| West Plains       | 1         | 0.79%   |
| Wausau            | 1         | 0.79%   |
| Vitória          | 1         | 0.79%   |
| Vitebsk           | 1         | 0.79%   |
| Vilnius           | 1         | 0.79%   |
| Villemomble       | 1         | 0.79%   |
| Victoria          | 1         | 0.79%   |
| Ulyanovsk         | 1         | 0.79%   |
| Twinsburg         | 1         | 0.79%   |
| Trindade          | 1         | 0.79%   |
| Tomasikovo        | 1         | 0.79%   |
| Tolyatti          | 1         | 0.79%   |
| Targoviste        | 1         | 0.79%   |
| Surabaya          | 1         | 0.79%   |
| St. Jean Baptiste | 1         | 0.79%   |
| St Petersburg     | 1         | 0.79%   |
| South Goa         | 1         | 0.79%   |
| Sofia             | 1         | 0.79%   |
| Sobral            | 1         | 0.79%   |
| Shenzhen          | 1         | 0.79%   |
| Seville           | 1         | 0.79%   |
| Selma             | 1         | 0.79%   |
| Schneverdingen    | 1         | 0.79%   |
| Santiago          | 1         | 0.79%   |
| San Jose          | 1         | 0.79%   |
| Salonta           | 1         | 0.79%   |
| Rome              | 1         | 0.79%   |
| Raleigh           | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 22     | 15.33%  |
| Seagate             | 15        | 16     | 10.95%  |
| Toshiba             | 14        | 15     | 10.22%  |
| WDC                 | 12        | 13     | 8.76%   |
| Hitachi             | 10        | 10     | 7.3%    |
| SanDisk             | 9         | 9      | 6.57%   |
| Kingston            | 8         | 8      | 5.84%   |
| Crucial             | 7         | 9      | 5.11%   |
| Intel               | 5         | 5      | 3.65%   |
| HGST                | 5         | 8      | 3.65%   |
| SK hynix            | 3         | 3      | 2.19%   |
| Micron Technology   | 3         | 3      | 2.19%   |
| China               | 3         | 3      | 2.19%   |
| Transcend           | 2         | 2      | 1.46%   |
| Gigabyte Technology | 2         | 2      | 1.46%   |
| Verbatim            | 1         | 1      | 0.73%   |
| V-GeN               | 1         | 1      | 0.73%   |
| SPCC                | 1         | 1      | 0.73%   |
| PNY                 | 1         | 1      | 0.73%   |
| Plextor             | 1         | 1      | 0.73%   |
| Patriot             | 1         | 1      | 0.73%   |
| OCZ                 | 1         | 1      | 0.73%   |
| Netac               | 1         | 1      | 0.73%   |
| KingSpec            | 1         | 1      | 0.73%   |
| Kingmax             | 1         | 1      | 0.73%   |
| Intenso             | 1         | 1      | 0.73%   |
| GOODRAM             | 1         | 1      | 0.73%   |
| Goldenfir           | 1         | 1      | 0.73%   |
| Fujitsu             | 1         | 1      | 0.73%   |
| Dogfish             | 1         | 1      | 0.73%   |
| Biostar             | 1         | 1      | 0.73%   |
| Apple               | 1         | 1      | 0.73%   |
| A-DATA Technology   | 1         | 1      | 0.73%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT480BX500SSD1 480GB         | 3         | 2.14%   |
| Seagate ST9500325AS 500GB            | 2         | 1.43%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.43%   |
| Kingston SV300S37A60G 64GB           | 2         | 1.43%   |
| Kingston SA400S37240G 240GB          | 2         | 1.43%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 1.43%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.43%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 2         | 1.43%   |
| WDC WDS500G2B0B-00YS70 500GB         | 1         | 0.71%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.71%   |
| WDC WDS100T2G0A-00JH30 1TB           | 1         | 0.71%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.71%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.71%   |
| WDC WD30PURZ-85AKKY0 3TB             | 1         | 0.71%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.71%   |
| WDC WD1600BEVT-60ZCT0 160GB          | 1         | 0.71%   |
| WDC WD1600BEVS-22VAT0 160GB          | 1         | 0.71%   |
| WDC WD10JPVX-80JC3T0 1TB             | 1         | 0.71%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.71%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.71%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.71%   |
| Verbatim Vi550 S3 SSD 512GB          | 1         | 0.71%   |
| V-GeN V-GEN08SM22AR256SDK 256GB      | 1         | 0.71%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.71%   |
| Transcend TS120GMTS420S 120GB        | 1         | 0.71%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.71%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.71%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.71%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.71%   |
| Toshiba MK8034GSX 80GB               | 1         | 0.71%   |
| Toshiba MK6461GSYN 640GB             | 1         | 0.71%   |
| Toshiba MK5065GSXF 500GB             | 1         | 0.71%   |
| Toshiba MK5059GSXP 500GB             | 1         | 0.71%   |
| Toshiba MK3263GSXN 320GB             | 1         | 0.71%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.71%   |
| Toshiba MK1655GSXF 160GB             | 1         | 0.71%   |
| Toshiba MK1646GSX 160GB              | 1         | 0.71%   |
| Toshiba MK1229GSG 120GB              | 1         | 0.71%   |
| Toshiba KXG6AZNV256G 256GB           | 1         | 0.71%   |
| SPCC Solid State Disk 256GB          | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 27.27%  |
| Toshiba             | 13        | 14     | 23.64%  |
| Hitachi             | 10        | 10     | 18.18%  |
| WDC                 | 8         | 8      | 14.55%  |
| HGST                | 5         | 8      | 9.09%   |
| Samsung Electronics | 3         | 4      | 5.45%   |
| Fujitsu             | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 9         | 9      | 14.29%  |
| Samsung Electronics | 9         | 9      | 14.29%  |
| Kingston            | 7         | 7      | 11.11%  |
| Crucial             | 7         | 9      | 11.11%  |
| Intel               | 4         | 4      | 6.35%   |
| China               | 3         | 3      | 4.76%   |
| WDC                 | 2         | 3      | 3.17%   |
| Micron Technology   | 2         | 2      | 3.17%   |
| Gigabyte Technology | 2         | 2      | 3.17%   |
| Verbatim            | 1         | 1      | 1.59%   |
| V-GeN               | 1         | 1      | 1.59%   |
| Transcend           | 1         | 1      | 1.59%   |
| SPCC                | 1         | 1      | 1.59%   |
| SK hynix            | 1         | 1      | 1.59%   |
| PNY                 | 1         | 1      | 1.59%   |
| Plextor             | 1         | 1      | 1.59%   |
| Patriot             | 1         | 1      | 1.59%   |
| OCZ                 | 1         | 1      | 1.59%   |
| Netac               | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| Kingmax             | 1         | 1      | 1.59%   |
| Intenso             | 1         | 1      | 1.59%   |
| GOODRAM             | 1         | 1      | 1.59%   |
| Goldenfir           | 1         | 1      | 1.59%   |
| Dogfish             | 1         | 1      | 1.59%   |
| Biostar             | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 58        | 66     | 44.96%  |
| HDD  | 53        | 61     | 41.09%  |
| NVMe | 18        | 19     | 13.95%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 127    | 84.87%  |
| NVMe | 18        | 19     | 15.13%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 90        | 104    | 83.33%  |
| 0.51-1.0   | 16        | 21     | 14.81%  |
| 2.01-3.0   | 1         | 1      | 0.93%   |
| 1.01-2.0   | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 61        | 48.41%  |
| 101-250    | 24        | 19.05%  |
| 251-500    | 18        | 14.29%  |
| 51-100     | 14        | 11.11%  |
| 501-1000   | 6         | 4.76%   |
| 21-50      | 2         | 1.59%   |
| Unknown    | 1         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 123       | 97.62%  |
| 21-50   | 1         | 0.79%   |
| 101-250 | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB         | 2         | 2      | 6.25%   |
| WDC WD30PURZ-85AKKY0 3TB          | 1         | 1      | 3.13%   |
| WDC WD10JPVX-60JC3T1 1TB          | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD032 320GB          | 1         | 1      | 3.13%   |
| Toshiba MK5059GSXP 500GB          | 1         | 1      | 3.13%   |
| Toshiba MK1646GSX 160GB           | 1         | 1      | 3.13%   |
| Toshiba MK1229GSG 120GB           | 1         | 1      | 3.13%   |
| SK hynix SC210 mSATA 256GB        | 1         | 1      | 3.13%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 3.13%   |
| Seagate ST9160827AS 160GB         | 1         | 1      | 3.13%   |
| Seagate ST9160314AS 160GB         | 1         | 1      | 3.13%   |
| Seagate ST500LM000-SSHD-8GB       | 1         | 1      | 3.13%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 3.13%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 3.13%   |
| Seagate ST320LT012-9WS14C 320GB   | 1         | 2      | 3.13%   |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 3.13%   |
| Kingston SV300S37A60G 64GB        | 1         | 1      | 3.13%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 3.13%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 3.13%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 3.13%   |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 3.13%   |
| Hitachi HTS542525K9A300 250GB     | 1         | 1      | 3.13%   |
| Hitachi HTS541616J9SA00 160GB     | 1         | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 3.13%   |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 3.13%   |
| HGST HTS541075A7E630 752GB        | 1         | 1      | 3.13%   |
| HGST HTS541010A9E680 1TB          | 1         | 2      | 3.13%   |
| Crucial M4-CT256M4SSD3 256GB      | 1         | 1      | 3.13%   |
| Crucial CT500MX500SSD1 500GB      | 1         | 2      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 28.13%  |
| Hitachi             | 6         | 6      | 18.75%  |
| Toshiba             | 5         | 5      | 15.63%  |
| HGST                | 4         | 5      | 12.5%   |
| WDC                 | 2         | 2      | 6.25%   |
| Crucial             | 2         | 3      | 6.25%   |
| SK hynix            | 1         | 1      | 3.13%   |
| Samsung Electronics | 1         | 1      | 3.13%   |
| Kingston            | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 33.33%  |
| Hitachi             | 6         | 6      | 22.22%  |
| Toshiba             | 5         | 5      | 18.52%  |
| HGST                | 4         | 5      | 14.81%  |
| WDC                 | 2         | 2      | 7.41%   |
| Samsung Electronics | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 29     | 83.87%  |
| SSD  | 5         | 6      | 16.13%  |

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
| Works   | 89        | 110    | 73.55%  |
| Malfunc | 31        | 35     | 25.62%  |
| Failed  | 1         | 1      | 0.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 98        | 74.24%  |
| AMD                              | 10        | 7.58%   |
| Samsung Electronics              | 8         | 6.06%   |
| SanDisk                          | 5         | 3.79%   |
| Nvidia                           | 3         | 2.27%   |
| SK hynix                         | 2         | 1.52%   |
| Toshiba                          | 1         | 0.76%   |
| Silicon Motion                   | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] | 1         | 0.76%   |
| Micron Technology                | 1         | 0.76%   |
| Kingston Technology Company      | 1         | 0.76%   |
| ADATA Technology                 | 1         | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 11.72%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 8.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 7.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 6.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 4.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 4.83%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 4.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 4.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.76%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 2.07%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 2         | 1.38%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.38%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.38%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.69%   |
| SK hynix hynix unknown                                                           | 1         | 0.69%   |
| SK hynix BC511                                                                   | 1         | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.69%   |
| Sandisk WD Black SN770 NVMe SSD                                                  | 1         | 0.69%   |
| SanDisk unknown                                                                  | 1         | 0.69%   |
| SanDisk NVMe Controller                                                          | 1         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.69%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.69%   |
| Micron NVMe Storage Controller                                                   | 1         | 0.69%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.69%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 100       | 72.46%  |
| NVMe | 17        | 12.32%  |
| IDE  | 17        | 12.32%  |
| RAID | 4         | 2.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 112       | 88.89%  |
| AMD    | 14        | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel CPU Version                           | 5         | 3.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 3.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 3.97%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 2.38%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 2.38%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 2.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 2.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.59%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.59%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 1.59%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz        | 2         | 1.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.59%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 1.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.59%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.79%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.79%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.79%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 1         | 0.79%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.79%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.79%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.79%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.79%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.79%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.79%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.79%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.79%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 0.79%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 0.79%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 1         | 0.79%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.79%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.79%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.79%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.79%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.79%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 30.95%  |
| Intel Core i7           | 21        | 16.67%  |
| Intel Celeron           | 15        | 11.9%   |
| Intel Core 2 Duo        | 13        | 10.32%  |
| Other                   | 9         | 7.14%   |
| Intel Core i3           | 7         | 5.56%   |
| AMD Ryzen 7             | 5         | 3.97%   |
| Intel Atom              | 4         | 3.17%   |
| AMD Ryzen 5             | 2         | 1.59%   |
| Intel Pentium Dual-Core | 1         | 0.79%   |
| Intel Pentium Dual      | 1         | 0.79%   |
| Intel Pentium           | 1         | 0.79%   |
| Intel Genuine           | 1         | 0.79%   |
| Intel Celeron D         | 1         | 0.79%   |
| AMD Ryzen Embedded      | 1         | 0.79%   |
| AMD Phenom II           | 1         | 0.79%   |
| AMD E1                  | 1         | 0.79%   |
| AMD E                   | 1         | 0.79%   |
| AMD Athlon              | 1         | 0.79%   |
| AMD A8                  | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 61.9%   |
| 4       | 23        | 18.25%  |
| Unknown | 14        | 11.11%  |
| 8       | 4         | 3.17%   |
| 1       | 4         | 3.17%   |
| 16      | 2         | 1.59%   |
| 12      | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 122       | 96.83%  |
| 2      | 4         | 3.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 74        | 58.73%  |
| 1       | 35        | 27.78%  |
| Unknown | 17        | 13.49%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 16        | 12.7%   |
| SandyBridge   | 15        | 11.9%   |
| KabyLake      | 14        | 11.11%  |
| Core          | 12        | 9.52%   |
| Penryn        | 10        | 7.94%   |
| Haswell       | 10        | 7.94%   |
| Skylake       | 8         | 6.35%   |
| Broadwell     | 6         | 4.76%   |
| Westmere      | 5         | 3.97%   |
| Silvermont    | 5         | 3.97%   |
| Bonnell       | 5         | 3.97%   |
| Zen+          | 3         | 2.38%   |
| TigerLake     | 3         | 2.38%   |
| Zen 3         | 2         | 1.59%   |
| Zen 2         | 2         | 1.59%   |
| Goldmont plus | 2         | 1.59%   |
| Bobcat        | 2         | 1.59%   |
| Zen           | 1         | 0.79%   |
| K10 Llano     | 1         | 0.79%   |
| K10           | 1         | 0.79%   |
| Goldmont      | 1         | 0.79%   |
| Excavator     | 1         | 0.79%   |
| Unknown       | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 102       | 70.34%  |
| Nvidia                           | 21        | 14.48%  |
| AMD                              | 21        | 14.48%  |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 10.26%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 8.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 5.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 5.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.85%   |
| Intel HD Graphics 5500                                                                   | 6         | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.85%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 3.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.28%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.28%   |
| Intel HD Graphics 620                                                                    | 2         | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.28%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.28%   |
| AMD Renoir                                                                               | 2         | 1.28%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.64%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.64%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.64%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.64%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.64%   |
| Nvidia GK208M [GeForce GT 735M]                                                          | 1         | 0.64%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.64%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 0.64%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.64%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.64%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.64%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 52.38%  |
| 2 x Intel      | 18        | 14.29%  |
| 1 x AMD        | 14        | 11.11%  |
| Intel + Nvidia | 13        | 10.32%  |
| 1 x Nvidia     | 6         | 4.76%   |
| Intel + AMD    | 5         | 3.97%   |
| 2 x Nvidia     | 1         | 0.79%   |
| 2 x AMD        | 1         | 0.79%   |
| 1 x SiS        | 1         | 0.79%   |
| AMD + Nvidia   | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 114       | 90.48%  |
| Proprietary | 7         | 5.56%   |
| Unknown     | 5         | 3.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 90.48%  |
| 0.01-0.5   | 8         | 6.35%   |
| 0.51-1.0   | 3         | 2.38%   |
| 7.01-8.0   | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 5         | 27.78%  |
| Samsung Electronics     | 3         | 16.67%  |
| LG Philips              | 1         | 5.56%   |
| LG Display              | 1         | 5.56%   |
| InfoVision              | 1         | 5.56%   |
| CPT                     | 1         | 5.56%   |
| Chimei Innolux          | 1         | 5.56%   |
| Chi Mei Optoelectronics | 1         | 5.56%   |
| BOE                     | 1         | 5.56%   |
| Apple                   | 1         | 5.56%   |
| AOC                     | 1         | 5.56%   |
| Unknown                 | 1         | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch      | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch     | 1         | 5.56%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch        | 1         | 5.56%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch            | 1         | 5.56%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 5.56%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch              | 1         | 5.56%   |
| CPT LCD Monitor CPT1BC0 1024x600 220x120mm 9.9-inch                      | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 5.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1465 1366x768 310x180mm 14.1-inch | 1         | 5.56%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                    | 1         | 5.56%   |
| AU Optronics LCD Monitor AUOB78F 1920x1080 340x190mm 15.3-inch           | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO323E 1600x900 310x170mm 13.9-inch            | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch            | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch            | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 380x210mm 17.1-inch           | 1         | 5.56%   |
| Apple Color LCD APPA014 2560x1600 290x180mm 13.4-inch                    | 1         | 5.56%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                        | 1         | 5.56%   |
| Unknown                                                                  | 1         | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 6         | 33.33%  |
| 1920x1080 (FHD) | 5         | 27.78%  |
| 2560x1600       | 2         | 11.11%  |
| 1600x900 (HD+)  | 2         | 11.11%  |
| 2560x1440 (QHD) | 1         | 5.56%   |
| 1280x800 (WXGA) | 1         | 5.56%   |
| 1024x600        | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 6         | 33.33%  |
| 15      | 5         | 27.78%  |
| 31      | 1         | 5.56%   |
| 21      | 1         | 5.56%   |
| 19      | 1         | 5.56%   |
| 17      | 1         | 5.56%   |
| 14      | 1         | 5.56%   |
| 9       | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 50%     |
| 201-300     | 4         | 22.22%  |
| 401-500     | 2         | 11.11%  |
| 601-700     | 1         | 5.56%   |
| 351-400     | 1         | 5.56%   |
| Unknown     | 1         | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 13        | 81.25%  |
| 16/10   | 2         | 12.5%   |
| Unknown | 1         | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 5         | 27.78%  |
| 91-100         | 4         | 22.22%  |
| 71-80          | 2         | 11.11%  |
| 351-500        | 1         | 5.56%   |
| 41-50          | 1         | 5.56%   |
| 201-250        | 1         | 5.56%   |
| 151-200        | 1         | 5.56%   |
| 121-130        | 1         | 5.56%   |
| 101-110        | 1         | 5.56%   |
| Unknown        | 1         | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 7         | 38.89%  |
| 121-160 | 6         | 33.33%  |
| 51-100  | 3         | 16.67%  |
| 161-240 | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 112       | 88.89%  |
| 0     | 8         | 6.35%   |
| 2     | 6         | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 71        | 36.98%  |
| Realtek Semiconductor             | 53        | 27.6%   |
| Qualcomm Atheros                  | 33        | 17.19%  |
| Broadcom                          | 11        | 5.73%   |
| Marvell Technology Group          | 5         | 2.6%    |
| Sierra Wireless                   | 3         | 1.56%   |
| Samsung Electronics               | 3         | 1.56%   |
| Ericsson Business Mobile Networks | 3         | 1.56%   |
| Xiaomi                            | 2         | 1.04%   |
| Nvidia                            | 2         | 1.04%   |
| MediaTek                          | 2         | 1.04%   |
| TP-Link                           | 1         | 0.52%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.52%   |
| JMicron Technology                | 1         | 0.52%   |
| Edimax Technology                 | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 29        | 11.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 5.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 4.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.83%   |
| Intel Wireless 8260                                                     | 6         | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 2.02%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.02%   |
| Intel Wireless 7265                                                     | 5         | 2.02%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 2.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 1.62%   |
| Intel Wireless 7260                                                     | 4         | 1.62%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 1.21%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.21%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.21%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.21%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.21%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 1.21%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 1.21%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.81%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 0.81%   |
| Intel Wireless 3165                                                     | 2         | 0.81%   |
| Intel WiFi Link 5100                                                    | 2         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.81%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 52.34%  |
| Qualcomm Atheros      | 29        | 22.66%  |
| Realtek Semiconductor | 18        | 14.06%  |
| Broadcom              | 9         | 7.03%   |
| Sierra Wireless       | 2         | 1.56%   |
| TP-Link               | 1         | 0.78%   |
| MediaTek              | 1         | 0.78%   |
| Edimax Technology     | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 8.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 6.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 5.38%   |
| Intel Wireless 8260                                                     | 6         | 4.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.85%   |
| Intel Wireless 7265                                                     | 5         | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.08%   |
| Intel Wireless 7260                                                     | 4         | 3.08%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.31%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 2.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.31%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 2.31%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.54%   |
| Intel Wireless 3165                                                     | 2         | 1.54%   |
| Intel WiFi Link 5100                                                    | 2         | 1.54%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.54%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.54%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.54%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.77%   |
| Sierra Wireless EM7455                                                  | 1         | 0.77%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.77%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.77%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 1         | 0.77%   |
| Realtek Bluetooth Adapter                                               | 1         | 0.77%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 1         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 44        | 39.29%  |
| Intel                            | 41        | 36.61%  |
| Qualcomm Atheros                 | 9         | 8.04%   |
| Marvell Technology Group         | 5         | 4.46%   |
| Samsung Electronics              | 3         | 2.68%   |
| Broadcom                         | 3         | 2.68%   |
| Xiaomi                           | 2         | 1.79%   |
| Nvidia                           | 2         | 1.79%   |
| Silicon Integrated Systems [SiS] | 1         | 0.89%   |
| MediaTek                         | 1         | 0.89%   |
| JMicron Technology               | 1         | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 25.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 11.61%  |
| Intel Ethernet Connection I219-LM                                 | 5         | 4.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 3.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 2.68%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.68%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.68%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 2.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.79%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.79%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.89%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.89%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.89%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.89%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.89%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.89%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.89%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.89%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.89%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.89%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.89%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.89%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.89%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 51.49%  |
| Ethernet | 109       | 46.38%  |
| Unknown  | 4         | 1.7%    |
| Modem    | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 60.34%  |
| Ethernet | 46        | 39.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 80.16%  |
| 1     | 23        | 18.25%  |
| 0     | 2         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 89.76%  |
| Yes  | 13        | 10.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 45.24%  |
| Qualcomm Atheros Communications | 11        | 13.1%   |
| Broadcom                        | 7         | 8.33%   |
| Foxconn / Hon Hai               | 6         | 7.14%   |
| Realtek Semiconductor           | 5         | 5.95%   |
| Apple                           | 5         | 5.95%   |
| IMC Networks                    | 3         | 3.57%   |
| ASUSTek Computer                | 3         | 3.57%   |
| Lite-On Technology              | 1         | 1.19%   |
| Hewlett-Packard                 | 1         | 1.19%   |
| Dell                            | 1         | 1.19%   |
| Cambridge Silicon Radio         | 1         | 1.19%   |
| Askey Computer                  | 1         | 1.19%   |
| Alps Electric                   | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 23        | 27.38%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 5         | 5.95%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 3.57%   |
| Intel AX201 Bluetooth                                       | 3         | 3.57%   |
| Intel AX200 Bluetooth                                       | 3         | 3.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 3.57%   |
| Apple Bluetooth Host Controller                             | 3         | 3.57%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.38%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 2.38%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 2.38%   |
| ASUS BT-270 Bluetooth Adapter                               | 2         | 2.38%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 2.38%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.19%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 1.19%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 1.19%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.19%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 1.19%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.19%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.19%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 1.19%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.19%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.19%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.19%   |
| IMC Networks Bluetooth module                               | 1         | 1.19%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 1.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.19%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.19%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.19%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.19%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 1.19%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.19%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.19%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.19%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.19%   |
| Askey BlueSoleil Generic Bluetooth Device                   | 1         | 1.19%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 108       | 78.26%  |
| AMD                               | 17        | 12.32%  |
| Nvidia                            | 7         | 5.07%   |
| Texas Instruments                 | 1         | 0.72%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.72%   |
| Phison Electronics                | 1         | 0.72%   |
| Generalplus Technology            | 1         | 0.72%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.72%   |
| Conexant Systems                  | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 10.91%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 9.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 7.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 6.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 5.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 5.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.64%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.64%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 3.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.42%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.21%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.21%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.61%   |
| Phison Electronics SoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoun                   | 1         | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.61%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.61%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                                          | 1         | 0.61%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 0.61%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.61%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 27.08%  |
| SK hynix            | 25        | 17.36%  |
| Unknown             | 16        | 11.11%  |
| Micron Technology   | 13        | 9.03%   |
| Unknown             | 10        | 6.94%   |
| Kingston            | 7         | 4.86%   |
| Crucial             | 6         | 4.17%   |
| Nanya Technology    | 4         | 2.78%   |
| Smart               | 3         | 2.08%   |
| Ramaxel Technology  | 3         | 2.08%   |
| Elpida              | 3         | 2.08%   |
| Corsair             | 3         | 2.08%   |
| A-DATA Technology   | 3         | 2.08%   |
| Unknown (ABCD)      | 2         | 1.39%   |
| Transcend           | 1         | 0.69%   |
| Swissbit            | 1         | 0.69%   |
| Silicon Power       | 1         | 0.69%   |
| SHARETRONIC         | 1         | 0.69%   |
| Multilaser          | 1         | 0.69%   |
| G.Skill             | 1         | 0.69%   |
| ASint Technology    | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 10        | 6.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 3.36%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 2.68%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 2.01%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 2.01%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 3         | 2.01%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 2.01%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.34%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 2         | 1.34%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.34%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.34%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s            | 2         | 1.34%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.34%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.34%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.67%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.67%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 1         | 0.67%   |
| Swissbit RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.67%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 667MT/s             | 1         | 0.67%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.67%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT42556MFR6A-G7 2GB Chip DDR3 1333MT/s             | 1         | 0.67%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB DDR3 1600MT/s                  | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                | 1         | 0.67%   |
| SK hynix RAM HMT351S6AFR8C-G7 4GB SODIMM DDR3 533MT/s            | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 64        | 51.61%  |
| DDR4    | 33        | 26.61%  |
| DDR2    | 15        | 12.1%   |
| Unknown | 4         | 3.23%   |
| SDRAM   | 3         | 2.42%   |
| LPDDR4  | 3         | 2.42%   |
| LPDDR3  | 2         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 91.2%   |
| Chip         | 4         | 3.2%    |
| Unknown      | 4         | 3.2%    |
| Row Of Chips | 2         | 1.6%    |
| DIMM         | 1         | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 47        | 34.56%  |
| 8192  | 39        | 28.68%  |
| 2048  | 33        | 24.26%  |
| 16384 | 8         | 5.88%   |
| 1024  | 8         | 5.88%   |
| 32768 | 1         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 34        | 26.36%  |
| 2400    | 15        | 11.63%  |
| 667     | 14        | 10.85%  |
| 1333    | 11        | 8.53%   |
| 3200    | 9         | 6.98%   |
| 2667    | 8         | 6.2%    |
| 1334    | 7         | 5.43%   |
| 1067    | 7         | 5.43%   |
| 2133    | 6         | 4.65%   |
| Unknown | 5         | 3.88%   |
| 1867    | 4         | 3.1%    |
| 800     | 4         | 3.1%    |
| 2048    | 2         | 1.55%   |
| 3733    | 1         | 0.78%   |
| 1066    | 1         | 0.78%   |
| 533     | 1         | 0.78%   |

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
| Chicony Electronics                    | 25        | 28.74%  |
| Bison Electronics                      | 12        | 13.79%  |
| Microdia                               | 9         | 10.34%  |
| Sunplus Innovation Technology          | 6         | 6.9%    |
| Realtek Semiconductor                  | 6         | 6.9%    |
| IMC Networks                           | 5         | 5.75%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.6%    |
| Silicon Motion                         | 3         | 3.45%   |
| Lite-On Technology                     | 3         | 3.45%   |
| Syntek                                 | 2         | 2.3%    |
| Suyin                                  | 2         | 2.3%    |
| Quanta                                 | 2         | 2.3%    |
| Lenovo                                 | 2         | 2.3%    |
| Z-Star Microelectronics                | 1         | 1.15%   |
| Y Media                                | 1         | 1.15%   |
| Supreme Electronics                    | 1         | 1.15%   |
| Luxvisions Innotech Limited            | 1         | 1.15%   |
| Apple                                  | 1         | 1.15%   |
| Alcor Micro                            | 1         | 1.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 8         | 9.2%    |
| Chicony Integrated Camera                                   | 6         | 6.9%    |
| Microdia Integrated_Webcam_HD                               | 5         | 5.75%   |
| Realtek Integrated_Webcam_HD                                | 4         | 4.6%    |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 3.45%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 2.3%    |
| Lite-On Integrated Camera                                   | 2         | 2.3%    |
| Lenovo Integrated Webcam                                    | 2         | 2.3%    |
| IMC Networks Integrated Webcam                              | 2         | 2.3%    |
| Chicony USB 2.0 Camera                                      | 2         | 2.3%    |
| Chicony FJ Camera                                           | 2         | 2.3%    |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 2         | 2.3%    |
| Bison Lenovo EasyCamera                                     | 2         | 2.3%    |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 1.15%   |
| Y Media USB Camera                                          | 1         | 1.15%   |
| Syntek HP Webcam                                            | 1         | 1.15%   |
| Syntek EasyCamera                                           | 1         | 1.15%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.15%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.15%   |
| Supreme Integrated Camera                                   | 1         | 1.15%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.15%   |
| Sunplus Integrated Camera                                   | 1         | 1.15%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.15%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 1.15%   |
| Silicon Motion WebCam SCX Series                            | 1         | 1.15%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 1.15%   |
| Silicon Motion ATIV VGA Camera                              | 1         | 1.15%   |
| Realtek USB 2.0 PC Camera                                   | 1         | 1.15%   |
| Realtek Dell EasyCamera                                     | 1         | 1.15%   |
| Quanta Realtek PC Camera                                    | 1         | 1.15%   |
| Quanta HD WebCam                                            | 1         | 1.15%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.15%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.15%   |
| Microdia Integrated Webcam                                  | 1         | 1.15%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.15%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.15%   |
| Lite-On TOSHIBA Web Camera - HD                             | 1         | 1.15%   |
| IMC Networks UVC VGA Webcam                                 | 1         | 1.15%   |
| IMC Networks Integrated Camera                              | 1         | 1.15%   |
| IMC Networks EasyCamera                                     | 1         | 1.15%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 28.57%  |
| Elan Microelectronics      | 3         | 21.43%  |
| AuthenTec                  | 3         | 21.43%  |
| Upek                       | 2         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| LighTuning Technology      | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan Fingerprint Sensor                                | 3         | 21.43%  |
| Validity Sensors Synaptics WBDI                        | 2         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| AuthenTec AES2810                                      | 1         | 7.14%   |
| AuthenTec AES2660                                      | 1         | 7.14%   |
| AuthenTec AES1660                                      | 1         | 7.14%   |

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
| 1     | 61        | 48.41%  |
| 2     | 30        | 23.81%  |
| 0     | 23        | 18.25%  |
| 3     | 11        | 8.73%   |
| 4     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 82        | 56.55%  |
| Net/wireless             | 18        | 12.41%  |
| Fingerprint reader       | 14        | 9.66%   |
| Card reader              | 14        | 9.66%   |
| Bluetooth                | 11        | 7.59%   |
| Storage                  | 4         | 2.76%   |
| Network                  | 1         | 0.69%   |
| Net/ethernet             | 1         | 0.69%   |

