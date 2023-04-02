BSD - Tested Hardware & Statistics (Notebooks)
----------------------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/bsdhw/TestDays_VE)

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

Total: 3371

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | X58C                        | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Chuwi         | Unknown                     | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Acer          | Aspire 5745DG               | [2b8bf9802e](https://bsd-hardware.info/?probe=2b8bf9802e) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Deciso        | NetBoard-A20                | [33ca458105](https://bsd-hardware.info/?probe=33ca458105) | Mar 30, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Google        | Stout                       | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Dell          | Inspiron 5547               | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Unknown       | Unknown                     | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| LG Electro... | COLUMBIA                    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [f5537face6](https://bsd-hardware.info/?probe=f5537face6) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| Dell          | Inspiron 5559               | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| HP            | EliteBook Folio 9470m       | [ea2865cbf5](https://bsd-hardware.info/?probe=ea2865cbf5) | Mar 26, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [b960dc3bde](https://bsd-hardware.info/?probe=b960dc3bde) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| eMachines     | eM350                       | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| Alienware     | 14                          | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [4cd1097c65](https://bsd-hardware.info/?probe=4cd1097c65) | Mar 24, 2023 |
| Intel         | H81U                        | [af9a6469c9](https://bsd-hardware.info/?probe=af9a6469c9) | Mar 24, 2023 |
| Dell          | G5 5587                     | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| Dell          | Latitude 5500               | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| Acer          | Nitro AN515-53              | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [42fffdf3f2](https://bsd-hardware.info/?probe=42fffdf3f2) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [83ee1d297d](https://bsd-hardware.info/?probe=83ee1d297d) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| MECHREVO S... | S1 Series                   | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| ASUSTek       | G750JS                      | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| HP            | ProBook 640 G3              | [860471150b](https://bsd-hardware.info/?probe=860471150b) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Intel         | S1200RP_SE                  | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| OEGStone      | W54_55SU1,SUW               | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| ASUSTek       | 1001P                       | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
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
| Dell          | Inspiron 5567               | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| Acer          | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Acer          | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E736               | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Deciso        | OPNsense Appliance          | [faebab61f2](https://bsd-hardware.info/?probe=faebab61f2) | Mar 12, 2023 |
| Google        | Kohaku                      | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| HP            | Laptop 15-bs1xx             | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [aa70f61a87](https://bsd-hardware.info/?probe=aa70f61a87) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| Star Labs     | StarBook                    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| Fujitsu       | FMVA532BSJ                  | [695e38d0ea](https://bsd-hardware.info/?probe=695e38d0ea) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X230 23252G8       | [2ff46d6b7c](https://bsd-hardware.info/?probe=2ff46d6b7c) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| HP            | EliteBook 2530p             | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Dell          | Latitude D620               | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| Samsung       | 750XEE                      | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [aafc670aa7](https://bsd-hardware.info/?probe=aafc670aa7) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Deciso        | OPNsense Appliance          | [1cca4a556d](https://bsd-hardware.info/?probe=1cca4a556d) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| ASUSTek       | 1201N                       | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| Lenovo        | G400s 20244                 | [215f16c5d9](https://bsd-hardware.info/?probe=215f16c5d9) | Mar 05, 2023 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [8037475831](https://bsd-hardware.info/?probe=8037475831) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Acer          | TravelMate TX50-G2          | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| HP            | G62                         | [18487b3ab2](https://bsd-hardware.info/?probe=18487b3ab2) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Deciso        | NetBoard-A10                | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| HP            | 240 G6 Notebook PC          | [d872652e25](https://bsd-hardware.info/?probe=d872652e25) | Feb 28, 2023 |
| Lenovo        | ThinkPad T430 2349S31       | [2b13f68cd6](https://bsd-hardware.info/?probe=2b13f68cd6) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Notebook      | N2x0WU                      | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [115bd3bc38](https://bsd-hardware.info/?probe=115bd3bc38) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| Dell          | Inspiron 15 3515            | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Acer          | Aspire ES1-571              | [d736d59649](https://bsd-hardware.info/?probe=d736d59649) | Feb 26, 2023 |
| Acer          | Aspire ES1-571              | [48aa652a09](https://bsd-hardware.info/?probe=48aa652a09) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Toshiba       | dynabook R63/P              | [c41c3adfa4](https://bsd-hardware.info/?probe=c41c3adfa4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005SU... | [7750c38cd0](https://bsd-hardware.info/?probe=7750c38cd0) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [b3e56e9656](https://bsd-hardware.info/?probe=b3e56e9656) | Feb 25, 2023 |
| Dell          | Latitude 5591               | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| HP            | EliteBook 840 G1            | [0480ce43f2](https://bsd-hardware.info/?probe=0480ce43f2) | Feb 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Deciso        | NetBoard-A20                | [d23ae47425](https://bsd-hardware.info/?probe=d23ae47425) | Feb 23, 2023 |
| Plaisio       | Turbo X                     | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440 20B60061MB    | [16a141cc35](https://bsd-hardware.info/?probe=16a141cc35) | Feb 23, 2023 |
| HP            | EliteBook 840 G1            | [77c17e4a2f](https://bsd-hardware.info/?probe=77c17e4a2f) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [7d7fa2bbc9](https://bsd-hardware.info/?probe=7d7fa2bbc9) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440 20B60061MB    | [4867945cfb](https://bsd-hardware.info/?probe=4867945cfb) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Deciso        | Netboard A20                | [25077b7e64](https://bsd-hardware.info/?probe=25077b7e64) | Feb 21, 2023 |
| HP            | ZBook 15 G3                 | [ff6ddb74bb](https://bsd-hardware.info/?probe=ff6ddb74bb) | Feb 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| Acer          | Aspire E1-421               | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [92bca4d026](https://bsd-hardware.info/?probe=92bca4d026) | Feb 19, 2023 |
| Lenovo        | G400s 20244                 | [f2c258a0ae](https://bsd-hardware.info/?probe=f2c258a0ae) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Acer          | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 427638U       | [baa0e928a8](https://bsd-hardware.info/?probe=baa0e928a8) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| IGEL Techn... | H830C                       | [069249225f](https://bsd-hardware.info/?probe=069249225f) | Feb 17, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Apple         | MacBookPro11,1              | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| Google        | Lulu                        | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Deciso        | OPNsense Appliance          | [1eda4c5b48](https://bsd-hardware.info/?probe=1eda4c5b48) | Feb 15, 2023 |
| Deciso        | NetBoard-A20                | [ffc9e123b4](https://bsd-hardware.info/?probe=ffc9e123b4) | Feb 14, 2023 |
| Deciso        | Netboard A20                | [7c91a0f01b](https://bsd-hardware.info/?probe=7c91a0f01b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T430 2347FV6       | [cf016ce514](https://bsd-hardware.info/?probe=cf016ce514) | Feb 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Acer          | Aspire one V1.05            | [eec371a28f](https://bsd-hardware.info/?probe=eec371a28f) | Feb 13, 2023 |
| Dell          | Inspiron 5567               | [df5f01d72e](https://bsd-hardware.info/?probe=df5f01d72e) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| Shuttle       | DS437T                      | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Unknown       | Unknown                     | [c2735d8120](https://bsd-hardware.info/?probe=c2735d8120) | Feb 11, 2023 |
| Apple         | MacBookAir6,1               | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| MSI           | GF76 12UE                   | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a9928bd16e](https://bsd-hardware.info/?probe=a9928bd16e) | Feb 10, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| Sony          | SVF1421E4E                  | [d0a9e97993](https://bsd-hardware.info/?probe=d0a9e97993) | Feb 09, 2023 |
| HP            | Laptop 14-df0xxx            | [1dc503f21d](https://bsd-hardware.info/?probe=1dc503f21d) | Feb 09, 2023 |
| Acer          | Aspire 4739Z                | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| ASUSTek       | N76VZ                       | [3b7e2ee70b](https://bsd-hardware.info/?probe=3b7e2ee70b) | Feb 08, 2023 |
| ASUSTek       | K84L                        | [d58c178c51](https://bsd-hardware.info/?probe=d58c178c51) | Feb 08, 2023 |
| HP            | Notebook                    | [507e85c092](https://bsd-hardware.info/?probe=507e85c092) | Feb 08, 2023 |
| ASUSTek       | 1201N                       | [3f44d6ed3f](https://bsd-hardware.info/?probe=3f44d6ed3f) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f3b0d5ac82](https://bsd-hardware.info/?probe=f3b0d5ac82) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4fc5363829](https://bsd-hardware.info/?probe=4fc5363829) | Feb 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | [baa7612257](https://bsd-hardware.info/?probe=baa7612257) | Feb 07, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| HP            | Notebook                    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| HP            | Victus by Gaming Laptop ... | [b97af82e5c](https://bsd-hardware.info/?probe=b97af82e5c) | Feb 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [80f8e59cab](https://bsd-hardware.info/?probe=80f8e59cab) | Feb 05, 2023 |
| HP            | 650                         | [48099613ec](https://bsd-hardware.info/?probe=48099613ec) | Feb 05, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [62452eaaaa](https://bsd-hardware.info/?probe=62452eaaaa) | Feb 05, 2023 |
| HP            | 2000                        | [7c997ce022](https://bsd-hardware.info/?probe=7c997ce022) | Feb 05, 2023 |
| Samsung       | 700T1C                      | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c771b7daf4](https://bsd-hardware.info/?probe=c771b7daf4) | Feb 05, 2023 |
| Toshiba       | PORTEGE Z930                | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [96df89832f](https://bsd-hardware.info/?probe=96df89832f) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [97da411601](https://bsd-hardware.info/?probe=97da411601) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [a8ec146fc6](https://bsd-hardware.info/?probe=a8ec146fc6) | Feb 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d36789c493](https://bsd-hardware.info/?probe=d36789c493) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3e58da5c30](https://bsd-hardware.info/?probe=3e58da5c30) | Feb 02, 2023 |
| Unknown       | Unknown                     | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3309453ed5](https://bsd-hardware.info/?probe=3309453ed5) | Feb 02, 2023 |
| HP            | Mini 210-1000               | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54516414a](https://bsd-hardware.info/?probe=a54516414a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T460p 20FW0018A... | [932e722b2d](https://bsd-hardware.info/?probe=932e722b2d) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| Unknown       | Unknown                     | [4cae5c6bb7](https://bsd-hardware.info/?probe=4cae5c6bb7) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| Acer          | Aspire ES1-520              | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [341bae363a](https://bsd-hardware.info/?probe=341bae363a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [39ae8fb9c8](https://bsd-hardware.info/?probe=39ae8fb9c8) | Jan 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| Dell          | Precision 5540              | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [75b9ef6ee6](https://bsd-hardware.info/?probe=75b9ef6ee6) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| IGEL Techn... | H830C                       | [322cc6bc3b](https://bsd-hardware.info/?probe=322cc6bc3b) | Jan 29, 2023 |
| Razer         | Blade Stealth               | [c0b9641604](https://bsd-hardware.info/?probe=c0b9641604) | Jan 29, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [aed5292edc](https://bsd-hardware.info/?probe=aed5292edc) | Jan 28, 2023 |
| Packard Be... | DOT S                       | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| Acer          | Aspire one V1.05            | [1cbfce4d7e](https://bsd-hardware.info/?probe=1cbfce4d7e) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [6914f6aab5](https://bsd-hardware.info/?probe=6914f6aab5) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Acer          | ES1-131-C2BM                | [400ef90a79](https://bsd-hardware.info/?probe=400ef90a79) | Jan 28, 2023 |
| Deciso        | NetBoard-A10                | [5b226a942e](https://bsd-hardware.info/?probe=5b226a942e) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| Dell          | Latitude 5400               | [a266199ace](https://bsd-hardware.info/?probe=a266199ace) | Jan 27, 2023 |
| Acer          | Aspire E3-112               | [513c7ff4be](https://bsd-hardware.info/?probe=513c7ff4be) | Jan 27, 2023 |
| Google        | Kefka                       | [83771661c6](https://bsd-hardware.info/?probe=83771661c6) | Jan 27, 2023 |
| Deciso        | Netboard A20                | [07de4617d2](https://bsd-hardware.info/?probe=07de4617d2) | Jan 26, 2023 |
| Lenovo        | B50-80 80EW                 | [7cbd8c5cbd](https://bsd-hardware.info/?probe=7cbd8c5cbd) | Jan 26, 2023 |
| HP            | EliteBook 840 G3            | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| Google        | Cave                        | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4eb4e63a2c](https://bsd-hardware.info/?probe=4eb4e63a2c) | Jan 25, 2023 |
| HP            | EliteBook 2560p             | [80c808de34](https://bsd-hardware.info/?probe=80c808de34) | Jan 25, 2023 |
| Timi          | TM1607                      | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Timi          | TM1607                      | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Dell          | Latitude 3540               | [a180a149f5](https://bsd-hardware.info/?probe=a180a149f5) | Jan 24, 2023 |
| Deciso        | NetBoard-A20                | [0a40a0b8e2](https://bsd-hardware.info/?probe=0a40a0b8e2) | Jan 24, 2023 |
| Deciso        | NetBoard-A20                | [211bc64e5e](https://bsd-hardware.info/?probe=211bc64e5e) | Jan 24, 2023 |
| Dell          | Latitude 5580               | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Apple         | MacBookPro9,2               | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| ASUSTek       | K50IN                       | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Medion        | S14409                      | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Unknown       | Unknown                     | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Unknown       | Unknown                     | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Acer          | Aspire ES1-571              | [a17d96dde0](https://bsd-hardware.info/?probe=a17d96dde0) | Jan 22, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [8ae819f673](https://bsd-hardware.info/?probe=8ae819f673) | Jan 21, 2023 |
| Datto         | 1000                        | [3d2880dd30](https://bsd-hardware.info/?probe=3d2880dd30) | Jan 21, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [3497ee2fcc](https://bsd-hardware.info/?probe=3497ee2fcc) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| Acer          | TravelMate B311-31          | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Dell          | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Datto         | Unknown                     | [0b70f2b2b0](https://bsd-hardware.info/?probe=0b70f2b2b0) | Jan 18, 2023 |
| Unknown       | Unknown                     | [cbdab56490](https://bsd-hardware.info/?probe=cbdab56490) | Jan 18, 2023 |
| Datto         | 1000                        | [c2abd24ed6](https://bsd-hardware.info/?probe=c2abd24ed6) | Jan 18, 2023 |
| Intel         | H81U                        | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Unknown       | Unknown                     | [4ccf28379a](https://bsd-hardware.info/?probe=4ccf28379a) | Jan 17, 2023 |
| Intel         | H81U                        | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| Apple         | MacBookAir7,2               | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| Lenovo        | B40-70 80F30005BR           | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| HP            | Pavilion dv6                | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | ProBook 455 G7              | [600f7f4f4f](https://bsd-hardware.info/?probe=600f7f4f4f) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| HP            | Pavilion dv6                | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Unknown       | Unknown                     | [c85b254f84](https://bsd-hardware.info/?probe=c85b254f84) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [ceb79702f2](https://bsd-hardware.info/?probe=ceb79702f2) | Jan 13, 2023 |
| Dell          | Latitude E6420              | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Datto         | 1000                        | [ab1aa0f250](https://bsd-hardware.info/?probe=ab1aa0f250) | Jan 11, 2023 |
| Razer         | Blade Stealth               | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | [ef45a319a3](https://bsd-hardware.info/?probe=ef45a319a3) | Jan 11, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| HP            | 2000                        | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Acer          | Aspire A514-54              | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Lenovo        | G50-80 80E5                 | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| Deciso        | OPNsense Appliance          | [cc421d80b4](https://bsd-hardware.info/?probe=cc421d80b4) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Lenovo        | B50-80 80EW                 | [b8f49b8d19](https://bsd-hardware.info/?probe=b8f49b8d19) | Jan 07, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Deciso        | Netboard A20                | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| SLIMBOOK      | ESSENTIAL-15-11             | [3f758732d3](https://bsd-hardware.info/?probe=3f758732d3) | Jan 05, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| Deciso        | NetBoard-A10                | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [aa6c483d4f](https://bsd-hardware.info/?probe=aa6c483d4f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Intel         | Milstead Platform           | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Alienware     | m15 R4                      | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [d5fa6c651c](https://bsd-hardware.info/?probe=d5fa6c651c) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | OPNsense Appliance          | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| Deciso        | NetBoard-A10                | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Star Labs     | Lite                        | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| Alienware     | m15 R4                      | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Tactus        | GeoFlex 110                 | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Sony          | VPCSB11FX                   | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Dell          | Precision M4800             | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Dell          | Latitude E6430              | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Dell          | Latitude E6430              | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Lenovo        | B50-80 80EW                 | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Intel         | H81U                        | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Lenovo        | G510 20238                  | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| Intel         | H81U                        | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Lenovo        | B50-80 80EW                 | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| Dell          | Vostro 15-3568              | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProBook 430 G7              | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | Pavilion dv4                | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| Apple         | MacBook3,1                  | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| Apple         | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| HP            | 2000                        | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| Deciso        | NetBoard-A10                | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| HP            | 245 G6                      | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| DFI           | BE17X(170/171/173)          | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Google        | Lick                        | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Apple         | MacBookPro14,1              | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| HASEE Comp... | N95XKP6                     | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Panasonic     | CF-54-1                     | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Dell          | Inspiron 3442               | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Acidanther... | MacBookPro15,1              | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| HP            | Laptop 14s-fq0xxx           | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| GPD           | P3 MAX                      | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Apple         | MacBook5,1                  | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| Dell          | Inspiron 5558               | [10bece0518](https://bsd-hardware.info/?probe=10bece0518) | Nov 27, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Acer          | Aspire 5738                 | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Dell          | Vostro 3501                 | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Dell          | Latitude D610               | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | [0bbf4f46e7](https://bsd-hardware.info/?probe=0bbf4f46e7) | Nov 24, 2022 |
| ASUSTek       | K55VD                       | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | [75a7bf9b27](https://bsd-hardware.info/?probe=75a7bf9b27) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [e32a104392](https://bsd-hardware.info/?probe=e32a104392) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4d92a3b73](https://bsd-hardware.info/?probe=a4d92a3b73) | Nov 23, 2022 |
| Dell          | XPS 13 9343                 | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| HP            | ProBook 4540s               | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Deciso        | NetBoard-A10                | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Dell          | Latitude D630               | [1c600cc283](https://bsd-hardware.info/?probe=1c600cc283) | Nov 18, 2022 |
| Acer          | Aspire 5251                 | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Acer          | Aspire 5251                 | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7650f7619d](https://bsd-hardware.info/?probe=7650f7619d) | Nov 14, 2022 |
| Medion        | E15415                      | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Deciso        | Netboard A20                | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Deciso        | NetBoard-A20                | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| Deciso        | NetBoard-A10                | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2294352c5a](https://bsd-hardware.info/?probe=2294352c5a) | Nov 08, 2022 |
| HP            | ProBook 4540s               | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| Dell          | Precision M4500             | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| HP            | Laptop 15-da0xxx            | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| Dell          | Latitude 5591               | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| HP            | Pavilion g6                 | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Acer          | JM11-MS                     | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Dell          | Inspiron 7720               | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Apple         | MacBook4,1                  | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Deciso        | NetBoard-A10                | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| Matsushita... | CF-51RCVDNLM                | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| Intel         | H81U                        | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Latitude 5591               | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| ASUSTek       | K53TA                       | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| Alienware     | m15                         | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| Lenovo        | G500 20236                  | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| Apple         | MacBookPro8,1               | [623594855a](https://bsd-hardware.info/?probe=623594855a) | Oct 22, 2022 |
| Dell          | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| Acer          | Aspire E1-570               | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Lenovo        | ThinkPad T61 765912G        | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| HP            | Laptop 15q-bu0xx            | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Unknown       | Unknown                     | [3b7146c456](https://bsd-hardware.info/?probe=3b7146c456) | Oct 14, 2022 |
| Unknown       | Unknown                     | [1ad8d9e64c](https://bsd-hardware.info/?probe=1ad8d9e64c) | Oct 14, 2022 |
| Intel         | H81U                        | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| Dell          | Latitude 5591               | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| Dell          | Latitude 5591               | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Dell          | Latitude E6420              | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK U904               | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Acer          | Aspire ES1-523              | [92a125995f](https://bsd-hardware.info/?probe=92a125995f) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| Acer          | Aspire F5-573               | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| Dell          | Precision 5510              | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Dell          | Latitude E6420              | [07b078fdef](https://bsd-hardware.info/?probe=07b078fdef) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| HP            | ProBook 4540s               | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Deciso        | OPNsense Appliance          | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| IBM           | ThinkPad T43 18714AG        | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad W530 2436CTO       | [6515a18552](https://bsd-hardware.info/?probe=6515a18552) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| Intel         | H81U                        | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Deciso        | OPNsense Appliance          | [659b695f09](https://bsd-hardware.info/?probe=659b695f09) | Sep 26, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW003PM... | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Deciso        | Netboard A20                | [388e27791d](https://bsd-hardware.info/?probe=388e27791d) | Sep 23, 2022 |
| Toshiba       | Satellite BE96-F299         | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Unknown       | Unknown                     | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Deciso        | OPNsense Appliance          | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| Acer          | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Dell          | Precision 7710              | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| HP            | Pavilion dv6700             | [f3058f97f9](https://bsd-hardware.info/?probe=f3058f97f9) | Sep 18, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| HP            | EliteBook 840 G3            | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| IBM           | ThinkPad T43 18714AG        | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| Deciso        | Netboard A20                | [8af40be425](https://bsd-hardware.info/?probe=8af40be425) | Sep 13, 2022 |
| SIEMENS       | SIMATIC IPC127E             | [d16e38e6b2](https://bsd-hardware.info/?probe=d16e38e6b2) | Sep 12, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Dell          | XPS M1330                   | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Apple         | MacBook5,2                  | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Intel         | SandyBridge Platform        | [7c10326786](https://bsd-hardware.info/?probe=7c10326786) | Sep 09, 2022 |
| Toshiba       | Satellite A200              | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Dell          | Precision 7540              | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Dell          | Latitude 5310               | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4f31f81571](https://bsd-hardware.info/?probe=4f31f81571) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | Precision 7550              | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Dell          | XPS 13 9343                 | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Deciso        | NetBoard-A10                | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| Apple         | MacBookPro8,1               | [0ff0fc4c3b](https://bsd-hardware.info/?probe=0ff0fc4c3b) | Sep 01, 2022 |
| Dell          | Latitude E5550              | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Dell          | Precision 7710              | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Toshiba       | Satellite A300              | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fc259fcf3e](https://bsd-hardware.info/?probe=fc259fcf3e) | Aug 30, 2022 |
| Dell          | Precision 5540              | [0c5089634d](https://bsd-hardware.info/?probe=0c5089634d) | Aug 30, 2022 |
| Dell          | Precision 5540              | [afb80a84fb](https://bsd-hardware.info/?probe=afb80a84fb) | Aug 30, 2022 |
| HP            | Unknown                     | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a5c0fe3db8](https://bsd-hardware.info/?probe=a5c0fe3db8) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Dell          | Latitude 7390               | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Dell          | Precision 7550              | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| Toshiba       | Satellite S55t-B            | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | ENVY Notebook               | [7e33273132](https://bsd-hardware.info/?probe=7e33273132) | Aug 25, 2022 |
| Deciso        | NetBoard-A10                | [aefb2f4660](https://bsd-hardware.info/?probe=aefb2f4660) | Aug 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Deciso        | Netboard A20                | [164274c6b4](https://bsd-hardware.info/?probe=164274c6b4) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [cc2a81fc1b](https://bsd-hardware.info/?probe=cc2a81fc1b) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [296e81dd9d](https://bsd-hardware.info/?probe=296e81dd9d) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [692e2f0837](https://bsd-hardware.info/?probe=692e2f0837) | Aug 20, 2022 |
| Unknown       | Unknown                     | [1dfb3adb6b](https://bsd-hardware.info/?probe=1dfb3adb6b) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7576399c3c](https://bsd-hardware.info/?probe=7576399c3c) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| HP            | Pavilion g6                 | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b79fa4531e](https://bsd-hardware.info/?probe=b79fa4531e) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [560213a2d6](https://bsd-hardware.info/?probe=560213a2d6) | Aug 19, 2022 |
| Deciso        | NetBoard-A20                | [7ec18da9e4](https://bsd-hardware.info/?probe=7ec18da9e4) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| HP            | EliteBook 840 G3            | [28929cae10](https://bsd-hardware.info/?probe=28929cae10) | Aug 17, 2022 |
| Dell          | Studio 1537                 | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| HP            | Victus by Gaming Laptop ... | [e09aa880f9](https://bsd-hardware.info/?probe=e09aa880f9) | Aug 16, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Intel         | Apollolake I Platform       | [8b6b08bc82](https://bsd-hardware.info/?probe=8b6b08bc82) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c9bda4b49d](https://bsd-hardware.info/?probe=c9bda4b49d) | Aug 14, 2022 |
| Acer          | Aspire 4552G                | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| MSI           | GF63 Thin 9SC               | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Samsung       | NC210/NC110                 | [6c697b3312](https://bsd-hardware.info/?probe=6c697b3312) | Aug 13, 2022 |
| Alienware     | m15 R4                      | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| Deciso        | NetBoard-A10                | [9d82dae644](https://bsd-hardware.info/?probe=9d82dae644) | Aug 11, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [45e44ad953](https://bsd-hardware.info/?probe=45e44ad953) | Aug 10, 2022 |
| HUAWEI        | BOM-WXX9                    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| Dell          | XPS 13 9360                 | [1d342196fb](https://bsd-hardware.info/?probe=1d342196fb) | Aug 08, 2022 |
| HP            | ProBook 4540s               | [0a7891d53f](https://bsd-hardware.info/?probe=0a7891d53f) | Aug 06, 2022 |
| eMachines     | eME728                      | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Dell          | Inspiron 3581               | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Unknown       | Unknown                     | [7cbf489a64](https://bsd-hardware.info/?probe=7cbf489a64) | Aug 04, 2022 |
| Dell          | Inspiron 15-3567            | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Intel         | H81U                        | [b5e2598580](https://bsd-hardware.info/?probe=b5e2598580) | Aug 03, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| Intel         | H81U                        | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d5e9213bb5](https://bsd-hardware.info/?probe=d5e9213bb5) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Unknown       | Unknown                     | [3efcb47333](https://bsd-hardware.info/?probe=3efcb47333) | Jul 31, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| HP            | EliteBook 8540w             | [0063369c40](https://bsd-hardware.info/?probe=0063369c40) | Jul 30, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [bf5cea4ab5](https://bsd-hardware.info/?probe=bf5cea4ab5) | Jul 30, 2022 |
| HP            | ProBook 430 G4              | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Acer          | Aspire E5-521G              | [dcc5d3116f](https://bsd-hardware.info/?probe=dcc5d3116f) | Jul 29, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| HP            | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Lenovo        | ThinkPad L412 0585AD9       | [cba0fc2340](https://bsd-hardware.info/?probe=cba0fc2340) | Jul 20, 2022 |
| Lenovo        | ThinkPad X200 7458NP9       | [4192abf903](https://bsd-hardware.info/?probe=4192abf903) | Jul 20, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| Deciso        | Netboard A20                | [2bc988b18a](https://bsd-hardware.info/?probe=2bc988b18a) | Jul 18, 2022 |
| HP            | OMEN by Laptop              | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| Dell          | Inspiron 15-3567            | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Deciso        | Netboard A20                | [a4be4171b6](https://bsd-hardware.info/?probe=a4be4171b6) | Jul 17, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Dell          | Inspiron 3505               | [ead2595782](https://bsd-hardware.info/?probe=ead2595782) | Jul 17, 2022 |
| Sony          | VGN-NS21M_S                 | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [995a8a5e6f](https://bsd-hardware.info/?probe=995a8a5e6f) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| Dell          | Inspiron MP061              | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| HP            | Laptop 15-bs1xx             | [fe84e9fda5](https://bsd-hardware.info/?probe=fe84e9fda5) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | [d9efb0425b](https://bsd-hardware.info/?probe=d9efb0425b) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | [6e85a064f0](https://bsd-hardware.info/?probe=6e85a064f0) | Jul 15, 2022 |
| Apple         | MacBook4,1                  | [db03ba8975](https://bsd-hardware.info/?probe=db03ba8975) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Deciso        | OPNsense Appliance          | [05fb88304d](https://bsd-hardware.info/?probe=05fb88304d) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| ASUSTek       | X751LB                      | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Deciso        | Netboard A20                | [743b330db3](https://bsd-hardware.info/?probe=743b330db3) | Jul 12, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| MSI           | GF63 Thin 10SC              | [139855ab73](https://bsd-hardware.info/?probe=139855ab73) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Acer          | Aspire E1-522               | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| HP            | Laptop 15-da0xxx            | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Unknown       | Unknown                     | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Acer          | Nitro AN515-55              | [f98a69101e](https://bsd-hardware.info/?probe=f98a69101e) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Fujitsu       | LIFEBOOK A555               | [1062220932](https://bsd-hardware.info/?probe=1062220932) | Jul 07, 2022 |
| Shuttle       | DS437                       | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Deciso        | Netboard A20                | [c70ba0979e](https://bsd-hardware.info/?probe=c70ba0979e) | Jul 07, 2022 |
| HP            | 250 G6 Notebook PC          | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| Fujitsu       | LIFEBOOK A555               | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| Deciso        | NetBoard-A10                | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| Star Labs     | LabTop                      | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| Dell          | Inspiron 5515               | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Acer          | AOD260                      | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Lenovo        | ThinkPad T430s 2356CV6      | [20df9d5df2](https://bsd-hardware.info/?probe=20df9d5df2) | Jun 29, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Unknown       | Unknown                     | [d9e6e5b83a](https://bsd-hardware.info/?probe=d9e6e5b83a) | Jun 29, 2022 |
| Deciso        | NetBoard-A10                | [ace8b06cd3](https://bsd-hardware.info/?probe=ace8b06cd3) | Jun 29, 2022 |
| System76      | Gazelle                     | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| ASUSTek       | K53TA                       | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Lenovo        | ThinkPad T460 20FN004CUK    | [18b5875c95](https://bsd-hardware.info/?probe=18b5875c95) | Jun 26, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [bb3de13b1a](https://bsd-hardware.info/?probe=bb3de13b1a) | Jun 23, 2022 |
| ASUSTek       | X202E                       | [bdbe613858](https://bsd-hardware.info/?probe=bdbe613858) | Jun 22, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [8ad937beaa](https://bsd-hardware.info/?probe=8ad937beaa) | Jun 21, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| HP            | Unknown                     | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| HP            | EliteBook 8440p             | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Deciso        | Netboard A20                | [8692e7d18b](https://bsd-hardware.info/?probe=8692e7d18b) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| Alienware     | M18xR2                      | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Dell          | Latitude E5420              | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| Apple         | MacBook5,1                  | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Lenovo        | G40-30 80FY                 | [f478f5edc1](https://bsd-hardware.info/?probe=f478f5edc1) | Jun 13, 2022 |
| Dell          | Latitude 7390               | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| HP            | ProBook 4230s               | [8c853f8ca9](https://bsd-hardware.info/?probe=8c853f8ca9) | Jun 11, 2022 |
| Acer          | Aspire E5-571               | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| HP            | EliteBook 830 G5            | [03cb6c6c7f](https://bsd-hardware.info/?probe=03cb6c6c7f) | Jun 09, 2022 |
| Dell          | Latitude E5420              | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| HP            | Pavilion g4                 | [79d8ca2681](https://bsd-hardware.info/?probe=79d8ca2681) | Jun 04, 2022 |
| Unknown       | Unknown                     | [e4d449d8dc](https://bsd-hardware.info/?probe=e4d449d8dc) | Jun 04, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| Dell          | Latitude 7490               | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| Acer          | Aspire E5-576               | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| GPD           | MicroPC                     | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| HP            | Pavilion g6                 | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| System76      | Galago Pro                  | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Apple         | MacBookPro5,3               | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| AAEON         | GENE-SKU7                   | [adecd2a0fc](https://bsd-hardware.info/?probe=adecd2a0fc) | May 26, 2022 |
| Unknown       | Unknown                     | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| Notebook      | N7x0WU                      | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [c41aea0ea7](https://bsd-hardware.info/?probe=c41aea0ea7) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [9e2661b9e0](https://bsd-hardware.info/?probe=9e2661b9e0) | May 24, 2022 |
| Dell          | Latitude E6540              | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| HP            | EliteBook 8530w             | [6401363886](https://bsd-hardware.info/?probe=6401363886) | May 23, 2022 |
| Deciso        | Netboard A20                | [eba0ffa870](https://bsd-hardware.info/?probe=eba0ffa870) | May 23, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Deciso        | Netboard A20                | [1fe95544bd](https://bsd-hardware.info/?probe=1fe95544bd) | May 22, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| HP            | EliteBook 8460p             | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| Dell          | Latitude 5520               | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 223       | 8.37%   |
| helloSystem 0.8.0    | 132       | 4.95%   |
| helloSystem 0.5.0    | 116       | 4.35%   |
| FreeBSD 13.1         | 112       | 4.2%    |
| FreeBSD 13.0         | 111       | 4.17%   |
| helloSystem 0.4.0    | 92        | 3.45%   |
| OpenBSD 6.8          | 90        | 3.38%   |
| helloSystem 0.8.1    | 87        | 3.26%   |
| helloSystem 0.6.0    | 71        | 2.66%   |
| FreeBSD 14.0-CURRENT | 65        | 2.44%   |
| FreeBSD 12.2         | 59        | 2.21%   |
| GhostBSD 20.04.02    | 58        | 2.18%   |
| OpenBSD 6.9          | 55        | 2.06%   |
| OpenBSD 7.2          | 54        | 2.03%   |
| OpenBSD 7.0          | 50        | 1.88%   |
| OpenBSD 7.1          | 41        | 1.54%   |
| FreeBSD 13.1-p5      | 41        | 1.54%   |
| FreeBSD 13.0-p4      | 35        | 1.31%   |
| NomadBSD 1.3.2       | 34        | 1.28%   |
| FreeBSD 12.2-p2      | 34        | 1.28%   |
| NomadBSD 5806f915    | 32        | 1.2%    |
| FreeBSD 13.0-CURRENT | 31        | 1.16%   |
| GhostBSD 21.08.27    | 29        | 1.09%   |
| FreeBSD 13.0-STABLE  | 28        | 1.05%   |
| FreeBSD 12.1         | 28        | 1.05%   |
| FreeBSD 12.1-p8      | 26        | 0.98%   |
| FreeBSD 13.0-p5      | 25        | 0.94%   |
| OpenBSD 6.7          | 23        | 0.86%   |
| FreeBSD 13.0-p3      | 23        | 0.86%   |
| FreeBSD 12.2-p4      | 23        | 0.86%   |
| FreeBSD 12.1-p10     | 23        | 0.86%   |
| FreeBSD 13.1-p2      | 21        | 0.79%   |
| FreeBSD 12.1-p5      | 20        | 0.75%   |
| FreeBSD 13.1-p7      | 19        | 0.71%   |
| FreeBSD 13.0-p7      | 19        | 0.71%   |
| NomadBSD 1.4         | 18        | 0.68%   |
| FreeBSD 12.2-p3      | 18        | 0.68%   |
| FreeBSD 13.0-p2      | 17        | 0.64%   |
| FreeBSD 13.1-STABLE  | 15        | 0.56%   |
| FreeBSD 12.1-STABLE  | 15        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 875       | 37.88%  |
| helloSystem | 692       | 29.96%  |
| OpenBSD     | 260       | 11.26%  |
| OPNsense    | 191       | 8.27%   |
| GhostBSD    | 139       | 6.02%   |
| NomadBSD    | 103       | 4.46%   |
| NetBSD      | 19        | 0.82%   |
| HardenedBSD | 7         | 0.3%    |
| FuryBSD     | 6         | 0.26%   |
| DragonFly   | 6         | 0.26%   |
| MidnightBSD | 4         | 0.17%   |
| FuguIta     | 3         | 0.13%   |
| OS108       | 2         | 0.09%   |
| PC-BSD      | 1         | 0.04%   |
| MyBee       | 1         | 0.04%   |
| LibertyBSD  | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 2154      | 96.25%  |
| i386   | 80        | 3.57%   |
| macppc | 3         | 0.13%   |
| arm64  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 754       | 31.87%  |
| Console       | 320       | 13.52%  |
| XFCE          | 261       | 11.03%  |
| KDE5          | 190       | 8.03%   |
| fvwm          | 181       | 7.65%   |
| MATE          | 171       | 7.23%   |
| Openbox       | 115       | 4.86%   |
| GNOME         | 96        | 4.06%   |
| TWM           | 86        | 3.63%   |
| i3            | 75        | 3.17%   |
| Cinnamon      | 19        | 0.8%    |
| AwesomeWM     | 15        | 0.63%   |
| LXQt          | 14        | 0.59%   |
| Fluxbox       | 11        | 0.46%   |
| Enlightenment | 9         | 0.38%   |
| LXDE          | 8         | 0.34%   |
| Lumina        | 5         | 0.21%   |
| DWM           | 5         | 0.21%   |
| xinitrc       | 4         | 0.17%   |
| IceWM         | 4         | 0.17%   |
| ctwm          | 4         | 0.17%   |
| GNUstep       | 3         | 0.13%   |
| spectrwm      | 2         | 0.08%   |
| Picom         | 2         | 0.08%   |
| Mutter        | 2         | 0.08%   |
| Awesome       | 2         | 0.08%   |
| Xfwm4         | 1         | 0.04%   |
| X-Cinnamon    | 1         | 0.04%   |
| Window Maker  | 1         | 0.04%   |
| sway          | 1         | 0.04%   |
| StumpWM       | 1         | 0.04%   |
| iwm           | 1         | 0.04%   |
| Compton       | 1         | 0.04%   |
| CDE           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1896      | 83.86%  |
| Console | 337       | 14.9%   |
| Wayland | 28        | 1.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 956       | 41.05%  |
| Console | 795       | 34.13%  |
| LightDM | 211       | 9.06%   |
| SDDM    | 204       | 8.76%   |
| XDM     | 78        | 3.35%   |
| GDM     | 70        | 3.01%   |
| Ly      | 12        | 0.52%   |
| PCDM    | 2         | 0.09%   |
| WDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 805       | 34.15%  |
| Unknown         | 669       | 28.38%  |
| C               | 458       | 19.43%  |
| ru_RU           | 59        | 2.5%    |
| en              | 49        | 2.08%   |
| fr_FR           | 47        | 1.99%   |
| de_DE           | 47        | 1.99%   |
| en_GB           | 33        | 1.4%    |
| zh_CN           | 19        | 0.81%   |
| es_ES           | 18        | 0.76%   |
| pl_PL           | 14        | 0.59%   |
| pt_BR           | 11        | 0.47%   |
| it_IT           | 8         | 0.34%   |
| en_CA           | 7         | 0.3%    |
| ru              | 6         | 0.25%   |
| pt              | 6         | 0.25%   |
| de              | 6         | 0.25%   |
| en_NZ           | 5         | 0.21%   |
| cs_CZ           | 5         | 0.21%   |
| uk_UA           | 4         | 0.17%   |
| nb_NO           | 4         | 0.17%   |
| ja_JP           | 4         | 0.17%   |
| es              | 4         | 0.17%   |
| en_AU           | 4         | 0.17%   |
| ko_KR           | 3         | 0.13%   |
| fi_FI           | 3         | 0.13%   |
| en_US.US-ASCII  | 3         | 0.13%   |
| en_US.ISO8859-1 | 3         | 0.13%   |
| tr_TR           | 2         | 0.08%   |
| nl_NL           | 2         | 0.08%   |
| it              | 2         | 0.08%   |
| hu_HU           | 2         | 0.08%   |
| fr              | 2         | 0.08%   |
| es_CO           | 2         | 0.08%   |
| es_AR           | 2         | 0.08%   |
| en_SG           | 2         | 0.08%   |
| en_IE           | 2         | 0.08%   |
| de_DE.ISO8859-1 | 2         | 0.08%   |
| de_CH           | 2         | 0.08%   |
| zh_TW           | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1770      | 78.21%  |
| BIOS | 493       | 21.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 1234      | 53.37%  |
| Ufs     | 577       | 24.96%  |
| Ffs     | 264       | 11.42%  |
| Cd9660  | 230       | 9.95%   |
| Hammer2 | 5         | 0.22%   |
| Xfs     | 1         | 0.04%   |
| Nfs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1970      | 87.25%  |
| MBR     | 261       | 11.56%  |
| Unknown | 23        | 1.02%   |
| BSD     | 4         | 0.18%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 738       | 33.01%  |
| Dell                           | 337       | 15.07%  |
| Hewlett-Packard                | 229       | 10.24%  |
| ASUSTek Computer               | 155       | 6.93%   |
| Acer                           | 129       | 5.77%   |
| Apple                          | 87        | 3.89%   |
| Toshiba                        | 54        | 2.42%   |
| Deciso                         | 54        | 2.42%   |
| Unknown                        | 42        | 1.88%   |
| Samsung Electronics            | 40        | 1.79%   |
| Sony                           | 31        | 1.39%   |
| MSI                            | 27        | 1.21%   |
| Fujitsu                        | 26        | 1.16%   |
| Intel                          | 20        | 0.89%   |
| Google                         | 17        | 0.76%   |
| TUXEDO                         | 16        | 0.72%   |
| Notebook                       | 16        | 0.72%   |
| System76                       | 15        | 0.67%   |
| Panasonic                      | 15        | 0.67%   |
| HUAWEI                         | 14        | 0.63%   |
| IBM                            | 13        | 0.58%   |
| Framework                      | 8         | 0.36%   |
| Packard Bell                   | 7         | 0.31%   |
| Alienware                      | 7         | 0.31%   |
| Timi                           | 6         | 0.27%   |
| LG Electronics                 | 6         | 0.27%   |
| Gigabyte Technology            | 6         | 0.27%   |
| Fujitsu Siemens                | 6         | 0.27%   |
| Gateway                        | 5         | 0.22%   |
| eMachines                      | 5         | 0.22%   |
| Star Labs                      | 4         | 0.18%   |
| SLIMBOOK                       | 4         | 0.18%   |
| Shuttle                        | 4         | 0.18%   |
| Datto                          | 4         | 0.18%   |
| Clevo                          | 4         | 0.18%   |
| Razer                          | 3         | 0.13%   |
| Medion                         | 3         | 0.13%   |
| Matsushita Electric Industrial | 3         | 0.13%   |
| GPD                            | 3         | 0.13%   |
| Chuwi                          | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 52        | 2.33%   |
| Deciso Netboard A20                 | 21        | 0.94%   |
| Deciso NetBoard-A10                 | 14        | 0.63%   |
| Deciso OPNsense Appliance           | 10        | 0.45%   |
| Intel H81U                          | 9         | 0.4%    |
| HP EliteBook 840 G3                 | 8         | 0.36%   |
| Dell Latitude E7240                 | 8         | 0.36%   |
| Dell Latitude E6420                 | 8         | 0.36%   |
| Framework Laptop                    | 7         | 0.31%   |
| Dell Latitude E6430                 | 7         | 0.31%   |
| Dell Inspiron 3442                  | 7         | 0.31%   |
| Apple MacBook4,1                    | 7         | 0.31%   |
| Lenovo ThinkPad X200 745969G        | 6         | 0.27%   |
| HP Pavilion dv6                     | 6         | 0.27%   |
| HP Notebook                         | 6         | 0.27%   |
| Dell Inspiron 3542                  | 6         | 0.27%   |
| Dell Inspiron 15-3567               | 6         | 0.27%   |
| Apple MacBookPro8,1                 | 6         | 0.27%   |
| HP Pavilion g6                      | 5         | 0.22%   |
| HP 2000                             | 5         | 0.22%   |
| Dell Precision M4800                | 5         | 0.22%   |
| Dell Latitude E5570                 | 5         | 0.22%   |
| Dell Latitude E5470                 | 5         | 0.22%   |
| Dell Latitude 5400                  | 5         | 0.22%   |
| Dell Inspiron 3521                  | 5         | 0.22%   |
| Deciso DEC2700 - OPNsense Appliance | 5         | 0.22%   |
| Apple MacBookPro9,2                 | 5         | 0.22%   |
| Apple MacBookAir5,1                 | 5         | 0.22%   |
| Apple MacBook5,1                    | 5         | 0.22%   |
| System76 Lemur Pro                  | 4         | 0.18%   |
| Lenovo ThinkPad X220 4286CTO        | 4         | 0.18%   |
| Lenovo ThinkPad T490 20N2CTO1WW     | 4         | 0.18%   |
| Fujitsu LIFEBOOK A555               | 4         | 0.18%   |
| Dell XPS 13 9360                    | 4         | 0.18%   |
| Dell Precision 7710                 | 4         | 0.18%   |
| Dell Latitude E7440                 | 4         | 0.18%   |
| Dell Latitude E6540                 | 4         | 0.18%   |
| Dell Latitude E6530                 | 4         | 0.18%   |
| Dell Latitude E6410                 | 4         | 0.18%   |
| Dell Latitude E5420                 | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 581       | 25.98%  |
| Dell Latitude       | 153       | 6.84%   |
| Dell Inspiron       | 92        | 4.11%   |
| Acer Aspire         | 85        | 3.8%    |
| Lenovo IdeaPad      | 66        | 2.95%   |
| Unknown             | 52        | 2.33%   |
| HP EliteBook        | 44        | 1.97%   |
| HP Pavilion         | 40        | 1.79%   |
| Toshiba Satellite   | 37        | 1.65%   |
| Dell Precision      | 34        | 1.52%   |
| HP ProBook          | 33        | 1.48%   |
| HP Laptop           | 27        | 1.21%   |
| Dell XPS            | 23        | 1.03%   |
| Fujitsu LIFEBOOK    | 21        | 0.94%   |
| Deciso Netboard     | 21        | 0.94%   |
| Dell Vostro         | 19        | 0.85%   |
| ASUS VivoBook       | 19        | 0.85%   |
| Deciso NetBoard-A10 | 14        | 0.63%   |
| Lenovo Legion       | 13        | 0.58%   |
| Lenovo Yoga         | 12        | 0.54%   |
| IBM ThinkPad        | 11        | 0.49%   |
| HP ZBook            | 11        | 0.49%   |
| HP Compaq           | 11        | 0.49%   |
| Deciso OPNsense     | 10        | 0.45%   |
| Intel H81U          | 9         | 0.4%    |
| Apple MacBookPro8   | 9         | 0.4%    |
| Apple MacBookPro5   | 9         | 0.4%    |
| Framework Laptop    | 8         | 0.36%   |
| ASUS ZenBook        | 8         | 0.36%   |
| ASUS ASUS           | 8         | 0.36%   |
| Acer TravelMate     | 8         | 0.36%   |
| Acer Swift          | 8         | 0.36%   |
| Toshiba PORTEGE     | 7         | 0.31%   |
| Apple MacBook5      | 7         | 0.31%   |
| Apple MacBook4      | 7         | 0.31%   |
| TUXEDO Pulse        | 6         | 0.27%   |
| HP OMEN             | 6         | 0.27%   |
| HP Notebook         | 6         | 0.27%   |
| HP 250              | 6         | 0.27%   |
| Dell Studio         | 6         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 229       | 10.24%  |
| 2019    | 216       | 9.66%   |
| 2021    | 180       | 8.05%   |
| 2011    | 172       | 7.69%   |
| 2018    | 157       | 7.02%   |
| 2013    | 154       | 6.89%   |
| 2015    | 153       | 6.84%   |
| 2012    | 139       | 6.22%   |
| 2016    | 133       | 5.95%   |
| 2022    | 117       | 5.23%   |
| 2014    | 111       | 4.96%   |
| 2010    | 110       | 4.92%   |
| 2017    | 108       | 4.83%   |
| 2009    | 92        | 4.11%   |
| 2008    | 67        | 3%      |
| 2007    | 39        | 1.74%   |
| 2006    | 24        | 1.07%   |
| Unknown | 10        | 0.45%   |
| 2023    | 6         | 0.27%   |
| 2005    | 6         | 0.27%   |
| 2004    | 5         | 0.22%   |
| 2003    | 5         | 0.22%   |
| 2002    | 3         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2236      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2196      | 98.21%  |
| Yes  | 40        | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 821       | 36.3%   |
| 4.01-8.0    | 543       | 24.01%  |
| 16.01-24.0  | 504       | 22.28%  |
| 32.01-64.0  | 121       | 5.35%   |
| 2.01-3.0    | 108       | 4.77%   |
| 3.01-4.0    | 60        | 2.65%   |
| 24.01-32.0  | 28        | 1.24%   |
| 64.01-256.0 | 24        | 1.06%   |
| 0.51-1.0    | 24        | 1.06%   |
| 1.01-2.0    | 20        | 0.88%   |
| 0.01-0.5    | 8         | 0.35%   |
| 0           | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1283      | 56%     |
| 0.51-1.0    | 628       | 27.41%  |
| 1.01-2.0    | 208       | 9.08%   |
| 2.01-3.0    | 67        | 2.92%   |
| 4.01-8.0    | 24        | 1.05%   |
| Unknown     | 24        | 1.05%   |
| 8.01-16.0   | 19        | 0.83%   |
| 0           | 18        | 0.79%   |
| 3.01-4.0    | 9         | 0.39%   |
| 24.01-32.0  | 4         | 0.17%   |
| 16.01-24.0  | 4         | 0.17%   |
| 32.01-64.0  | 2         | 0.09%   |
| 64.01-256.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1673      | 73.02%  |
| 2      | 440       | 19.21%  |
| 0      | 111       | 4.85%   |
| 3      | 56        | 2.44%   |
| 4      | 10        | 0.44%   |
| 58     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1612      | 71.42%  |
| Yes       | 645       | 28.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1931      | 86.32%  |
| No        | 306       | 13.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2088      | 93.21%  |
| No        | 152       | 6.79%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1456      | 64.37%  |
| No        | 806       | 35.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 435       | 19.31%  |
| Germany     | 252       | 11.19%  |
| Russia      | 149       | 6.61%   |
| France      | 115       | 5.1%    |
| UK          | 88        | 3.91%   |
| Brazil      | 84        | 3.73%   |
| Canada      | 70        | 3.11%   |
| China       | 67        | 2.97%   |
| Poland      | 65        | 2.89%   |
| Netherlands | 60        | 2.66%   |
| Italy       | 60        | 2.66%   |
| Spain       | 58        | 2.57%   |
| Ukraine     | 40        | 1.78%   |
| Australia   | 38        | 1.69%   |
| Indonesia   | 37        | 1.64%   |
| India       | 36        | 1.6%    |
| Switzerland | 33        | 1.46%   |
| Sweden      | 31        | 1.38%   |
| Austria     | 29        | 1.29%   |
| Czechia     | 25        | 1.11%   |
| Japan       | 24        | 1.07%   |
| Norway      | 22        | 0.98%   |
| Hungary     | 22        | 0.98%   |
| Romania     | 21        | 0.93%   |
| Mexico      | 20        | 0.89%   |
| Finland     | 20        | 0.89%   |
| Portugal    | 19        | 0.84%   |
| Bulgaria    | 16        | 0.71%   |
| Argentina   | 15        | 0.67%   |
| Turkey      | 14        | 0.62%   |
| Greece      | 14        | 0.62%   |
| Denmark     | 14        | 0.62%   |
| Philippines | 12        | 0.53%   |
| New Zealand | 12        | 0.53%   |
| Colombia    | 12        | 0.53%   |
| Belgium     | 12        | 0.53%   |
| Latvia      | 11        | 0.49%   |
| Vietnam     | 10        | 0.44%   |
| Slovakia    | 9         | 0.4%    |
| Lithuania   | 9         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 56        | 2.31%   |
| Berlin            | 28        | 1.15%   |
| Vienna            | 24        | 0.99%   |
| Montreal          | 23        | 0.95%   |
| Brooklyn          | 22        | 0.91%   |
| Paris             | 21        | 0.87%   |
| Zurich            | 16        | 0.66%   |
| St Petersburg     | 16        | 0.66%   |
| Jakarta           | 15        | 0.62%   |
| Kyiv              | 14        | 0.58%   |
| Amsterdam         | 14        | 0.58%   |
| Warsaw            | 13        | 0.54%   |
| Rome              | 12        | 0.49%   |
| Riga              | 11        | 0.45%   |
| Madrid            | 11        | 0.45%   |
| Seattle           | 10        | 0.41%   |
| Munich            | 10        | 0.41%   |
| London            | 10        | 0.41%   |
| Frankfurt am Main | 10        | 0.41%   |
| Sydney            | 9         | 0.37%   |
| Saint-Laurent     | 9         | 0.37%   |
| Portland          | 9         | 0.37%   |
| New York          | 9         | 0.37%   |
| Los Angeles       | 9         | 0.37%   |
| Dublin            | 9         | 0.37%   |
| Bucharest         | 8         | 0.33%   |
| Brighton          | 8         | 0.33%   |
| Barcelona         | 8         | 0.33%   |
| Athens            | 8         | 0.33%   |
| Wroclaw           | 7         | 0.29%   |
| Vilnius           | 7         | 0.29%   |
| Vancouver         | 7         | 0.29%   |
| Sofia             | 7         | 0.29%   |
| Shanghai          | 7         | 0.29%   |
| Krakow            | 7         | 0.29%   |
| Hamburg           | 7         | 0.29%   |
| Guangzhou         | 7         | 0.29%   |
| Gdansk            | 7         | 0.29%   |
| Franconville      | 7         | 0.29%   |
| Chicago           | 7         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 454       | 603    | 17.63%  |
| WDC                 | 340       | 426    | 13.2%   |
| Seagate             | 228       | 284    | 8.85%   |
| Toshiba             | 183       | 258    | 7.11%   |
| Kingston            | 158       | 194    | 6.14%   |
| Crucial             | 131       | 169    | 5.09%   |
| SanDisk             | 126       | 149    | 4.89%   |
| Hitachi             | 96        | 115    | 3.73%   |
| Transcend           | 92        | 127    | 3.57%   |
| Intel               | 84        | 105    | 3.26%   |
| NVMe                | 75        | 99     | 2.91%   |
| HGST                | 52        | 119    | 2.02%   |
| SK hynix            | 50        | 59     | 1.94%   |
| Micron Technology   | 42        | 50     | 1.63%   |
| A-DATA Technology   | 42        | 56     | 1.63%   |
| Apple               | 30        | 31     | 1.17%   |
| Fujitsu             | 23        | 32     | 0.89%   |
| SPCC                | 20        | 24     | 0.78%   |
| PNY                 | 20        | 22     | 0.78%   |
| Phison              | 16        | 23     | 0.62%   |
| KIOXIA              | 16        | 16     | 0.62%   |
| KingSpec            | 16        | 19     | 0.62%   |
| Gigabyte Technology | 14        | 18     | 0.54%   |
| China               | 14        | 16     | 0.54%   |
| LITEON              | 13        | 18     | 0.5%    |
| Corsair             | 11        | 11     | 0.43%   |
| Patriot             | 10        | 13     | 0.39%   |
| OCZ                 | 10        | 14     | 0.39%   |
| Intenso             | 10        | 11     | 0.39%   |
| SSSTC               | 9         | 9      | 0.35%   |
| OWC                 | 9         | 10     | 0.35%   |
| Hewlett-Packard     | 9         | 12     | 0.35%   |
| FORESEE             | 8         | 10     | 0.31%   |
| Apacer              | 8         | 10     | 0.31%   |
| Silicon Motion      | 7         | 7      | 0.27%   |
| Netac               | 7         | 7      | 0.27%   |
| LITEONIT            | 7         | 7      | 0.27%   |
| Team                | 6         | 7      | 0.23%   |
| Plextor             | 6         | 6      | 0.23%   |
| Lexar               | 6         | 12     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 36        | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB     | 32        | 1.21%   |
| Toshiba MQ01ABD100 1TB             | 28        | 1.05%   |
| Transcend TS256GMTS952T2 256GB     | 26        | 0.98%   |
| Samsung SSD 860 EVO 500GB          | 22        | 0.83%   |
| Crucial CT500MX500SSD1 500GB       | 22        | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 21        | 0.79%   |
| Toshiba MQ01ABF050 500GB           | 20        | 0.75%   |
| Samsung SSD 850 EVO 250GB          | 20        | 0.75%   |
| Transcend TS256GMTE652T2 256GB     | 19        | 0.72%   |
| Kingston SA400S37120G 120GB        | 15        | 0.56%   |
| HGST HTS721010A9E630 1TB           | 15        | 0.56%   |
| Samsung SSD 850 EVO 500GB          | 14        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB       | 13        | 0.49%   |
| Samsung SSD 860 EVO 250GB          | 13        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB        | 13        | 0.49%   |
| Seagate ST9500325AS 500GB          | 12        | 0.45%   |
| Seagate ST500LT012-9WS142 500GB    | 12        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB    | 11        | 0.41%   |
| Kingston SV300S37A120G 120GB       | 11        | 0.41%   |
| Kingston SA400S37480G 480GB        | 11        | 0.41%   |
| HGST HTS725050A7E630 500GB         | 11        | 0.41%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 10        | 0.38%   |
| Toshiba MQ04ABF100 1TB             | 10        | 0.38%   |
| Seagate ST9500420AS 500GB          | 10        | 0.38%   |
| SanDisk SSD PLUS 240GB             | 10        | 0.38%   |
| Samsung SSD 860 EVO 1TB            | 10        | 0.38%   |
| Crucial CT240BX500SSD1 240GB       | 10        | 0.38%   |
| Seagate ST9320423AS 320GB          | 9         | 0.34%   |
| Seagate ST1000LM048-2E7172 1TB     | 9         | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB       | 9         | 0.34%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 9         | 0.34%   |
| Seagate ST500LM021-1KJ152 500GB    | 8         | 0.3%    |
| Seagate ST1000LM049-2GH172 1TB     | 8         | 0.3%    |
| NVMe WDC PC SN730 SDB 256GB        | 8         | 0.3%    |
| NVMe Samsung SSD 980 500GB         | 8         | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB       | 7         | 0.26%   |
| WDC WD10JPVX-22JC3T0 1TB           | 7         | 0.26%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB | 7         | 0.26%   |
| Transcend TS128GMTE110S 128GB      | 7         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 227       | 283    | 26.96%  |
| WDC                                    | 217       | 265    | 25.77%  |
| Toshiba                                | 131       | 183    | 15.56%  |
| Hitachi                                | 96        | 115    | 11.4%   |
| NVMe                                   | 52        | 66     | 6.18%   |
| HGST                                   | 52        | 119    | 6.18%   |
| Samsung Electronics                    | 29        | 32     | 3.44%   |
| Fujitsu                                | 22        | 30     | 2.61%   |
| Apple                                  | 3         | 3      | 0.36%   |
| Product:              USB Flash Memory | 2         | 2      | 0.24%   |
| Generic                                | 2         | 2      | 0.24%   |
| USB                                    | 1         | 1      | 0.12%   |
| UFD 2.0                                | 1         | 1      | 0.12%   |
| OPENBSD                                | 1         | 1      | 0.12%   |
| Lexar                                  | 1         | 1      | 0.12%   |
| LDLC F6+                               | 1         | 1      | 0.12%   |
| Jetflash                               | 1         | 1      | 0.12%   |
| IBM/Hitachi                            | 1         | 1      | 0.12%   |
| HPE                                    | 1         | 5      | 0.12%   |
| General                                | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 271       | 352    | 21.98%  |
| Kingston            | 134       | 165    | 10.87%  |
| SanDisk             | 126       | 149    | 10.22%  |
| Crucial             | 112       | 143    | 9.08%   |
| Transcend           | 64        | 96     | 5.19%   |
| WDC                 | 61        | 77     | 4.95%   |
| Intel               | 53        | 70     | 4.3%    |
| Apple               | 27        | 28     | 2.19%   |
| Toshiba             | 26        | 32     | 2.11%   |
| A-DATA Technology   | 25        | 35     | 2.03%   |
| Micron Technology   | 21        | 25     | 1.7%    |
| SK hynix            | 20        | 21     | 1.62%   |
| NVMe                | 20        | 23     | 1.62%   |
| SPCC                | 18        | 21     | 1.46%   |
| PNY                 | 18        | 20     | 1.46%   |
| KingSpec            | 16        | 19     | 1.3%    |
| China               | 14        | 16     | 1.14%   |
| LITEON              | 12        | 17     | 0.97%   |
| Corsair             | 11        | 11     | 0.89%   |
| Patriot             | 10        | 13     | 0.81%   |
| OCZ                 | 10        | 14     | 0.81%   |
| Intenso             | 10        | 11     | 0.81%   |
| OWC                 | 9         | 10     | 0.73%   |
| Gigabyte Technology | 9         | 12     | 0.73%   |
| Hewlett-Packard     | 8         | 11     | 0.65%   |
| Apacer              | 8         | 10     | 0.65%   |
| Netac               | 7         | 7      | 0.57%   |
| LITEONIT            | 7         | 7      | 0.57%   |
| Team                | 6         | 7      | 0.49%   |
| Plextor             | 6         | 6      | 0.49%   |
| GOODRAM             | 6         | 6      | 0.49%   |
| Phison              | 5         | 6      | 0.41%   |
| Lexar               | 5         | 11     | 0.41%   |
| Kston               | 5         | 7      | 0.41%   |
| Hoodisk             | 5         | 6      | 0.41%   |
| Zheino              | 4         | 7      | 0.32%   |
| FORESEE             | 4         | 6      | 0.32%   |
| Mushkin             | 3         | 3      | 0.24%   |
| Leven               | 3         | 3      | 0.24%   |
| KingDian            | 3         | 3      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1112      | 1547   | 46.33%  |
| HDD  | 795       | 1113   | 33.13%  |
| NVMe | 493       | 654    | 20.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1757      | 2660   | 78.09%  |
| NVMe | 493       | 654    | 21.91%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1413      | 1978   | 74.88%  |
| 0.51-1.0        | 399       | 533    | 21.14%  |
| 1.01-2.0        | 65        | 90     | 3.44%   |
| 3.01-4.0        | 3         | 51     | 0.16%   |
| 4.01-10.0       | 3         | 3      | 0.16%   |
| 2.01-3.0        | 2         | 3      | 0.11%   |
| More than 100.0 | 1         | 1      | 0.05%   |
| 0               | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 736       | 31.17%  |
| 1-20           | 564       | 23.89%  |
| 251-500        | 476       | 20.16%  |
| 501-1000       | 210       | 8.89%   |
| 51-100         | 182       | 7.71%   |
| 21-50          | 129       | 5.46%   |
| 1001-2000      | 39        | 1.65%   |
| Unknown        | 21        | 0.89%   |
| 2001-3000      | 3         | 0.13%   |
| More than 3000 | 1         | 0.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1931      | 83.3%   |
| 21-50          | 190       | 8.2%    |
| 51-100         | 77        | 3.32%   |
| 101-250        | 69        | 2.98%   |
| Unknown        | 21        | 0.91%   |
| 251-500        | 19        | 0.82%   |
| 501-1000       | 10        | 0.43%   |
| More than 3000 | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 11        | 12     | 2.73%   |
| Seagate ST500LT012-9WS142 500GB    | 9         | 13     | 2.23%   |
| Seagate ST9500420AS 500GB          | 8         | 10     | 1.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 10     | 1.99%   |
| HGST HTS725050A7E630 500GB         | 8         | 14     | 1.99%   |
| Toshiba MQ01ABF050 500GB           | 6         | 8      | 1.49%   |
| Seagate ST9320423AS 320GB          | 6         | 6      | 1.49%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 6      | 1.49%   |
| Seagate ST500LM021-1KJ152 500GB    | 6         | 6      | 1.49%   |
| Seagate ST9500325AS 500GB          | 5         | 7      | 1.24%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 6      | 1.24%   |
| Hitachi HTS541612J9SA00 120GB      | 5         | 5      | 1.24%   |
| Toshiba MK3261GSYN 320GB           | 4         | 6      | 0.99%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 0.99%   |
| Hitachi HTS545032B9A300 320GB      | 4         | 6      | 0.99%   |
| Toshiba MQ01ABD075 752GB           | 3         | 3      | 0.74%   |
| Toshiba MQ01ABD032 320GB           | 3         | 4      | 0.74%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 0.74%   |
| Seagate ST9160412AS 160GB          | 3         | 3      | 0.74%   |
| Seagate ST320LT007-9ZV142 320GB    | 3         | 3      | 0.74%   |
| Micron Technology 1100 SATA 256GB  | 3         | 3      | 0.74%   |
| Kingston SA400S37240G 240GB        | 3         | 3      | 0.74%   |
| Intel SSDSC2BF180A4L 180GB         | 3         | 3      | 0.74%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.74%   |
| Hitachi HTS545025B9SA02 250GB      | 3         | 5      | 0.74%   |
| HGST HTS721010A9E630 1TB           | 3         | 16     | 0.74%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 2         | 2      | 0.5%    |
| WDC WD3200BPVT-80JJ5T0 320GB       | 2         | 2      | 0.5%    |
| WDC WD3200BPVT-75ZEST0 320GB       | 2         | 2      | 0.5%    |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 0.5%    |
| WDC WD10JPVX-75JC3T0 1TB           | 2         | 2      | 0.5%    |
| WDC WD10JPVX-60JC3T1 1TB           | 2         | 2      | 0.5%    |
| WDC WD10JPVX-60JC3T0 1TB           | 2         | 2      | 0.5%    |
| Toshiba MQ04ABF100 1TB             | 2         | 2      | 0.5%    |
| Toshiba MQ01ACF032 320GB           | 2         | 4      | 0.5%    |
| Toshiba MK6475GSX 640GB            | 2         | 3      | 0.5%    |
| Toshiba MK5061GSYN 500GB           | 2         | 2      | 0.5%    |
| Toshiba MK3265GSXN 320GB           | 2         | 7      | 0.5%    |
| Toshiba MK2546GSX 250GB            | 2         | 2      | 0.5%    |
| SSSTC CVB-8D128-HP 128GB           | 2         | 2      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 119    | 23.62%  |
| Toshiba             | 60        | 84     | 15.08%  |
| Hitachi             | 55        | 64     | 13.82%  |
| WDC                 | 51        | 54     | 12.81%  |
| Samsung Electronics | 24        | 27     | 6.03%   |
| Kingston            | 22        | 24     | 5.53%   |
| HGST                | 18        | 40     | 4.52%   |
| Intel               | 16        | 19     | 4.02%   |
| SanDisk             | 9         | 10     | 2.26%   |
| Micron Technology   | 7         | 7      | 1.76%   |
| Crucial             | 7         | 10     | 1.76%   |
| Fujitsu             | 5         | 8      | 1.26%   |
| A-DATA Technology   | 4         | 8      | 1.01%   |
| SK hynix            | 3         | 3      | 0.75%   |
| Corsair             | 3         | 3      | 0.75%   |
| Apple               | 3         | 3      | 0.75%   |
| SSSTC               | 2         | 2      | 0.5%    |
| OCZ                 | 2         | 2      | 0.5%    |
| LITEON              | 2         | 2      | 0.5%    |
| China               | 2         | 3      | 0.5%    |
| Transcend           | 1         | 1      | 0.25%   |
| SMI                 | 1         | 1      | 0.25%   |
| Patriot             | 1         | 1      | 0.25%   |
| Kston               | 1         | 1      | 0.25%   |
| KingSpec            | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |
| Hewlett-Packard     | 1         | 2      | 0.25%   |
| Fanxiang            | 1         | 1      | 0.25%   |
| AGI                 | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 119    | 32.3%   |
| Toshiba             | 58        | 78     | 19.93%  |
| Hitachi             | 55        | 64     | 18.9%   |
| WDC                 | 50        | 53     | 17.18%  |
| HGST                | 18        | 40     | 6.19%   |
| Samsung Electronics | 9         | 11     | 3.09%   |
| Fujitsu             | 5         | 8      | 1.72%   |
| IBM/Hitachi         | 1         | 1      | 0.34%   |
| Apple               | 1         | 1      | 0.34%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 281       | 375    | 72.42%  |
| SSD  | 102       | 122    | 26.29%  |
| NVMe | 5         | 5      | 1.29%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 128GB                | 2         | 2      | 40%     |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 20%     |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 20%     |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 40%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HPE                 | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1780      | 2686   | 78.66%  |
| Malfunc  | 387       | 502    | 17.1%   |
| Detected | 91        | 121    | 4.02%   |
| Failed   | 5         | 5      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1663      | 66.76%  |
| AMD                                     | 214       | 8.59%   |
| Samsung Electronics                     | 204       | 8.19%   |
| SanDisk                                 | 92        | 3.69%   |
| SK hynix                                | 37        | 1.49%   |
| Transcend                               | 26        | 1.04%   |
| Phison Electronics                      | 26        | 1.04%   |
| Kingston Technology Company             | 26        | 1.04%   |
| Toshiba                                 | 25        | 1%      |
| Nvidia                                  | 23        | 0.92%   |
| Micron Technology                       | 23        | 0.92%   |
| KIOXIA                                  | 20        | 0.8%    |
| Micron/Crucial Technology               | 19        | 0.76%   |
| Silicon Motion                          | 18        | 0.72%   |
| ADATA Technology                        | 14        | 0.56%   |
| Solid State Storage Technology          | 8         | 0.32%   |
| Silicon Integrated Systems [SiS]        | 8         | 0.32%   |
| Realtek Semiconductor                   | 7         | 0.28%   |
| Marvell Technology Group                | 6         | 0.24%   |
| Lenovo                                  | 6         | 0.24%   |
| Union Memory (Shenzhen)                 | 5         | 0.2%    |
| JMicron Technology                      | 5         | 0.2%    |
| Shenzhen Longsys Electronics            | 3         | 0.12%   |
| Biwin Storage Technology                | 3         | 0.12%   |
| VIA Technologies                        | 2         | 0.08%   |
| Shenzhen Unionmemory Information System | 2         | 0.08%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.08%   |
| ULi Electronics                         | 1         | 0.04%   |
| Lite-On Technology                      | 1         | 0.04%   |
| Broadcom / LSI                          | 1         | 0.04%   |
| Apple                                   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 229       | 8.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 208       | 7.75%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 178       | 6.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 168       | 6.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 129       | 4.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 106       | 3.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 97        | 3.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 88        | 3.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 81        | 3.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 65        | 2.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 65        | 2.42%   |
| Unknown                                                                          | 64        | 2.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 52        | 1.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 49        | 1.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 44        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 41        | 1.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 40        | 1.49%   |
| Samsung NVMe SSD Controller 980                                                  | 36        | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 32        | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                            | 32        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 27        | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 27        | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 26        | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 26        | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 25        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 25        | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 24        | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 24        | 0.89%   |
| Micron NVMe Storage Controller                                                   | 23        | 0.86%   |
| Nvidia MCP79 AHCI Controller                                                     | 22        | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 21        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 21        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 19        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 18        | 0.67%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 17        | 0.63%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 17        | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 15        | 0.56%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 13        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1701      | 65.85%  |
| NVMe | 553       | 21.41%  |
| IDE  | 234       | 9.06%   |
| RAID | 94        | 3.64%   |
| SAS  | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1920      | 85.75%  |
| AMD          | 313       | 13.98%  |
| PowerPC      | 2         | 0.09%   |
| ARM          | 1         | 0.04%   |
| 123456789ABC | 1         | 0.04%   |
| 11th         | 1         | 0.04%   |
| Unknown      | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 60        | 2.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 48        | 2.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 44        | 1.95%   |
| Intel CPU Version                       | 40        | 1.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 34        | 1.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 30        | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 29        | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 29        | 1.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 26        | 1.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 26        | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 25        | 1.11%   |
| AMD Ryzen Embedded V1500B               | 25        | 1.11%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 24        | 1.07%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 22        | 0.98%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 21        | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 21        | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 20        | 0.89%   |
| AMD EPYC 3201 8-Core Processor          | 20        | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 19        | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 19        | 0.84%   |
| Intel Core 2 Duo                        | 19        | 0.84%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 18        | 0.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 18        | 0.8%    |
| Intel Core i3-6006U CPU @ 2.00GHz       | 18        | 0.8%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 17        | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 0.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 17        | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 16        | 0.71%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 16        | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 16        | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 16        | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 15        | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 15        | 0.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 14        | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 14        | 0.62%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 14        | 0.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 14        | 0.62%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 13        | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 12        | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 12        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 690       | 30.73%  |
| Intel Core i7           | 482       | 21.47%  |
| Intel Core i3           | 159       | 7.08%   |
| Other                   | 143       | 6.37%   |
| Intel Core 2 Duo        | 143       | 6.37%   |
| Intel Celeron           | 112       | 4.99%   |
| AMD Ryzen 7             | 59        | 2.63%   |
| AMD Ryzen 5             | 53        | 2.36%   |
| Intel Atom              | 45        | 2%      |
| Intel Pentium           | 42        | 1.87%   |
| AMD EPYC                | 29        | 1.29%   |
| AMD Ryzen Embedded      | 26        | 1.16%   |
| Intel Pentium M         | 20        | 0.89%   |
| AMD A6                  | 17        | 0.76%   |
| Intel Core 2            | 16        | 0.71%   |
| AMD Ryzen 7 PRO         | 15        | 0.67%   |
| Intel Xeon              | 14        | 0.62%   |
| Intel Genuine           | 14        | 0.62%   |
| AMD Ryzen 3             | 12        | 0.53%   |
| Intel Pentium Silver    | 11        | 0.49%   |
| AMD E1                  | 10        | 0.45%   |
| AMD A8                  | 10        | 0.45%   |
| AMD Ryzen 5 PRO         | 9         | 0.4%    |
| AMD E                   | 9         | 0.4%    |
| Intel Pentium Dual      | 8         | 0.36%   |
| AMD A4                  | 7         | 0.31%   |
| Intel Core m3           | 6         | 0.27%   |
| Intel Core i9           | 6         | 0.27%   |
| AMD A10                 | 6         | 0.27%   |
| Intel Pentium Dual-Core | 5         | 0.22%   |
| AMD E2                  | 5         | 0.22%   |
| Intel Pentium 4         | 4         | 0.18%   |
| Intel Core M            | 4         | 0.18%   |
| Intel Core Duo          | 4         | 0.18%   |
| Intel Celeron M         | 4         | 0.18%   |
| AMD C-50                | 4         | 0.18%   |
| Intel 686-class         | 3         | 0.13%   |
| AMD Ryzen 9             | 3         | 0.13%   |
| AMD GX                  | 3         | 0.13%   |
| Intel Mobile Pentium 4  | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1153      | 51.31%  |
| 4       | 562       | 25.01%  |
| Unknown | 192       | 8.54%   |
| 8       | 121       | 5.38%   |
| 6       | 64        | 2.85%   |
| 1       | 63        | 2.8%    |
| 16      | 55        | 2.45%   |
| 12      | 30        | 1.34%   |
| 10      | 5         | 0.22%   |
| 24      | 1         | 0.04%   |
| 20      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2155      | 95.95%  |
| Unknown | 57        | 2.54%   |
| 2       | 34        | 1.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1451      | 64.6%   |
| 1       | 567       | 25.24%  |
| Unknown | 228       | 10.15%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 376       | 16.76%  |
| IvyBridge       | 232       | 10.34%  |
| Haswell         | 207       | 9.23%   |
| SandyBridge     | 203       | 9.05%   |
| Skylake         | 164       | 7.31%   |
| Penryn          | 134       | 5.97%   |
| Broadwell       | 117       | 5.22%   |
| Westmere        | 96        | 4.28%   |
| Core            | 80        | 3.57%   |
| Zen             | 69        | 3.08%   |
| Unknown         | 65        | 2.9%    |
| Bonnell         | 54        | 2.41%   |
| Silvermont      | 49        | 2.18%   |
| TigerLake       | 47        | 2.1%    |
| Zen 2           | 45        | 2.01%   |
| Zen+            | 44        | 1.96%   |
| P6              | 33        | 1.47%   |
| CometLake       | 32        | 1.43%   |
| Zen 3           | 25        | 1.11%   |
| Goldmont plus   | 24        | 1.07%   |
| Bobcat          | 20        | 0.89%   |
| Excavator       | 19        | 0.85%   |
| Goldmont        | 18        | 0.8%    |
| Puma            | 16        | 0.71%   |
| Jaguar          | 15        | 0.67%   |
| IceLake         | 14        | 0.62%   |
| K10             | 9         | 0.4%    |
| Piledriver      | 7         | 0.31%   |
| NetBurst        | 7         | 0.31%   |
| K10 Llano       | 6         | 0.27%   |
| K8 Hammer       | 5         | 0.22%   |
| Nehalem         | 4         | 0.18%   |
| Steamroller     | 3         | 0.13%   |
| K8 & K10 hybrid | 3         | 0.13%   |
| Geode           | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1734      | 67.52%  |
| Nvidia                           | 433       | 16.86%  |
| AMD                              | 386       | 15.03%  |
| Silicon Integrated Systems [SiS] | 6         | 0.23%   |
| Silicon Motion                   | 3         | 0.12%   |
| VIA Technologies                 | 2         | 0.08%   |
| Trident Microsystems             | 1         | 0.04%   |
| S3 Graphics                      | 1         | 0.04%   |
| Matrox Electronics Systems       | 1         | 0.04%   |
| ATI                              | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 217       | 8.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 188       | 7.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 142       | 5.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 117       | 4.37%   |
| Intel HD Graphics 5500                                                                   | 102       | 3.81%   |
| Intel HD Graphics 620                                                                    | 85        | 3.17%   |
| Intel UHD Graphics 620                                                                   | 81        | 3.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 74        | 2.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 71        | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 59        | 2.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 54        | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 52        | 1.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 50        | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 50        | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 46        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 1.72%   |
| AMD Renoir                                                                               | 44        | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 43        | 1.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 42        | 1.57%   |
| Intel HD Graphics 530                                                                    | 32        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 1.01%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 26        | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 25        | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 22        | 0.82%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 22        | 0.82%   |
| AMD Lucienne                                                                             | 22        | 0.82%   |
| Intel HD Graphics 630                                                                    | 21        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 20        | 0.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 0.67%   |
| Nvidia C79 [GeForce 9400M]                                                               | 18        | 0.67%   |
| Nvidia TU117M                                                                            | 17        | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 0.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.52%   |
| Intel HD Graphics 500                                                                    | 14        | 0.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1189      | 52.89%  |
| Intel + Nvidia           | 285       | 12.68%  |
| 1 x AMD                  | 279       | 12.41%  |
| 2 x Intel                | 194       | 8.63%   |
| 1 x Nvidia               | 118       | 5.25%   |
| Intel + AMD              | 67        | 2.98%   |
| Other                    | 57        | 2.54%   |
| AMD + Nvidia             | 27        | 1.2%    |
| 2 x AMD                  | 11        | 0.49%   |
| 1 x SiS                  | 6         | 0.27%   |
| 2 x Nvidia               | 5         | 0.22%   |
| 1 x Silicon Motion       | 3         | 0.13%   |
| 1 x VIA                  | 2         | 0.09%   |
| 2 x Intel + 1 x Nvidia   | 1         | 0.04%   |
| 1 x Trident Microsystems | 1         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1984      | 87.63%  |
| Unknown     | 141       | 6.23%   |
| Proprietary | 139       | 6.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1985      | 87.14%  |
| 0.01-0.5   | 141       | 6.19%   |
| 1.01-2.0   | 64        | 2.81%   |
| 0.51-1.0   | 45        | 1.98%   |
| 3.01-4.0   | 25        | 1.1%    |
| 7.01-8.0   | 7         | 0.31%   |
| 5.01-6.0   | 6         | 0.26%   |
| 2.01-3.0   | 4         | 0.18%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 313       | 19.29%  |
| AU Optronics            | 306       | 18.85%  |
| Chimei Innolux          | 193       | 11.89%  |
| BOE                     | 181       | 11.15%  |
| Samsung Electronics     | 135       | 8.32%   |
| Lenovo                  | 97        | 5.98%   |
| Apple                   | 52        | 3.2%    |
| Sharp                   | 36        | 2.22%   |
| Chi Mei Optoelectronics | 34        | 2.09%   |
| Dell                    | 24        | 1.48%   |
| InfoVision              | 21        | 1.29%   |
| PANDA                   | 16        | 0.99%   |
| Goldstar                | 16        | 0.99%   |
| Hewlett-Packard         | 15        | 0.92%   |
| AOC                     | 15        | 0.92%   |
| Philips                 | 13        | 0.8%    |
| LG Philips              | 13        | 0.8%    |
| BenQ                    | 12        | 0.74%   |
| Ancor Communications    | 10        | 0.62%   |
| Acer                    | 10        | 0.62%   |
| LGD                     | 8         | 0.49%   |
| HannStar                | 7         | 0.43%   |
| CSO                     | 7         | 0.43%   |
| Panasonic               | 6         | 0.37%   |
| CPT                     | 6         | 0.37%   |
| Toshiba                 | 5         | 0.31%   |
| JDI                     | 5         | 0.31%   |
| Iiyama                  | 5         | 0.31%   |
| ViewSonic               | 4         | 0.25%   |
| Sceptre Tech            | 4         | 0.25%   |
| IBM                     | 4         | 0.25%   |
| Fujitsu Siemens         | 4         | 0.25%   |
| Eizo                    | 3         | 0.18%   |
| ASUSTek Computer        | 3         | 0.18%   |
| Vizio                   | 2         | 0.12%   |
| Unknown                 | 2         | 0.12%   |
| Sony                    | 2         | 0.12%   |
| Nvidia                  | 2         | 0.12%   |
| Lenovo Group Limited    | 2         | 0.12%   |
| HKC                     | 2         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 21        | 1.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 15        | 0.92%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 11        | 0.67%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 11        | 0.67%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 10        | 0.61%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 10        | 0.61%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 9         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 9         | 0.55%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 9         | 0.55%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 9         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 8         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 8         | 0.49%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 8         | 0.49%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 8         | 0.49%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 8         | 0.49%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 8         | 0.49%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 8         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 8         | 0.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 8         | 0.49%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 8         | 0.49%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 8         | 0.49%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 7         | 0.43%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 7         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch         | 7         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 7         | 0.43%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 7         | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 7         | 0.43%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 6         | 0.37%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 6         | 0.37%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 6         | 0.37%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 6         | 0.37%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 6         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 6         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 6         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 6         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch           | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 6         | 0.37%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                   | 6         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 560       | 35.33%  |
| 1366x768 (WXGA)    | 540       | 34.07%  |
| 1280x800 (WXGA)    | 106       | 6.69%   |
| 1600x900 (HD+)     | 98        | 6.18%   |
| 3840x2160 (4K)     | 48        | 3.03%   |
| 2560x1440 (QHD)    | 45        | 2.84%   |
| 1440x900 (WXGA+)   | 29        | 1.83%   |
| 1024x600           | 26        | 1.64%   |
| 1920x1200 (WUXGA)  | 19        | 1.2%    |
| 1280x1024 (SXGA)   | 12        | 0.76%   |
| 1680x1050 (WSXGA+) | 11        | 0.69%   |
| 3200x1800 (QHD+)   | 9         | 0.57%   |
| 2560x1080          | 8         | 0.5%    |
| 2256x1504          | 8         | 0.5%    |
| 2880x1800          | 6         | 0.38%   |
| 2880x1620          | 6         | 0.38%   |
| 1024x768 (XGA)     | 6         | 0.38%   |
| 3440x1440          | 5         | 0.32%   |
| 2560x1600          | 5         | 0.32%   |
| Unknown            | 5         | 0.32%   |
| 1920x540           | 4         | 0.25%   |
| 3000x2000          | 3         | 0.19%   |
| 2160x1440          | 3         | 0.19%   |
| 3840x2400          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 1360x768           | 2         | 0.13%   |
| 9600x2160          | 1         | 0.06%   |
| 720x1280           | 1         | 0.06%   |
| 7040x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5760x1080          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3520x1080          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 2520x1680          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1440x960           | 1         | 0.06%   |
| 1280x854           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 549       | 33.89%  |
| 13      | 492       | 30.37%  |
| 12      | 157       | 9.69%   |
| 17      | 63        | 3.89%   |
| 14      | 60        | 3.7%    |
| 11      | 51        | 3.15%   |
| 24      | 43        | 2.65%   |
| 27      | 34        | 2.1%    |
| Unknown | 29        | 1.79%   |
| 10      | 25        | 1.54%   |
| 23      | 24        | 1.48%   |
| 21      | 13        | 0.8%    |
| 19      | 13        | 0.8%    |
| 34      | 9         | 0.56%   |
| 31      | 8         | 0.49%   |
| 18      | 8         | 0.49%   |
| 9       | 5         | 0.31%   |
| 22      | 4         | 0.25%   |
| 64      | 3         | 0.19%   |
| 29      | 3         | 0.19%   |
| 26      | 3         | 0.19%   |
| 20      | 3         | 0.19%   |
| 16      | 3         | 0.19%   |
| 42      | 2         | 0.12%   |
| 39      | 2         | 0.12%   |
| 54      | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 35      | 1         | 0.06%   |
| 33      | 1         | 0.06%   |
| 32      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |
| 6       | 1         | 0.06%   |
| 5       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 912       | 56.47%  |
| 201-300     | 429       | 26.56%  |
| 501-600     | 93        | 5.76%   |
| 351-400     | 67        | 4.15%   |
| 401-500     | 35        | 2.17%   |
| Unknown     | 29        | 1.8%    |
| 601-700     | 19        | 1.18%   |
| 701-800     | 11        | 0.68%   |
| 1001-1500   | 8         | 0.5%    |
| 801-900     | 5         | 0.31%   |
| 101-200     | 4         | 0.25%   |
| 901-1000    | 2         | 0.12%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1227      | 81.58%  |
| 16/10   | 179       | 11.9%   |
| 3/2     | 28        | 1.86%   |
| Unknown | 26        | 1.73%   |
| 21/9    | 14        | 0.93%   |
| 4/3     | 13        | 0.86%   |
| 5/4     | 12        | 0.8%    |
| 6/5     | 1         | 0.07%   |
| 3.18    | 1         | 0.07%   |
| 11/10   | 1         | 0.07%   |
| 1.96    | 1         | 0.07%   |
| 0.46    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 466       | 28.73%  |
| 91-100         | 431       | 26.57%  |
| 61-70          | 156       | 9.62%   |
| 101-110        | 124       | 7.64%   |
| 71-80          | 79        | 4.87%   |
| 201-250        | 75        | 4.62%   |
| 121-130        | 54        | 3.33%   |
| 51-60          | 50        | 3.08%   |
| 301-350        | 39        | 2.4%    |
| Unknown        | 29        | 1.79%   |
| 41-50          | 28        | 1.73%   |
| 351-500        | 21        | 1.29%   |
| 151-200        | 16        | 0.99%   |
| 141-150        | 13        | 0.8%    |
| 251-300        | 11        | 0.68%   |
| 501-1000       | 9         | 0.55%   |
| 131-140        | 6         | 0.37%   |
| More than 1000 | 5         | 0.31%   |
| 1-40           | 5         | 0.31%   |
| 111-120        | 5         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 674       | 42.15%  |
| 101-120       | 496       | 31.02%  |
| 51-100        | 204       | 12.76%  |
| 161-240       | 150       | 9.38%   |
| More than 240 | 43        | 2.69%   |
| Unknown       | 29        | 1.81%   |
| 1-50          | 3         | 0.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1564      | 67.97%  |
| 0     | 567       | 24.64%  |
| 2     | 163       | 7.08%   |
| 3     | 6         | 0.26%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1499      | 42.55%  |
| Realtek Semiconductor             | 867       | 24.61%  |
| Qualcomm Atheros                  | 442       | 12.55%  |
| Broadcom                          | 253       | 7.18%   |
| AMD                               | 55        | 1.56%   |
| Marvell Technology Group          | 51        | 1.45%   |
| Ericsson Business Mobile Networks | 31        | 0.88%   |
| Ralink Technology                 | 30        | 0.85%   |
| TP-Link                           | 27        | 0.77%   |
| Sierra Wireless                   | 25        | 0.71%   |
| Edimax Technology                 | 23        | 0.65%   |
| Nvidia                            | 21        | 0.6%    |
| Ralink                            | 19        | 0.54%   |
| Samsung Electronics               | 16        | 0.45%   |
| MediaTek                          | 14        | 0.4%    |
| Xiaomi                            | 12        | 0.34%   |
| Dell                              | 12        | 0.34%   |
| Google                            | 11        | 0.31%   |
| JMicron Technology                | 10        | 0.28%   |
| Hewlett-Packard                   | 9         | 0.26%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.23%   |
| Huawei Technologies               | 8         | 0.23%   |
| D-Link System                     | 8         | 0.23%   |
| NetGear                           | 6         | 0.17%   |
| D-Link                            | 6         | 0.17%   |
| Qualcomm Atheros Communications   | 5         | 0.14%   |
| ASUSTek Computer                  | 5         | 0.14%   |
| Qualcomm                          | 4         | 0.11%   |
| Apple                             | 4         | 0.11%   |
| Fibocom                           | 3         | 0.09%   |
| VIA Technologies                  | 2         | 0.06%   |
| Realtek                           | 2         | 0.06%   |
| OPPO Electronics                  | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| Novatel Wireless                  | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| BUFFALO                           | 2         | 0.06%   |
| Atheros                           | 2         | 0.06%   |
| Arduino SA                        | 2         | 0.06%   |
| Van Ooijen Technische Informatica | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 568       | 12.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 198       | 4.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 182       | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 142       | 3.16%   |
| Intel Wireless 8265 / 8275                                              | 129       | 2.87%   |
| Intel Wireless 7260                                                     | 108       | 2.41%   |
| Intel Wireless 8260                                                     | 105       | 2.34%   |
| Intel Wireless 7265                                                     | 102       | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 83        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 70        | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 69        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                     | 69        | 1.54%   |
| Intel Ethernet Connection I219-LM                                       | 63        | 1.4%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0               | 54        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 53        | 1.18%   |
| Intel I210 Gigabit Network Connection                                   | 50        | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                                   | 49        | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 47        | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                                   | 47        | 1.05%   |
| Intel 82577LM Gigabit Network Connection                                | 46        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 43        | 0.96%   |
| Intel Ethernet Connection I218-LM                                       | 41        | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 40        | 0.89%   |
| Intel Wi-Fi 6 AX201                                                     | 39        | 0.87%   |
| Intel Ethernet Connection I217-LM                                       | 38        | 0.85%   |
| Intel Wireless 3165                                                     | 37        | 0.82%   |
| Intel 82567LM Gigabit Network Connection                                | 37        | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 0.8%    |
| Intel Wireless-AC 9260                                                  | 36        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 34        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                          | 33        | 0.73%   |
| Intel I211 Gigabit Network Connection                                   | 32        | 0.71%   |
| Intel Centrino Advanced-N 6200                                          | 32        | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 29        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 29        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                    | 28        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 27        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1316      | 57.12%  |
| Qualcomm Atheros                | 386       | 16.75%  |
| Realtek Semiconductor           | 240       | 10.42%  |
| Broadcom                        | 188       | 8.16%   |
| Ralink Technology               | 30        | 1.3%    |
| TP-Link                         | 27        | 1.17%   |
| Edimax Technology               | 23        | 1%      |
| Sierra Wireless                 | 19        | 0.82%   |
| Ralink                          | 19        | 0.82%   |
| MediaTek                        | 13        | 0.56%   |
| D-Link System                   | 7         | 0.3%    |
| NetGear                         | 6         | 0.26%   |
| D-Link                          | 6         | 0.26%   |
| Qualcomm Atheros Communications | 5         | 0.22%   |
| Dell                            | 5         | 0.22%   |
| ASUSTek Computer                | 5         | 0.22%   |
| BUFFALO                         | 2         | 0.09%   |
| Atheros                         | 2         | 0.09%   |
| Sagem                           | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 142       | 6.09%   |
| Intel Wireless 8265 / 8275                                              | 129       | 5.53%   |
| Intel Wireless 7260                                                     | 108       | 4.63%   |
| Intel Wireless 8260                                                     | 105       | 4.5%    |
| Intel Wireless 7265                                                     | 102       | 4.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 83        | 3.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 70        | 3%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 69        | 2.96%   |
| Intel Wi-Fi 6 AX200                                                     | 69        | 2.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 53        | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 47        | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 43        | 1.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 40        | 1.72%   |
| Intel Wi-Fi 6 AX201                                                     | 39        | 1.67%   |
| Intel Wireless 3165                                                     | 37        | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 1.54%   |
| Intel Wireless-AC 9260                                                  | 36        | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 34        | 1.46%   |
| Intel Centrino Ultimate-N 6300                                          | 32        | 1.37%   |
| Intel Centrino Advanced-N 6200                                          | 32        | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 29        | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 29        | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 27        | 1.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 26        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 23        | 0.99%   |
| Intel WiFi Link 5100                                                    | 23        | 0.99%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 23        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 22        | 0.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 22        | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 22        | 0.94%   |
| Intel Wireless 3160                                                     | 21        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 21        | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 21        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 20        | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 840       | 41.14%  |
| Realtek Semiconductor                  | 768       | 37.61%  |
| Qualcomm Atheros                       | 116       | 5.68%   |
| Broadcom                               | 108       | 5.29%   |
| AMD                                    | 54        | 2.64%   |
| Marvell Technology Group               | 51        | 2.5%    |
| Nvidia                                 | 21        | 1.03%   |
| Samsung Electronics                    | 16        | 0.78%   |
| Xiaomi                                 | 12        | 0.59%   |
| JMicron Technology                     | 10        | 0.49%   |
| Google                                 | 9         | 0.44%   |
| Silicon Integrated Systems [SiS]       | 7         | 0.34%   |
| Qualcomm                               | 4         | 0.2%    |
| Huawei Technologies                    | 3         | 0.15%   |
| Apple                                  | 3         | 0.15%   |
| VIA Technologies                       | 2         | 0.1%    |
| Realtek                                | 2         | 0.1%    |
| OPPO Electronics                       | 2         | 0.1%    |
| OnePlus Technology (Shenzhen)          | 2         | 0.1%    |
| Novatel Wireless                       | 2         | 0.1%    |
| Lenovo                                 | 2         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| HMD Global                             | 1         | 0.05%   |
| Attansic                               | 1         | 0.05%   |
| Aquantia                               | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 568       | 27.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 198       | 9.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 182       | 8.85%   |
| Intel Ethernet Connection I219-LM                                 | 63        | 3.06%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 54        | 2.63%   |
| Intel I210 Gigabit Network Connection                             | 50        | 2.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 49        | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 47        | 2.29%   |
| Intel 82577LM Gigabit Network Connection                          | 46        | 2.24%   |
| Intel Ethernet Connection I218-LM                                 | 41        | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.85%   |
| Intel 82567LM Gigabit Network Connection                          | 37        | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 32        | 1.56%   |
| Intel Ethernet Connection (4) I219-V                              | 28        | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 1.17%   |
| Nvidia MCP79 Ethernet                                             | 21        | 1.02%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.83%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.78%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 0.73%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 14        | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 13        | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 13        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.49%   |
| Intel Ethernet Connection (3) I218-V                              | 10        | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 10        | 0.49%   |
| Intel 82573L Gigabit Ethernet Controller                          | 10        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 9         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 9         | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 9         | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2088      | 50.66%  |
| Ethernet | 1931      | 46.85%  |
| Modem    | 60        | 1.46%   |
| Unknown  | 43        | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1472      | 49.95%  |
| Ethernet | 1452      | 49.27%  |
| Modem    | 13        | 0.44%   |
| Unknown  | 10        | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1733      | 77.3%   |
| 1     | 366       | 16.32%  |
| 6     | 51        | 2.27%   |
| 3     | 46        | 2.05%   |
| 5     | 25        | 1.12%   |
| 0     | 13        | 0.58%   |
| 8     | 3         | 0.13%   |
| 4     | 3         | 0.13%   |
| 10    | 1         | 0.04%   |
| 7     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2093      | 92.12%  |
| Yes  | 179       | 7.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 796       | 54%     |
| Broadcom                        | 155       | 10.52%  |
| Qualcomm Atheros Communications | 103       | 6.99%   |
| Realtek Semiconductor           | 80        | 5.43%   |
| Apple                           | 80        | 5.43%   |
| IMC Networks                    | 51        | 3.46%   |
| Foxconn / Hon Hai               | 46        | 3.12%   |
| Lite-On Technology              | 41        | 2.78%   |
| Dell                            | 31        | 2.1%    |
| Hewlett-Packard                 | 24        | 1.63%   |
| Alps Electric                   | 17        | 1.15%   |
| Cambridge Silicon Radio         | 15        | 1.02%   |
| ASUSTek Computer                | 13        | 0.88%   |
| Ralink                          | 9         | 0.61%   |
| Skylight Digital                | 6         | 0.41%   |
| Toshiba                         | 2         | 0.14%   |
| Creative Technology             | 2         | 0.14%   |
| Opticis                         | 1         | 0.07%   |
| Esel International              | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 406       | 27.49%  |
| Intel AX201 Bluetooth                                       | 103       | 6.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 95        | 6.43%   |
| Intel AX200 Bluetooth                                       | 66        | 4.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 53        | 3.59%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 50        | 3.39%   |
| Apple Bluetooth Host Controller                             | 42        | 2.84%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 32        | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 29        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                            | 29        | 1.96%   |
| Realtek Bluetooth Adapter                                   | 22        | 1.49%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 22        | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 21        | 1.42%   |
| Intel AX210 Bluetooth                                       | 20        | 1.35%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 16        | 1.08%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 16        | 1.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 15        | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                            | 14        | 0.95%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 14        | 0.95%   |
| Apple Broadcom Built-in Bluetooth                           | 14        | 0.95%   |
| Realtek  Bluetooth 4.2 Adapter                              | 13        | 0.88%   |
| Dell DW375 Bluetooth Module                                 | 12        | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 11        | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 11        | 0.74%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 11        | 0.74%   |
| Apple Built-in iSight (no firmware loaded)                  | 11        | 0.74%   |
| Alps Electric UGTZ4 Bluetooth                               | 11        | 0.74%   |
| Realtek Bluetooth 4.0 Adapter                               | 10        | 0.68%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 10        | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 10        | 0.68%   |
| IMC Networks Realtek Bluetooth Adapter                      | 10        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 10        | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 10        | 0.68%   |
| Realtek RTL8723B Bluetooth                                  | 9         | 0.61%   |
| Ralink RT3290 Bluetooth                                     | 9         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                            | 9         | 0.61%   |
| IMC Networks Bluetooth module                               | 8         | 0.54%   |
| Realtek RTL8821A Bluetooth                                  | 7         | 0.47%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 7         | 0.47%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 7         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1862      | 75.32%  |
| AMD                                          | 354       | 14.32%  |
| Nvidia                                       | 168       | 6.8%    |
| Lenovo                                       | 12        | 0.49%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.32%   |
| Realtek Semiconductor                        | 7         | 0.28%   |
| GN Netcom                                    | 7         | 0.28%   |
| Logitech                                     | 6         | 0.24%   |
| C-Media Electronics                          | 6         | 0.24%   |
| Texas Instruments                            | 5         | 0.2%    |
| SteelSeries ApS                              | 3         | 0.12%   |
| Plantronics                                  | 3         | 0.12%   |
| Kingston Technology                          | 3         | 0.12%   |
| Creative Technology                          | 3         | 0.12%   |
| VIA Technologies                             | 2         | 0.08%   |
| JMTek                                        | 2         | 0.08%   |
| Generalplus Technology                       | 2         | 0.08%   |
| ESS Technology                               | 2         | 0.08%   |
| ASUSTek Computer                             | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| ULi Electronics                              | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.04%   |
| Sony                                         | 1         | 0.04%   |
| RODE Microphones                             | 1         | 0.04%   |
| Phison Electronics                           | 1         | 0.04%   |
| Microsoft                                    | 1         | 0.04%   |
| M-Audio                                      | 1         | 0.04%   |
| Hewlett-Packard                              | 1         | 0.04%   |
| DSEA A/S                                     | 1         | 0.04%   |
| CMX Systems                                  | 1         | 0.04%   |
| Cambridge Silicon Radio                      | 1         | 0.04%   |
| Cambridge Audio                              | 1         | 0.04%   |
| Blue Microphones                             | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 298       | 9.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 250       | 8.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 177       | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 173       | 5.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 140       | 4.65%   |
| Intel 8 Series HD Audio Controller                                                                | 140       | 4.65%   |
| Intel Broadwell-U Audio Controller                                                                | 117       | 3.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 112       | 3.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 102       | 3.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 96        | 3.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 79        | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 78        | 2.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 71        | 2.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 63        | 2.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 62        | 2.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 58        | 1.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 53        | 1.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 52        | 1.73%   |
| AMD FCH Azalia Controller                                                                         | 52        | 1.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 48        | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 36        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 36        | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 35        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 31        | 1.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 31        | 1.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 30        | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 26        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 25        | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 24        | 0.8%    |
| Nvidia MCP79 High Definition Audio                                                                | 23        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 18        | 0.6%    |
| AMD Wrestler HDMI Audio                                                                           | 17        | 0.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 17        | 0.56%   |
| AMD High Definition Audio Controller                                                              | 15        | 0.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 0.47%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 13        | 0.43%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13        | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 12        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 648       | 26.88%  |
| SK hynix            | 492       | 20.41%  |
| Micron Technology   | 238       | 9.87%   |
| Kingston            | 214       | 8.88%   |
| Unknown             | 190       | 7.88%   |
| Crucial             | 100       | 4.15%   |
| Transcend           | 65        | 2.7%    |
| Elpida              | 65        | 2.7%    |
| Ramaxel Technology  | 58        | 2.41%   |
| Unknown             | 58        | 2.41%   |
| A-DATA Technology   | 37        | 1.53%   |
| Nanya Technology    | 34        | 1.41%   |
| Corsair             | 31        | 1.29%   |
| Smart               | 26        | 1.08%   |
| G.Skill             | 19        | 0.79%   |
| Team                | 11        | 0.46%   |
| Unknown (ABCD)      | 10        | 0.41%   |
| PNY                 | 8         | 0.33%   |
| 48spaces            | 8         | 0.33%   |
| Teikon              | 7         | 0.29%   |
| Goodram             | 7         | 0.29%   |
| Apacer              | 7         | 0.29%   |
| Smart Brazil        | 5         | 0.21%   |
| Neo Forza           | 5         | 0.21%   |
| Avant               | 5         | 0.21%   |
| Patriot             | 4         | 0.17%   |
| High Bridge         | 4         | 0.17%   |
| ASint Technology    | 4         | 0.17%   |
| Goldkey             | 3         | 0.12%   |
| V-GeN               | 2         | 0.08%   |
| Toshiba             | 2         | 0.08%   |
| Super Talent        | 2         | 0.08%   |
| Silicon Power       | 2         | 0.08%   |
| SHARETRONIC         | 2         | 0.08%   |
| Sesame              | 2         | 0.08%   |
| PUSKILL             | 2         | 0.08%   |
| Magnum Tech         | 2         | 0.08%   |
| KomputerBay         | 2         | 0.08%   |
| GSkill              | 2         | 0.08%   |
| V-Color             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown                                                 | 58        | 2.25%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 45        | 1.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 39        | 1.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 37        | 1.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 36        | 1.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 35        | 1.36%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s  | 32        | 1.24%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 30        | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 28        | 1.09%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s     | 27        | 1.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 27        | 1.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 26        | 1.01%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 23        | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 22        | 0.85%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s   | 21        | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 20        | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 19        | 0.74%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 17        | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 17        | 0.66%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 17        | 0.66%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s        | 16        | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 14        | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 13        | 0.5%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 13        | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 12        | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 12        | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s   | 12        | 0.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 12        | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 11        | 0.43%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s     | 11        | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s  | 11        | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 11        | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 11        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s   | 11        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 11        | 0.43%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s   | 11        | 0.43%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s            | 10        | 0.39%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 10        | 0.39%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 10        | 0.39%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 10        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 984       | 48.62%  |
| DDR4    | 693       | 34.24%  |
| DDR2    | 162       | 8%      |
| LPDDR3  | 59        | 2.92%   |
| LPDDR4  | 35        | 1.73%   |
| DDR     | 26        | 1.28%   |
| Unknown | 26        | 1.28%   |
| SDRAM   | 18        | 0.89%   |
| DRAM    | 9         | 0.44%   |
| DDR5    | 5         | 0.25%   |
| LPDDR5  | 4         | 0.2%    |
| RAM     | 2         | 0.1%    |
| SRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1877      | 92.19%  |
| Row Of Chips | 91        | 4.47%   |
| Chip         | 44        | 2.16%   |
| Unknown      | 14        | 0.69%   |
| DIMM         | 10        | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 775       | 34.69%  |
| 8192  | 729       | 32.63%  |
| 2048  | 388       | 17.37%  |
| 16384 | 206       | 9.22%   |
| 1024  | 83        | 3.72%   |
| 32768 | 29        | 1.3%    |
| 512   | 15        | 0.67%   |
| 256   | 6         | 0.27%   |
| 128   | 2         | 0.09%   |
| 2560  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 613       | 28%     |
| 2667    | 266       | 12.15%  |
| 1333    | 209       | 9.55%   |
| 2400    | 198       | 9.05%   |
| 3200    | 167       | 7.63%   |
| 2133    | 149       | 6.81%   |
| 1334    | 132       | 6.03%   |
| 667     | 105       | 4.8%    |
| Unknown | 70        | 3.2%    |
| 1067    | 64        | 2.92%   |
| 1867    | 58        | 2.65%   |
| 800     | 52        | 2.38%   |
| 533     | 22        | 1.01%   |
| 4267    | 17        | 0.78%   |
| 1066    | 17        | 0.78%   |
| 975     | 11        | 0.5%    |
| 4800    | 5         | 0.23%   |
| 2048    | 5         | 0.23%   |
| 1866    | 5         | 0.23%   |
| 4266    | 4         | 0.18%   |
| 6400    | 3         | 0.14%   |
| 1200    | 3         | 0.14%   |
| 333     | 3         | 0.14%   |
| 2933    | 2         | 0.09%   |
| 166     | 2         | 0.09%   |
| 3733    | 1         | 0.05%   |
| 2666    | 1         | 0.05%   |
| 1596    | 1         | 0.05%   |
| 666     | 1         | 0.05%   |
| 266     | 1         | 0.05%   |
| 200     | 1         | 0.05%   |
| 100     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 50%     |
| Samsung ML-1610 Mono Laser Printer | 1         | 25%     |
| HP LaserJet 1020                   | 1         | 25%     |

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
| Chicony Electronics                    | 468       | 29.92%  |
| Bison Electronics                      | 170       | 10.87%  |
| IMC Networks                           | 155       | 9.91%   |
| Microdia                               | 137       | 8.76%   |
| Realtek Semiconductor                  | 135       | 8.63%   |
| Sunplus Innovation Technology          | 87        | 5.56%   |
| Suyin                                  | 58        | 3.71%   |
| Lite-On Technology                     | 53        | 3.39%   |
| Syntek                                 | 35        | 2.24%   |
| Quanta                                 | 34        | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 2.17%   |
| Apple                                  | 25        | 1.6%    |
| Silicon Motion                         | 24        | 1.53%   |
| Lenovo                                 | 23        | 1.47%   |
| Alcor Micro                            | 20        | 1.28%   |
| Luxvisions Innotech Limited            | 17        | 1.09%   |
| ALi                                    | 13        | 0.83%   |
| Ricoh                                  | 11        | 0.7%    |
| Logitech                               | 11        | 0.7%    |
| Z-Star Microelectronics                | 10        | 0.64%   |
| Importek                               | 8         | 0.51%   |
| Supreme Electronics                    | 4         | 0.26%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.19%   |
| Primax Electronics                     | 3         | 0.19%   |
| Intel                                  | 3         | 0.19%   |
| USB Camera                             | 2         | 0.13%   |
| Unknown                                | 2         | 0.13%   |
| Tripath Technology                     | 2         | 0.13%   |
| Pixart Imaging                         | 2         | 0.13%   |
| OmniVision Technologies                | 2         | 0.13%   |
| Jiangxi Shinetech Optical              | 2         | 0.13%   |
| DigiTech                               | 2         | 0.13%   |
| Y Media                                | 1         | 0.06%   |
| SIMPLO Technology                      | 1         | 0.06%   |
| Nanchang BYD Electronics               | 1         | 0.06%   |
| Goodong Industry                       | 1         | 0.06%   |
| Genesys Logic                          | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| Denron                                 | 1         | 0.06%   |
| Cubeternet                             | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 142       | 8.99%   |
| Bison Integrated Camera                   | 81        | 5.13%   |
| IMC Networks Integrated Camera            | 48        | 3.04%   |
| Microdia Integrated_Webcam_HD             | 40        | 2.53%   |
| Realtek Integrated_Webcam_HD              | 36        | 2.28%   |
| Chicony HD WebCam                         | 36        | 2.28%   |
| Lite-On Integrated Camera                 | 35        | 2.22%   |
| Microdia Integrated Webcam                | 34        | 2.15%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 33        | 2.09%   |
| Sunplus Integrated_Webcam_HD              | 27        | 1.71%   |
| Realtek USB 2.0 PC Camera                 | 23        | 1.46%   |
| Bison Lenovo EasyCamera                   | 21        | 1.33%   |
| Chicony Integrated Camera (1280x720@30)   | 20        | 1.27%   |
| IMC Networks Realtek PC Camera            | 19        | 1.2%    |
| IMC Networks EasyCamera                   | 18        | 1.14%   |
| Chicony Integrated Camera [ThinkPad]      | 16        | 1.01%   |
| Chicony Realtek DMFT RGB                  | 15        | 0.95%   |
| Apple FaceTime HD Camera                  | 15        | 0.95%   |
| Syntek Lenovo EasyCamera                  | 14        | 0.89%   |
| Lenovo Integrated Webcam [R5U877]         | 14        | 0.89%   |
| Chicony HP HD Webcam [Fixed]              | 14        | 0.89%   |
| Chicony Integrated IR Camera              | 13        | 0.82%   |
| Bison SunplusIT Integrated Camera         | 13        | 0.82%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 12        | 0.76%   |
| Chicony Chicony USB2.0 Camera             | 12        | 0.76%   |
| Bison ThinkPad Integrated Camera          | 12        | 0.76%   |
| Syntek EasyCamera                         | 11        | 0.7%    |
| Realtek USB Camera                        | 11        | 0.7%    |
| Microdia Dell Laptop Integrated Webcam HD | 10        | 0.63%   |
| IMC Networks Realtek DMFT RGB             | 10        | 0.63%   |
| Chicony Lenovo EasyCamera                 | 10        | 0.63%   |
| Chicony FJ Camera                         | 10        | 0.63%   |
| Bison Lenovo Integrated Webcam            | 10        | 0.63%   |
| Suyin Integrated_Webcam_HD                | 9         | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD      | 9         | 0.57%   |
| IMC Networks Integrated Webcam            | 9         | 0.57%   |
| Chicony ThinkPad T490 Webcam              | 9         | 0.57%   |
| Bison HD Webcam                           | 9         | 0.57%   |
| ALi Gateway Webcam                        | 9         | 0.57%   |
| Syntek Integrated Camera                  | 8         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 168       | 38.01%  |
| Synaptics                  | 81        | 18.33%  |
| Upek                       | 54        | 12.22%  |
| AuthenTec                  | 40        | 9.05%   |
| Shenzhen Goodix Technology | 35        | 7.92%   |
| STMicroelectronics         | 26        | 5.88%   |
| Broadcom                   | 15        | 3.39%   |
| LighTuning Technology      | 12        | 2.71%   |
| FocalTech Systems          | 4         | 0.9%    |
| Elan Microelectronics      | 4         | 0.9%    |
| Samsung Electronics        | 2         | 0.45%   |
| Next Biometrics            | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 57        | 12.9%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 51        | 11.54%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 33        | 7.47%   |
| Shenzhen Goodix Fingerprint Reader                                           | 28        | 6.33%   |
| Validity Sensors Synaptics WBDI                                              | 27        | 6.11%   |
| STMicroelectronics Fingerprint Reader                                        | 26        | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 24        | 5.43%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 20        | 4.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 16        | 3.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 15        | 3.39%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 3.39%   |
| AuthenTec AES2810                                                            | 11        | 2.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 9         | 2.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 8         | 1.81%   |
| AuthenTec AES1660                                                            | 8         | 1.81%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 6         | 1.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 6         | 1.36%   |
| AuthenTec AES1600                                                            | 6         | 1.36%   |
| Validity Sensors VFS491                                                      | 5         | 1.13%   |
| Validity Sensors Fingerprint scanner                                         | 5         | 1.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.13%   |
| Shenzhen Goodix  Fingerprint Device                                          | 5         | 1.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.9%    |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 0.9%    |
| Synaptics WBDI                                                               | 4         | 0.9%    |
| Elan Fingerprint Sensor                                                      | 4         | 0.9%    |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 3         | 0.68%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 0.68%   |
| FocalTech Systems Fingerprint Reader                                         | 3         | 0.68%   |
| AuthenTec AES2660                                                            | 3         | 0.68%   |
| Synaptics UWP WBDI Device                                                    | 2         | 0.45%   |
| Synaptics UWP WBDI                                                           | 2         | 0.45%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 2         | 0.45%   |
| Samsung CanvasBio Fingerprint Reader                                         | 2         | 0.45%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.45%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.23%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 1         | 0.23%   |

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
| 1     | 774       | 32.92%  |
| 2     | 683       | 29.05%  |
| 3     | 360       | 15.31%  |
| 0     | 316       | 13.44%  |
| 4     | 156       | 6.64%   |
| 5     | 41        | 1.74%   |
| 6     | 14        | 0.6%    |
| 7     | 5         | 0.21%   |
| 9     | 1         | 0.04%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1562      | 41.83%  |
| Bluetooth                | 510       | 13.66%  |
| Card reader              | 450       | 12.05%  |
| Net/wireless             | 443       | 11.86%  |
| Fingerprint reader       | 377       | 10.1%   |
| Firewire controller      | 150       | 4.02%   |
| Graphics card            | 69        | 1.85%   |
| Sound                    | 44        | 1.18%   |
| Storage                  | 41        | 1.1%    |
| Network                  | 35        | 0.94%   |
| Modem                    | 22        | 0.59%   |
| Net/ethernet             | 15        | 0.4%    |
| Storage/ata              | 7         | 0.19%   |
| Storage/raid             | 3         | 0.08%   |
| Storage/nvme             | 2         | 0.05%   |
| Storage/ide              | 2         | 0.05%   |
| Dvb card                 | 2         | 0.05%   |

