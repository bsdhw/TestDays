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

Total: 126

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 109       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 108       | 99.08%  |
| GNOME        | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 109       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 109       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 58        | 52.73%  |
| fr_FR   | 12        | 10.91%  |
| de_DE   | 9         | 8.18%   |
| ru_RU   | 8         | 7.27%   |
| es_ES   | 5         | 4.55%   |
| pt_BR   | 4         | 3.64%   |
| pl_PL   | 4         | 3.64%   |
| Unknown | 4         | 3.64%   |
| pt      | 1         | 0.91%   |
| nl_NL   | 1         | 0.91%   |
| ko_KR   | 1         | 0.91%   |
| it_IT   | 1         | 0.91%   |
| fi_FI   | 1         | 0.91%   |
| en      | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 109       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 55        | 50.46%  |
| Cd9660 | 54        | 49.54%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 109       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 36.7%   |
| Dell                | 15        | 13.76%  |
| Hewlett-Packard     | 10        | 9.17%   |
| Toshiba             | 7         | 6.42%   |
| ASUSTek Computer    | 7         | 6.42%   |
| Acer                | 6         | 5.5%    |
| Samsung Electronics | 5         | 4.59%   |
| Apple               | 4         | 3.67%   |
| Fujitsu             | 3         | 2.75%   |
| Google              | 2         | 1.83%   |
| Sony                | 1         | 0.92%   |
| Plaisio             | 1         | 0.92%   |
| Packard Bell        | 1         | 0.92%   |
| Medion              | 1         | 0.92%   |
| LG Electronics      | 1         | 0.92%   |
| Irbis               | 1         | 0.92%   |
| Intel               | 1         | 0.92%   |
| IGEL Technology     | 1         | 0.92%   |
| Dynabook Europe     | 1         | 0.92%   |
| DNS                 | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba Satellite P300                | 1         | 0.92%   |
| Toshiba Satellite L675D               | 1         | 0.92%   |
| Toshiba Satellite L50-B               | 1         | 0.92%   |
| Toshiba Satellite L40                 | 1         | 0.92%   |
| Toshiba Satellite C845                | 1         | 0.92%   |
| Toshiba Satellite A200                | 1         | 0.92%   |
| Toshiba PORTEGE R700                  | 1         | 0.92%   |
| Sony VGN-FZ19VN                       | 1         | 0.92%   |
| Samsung R520/R522/R620                | 1         | 0.92%   |
| Samsung R468/R418                     | 1         | 0.92%   |
| Samsung 370E4K                        | 1         | 0.92%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.92%   |
| Samsung 275E4E/275E5E                 | 1         | 0.92%   |
| Plaisio Turbo X                       | 1         | 0.92%   |
| Packard Bell DOT SE                   | 1         | 0.92%   |
| Medion E15302                         | 1         | 0.92%   |
| LG E500-L.A2M4A2                      | 1         | 0.92%   |
| Lenovo ZIUS6                          | 1         | 0.92%   |
| Lenovo Yoga Slim 7 14ITL05 82A3       | 1         | 0.92%   |
| Lenovo ThinkPad X61s 7667WQS          | 1         | 0.92%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05 | 1         | 0.92%   |
| Lenovo ThinkPad X270 20HMS06Q1D       | 1         | 0.92%   |
| Lenovo ThinkPad X230 Tablet 34352TU   | 1         | 0.92%   |
| Lenovo ThinkPad X230 232578G          | 1         | 0.92%   |
| Lenovo ThinkPad X220 4291AN9          | 1         | 0.92%   |
| Lenovo ThinkPad X220 4290DK6          | 1         | 0.92%   |
| Lenovo ThinkPad X220 4286CTO          | 1         | 0.92%   |
| Lenovo ThinkPad X201 36801T6          | 1         | 0.92%   |
| Lenovo ThinkPad X200 74591P0          | 1         | 0.92%   |
| Lenovo ThinkPad X200 2024AY7          | 1         | 0.92%   |
| Lenovo ThinkPad X1 Carbon 3448AWU     | 1         | 0.92%   |
| Lenovo ThinkPad X1 Carbon 34487SM     | 1         | 0.92%   |
| Lenovo ThinkPad W541 20EF000NUS       | 1         | 0.92%   |
| Lenovo ThinkPad T61 7659CA1           | 1         | 0.92%   |
| Lenovo ThinkPad T61 7658CTO           | 1         | 0.92%   |
| Lenovo ThinkPad T540p 20BFS10W03      | 1         | 0.92%   |
| Lenovo ThinkPad T520 4243F39          | 1         | 0.92%   |
| Lenovo ThinkPad T520 4242PN3          | 1         | 0.92%   |
| Lenovo ThinkPad T470 W10DG 20JNS02000 | 1         | 0.92%   |
| Lenovo ThinkPad T460s 20FAS2BR00      | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 30        | 27.52%  |
| Dell Latitude             | 8         | 7.34%   |
| Toshiba Satellite         | 6         | 5.5%    |
| Dell Inspiron             | 6         | 5.5%    |
| Lenovo IdeaPad            | 4         | 3.67%   |
| HP Laptop                 | 4         | 3.67%   |
| HP Pavilion               | 3         | 2.75%   |
| HP EliteBook              | 2         | 1.83%   |
| Fujitsu LIFEBOOK          | 2         | 1.83%   |
| ASUS VivoBook             | 2         | 1.83%   |
| Acer Aspire               | 2         | 1.83%   |
| Toshiba PORTEGE           | 1         | 0.92%   |
| Sony VGN-FZ19VN           | 1         | 0.92%   |
| Samsung R520              | 1         | 0.92%   |
| Samsung R468              | 1         | 0.92%   |
| Samsung 370E4K            | 1         | 0.92%   |
| Samsung 305E4A            | 1         | 0.92%   |
| Samsung 275E4E            | 1         | 0.92%   |
| Plaisio Turbo             | 1         | 0.92%   |
| Packard Bell DOT          | 1         | 0.92%   |
| Medion E15302             | 1         | 0.92%   |
| LG E500-L.A2M4A2          | 1         | 0.92%   |
| Lenovo ZIUS6              | 1         | 0.92%   |
| Lenovo Yoga               | 1         | 0.92%   |
| Lenovo ThinkBook          | 1         | 0.92%   |
| Lenovo Legion             | 1         | 0.92%   |
| Lenovo G570               | 1         | 0.92%   |
| Lenovo G500               | 1         | 0.92%   |
| Irbis NB78                | 1         | 0.92%   |
| Intel Intel               | 1         | 0.92%   |
| IGEL M350C                | 1         | 0.92%   |
| Google Wolf               | 1         | 0.92%   |
| Google Terra              | 1         | 0.92%   |
| Fujitsu CELSIUS           | 1         | 0.92%   |
| Dynabook Europe Satellite | 1         | 0.92%   |
| DNS W9x0LU                | 1         | 0.92%   |
| Dell XPS                  | 1         | 0.92%   |
| ASUS X71Vn                | 1         | 0.92%   |
| ASUS X58C                 | 1         | 0.92%   |
| ASUS G74Sx                | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 13        | 11.93%  |
| 2013 | 10        | 9.17%   |
| 2019 | 9         | 8.26%   |
| 2022 | 8         | 7.34%   |
| 2020 | 8         | 7.34%   |
| 2012 | 8         | 7.34%   |
| 2009 | 7         | 6.42%   |
| 2008 | 7         | 6.42%   |
| 2021 | 6         | 5.5%    |
| 2017 | 5         | 4.59%   |
| 2016 | 5         | 4.59%   |
| 2015 | 5         | 4.59%   |
| 2014 | 5         | 4.59%   |
| 2007 | 5         | 4.59%   |
| 2018 | 3         | 2.75%   |
| 2010 | 3         | 2.75%   |
| 2023 | 2         | 1.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 109       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 96.33%  |
| Yes  | 4         | 3.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 40        | 36.7%   |
| 4.01-8.0   | 35        | 32.11%  |
| 16.01-24.0 | 19        | 17.43%  |
| 2.01-3.0   | 11        | 10.09%  |
| 32.01-64.0 | 3         | 2.75%   |
| 3.01-4.0   | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 70        | 64.22%  |
| 0.51-1.0 | 31        | 28.44%  |
| 1.01-2.0 | 7         | 6.42%   |
| 2.01-3.0 | 1         | 0.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 75.23%  |
| 2      | 14        | 12.84%  |
| 0      | 9         | 8.26%   |
| 3      | 4         | 3.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 66.97%  |
| Yes       | 36        | 33.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 87.16%  |
| No        | 14        | 12.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 96.33%  |
| No        | 4         | 3.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 66.97%  |
| No        | 36        | 33.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 19        | 17.43%  |
| Germany     | 12        | 11.01%  |
| Brazil      | 10        | 9.17%   |
| Russia      | 9         | 8.26%   |
| Poland      | 8         | 7.34%   |
| Spain       | 4         | 3.67%   |
| Romania     | 4         | 3.67%   |
| Italy       | 4         | 3.67%   |
| Indonesia   | 4         | 3.67%   |
| Canada      | 4         | 3.67%   |
| India       | 3         | 2.75%   |
| France      | 3         | 2.75%   |
| UK          | 2         | 1.83%   |
| Turkey      | 2         | 1.83%   |
| Mexico      | 2         | 1.83%   |
| Bulgaria    | 2         | 1.83%   |
| Switzerland | 1         | 0.92%   |
| South Korea | 1         | 0.92%   |
| Slovenia    | 1         | 0.92%   |
| Slovakia    | 1         | 0.92%   |
| Portugal    | 1         | 0.92%   |
| Philippines | 1         | 0.92%   |
| Netherlands | 1         | 0.92%   |
| Lithuania   | 1         | 0.92%   |
| Israel      | 1         | 0.92%   |
| Ireland     | 1         | 0.92%   |
| Finland     | 1         | 0.92%   |
| Czechia     | 1         | 0.92%   |
| Colombia    | 1         | 0.92%   |
| China       | 1         | 0.92%   |
| Chile       | 1         | 0.92%   |
| Bolivia     | 1         | 0.92%   |
| Australia   | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 4         | 3.64%   |
| Berlin            | 3         | 2.73%   |
| Wroclaw           | 2         | 1.82%   |
| Valencia          | 2         | 1.82%   |
| Montreal          | 2         | 1.82%   |
| Milan             | 2         | 1.82%   |
| Yeosu             | 1         | 0.91%   |
| Yekaterinburg     | 1         | 0.91%   |
| Woodbridge        | 1         | 0.91%   |
| West Plains       | 1         | 0.91%   |
| Wausau            | 1         | 0.91%   |
| Warsaw            | 1         | 0.91%   |
| Vitória          | 1         | 0.91%   |
| Vilnius           | 1         | 0.91%   |
| Villemomble       | 1         | 0.91%   |
| Victoria          | 1         | 0.91%   |
| Twinsburg         | 1         | 0.91%   |
| Trindade          | 1         | 0.91%   |
| Tomasikovo        | 1         | 0.91%   |
| Tolyatti          | 1         | 0.91%   |
| Targoviste        | 1         | 0.91%   |
| Sydney            | 1         | 0.91%   |
| Surabaya          | 1         | 0.91%   |
| St. Jean Baptiste | 1         | 0.91%   |
| St Petersburg     | 1         | 0.91%   |
| South Goa         | 1         | 0.91%   |
| Sofia             | 1         | 0.91%   |
| Sobral            | 1         | 0.91%   |
| Shenzhen          | 1         | 0.91%   |
| Seville           | 1         | 0.91%   |
| Selma             | 1         | 0.91%   |
| Schneverdingen    | 1         | 0.91%   |
| Santiago          | 1         | 0.91%   |
| San Jose          | 1         | 0.91%   |
| Salonta           | 1         | 0.91%   |
| Rome              | 1         | 0.91%   |
| Raleigh           | 1         | 0.91%   |
| Queensbury        | 1         | 0.91%   |
| Poznan            | 1         | 0.91%   |
| Peterborough      | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 18     | 15.13%  |
| Seagate             | 13        | 14     | 10.92%  |
| WDC                 | 10        | 11     | 8.4%    |
| Toshiba             | 10        | 11     | 8.4%    |
| SanDisk             | 9         | 9      | 7.56%   |
| Hitachi             | 9         | 9      | 7.56%   |
| Kingston            | 7         | 7      | 5.88%   |
| Crucial             | 7         | 9      | 5.88%   |
| Intel               | 5         | 5      | 4.2%    |
| HGST                | 5         | 6      | 4.2%    |
| SK hynix            | 3         | 3      | 2.52%   |
| Micron Technology   | 3         | 3      | 2.52%   |
| China               | 3         | 3      | 2.52%   |
| Transcend           | 2         | 2      | 1.68%   |
| Verbatim            | 1         | 1      | 0.84%   |
| V-GeN               | 1         | 1      | 0.84%   |
| SPCC                | 1         | 1      | 0.84%   |
| PNY                 | 1         | 1      | 0.84%   |
| Plextor             | 1         | 1      | 0.84%   |
| Patriot             | 1         | 1      | 0.84%   |
| OCZ                 | 1         | 1      | 0.84%   |
| Netac               | 1         | 1      | 0.84%   |
| KingSpec            | 1         | 1      | 0.84%   |
| Intenso             | 1         | 1      | 0.84%   |
| GOODRAM             | 1         | 1      | 0.84%   |
| Gigabyte Technology | 1         | 1      | 0.84%   |
| Fujitsu             | 1         | 1      | 0.84%   |
| Dogfish             | 1         | 1      | 0.84%   |
| A-DATA Technology   | 1         | 1      | 0.84%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT480BX500SSD1 480GB         | 3         | 2.48%   |
| Seagate ST9500325AS 500GB            | 2         | 1.65%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.65%   |
| Kingston SV300S37A60G 64GB           | 2         | 1.65%   |
| Kingston SA400S37240G 240GB          | 2         | 1.65%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.65%   |
| WDC WDS500G2B0B-00YS70 500GB         | 1         | 0.83%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.83%   |
| WDC WDS100T2G0A-00JH30 1TB           | 1         | 0.83%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.83%   |
| WDC WD30PURZ-85AKKY0 3TB             | 1         | 0.83%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.83%   |
| WDC WD1600BEVS-22VAT0 160GB          | 1         | 0.83%   |
| WDC WD10JPVX-80JC3T0 1TB             | 1         | 0.83%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.83%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.83%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.83%   |
| Verbatim Vi550 S3 SSD 512GB          | 1         | 0.83%   |
| V-GeN V-GEN08SM22AR256SDK 256GB      | 1         | 0.83%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.83%   |
| Transcend TS120GMTS420S 120GB        | 1         | 0.83%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.83%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.83%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.83%   |
| Toshiba MK6461GSYN 640GB             | 1         | 0.83%   |
| Toshiba MK5065GSXF 500GB             | 1         | 0.83%   |
| Toshiba MK3263GSXN 320GB             | 1         | 0.83%   |
| Toshiba MK1655GSXF 160GB             | 1         | 0.83%   |
| Toshiba MK1646GSX 160GB              | 1         | 0.83%   |
| Toshiba MK1229GSG 120GB              | 1         | 0.83%   |
| Toshiba KXG6AZNV256G 256GB           | 1         | 0.83%   |
| SPCC Solid State Disk 256GB          | 1         | 0.83%   |
| SK hynix SC210 mSATA 256GB           | 1         | 0.83%   |
| SK hynix PC601 NVMe 1TB              | 1         | 0.83%   |
| SK hynix BC511 NVMe 512GB            | 1         | 0.83%   |
| Seagate ST9320320AS 320GB            | 1         | 0.83%   |
| Seagate ST9250827AS 250GB            | 1         | 0.83%   |
| Seagate ST9250410AS 250GB            | 1         | 0.83%   |
| Seagate ST9160827AS 160GB            | 1         | 0.83%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 28.89%  |
| Toshiba             | 9         | 10     | 20%     |
| Hitachi             | 9         | 9      | 20%     |
| WDC                 | 6         | 6      | 13.33%  |
| HGST                | 5         | 6      | 11.11%  |
| Samsung Electronics | 2         | 2      | 4.44%   |
| Fujitsu             | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 9         | 9      | 15.79%  |
| Samsung Electronics | 9         | 9      | 15.79%  |
| Crucial             | 7         | 9      | 12.28%  |
| Kingston            | 6         | 6      | 10.53%  |
| Intel               | 4         | 4      | 7.02%   |
| China               | 3         | 3      | 5.26%   |
| WDC                 | 2         | 3      | 3.51%   |
| Micron Technology   | 2         | 2      | 3.51%   |
| Verbatim            | 1         | 1      | 1.75%   |
| V-GeN               | 1         | 1      | 1.75%   |
| Transcend           | 1         | 1      | 1.75%   |
| SPCC                | 1         | 1      | 1.75%   |
| SK hynix            | 1         | 1      | 1.75%   |
| PNY                 | 1         | 1      | 1.75%   |
| Plextor             | 1         | 1      | 1.75%   |
| Patriot             | 1         | 1      | 1.75%   |
| OCZ                 | 1         | 1      | 1.75%   |
| Netac               | 1         | 1      | 1.75%   |
| KingSpec            | 1         | 1      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| GOODRAM             | 1         | 1      | 1.75%   |
| Gigabyte Technology | 1         | 1      | 1.75%   |
| Dogfish             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 52        | 60     | 46.43%  |
| HDD  | 44        | 48     | 39.29%  |
| NVMe | 16        | 17     | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 108    | 84.47%  |
| NVMe | 16        | 17     | 15.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 87     | 81.91%  |
| 0.51-1.0   | 15        | 19     | 15.96%  |
| 2.01-3.0   | 1         | 1      | 1.06%   |
| 1.01-2.0   | 1         | 1      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 52        | 47.71%  |
| 101-250    | 23        | 21.1%   |
| 251-500    | 16        | 14.68%  |
| 51-100     | 10        | 9.17%   |
| 501-1000   | 6         | 5.5%    |
| 21-50      | 2         | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 107       | 98.17%  |
| 21-50   | 1         | 0.92%   |
| 101-250 | 1         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB       | 2         | 2      | 7.14%   |
| WDC WD30PURZ-85AKKY0 3TB        | 1         | 1      | 3.57%   |
| WDC WD10JPVX-60JC3T1 1TB        | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD100 1TB          | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD032 320GB        | 1         | 1      | 3.57%   |
| Toshiba MK1646GSX 160GB         | 1         | 1      | 3.57%   |
| Toshiba MK1229GSG 120GB         | 1         | 1      | 3.57%   |
| SK hynix SC210 mSATA 256GB      | 1         | 1      | 3.57%   |
| Seagate ST9250410AS 250GB       | 1         | 1      | 3.57%   |
| Seagate ST9160827AS 160GB       | 1         | 1      | 3.57%   |
| Seagate ST500LM000-1EJ162 500GB | 1         | 1      | 3.57%   |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 3.57%   |
| Seagate ST320LT012-9WS14C 320GB | 1         | 2      | 3.57%   |
| Kingston SV300S37A60G 64GB      | 1         | 1      | 3.57%   |
| Intel SSDSC2BF180A4L 180GB      | 1         | 1      | 3.57%   |
| Hitachi HTS727550A9E364 500GB   | 1         | 1      | 3.57%   |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 3.57%   |
| Hitachi HTS547550A9E384 500GB   | 1         | 1      | 3.57%   |
| Hitachi HTS545050B9A300 500GB   | 1         | 1      | 3.57%   |
| Hitachi HTS542525K9A300 250GB   | 1         | 1      | 3.57%   |
| Hitachi HTS541616J9SA00 160GB   | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB      | 1         | 1      | 3.57%   |
| HGST HTS545050A7E380 500GB      | 1         | 1      | 3.57%   |
| HGST HTS541075A7E630 752GB      | 1         | 1      | 3.57%   |
| HGST HTS541010A9E680 1TB        | 1         | 1      | 3.57%   |
| Crucial M4-CT256M4SSD3 256GB    | 1         | 1      | 3.57%   |
| Crucial CT500MX500SSD1 500GB    | 1         | 2      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 7         | 8      | 25%     |
| Hitachi  | 6         | 6      | 21.43%  |
| Toshiba  | 4         | 4      | 14.29%  |
| HGST     | 4         | 4      | 14.29%  |
| WDC      | 2         | 2      | 7.14%   |
| Crucial  | 2         | 3      | 7.14%   |
| SK hynix | 1         | 1      | 3.57%   |
| Kingston | 1         | 1      | 3.57%   |
| Intel    | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 30.43%  |
| Hitachi | 6         | 6      | 26.09%  |
| Toshiba | 4         | 4      | 17.39%  |
| HGST    | 4         | 4      | 17.39%  |
| WDC     | 2         | 2      | 8.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 24     | 82.14%  |
| SSD  | 5         | 6      | 17.86%  |

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
| Works   | 76        | 95     | 73.08%  |
| Malfunc | 28        | 30     | 26.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 85        | 72.65%  |
| AMD                              | 10        | 8.55%   |
| Samsung Electronics              | 6         | 5.13%   |
| SanDisk                          | 5         | 4.27%   |
| Nvidia                           | 3         | 2.56%   |
| SK hynix                         | 2         | 1.71%   |
| Toshiba                          | 1         | 0.85%   |
| Silicon Motion                   | 1         | 0.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.85%   |
| Micron Technology                | 1         | 0.85%   |
| Kingston Technology Company      | 1         | 0.85%   |
| ADATA Technology                 | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 11.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 8.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 6.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 5.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 5.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 5.38%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 5.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 2.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 2.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 2.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 2.31%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 2         | 1.54%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.54%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.54%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.54%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.77%   |
| SK hynix hynix unknown                                                           | 1         | 0.77%   |
| SK hynix BC511                                                                   | 1         | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.77%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.77%   |
| Sandisk WD Black SN770 NVMe SSD                                                  | 1         | 0.77%   |
| SanDisk unknown                                                                  | 1         | 0.77%   |
| SanDisk NVMe Controller                                                          | 1         | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.77%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.77%   |
| Micron NVMe Storage Controller                                                   | 1         | 0.77%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.77%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 88        | 71.54%  |
| IDE  | 17        | 13.82%  |
| NVMe | 15        | 12.2%   |
| RAID | 3         | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 97        | 88.99%  |
| AMD    | 12        | 11.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz      | 5         | 4.59%   |
| Intel CPU Version                      | 4         | 3.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 4         | 3.67%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 3         | 2.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 3         | 2.75%   |
| Intel Core i5-3337U CPU @ 1.80GHz      | 2         | 1.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 2         | 1.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz      | 2         | 1.83%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz   | 2         | 1.83%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz   | 2         | 1.83%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 2         | 1.83%   |
| Intel Celeron CPU N3060 @ 1.60GHz      | 2         | 1.83%   |
| Intel Atom CPU N570 @ 1.66GHz          | 2         | 1.83%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz | 1         | 0.92%   |
| Intel Pentium CPU N3700 @ 1.60GHz      | 1         | 0.92%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 0.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz      | 1         | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 0.92%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz     | 1         | 0.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 0.92%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 1         | 0.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 0.92%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz     | 1         | 0.92%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz     | 1         | 0.92%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz     | 1         | 0.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz      | 1         | 0.92%   |
| Intel Core i7-3720QM CPU @ 2.60GHz     | 1         | 0.92%   |
| Intel Core i7-3667U CPU @ 2.00GHz      | 1         | 0.92%   |
| Intel Core i7-3632QM CPU @ 2.20GHz     | 1         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz     | 1         | 0.92%   |
| Intel Core i7-2620M CPU @ 2.70GHz      | 1         | 0.92%   |
| Intel Core i7-10610U CPU @ 1.80GHz     | 1         | 0.92%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 0.92%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1         | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1         | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 1         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 0.92%   |
| Intel Core i5-3427U CPU @ 1.80GHz      | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 31        | 28.44%  |
| Intel Core i7      | 20        | 18.35%  |
| Intel Core 2 Duo   | 13        | 11.93%  |
| Intel Celeron      | 13        | 11.93%  |
| Other              | 8         | 7.34%   |
| Intel Core i3      | 6         | 5.5%    |
| Intel Atom         | 4         | 3.67%   |
| AMD Ryzen 7        | 3         | 2.75%   |
| AMD Ryzen 5        | 2         | 1.83%   |
| Intel Pentium Dual | 1         | 0.92%   |
| Intel Pentium      | 1         | 0.92%   |
| Intel Celeron D    | 1         | 0.92%   |
| AMD Ryzen Embedded | 1         | 0.92%   |
| AMD Phenom II      | 1         | 0.92%   |
| AMD E1             | 1         | 0.92%   |
| AMD E              | 1         | 0.92%   |
| AMD Athlon         | 1         | 0.92%   |
| AMD A8             | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 68        | 62.39%  |
| 4       | 21        | 19.27%  |
| Unknown | 13        | 11.93%  |
| 8       | 3         | 2.75%   |
| 1       | 2         | 1.83%   |
| 16      | 1         | 0.92%   |
| 12      | 1         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 105       | 96.33%  |
| 2      | 4         | 3.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 63        | 57.8%   |
| 1       | 31        | 28.44%  |
| Unknown | 15        | 13.76%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 14        | 12.84%  |
| KabyLake      | 12        | 11.01%  |
| SandyBridge   | 11        | 10.09%  |
| Core          | 11        | 10.09%  |
| Penryn        | 9         | 8.26%   |
| Haswell       | 9         | 8.26%   |
| Skylake       | 7         | 6.42%   |
| Broadwell     | 6         | 5.5%    |
| Westmere      | 4         | 3.67%   |
| Silvermont    | 4         | 3.67%   |
| Bonnell       | 4         | 3.67%   |
| Zen+          | 3         | 2.75%   |
| TigerLake     | 3         | 2.75%   |
| Zen 3         | 2         | 1.83%   |
| Goldmont plus | 2         | 1.83%   |
| Bobcat        | 2         | 1.83%   |
| Zen 2         | 1         | 0.92%   |
| Zen           | 1         | 0.92%   |
| K10 Llano     | 1         | 0.92%   |
| K10           | 1         | 0.92%   |
| Goldmont      | 1         | 0.92%   |
| Excavator     | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 88        | 71.54%  |
| AMD                              | 19        | 15.45%  |
| Nvidia                           | 15        | 12.2%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 10.45%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 7.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 6.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 6.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 4.48%   |
| Intel HD Graphics 5500                                                                   | 6         | 4.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.73%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.24%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.24%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.49%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.49%   |
| Intel HD Graphics 620                                                                    | 2         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.49%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.49%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.75%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.75%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.75%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.75%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 0.75%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.75%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.75%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 0.75%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.75%   |
| Nvidia C79 [GeForce 9400M / ION]                                                         | 1         | 0.75%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 0.75%   |
| Intel HD Graphics 630                                                                    | 1         | 0.75%   |
| Intel HD Graphics 520                                                                    | 1         | 0.75%   |
| Intel HD Graphics 500                                                                    | 1         | 0.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 54.13%  |
| 2 x Intel      | 16        | 14.68%  |
| 1 x AMD        | 12        | 11.01%  |
| Intel + Nvidia | 8         | 7.34%   |
| 1 x Nvidia     | 5         | 4.59%   |
| Intel + AMD    | 5         | 4.59%   |
| 2 x Nvidia     | 1         | 0.92%   |
| 2 x AMD        | 1         | 0.92%   |
| 1 x SiS        | 1         | 0.92%   |
| AMD + Nvidia   | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 99        | 90.83%  |
| Proprietary | 6         | 5.5%    |
| Unknown     | 4         | 3.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 89.91%  |
| 0.01-0.5   | 7         | 6.42%   |
| 0.51-1.0   | 3         | 2.75%   |
| 7.01-8.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution | Notebooks | Percent |
|------------|-----------|---------|
| 2560x1600  | 1         | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 1         | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 1         | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 98        | 89.91%  |
| 0     | 7         | 6.42%   |
| 2     | 4         | 3.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 64        | 38.79%  |
| Realtek Semiconductor             | 44        | 26.67%  |
| Qualcomm Atheros                  | 29        | 17.58%  |
| Broadcom                          | 8         | 4.85%   |
| Marvell Technology Group          | 5         | 3.03%   |
| Sierra Wireless                   | 3         | 1.82%   |
| Xiaomi                            | 2         | 1.21%   |
| Samsung Electronics               | 2         | 1.21%   |
| Nvidia                            | 2         | 1.21%   |
| Ericsson Business Mobile Networks | 2         | 1.21%   |
| TP-Link                           | 1         | 0.61%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.61%   |
| MediaTek                          | 1         | 0.61%   |
| Edimax Technology                 | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 23        | 10.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 5.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 5.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 4.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.29%   |
| Intel Wireless 8260                                                     | 6         | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.35%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 2.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 1.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.88%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.88%   |
| Intel Wireless 7265                                                     | 4         | 1.88%   |
| Intel Wireless 7260                                                     | 4         | 1.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.41%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 1.41%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 1.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.94%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.94%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 0.94%   |
| Intel Wireless 3165                                                     | 2         | 0.94%   |
| Intel WiFi Link 5100                                                    | 2         | 0.94%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.94%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.94%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.94%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 53.57%  |
| Qualcomm Atheros      | 25        | 22.32%  |
| Realtek Semiconductor | 15        | 13.39%  |
| Broadcom              | 7         | 6.25%   |
| Sierra Wireless       | 2         | 1.79%   |
| TP-Link               | 1         | 0.89%   |
| MediaTek              | 1         | 0.89%   |
| Edimax Technology     | 1         | 0.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 7.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 6.19%   |
| Intel Wireless 8260                                                     | 6         | 5.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 4.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 3.54%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.54%   |
| Intel Wireless 7265                                                     | 4         | 3.54%   |
| Intel Wireless 7260                                                     | 4         | 3.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 2.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.77%   |
| Intel Wireless 3165                                                     | 2         | 1.77%   |
| Intel WiFi Link 5100                                                    | 2         | 1.77%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.77%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.77%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.77%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.77%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.88%   |
| Sierra Wireless EM7455                                                  | 1         | 0.88%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.88%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.88%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.88%   |
| Realtek Bluetooth Adapter                                               | 1         | 0.88%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 1         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 40.63%  |
| Realtek Semiconductor            | 36        | 37.5%   |
| Qualcomm Atheros                 | 8         | 8.33%   |
| Marvell Technology Group         | 5         | 5.21%   |
| Xiaomi                           | 2         | 2.08%   |
| Samsung Electronics              | 2         | 2.08%   |
| Nvidia                           | 2         | 2.08%   |
| Silicon Integrated Systems [SiS] | 1         | 1.04%   |
| Broadcom                         | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 23.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 12.5%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 5.21%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 4.17%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.13%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 3.13%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 3.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 2.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.08%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.04%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.04%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.04%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.04%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.04%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.04%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.04%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.04%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.04%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 51.47%  |
| Ethernet | 95        | 46.57%  |
| Unknown  | 3         | 1.47%   |
| Modem    | 1         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 58.25%  |
| Ethernet | 43        | 41.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 88        | 80.73%  |
| 1     | 19        | 17.43%  |
| 0     | 2         | 1.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 89.09%  |
| Yes  | 12        | 10.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 46.58%  |
| Qualcomm Atheros Communications | 11        | 15.07%  |
| Broadcom                        | 7         | 9.59%   |
| Realtek Semiconductor           | 4         | 5.48%   |
| Apple                           | 4         | 5.48%   |
| IMC Networks                    | 3         | 4.11%   |
| Foxconn / Hon Hai               | 3         | 4.11%   |
| ASUSTek Computer                | 2         | 2.74%   |
| Lite-On Technology              | 1         | 1.37%   |
| Hewlett-Packard                 | 1         | 1.37%   |
| Dell                            | 1         | 1.37%   |
| Cambridge Silicon Radio         | 1         | 1.37%   |
| Askey Computer                  | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 21        | 28.77%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 5         | 6.85%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 4.11%   |
| Intel AX201 Bluetooth                                    | 3         | 4.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 4.11%   |
| Realtek Bluetooth Adapter                                | 2         | 2.74%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 2         | 2.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 2         | 2.74%   |
| Intel AX200 Bluetooth                                    | 2         | 2.74%   |
| Apple Built-in iSight (no firmware loaded)               | 2         | 2.74%   |
| Apple Bluetooth Host Controller                          | 2         | 2.74%   |
| Realtek RTL8821A Bluetooth                               | 1         | 1.37%   |
| Realtek Bluetooth 4.0 + High Speed Chip                  | 1         | 1.37%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 1.37%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth            | 1         | 1.37%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE      | 1         | 1.37%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth            | 1         | 1.37%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)          | 1         | 1.37%   |
| Lite-On Qualcomm Atheros Bluetooth                       | 1         | 1.37%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 1.37%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 1.37%   |
| IMC Networks Bluetooth module                            | 1         | 1.37%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 1.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 1         | 1.37%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter             | 1         | 1.37%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 1.37%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 1.37%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 1.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 1         | 1.37%   |
| Broadcom BCM20702A0 Bluetooth                            | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 1         | 1.37%   |
| ASUS BT-270 Bluetooth Adapter                            | 1         | 1.37%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 1.37%   |
| Askey BlueSoleil Generic Bluetooth Device                | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 93        | 79.49%  |
| AMD                              | 15        | 12.82%  |
| Nvidia                           | 6         | 5.13%   |
| Silicon Integrated Systems [SiS] | 1         | 0.85%   |
| Phison Electronics               | 1         | 0.85%   |
| Generalplus Technology           | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 11.35%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 9.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 7.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 6.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 4.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 4.96%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 3.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.55%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.84%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.42%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.42%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.71%   |
| Phison Electronics SoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoun                   | 1         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.71%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.71%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.71%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 0.71%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.71%   |
| AMD R600 HDMI Audio [Radeon HD 2900 GT/PRO/XT]                                                    | 1         | 0.71%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 26.98%  |
| SK hynix            | 24        | 19.05%  |
| Unknown             | 13        | 10.32%  |
| Micron Technology   | 10        | 7.94%   |
| Unknown             | 7         | 5.56%   |
| Kingston            | 6         | 4.76%   |
| Crucial             | 6         | 4.76%   |
| Nanya Technology    | 4         | 3.17%   |
| Smart               | 3         | 2.38%   |
| Elpida              | 3         | 2.38%   |
| Corsair             | 3         | 2.38%   |
| A-DATA Technology   | 3         | 2.38%   |
| Unknown (ABCD)      | 2         | 1.59%   |
| Ramaxel Technology  | 2         | 1.59%   |
| Swissbit            | 1         | 0.79%   |
| Silicon Power       | 1         | 0.79%   |
| SHARETRONIC         | 1         | 0.79%   |
| Multilaser          | 1         | 0.79%   |
| G.Skill             | 1         | 0.79%   |
| ASint Technology    | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 7         | 5.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 3.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 3.1%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 2.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 2.33%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.55%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 2         | 1.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 2         | 1.55%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s            | 2         | 1.55%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.55%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.78%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.78%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.78%   |
| Swissbit RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.78%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.78%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.78%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 667MT/s             | 1         | 0.78%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.78%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.78%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT42556MFR6A-G7 2GB Chip DDR3 1333MT/s             | 1         | 0.78%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB DDR3 1600MT/s                  | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                | 1         | 0.78%   |
| SK hynix RAM HMT351S6AFR8C-G7 4GB SODIMM DDR3 533MT/s            | 1         | 0.78%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.78%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.78%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.78%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 56        | 51.85%  |
| DDR4    | 29        | 26.85%  |
| DDR2    | 13        | 12.04%  |
| SDRAM   | 3         | 2.78%   |
| LPDDR4  | 3         | 2.78%   |
| Unknown | 3         | 2.78%   |
| LPDDR3  | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 91.74%  |
| Chip         | 4         | 3.67%   |
| Row Of Chips | 2         | 1.83%   |
| Unknown      | 2         | 1.83%   |
| DIMM         | 1         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 39        | 33.33%  |
| 8192  | 36        | 30.77%  |
| 2048  | 29        | 24.79%  |
| 1024  | 7         | 5.98%   |
| 16384 | 6         | 5.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 27.43%  |
| 2400    | 14        | 12.39%  |
| 667     | 12        | 10.62%  |
| 3200    | 8         | 7.08%   |
| 1333    | 8         | 7.08%   |
| 1334    | 7         | 6.19%   |
| 2667    | 6         | 5.31%   |
| 2133    | 6         | 5.31%   |
| 1067    | 6         | 5.31%   |
| Unknown | 4         | 3.54%   |
| 1867    | 3         | 2.65%   |
| 800     | 3         | 2.65%   |
| 2048    | 2         | 1.77%   |
| 3733    | 1         | 0.88%   |
| 1066    | 1         | 0.88%   |
| 533     | 1         | 0.88%   |

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
| Chicony Electronics                    | 19        | 25.33%  |
| Bison Electronics                      | 11        | 14.67%  |
| Microdia                               | 9         | 12%     |
| Sunplus Innovation Technology          | 6         | 8%      |
| Realtek Semiconductor                  | 6         | 8%      |
| IMC Networks                           | 4         | 5.33%   |
| Silicon Motion                         | 3         | 4%      |
| Lite-On Technology                     | 3         | 4%      |
| Syntek                                 | 2         | 2.67%   |
| Quanta                                 | 2         | 2.67%   |
| Lenovo                                 | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.67%   |
| Z-Star Microelectronics                | 1         | 1.33%   |
| Y Media                                | 1         | 1.33%   |
| Suyin                                  | 1         | 1.33%   |
| Supreme Electronics                    | 1         | 1.33%   |
| Luxvisions Innotech Limited            | 1         | 1.33%   |
| Alcor Micro                            | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 8         | 10.67%  |
| Microdia Integrated_Webcam_HD                               | 5         | 6.67%   |
| Chicony Integrated Camera                                   | 5         | 6.67%   |
| Realtek Integrated_Webcam_HD                                | 4         | 5.33%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 4%      |
| Sunplus HP TrueVision HD Camera                             | 2         | 2.67%   |
| Lite-On Integrated Camera                                   | 2         | 2.67%   |
| Lenovo Integrated Webcam                                    | 2         | 2.67%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 2         | 2.67%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 1.33%   |
| Y Media USB Camera                                          | 1         | 1.33%   |
| Syntek HP Webcam                                            | 1         | 1.33%   |
| Syntek EasyCamera                                           | 1         | 1.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.33%   |
| Supreme Integrated Camera                                   | 1         | 1.33%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.33%   |
| Sunplus Integrated Camera                                   | 1         | 1.33%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.33%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 1.33%   |
| Silicon Motion WebCam SCX Series                            | 1         | 1.33%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 1.33%   |
| Silicon Motion ATIV VGA Camera                              | 1         | 1.33%   |
| Realtek USB 2.0 PC Camera                                   | 1         | 1.33%   |
| Realtek Dell EasyCamera                                     | 1         | 1.33%   |
| Quanta Realtek PC Camera                                    | 1         | 1.33%   |
| Quanta HD WebCam                                            | 1         | 1.33%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.33%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.33%   |
| Microdia Integrated Webcam                                  | 1         | 1.33%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.33%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.33%   |
| Lite-On TOSHIBA Web Camera - HD                             | 1         | 1.33%   |
| IMC Networks UVC VGA Webcam                                 | 1         | 1.33%   |
| IMC Networks Integrated Webcam                              | 1         | 1.33%   |
| IMC Networks Integrated Camera                              | 1         | 1.33%   |
| IMC Networks EasyCamera                                     | 1         | 1.33%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 1.33%   |
| Chicony USB Video Device                                    | 1         | 1.33%   |
| Chicony thinkpad t430s camera                               | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| AuthenTec                  | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| LighTuning Technology      | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 2         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 18.18%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner                   | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |
| AuthenTec AES2660                                      | 1         | 9.09%   |
| AuthenTec AES1660                                      | 1         | 9.09%   |

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
| 1     | 52        | 47.71%  |
| 2     | 26        | 23.85%  |
| 0     | 20        | 18.35%  |
| 3     | 10        | 9.17%   |
| 4     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 72        | 57.6%   |
| Net/wireless             | 15        | 12%     |
| Card reader              | 12        | 9.6%    |
| Fingerprint reader       | 11        | 8.8%    |
| Bluetooth                | 10        | 8%      |
| Storage                  | 4         | 3.2%    |
| Network                  | 1         | 0.8%    |

