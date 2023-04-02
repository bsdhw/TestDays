FreeBSD - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for FreeBSD.

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

Total: 1362

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Chuwi         | Unknown                     | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Google        | Stout                       | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| Dell          | Inspiron 5559               | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| eMachines     | eM350                       | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| Alienware     | 14                          | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Acer          | Nitro AN515-53              | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| ASUSTek       | 1001P                       | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Dell          | Inspiron 5567               | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| Google        | Kohaku                      | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Dell          | Latitude D620               | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| Samsung       | 750XEE                      | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Lenovo        | ThinkPad T430 2347FV6       | [cf016ce514](https://bsd-hardware.info/?probe=cf016ce514) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Acer          | Aspire one V1.05            | [eec371a28f](https://bsd-hardware.info/?probe=eec371a28f) | Feb 13, 2023 |
| Dell          | Inspiron 5567               | [df5f01d72e](https://bsd-hardware.info/?probe=df5f01d72e) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f3b0d5ac82](https://bsd-hardware.info/?probe=f3b0d5ac82) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4fc5363829](https://bsd-hardware.info/?probe=4fc5363829) | Feb 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Samsung       | 700T1C                      | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Toshiba       | PORTEGE Z930                | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d36789c493](https://bsd-hardware.info/?probe=d36789c493) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54516414a](https://bsd-hardware.info/?probe=a54516414a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T460p 20FW0018A... | [932e722b2d](https://bsd-hardware.info/?probe=932e722b2d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [341bae363a](https://bsd-hardware.info/?probe=341bae363a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [39ae8fb9c8](https://bsd-hardware.info/?probe=39ae8fb9c8) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [75b9ef6ee6](https://bsd-hardware.info/?probe=75b9ef6ee6) | Jan 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| Acer          | Aspire one V1.05            | [1cbfce4d7e](https://bsd-hardware.info/?probe=1cbfce4d7e) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| HP            | EliteBook 840 G3            | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4eb4e63a2c](https://bsd-hardware.info/?probe=4eb4e63a2c) | Jan 25, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Dell          | Latitude E6400              | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Acer          | TravelMate B311-31          | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Dell          | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| Dell          | Latitude E6420              | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| Acer          | Aspire A514-54              | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Dell          | XPS 13 9310                 | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| Alienware     | m15 R4                      | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Alienware     | m15 R4                      | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Dell          | Vostro 1400                 | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Dell          | Precision M4800             | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Dell          | Latitude E6430              | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Dell          | Latitude E6430              | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | B50-80 80EW                 | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Dell          | Vostro 15-3568              | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Google        | Lick                        | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Panasonic     | CF-31-5                     | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Dell          | XPS 13 9343                 | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| HP            | ProBook 4540s               | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| Medion        | E15415                      | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| HP            | ProBook 4540s               | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Dell          | Inspiron 7720               | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| Dell          | Precision 5510              | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| IBM           | ThinkPad T43 18714AG        | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Acer          | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| IBM           | ThinkPad T43 18714AG        | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Toshiba       | Satellite A200              | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Dell          | Precision 7540              | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Dell          | Latitude 5310               | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | Precision 7550              | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Dell          | XPS 13 9343                 | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Toshiba       | Satellite A300              | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Dell          | Latitude 7390               | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Dell          | Precision 7550              | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | ENVY Notebook               | [7e33273132](https://bsd-hardware.info/?probe=7e33273132) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [cc2a81fc1b](https://bsd-hardware.info/?probe=cc2a81fc1b) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [560213a2d6](https://bsd-hardware.info/?probe=560213a2d6) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Acer          | Aspire 4552G                | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| MSI           | GF63 Thin 9SC               | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [45e44ad953](https://bsd-hardware.info/?probe=45e44ad953) | Aug 10, 2022 |
| Dell          | Inspiron 3581               | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d5e9213bb5](https://bsd-hardware.info/?probe=d5e9213bb5) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| Dell          | Studio XPS 1340             | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Sony          | VGN-NS21M_S                 | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| HP            | Laptop 15-bs1xx             | [fe84e9fda5](https://bsd-hardware.info/?probe=fe84e9fda5) | Jul 15, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Fujitsu       | LIFEBOOK A555               | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [8ad937beaa](https://bsd-hardware.info/?probe=8ad937beaa) | Jun 21, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Dell          | Latitude E5420              | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Dell          | Latitude 7390               | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | Latitude E5420              | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| Acer          | Aspire E5-576               | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| GPD           | MicroPC                     | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| HP            | Pavilion g6                 | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| System76      | Galago Pro                  | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| Unknown       | Unknown                     | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| Notebook      | N7x0WU                      | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [c41aea0ea7](https://bsd-hardware.info/?probe=c41aea0ea7) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Dell          | Latitude E6540              | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| Dell          | Latitude 5520               | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Dell          | XPS 13 9343                 | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Acer          | Aspire 5742                 | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Dell          | Precision M4800             | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| Acer          | Aspire A715-42G             | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Dell          | Latitude 2100               | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Dell          | Inspiron 15-7568            | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| Dell          | Vostro 5590                 | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| Dell          | Latitude E5570              | [c214ce4ab0](https://bsd-hardware.info/?probe=c214ce4ab0) | May 01, 2022 |
| Toshiba       | Satellite P25               | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| HP            | Laptop 15-dw1xxx            | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Notebook      | N7x0WU                      | [b7c06932a3](https://bsd-hardware.info/?probe=b7c06932a3) | Apr 27, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Apple         | MacBookPro8,3               | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| Dell          | Latitude E6520              | [c4ae703add](https://bsd-hardware.info/?probe=c4ae703add) | Apr 23, 2022 |
| Lenovo        | B570 1068FQG                | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| System76      | Lemur Pro                   | [bbeb7d48fa](https://bsd-hardware.info/?probe=bbeb7d48fa) | Apr 17, 2022 |
| HUAWEI        | NBLL-WXX9                   | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [eda0880c67](https://bsd-hardware.info/?probe=eda0880c67) | Apr 15, 2022 |
| Dell          | Latitude E6440              | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | [edbde611c3](https://bsd-hardware.info/?probe=edbde611c3) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Dell          | Vostro 1400                 | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Deciso        | Netboard A20                | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| Dell          | Precision M4800             | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| ASUSTek       | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| VIT           | M2420                       | [108b4d79a6](https://bsd-hardware.info/?probe=108b4d79a6) | Apr 03, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Deciso        | OPNsense Appliance          | [cdd056df79](https://bsd-hardware.info/?probe=cdd056df79) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK A544               | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| Deciso        | Netboard A20                | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| Deciso        | Netboard A20                | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [315573b63e](https://bsd-hardware.info/?probe=315573b63e) | Mar 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| Gateway       | NV55C                       | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | [6a579dca44](https://bsd-hardware.info/?probe=6a579dca44) | Mar 20, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Dell          | Latitude E7440              | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| ASUSTek       | N50Vc                       | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| Gateway       | LT27                        | [6d1c6f8215](https://bsd-hardware.info/?probe=6d1c6f8215) | Mar 14, 2022 |
| Dell          | Inspiron 5502               | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| Apple         | MacBookPro12,1              | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [be311b6a34](https://bsd-hardware.info/?probe=be311b6a34) | Mar 10, 2022 |
| Dell          | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Framework     | Laptop                      | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Dell          | Latitude E5440              | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | Inspiron 5559               | [c34e21ffd5](https://bsd-hardware.info/?probe=c34e21ffd5) | Feb 26, 2022 |
| Dell          | Latitude E6430              | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Dell          | Latitude 7480               | [f0e8e4a30a](https://bsd-hardware.info/?probe=f0e8e4a30a) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Lenovo        | V145-15AST 81MT             | [bc5296ee7d](https://bsd-hardware.info/?probe=bc5296ee7d) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| Dell          | Latitude 3420               | [f1796d75ed](https://bsd-hardware.info/?probe=f1796d75ed) | Feb 14, 2022 |
| WOOKING       | X5                          | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Apple         | MacBookPro8,1               | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| ASUSTek       | 1215B                       | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| ASUSTek       | A9T                         | [2962e2b02f](https://bsd-hardware.info/?probe=2962e2b02f) | Feb 09, 2022 |
| Notebook      | N7x0WU                      | [5063e8f546](https://bsd-hardware.info/?probe=5063e8f546) | Feb 08, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| System76      | Lemur Pro                   | [713b33351f](https://bsd-hardware.info/?probe=713b33351f) | Feb 06, 2022 |
| Notebook      | NS50_70MU                   | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [f333ed9201](https://bsd-hardware.info/?probe=f333ed9201) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| HUAWEI        | MACHD-WXX9                  | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [c03bfe6a21](https://bsd-hardware.info/?probe=c03bfe6a21) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cb0ebb96d5](https://bsd-hardware.info/?probe=cb0ebb96d5) | Feb 01, 2022 |
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1GX0... | [556fcb7e5e](https://bsd-hardware.info/?probe=556fcb7e5e) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| GPD           | G1621-02                    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| HP            | Notebook                    | [b0e0bc12c8](https://bsd-hardware.info/?probe=b0e0bc12c8) | Jan 30, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| MSI           | GE76 Raider 10UG            | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [652e2e284f](https://bsd-hardware.info/?probe=652e2e284f) | Jan 26, 2022 |
| Dell          | Inspiron 5555               | [e54be582a7](https://bsd-hardware.info/?probe=e54be582a7) | Jan 25, 2022 |
| MSI           | GT75VR 7RF                  | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [268e1621eb](https://bsd-hardware.info/?probe=268e1621eb) | Jan 18, 2022 |
| HP            | EliteBook 8570p             | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1763a44db9](https://bsd-hardware.info/?probe=1763a44db9) | Jan 18, 2022 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [2aea9384ac](https://bsd-hardware.info/?probe=2aea9384ac) | Jan 17, 2022 |
| ASUSTek       | N50Vc                       | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| Acer          | TravelMate 8481TG           | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | [3ef1595af6](https://bsd-hardware.info/?probe=3ef1595af6) | Jan 13, 2022 |
| Lenovo        | ThinkPad E480 20KN0048IA    | [1a2f28f5cc](https://bsd-hardware.info/?probe=1a2f28f5cc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |
| Dell          | Latitude E6430              | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| MSI           | GT75VR 7RF                  | [cca6cc3c0b](https://bsd-hardware.info/?probe=cca6cc3c0b) | Jan 07, 2022 |
| Dell          | Precision 7530              | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| TUXEDO        | N14xWU                      | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| Apple         | MacBook5,1                  | [f0aeeb7f3c](https://bsd-hardware.info/?probe=f0aeeb7f3c) | Jan 05, 2022 |
| Dell          | XPS 15 9575                 | [e7925aa387](https://bsd-hardware.info/?probe=e7925aa387) | Jan 05, 2022 |
| Dell          | Latitude E5450              | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| Toshiba       | TECRA Z40-B                 | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| Dell          | Inspiron 5558               | [3a239ea97a](https://bsd-hardware.info/?probe=3a239ea97a) | Jan 02, 2022 |
| Framework     | Laptop                      | [9c201bb573](https://bsd-hardware.info/?probe=9c201bb573) | Jan 01, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [efccc9b019](https://bsd-hardware.info/?probe=efccc9b019) | Dec 21, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [66b8fc8279](https://bsd-hardware.info/?probe=66b8fc8279) | Dec 18, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP            | ProBook 650 G5              | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [32080a81c5](https://bsd-hardware.info/?probe=32080a81c5) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [e517ae0a82](https://bsd-hardware.info/?probe=e517ae0a82) | Dec 15, 2021 |
| ASUSTek       | 1005P                       | [4c43bd561f](https://bsd-hardware.info/?probe=4c43bd561f) | Dec 14, 2021 |
| HP            | ProBook 440 G6              | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| HP            | ProBook 440 G6              | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| HUAWEI        | KLVL-WXX9                   | [b7841e03f5](https://bsd-hardware.info/?probe=b7841e03f5) | Dec 11, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| Framework     | Laptop                      | [46dec0c088](https://bsd-hardware.info/?probe=46dec0c088) | Dec 08, 2021 |
| Framework     | Laptop                      | [a8cd4dc680](https://bsd-hardware.info/?probe=a8cd4dc680) | Dec 08, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [088facef28](https://bsd-hardware.info/?probe=088facef28) | Dec 08, 2021 |
| Toshiba       | Satellite P755              | [44818070a2](https://bsd-hardware.info/?probe=44818070a2) | Dec 08, 2021 |
| Lenovo        | ThinkPad T470s 20HGS18V0... | [a7b9f4a7f8](https://bsd-hardware.info/?probe=a7b9f4a7f8) | Dec 06, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| ASUSTek       | 1215B                       | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| Samsung       | 530XBB                      | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8f9e9ddde5](https://bsd-hardware.info/?probe=8f9e9ddde5) | Dec 02, 2021 |
| Samsung       | 530XBB                      | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| ASUSTek       | 1015BX                      | [9e57263095](https://bsd-hardware.info/?probe=9e57263095) | Nov 29, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [91d67ba784](https://bsd-hardware.info/?probe=91d67ba784) | Nov 27, 2021 |
| Lenovo        | ThinkPad W530 2447AV9       | [4e7fc367bc](https://bsd-hardware.info/?probe=4e7fc367bc) | Nov 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire E5-521G              | [5306253276](https://bsd-hardware.info/?probe=5306253276) | Nov 23, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| Acer          | Aspire 5560                 | [e117631726](https://bsd-hardware.info/?probe=e117631726) | Nov 22, 2021 |
| Acer          | Aspire A315-21              | [44c1f82bee](https://bsd-hardware.info/?probe=44c1f82bee) | Nov 20, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [d8628f80c0](https://bsd-hardware.info/?probe=d8628f80c0) | Nov 19, 2021 |
| HP            | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ddfd14ef31](https://bsd-hardware.info/?probe=ddfd14ef31) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ad4f0d967d](https://bsd-hardware.info/?probe=ad4f0d967d) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [73774ed18e](https://bsd-hardware.info/?probe=73774ed18e) | Nov 16, 2021 |
| Dell          | Vostro 14-5480              | [0ba4cab539](https://bsd-hardware.info/?probe=0ba4cab539) | Nov 14, 2021 |
| Dell          | G15 5510                    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Dell          | Vostro 1400                 | [1c594c9ded](https://bsd-hardware.info/?probe=1c594c9ded) | Nov 12, 2021 |
| Apple         | MacBook3,1                  | [61f1f0aef0](https://bsd-hardware.info/?probe=61f1f0aef0) | Nov 10, 2021 |
| HP            | Compaq 6720s                | [6b0d316afc](https://bsd-hardware.info/?probe=6b0d316afc) | Nov 10, 2021 |
| ASUSTek       | 1001P                       | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
| HP            | Compaq 6720s                | [06e31b2e77](https://bsd-hardware.info/?probe=06e31b2e77) | Nov 09, 2021 |
| HP            | Mini 110-1000               | [ef66d7a110](https://bsd-hardware.info/?probe=ef66d7a110) | Nov 09, 2021 |
| Dell          | Latitude E6430              | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| IBM           | ThinkPad R52 185869G        | [6fd6fd89c5](https://bsd-hardware.info/?probe=6fd6fd89c5) | Nov 08, 2021 |
| Dell          | Inspiron N5050              | [2fbf2a9b2b](https://bsd-hardware.info/?probe=2fbf2a9b2b) | Nov 06, 2021 |
| Dell          | XPS 13 9350                 | [4cc0fd57a5](https://bsd-hardware.info/?probe=4cc0fd57a5) | Nov 04, 2021 |
| Lenovo        | IdeaPad S510p 20298         | [d3cfb73823](https://bsd-hardware.info/?probe=d3cfb73823) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [c469695daf](https://bsd-hardware.info/?probe=c469695daf) | Nov 04, 2021 |
| Dell          | XPS 13 9343                 | [227c2380d0](https://bsd-hardware.info/?probe=227c2380d0) | Nov 04, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| Toshiba       | Satellite Pro L510          | [52ce915b05](https://bsd-hardware.info/?probe=52ce915b05) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Acer          | Aspire E5-575               | [6ea93bc344](https://bsd-hardware.info/?probe=6ea93bc344) | Oct 31, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| Lenovo        | ThinkPad T430s 23532QG      | [db2a9e5e6f](https://bsd-hardware.info/?probe=db2a9e5e6f) | Oct 29, 2021 |
| Toshiba       | Dakar10FW8                  | [06598a2ed3](https://bsd-hardware.info/?probe=06598a2ed3) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | [e390271460](https://bsd-hardware.info/?probe=e390271460) | Oct 29, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0fa0f325e9](https://bsd-hardware.info/?probe=0fa0f325e9) | Oct 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0PM0... | [7a61d90a55](https://bsd-hardware.info/?probe=7a61d90a55) | Oct 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8ad7b068f4](https://bsd-hardware.info/?probe=8ad7b068f4) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c520513abd](https://bsd-hardware.info/?probe=c520513abd) | Oct 26, 2021 |
| GPD           | MicroPC                     | [8d0ac5e551](https://bsd-hardware.info/?probe=8d0ac5e551) | Oct 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Dell          | XPS 13 9350                 | [a1ab44830c](https://bsd-hardware.info/?probe=a1ab44830c) | Oct 24, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Dell          | XPS 13 9343                 | [4b8421b910](https://bsd-hardware.info/?probe=4b8421b910) | Oct 21, 2021 |
| Lenovo        | G580 26897SJ                | [da14095fb7](https://bsd-hardware.info/?probe=da14095fb7) | Oct 20, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d8a6d0daf3](https://bsd-hardware.info/?probe=d8a6d0daf3) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| Dell          | Inspiron 3493               | [ed41c18cfc](https://bsd-hardware.info/?probe=ed41c18cfc) | Oct 16, 2021 |
| Dell          | Latitude E6430              | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Dell          | XPS 13 9343                 | [7dd8f42ab1](https://bsd-hardware.info/?probe=7dd8f42ab1) | Oct 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 7460               | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [be42957ecd](https://bsd-hardware.info/?probe=be42957ecd) | Oct 10, 2021 |
| Acer          | Acadia V1.45                | [29fe65832b](https://bsd-hardware.info/?probe=29fe65832b) | Oct 10, 2021 |
| Google        | Terra                       | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| ASUSTek       | K53E                        | [4572d8b5e7](https://bsd-hardware.info/?probe=4572d8b5e7) | Oct 08, 2021 |
| Framework     | Laptop                      | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| ASUSTek       | F83VD                       | [5f2df13f5b](https://bsd-hardware.info/?probe=5f2df13f5b) | Oct 06, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5b08c1de3d](https://bsd-hardware.info/?probe=5b08c1de3d) | Oct 06, 2021 |
| ASUSTek       | A9T                         | [83106a58ef](https://bsd-hardware.info/?probe=83106a58ef) | Oct 03, 2021 |
| Valve         | Jupiter                     | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| HP            | Stream Notebook PC 11       | [c8ea8a4c4f](https://bsd-hardware.info/?probe=c8ea8a4c4f) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| Dell          | Latitude 5490               | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| System76      | Darter Pro                  | [f99c9f56b7](https://bsd-hardware.info/?probe=f99c9f56b7) | Sep 25, 2021 |
| Toshiba       | Dakar10FW8                  | [6a4298baaa](https://bsd-hardware.info/?probe=6a4298baaa) | Sep 24, 2021 |
| Dell          | Precision 7710              | [f0bebc2b21](https://bsd-hardware.info/?probe=f0bebc2b21) | Sep 23, 2021 |
| System76      | Galago Pro                  | [ebe0575f31](https://bsd-hardware.info/?probe=ebe0575f31) | Sep 23, 2021 |
| Dell          | Precision 7710              | [46e9438bf9](https://bsd-hardware.info/?probe=46e9438bf9) | Sep 22, 2021 |
| Dell          | Latitude 5491               | [006dc5a9f4](https://bsd-hardware.info/?probe=006dc5a9f4) | Sep 22, 2021 |
| Dell          | Latitude E7450              | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| MSI           | P65 Creator 8RE             | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| ASUSTek       | G551JW                      | [5624c69d4b](https://bsd-hardware.info/?probe=5624c69d4b) | Sep 16, 2021 |
| System76      | Galago Pro                  | [41cd62c0fe](https://bsd-hardware.info/?probe=41cd62c0fe) | Sep 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| IBM           | ThinkPad X41 2525FAG        | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| ASUSTek       | TP300LD                     | [e9d8f7de51](https://bsd-hardware.info/?probe=e9d8f7de51) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Dell          | XPS 13 9343                 | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [ff88b24116](https://bsd-hardware.info/?probe=ff88b24116) | Sep 08, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | [30424125f5](https://bsd-hardware.info/?probe=30424125f5) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | [76da651584](https://bsd-hardware.info/?probe=76da651584) | Sep 08, 2021 |
| Dell          | XPS 15 9570                 | [ee8980fec1](https://bsd-hardware.info/?probe=ee8980fec1) | Sep 07, 2021 |
| ASUSTek       | G551JW                      | [309b5d559f](https://bsd-hardware.info/?probe=309b5d559f) | Sep 07, 2021 |
| System76      | Galago Pro                  | [203560e1f5](https://bsd-hardware.info/?probe=203560e1f5) | Sep 07, 2021 |
| System76      | Galago Pro                  | [d3b33c7681](https://bsd-hardware.info/?probe=d3b33c7681) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b8408cb369](https://bsd-hardware.info/?probe=b8408cb369) | Sep 06, 2021 |
| Panasonic     | CF-F9KWHZZQ2                | [d160186cfb](https://bsd-hardware.info/?probe=d160186cfb) | Sep 05, 2021 |
| Panasonic     | CF-F9KWHZZQ2                | [05e94c09f6](https://bsd-hardware.info/?probe=05e94c09f6) | Sep 05, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [713b72cfff](https://bsd-hardware.info/?probe=713b72cfff) | Sep 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Apple         | MacBookPro5,1               | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | Latitude E6530              | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| HP            | 2000                        | [4e83c9da3f](https://bsd-hardware.info/?probe=4e83c9da3f) | Sep 02, 2021 |
| HP            | 2000                        | [7a48e639e6](https://bsd-hardware.info/?probe=7a48e639e6) | Sep 02, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [67fd361be0](https://bsd-hardware.info/?probe=67fd361be0) | Aug 28, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Notebook      | N7x0WU                      | [7681a46a5b](https://bsd-hardware.info/?probe=7681a46a5b) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| Apple         | MacBookPro8,3               | [455af20b0d](https://bsd-hardware.info/?probe=455af20b0d) | Aug 26, 2021 |
| BANGHO        | MAX G5                      | [d2560f69f7](https://bsd-hardware.info/?probe=d2560f69f7) | Aug 24, 2021 |
| Avell High... | A60 MUV                     | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| Lenovo        | ZhaoYang K4e-IML 81VQ       | [cd3ac84240](https://bsd-hardware.info/?probe=cd3ac84240) | Aug 21, 2021 |
| Dell          | Inspiron N7010              | [0db8536c63](https://bsd-hardware.info/?probe=0db8536c63) | Aug 21, 2021 |
| Toshiba       | Satellite L50-C             | [250db17f57](https://bsd-hardware.info/?probe=250db17f57) | Aug 20, 2021 |
| Toshiba       | Satellite L50-C             | [a2e1cbd3d8](https://bsd-hardware.info/?probe=a2e1cbd3d8) | Aug 20, 2021 |
| Dell          | Latitude E6540              | [7d7cc24971](https://bsd-hardware.info/?probe=7d7cc24971) | Aug 19, 2021 |
| HP            | EliteBook 8570p             | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [b5018b8651](https://bsd-hardware.info/?probe=b5018b8651) | Aug 14, 2021 |
| HP            | EliteBook 8570p             | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Dell          | Latitude E7240              | [762d8366d0](https://bsd-hardware.info/?probe=762d8366d0) | Aug 12, 2021 |
| Lenovo        | Unknown                     | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| HP            | ZBook 17 G2                 | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [6d5e1a13d0](https://bsd-hardware.info/?probe=6d5e1a13d0) | Aug 07, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| Samsung       | 300E5M/300E5L               | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Lenovo        | G505 20240                  | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| Dell          | Inspiron 3442               | [6283cb4190](https://bsd-hardware.info/?probe=6283cb4190) | Aug 01, 2021 |
| Apple         | MacBookPro8,1               | [1d941ee61d](https://bsd-hardware.info/?probe=1d941ee61d) | Jul 31, 2021 |
| HP            | ZBook 17 G2                 | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Intel         | Skylake Platform            | [a9144c7e47](https://bsd-hardware.info/?probe=a9144c7e47) | Jul 25, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| HP            | ZBook 17 G2                 | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Dell          | G5 5505                     | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | [d6feef8717](https://bsd-hardware.info/?probe=d6feef8717) | Jul 23, 2021 |
| Acer          | Aspire A715-75G             | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | [9a3c3705d0](https://bsd-hardware.info/?probe=9a3c3705d0) | Jul 23, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [e16321d2fb](https://bsd-hardware.info/?probe=e16321d2fb) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [122a5774ab](https://bsd-hardware.info/?probe=122a5774ab) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [fdb4ebcf10](https://bsd-hardware.info/?probe=fdb4ebcf10) | Jul 21, 2021 |
| Avell High... | A62 LIV                     | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [daa7e68a1f](https://bsd-hardware.info/?probe=daa7e68a1f) | Jul 21, 2021 |
| Apple         | MacBookPro8,1               | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| Dell          | Inspiron 3521               | [1fed4e841b](https://bsd-hardware.info/?probe=1fed4e841b) | Jul 19, 2021 |
| Dell          | Inspiron 5559               | [e38b3f1f93](https://bsd-hardware.info/?probe=e38b3f1f93) | Jul 19, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| HP            | ProBook 440 G7              | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| Dell          | Inspiron 3442               | [8f8cc52f23](https://bsd-hardware.info/?probe=8f8cc52f23) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| Framework     | Laptop                      | [8a7b477512](https://bsd-hardware.info/?probe=8a7b477512) | Jul 15, 2021 |
| Framework     | Laptop                      | [647138144b](https://bsd-hardware.info/?probe=647138144b) | Jul 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| ASUSTek       | G74Sx                       | [96bee8d702](https://bsd-hardware.info/?probe=96bee8d702) | Jul 12, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [ba0270c8f8](https://bsd-hardware.info/?probe=ba0270c8f8) | Jul 09, 2021 |
| Dell          | Inspiron N5110              | [08641f83e8](https://bsd-hardware.info/?probe=08641f83e8) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| HP            | 250 G4 Notebook PC          | [7c3643f8b1](https://bsd-hardware.info/?probe=7c3643f8b1) | Jul 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [128c08e60f](https://bsd-hardware.info/?probe=128c08e60f) | Jul 04, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| Gigabyte      | MMLP3AP-00                  | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| Dell          | XPS 13 9343                 | [323044ccaf](https://bsd-hardware.info/?probe=323044ccaf) | Jul 03, 2021 |
| Notebook      | W510LU                      | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Acer          | Aspire E5-521               | [f8300de583](https://bsd-hardware.info/?probe=f8300de583) | Jul 01, 2021 |
| Samsung       | NC10                        | [d33644912a](https://bsd-hardware.info/?probe=d33644912a) | Jun 28, 2021 |
| Toshiba       | Satellite C655D             | [10bdf263b3](https://bsd-hardware.info/?probe=10bdf263b3) | Jun 27, 2021 |
| Dell          | Vostro 5481                 | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| ASUSTek       | X556UAK                     | [795f6e5a42](https://bsd-hardware.info/?probe=795f6e5a42) | Jun 26, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [591cbc0879](https://bsd-hardware.info/?probe=591cbc0879) | Jun 24, 2021 |
| Dell          | Inspiron 5567               | [0b90603ace](https://bsd-hardware.info/?probe=0b90603ace) | Jun 23, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| ASUSTek       | G74Sx                       | [8b444409f4](https://bsd-hardware.info/?probe=8b444409f4) | Jun 22, 2021 |
| Lenovo        | ThinkPad X270 20HMS0MA18    | [117b790a84](https://bsd-hardware.info/?probe=117b790a84) | Jun 22, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Dell          | Studio 1558                 | [c2ba752ab5](https://bsd-hardware.info/?probe=c2ba752ab5) | Jun 20, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| IBM           | ThinkPad T42 2374K46        | [acf931a3e0](https://bsd-hardware.info/?probe=acf931a3e0) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7138c789e3](https://bsd-hardware.info/?probe=7138c789e3) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7d36d27958](https://bsd-hardware.info/?probe=7d36d27958) | Jun 19, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | [2b05811c5f](https://bsd-hardware.info/?probe=2b05811c5f) | Jun 18, 2021 |
| LG Electro... | E500-GP01A9                 | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| Acer          | Aspire V3-571G              | [a9fe2f5aad](https://bsd-hardware.info/?probe=a9fe2f5aad) | Jun 16, 2021 |
| LG Electro... | E500-GP01A9                 | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [901005edd3](https://bsd-hardware.info/?probe=901005edd3) | Jun 15, 2021 |
| Dell          | Latitude E6440              | [8fa2c1f5c4](https://bsd-hardware.info/?probe=8fa2c1f5c4) | Jun 13, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3d50ba4d85](https://bsd-hardware.info/?probe=3d50ba4d85) | Jun 13, 2021 |
| Dell          | G5 5505                     | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Dell          | Latitude E6440              | [77f259babe](https://bsd-hardware.info/?probe=77f259babe) | Jun 12, 2021 |
| Dell          | Vostro 5490                 | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| SLIMBOOK      | Unknown                     | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| Dell          | Latitude E4300              | [1150e00893](https://bsd-hardware.info/?probe=1150e00893) | Jun 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [1138d47591](https://bsd-hardware.info/?probe=1138d47591) | Jun 10, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Lenovo        | ThinkPad T410 2518A37       | [c887ff2917](https://bsd-hardware.info/?probe=c887ff2917) | Jun 07, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Acer          | Aspire ES1-132              | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Acer          | Aspire A515-51G             | [53a69aa8c1](https://bsd-hardware.info/?probe=53a69aa8c1) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| HP            | EliteBook 8570p             | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| Acer          | Aspire E5-573G              | [52de90ff3d](https://bsd-hardware.info/?probe=52de90ff3d) | Jun 02, 2021 |
| Apple         | MacBookPro9,1               | [afc70d9c77](https://bsd-hardware.info/?probe=afc70d9c77) | Jun 01, 2021 |
| Notebook      | N7x0WU                      | [ba4260c181](https://bsd-hardware.info/?probe=ba4260c181) | Jun 01, 2021 |
| Sony          | SVF1421DSGW                 | [64f3f02018](https://bsd-hardware.info/?probe=64f3f02018) | Jun 01, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [6311d603ff](https://bsd-hardware.info/?probe=6311d603ff) | May 31, 2021 |
| ASUSTek       | UX31A                       | [67a6df2b68](https://bsd-hardware.info/?probe=67a6df2b68) | May 30, 2021 |
| System76      | Gazelle                     | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
| Dell          | Vostro 5568                 | [84a1925fc9](https://bsd-hardware.info/?probe=84a1925fc9) | May 29, 2021 |
| Dell          | Inspiron N5050              | [9b06ff01bb](https://bsd-hardware.info/?probe=9b06ff01bb) | May 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo        | ThinkPad A485 20MVS0FD00    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Acer          | Nitro AN515-54              | [337a8b5a3d](https://bsd-hardware.info/?probe=337a8b5a3d) | May 28, 2021 |
| Lenovo        | ThinkPad X220 4291PU5       | [c6d626c350](https://bsd-hardware.info/?probe=c6d626c350) | May 24, 2021 |
| Acer          | Aspire E5-571P              | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| ASUSTek       | 1015PX                      | [c6e717c1e9](https://bsd-hardware.info/?probe=c6e717c1e9) | May 24, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | Latitude D620               | [1bd280a155](https://bsd-hardware.info/?probe=1bd280a155) | May 23, 2021 |
| Notebook      | N7x0WU                      | [70760365d0](https://bsd-hardware.info/?probe=70760365d0) | May 20, 2021 |
| Dell          | Latitude E6410              | [c0115917d2](https://bsd-hardware.info/?probe=c0115917d2) | May 19, 2021 |
| Lenovo        | Z51-70 80K6                 | [89ca4554ca](https://bsd-hardware.info/?probe=89ca4554ca) | May 18, 2021 |
| Packard Be... | AOA110                      | [4d9eb84daa](https://bsd-hardware.info/?probe=4d9eb84daa) | May 16, 2021 |
| MSI           | GL65 Leopard 10SFSK         | [a40e426983](https://bsd-hardware.info/?probe=a40e426983) | May 15, 2021 |
| Dell          | Latitude E5550              | [dca8ba9d37](https://bsd-hardware.info/?probe=dca8ba9d37) | May 13, 2021 |
| ASUSTek       | G750JM                      | [37be4ea27a](https://bsd-hardware.info/?probe=37be4ea27a) | May 13, 2021 |
| Apple         | MacBookPro6,2               | [0ab44e95df](https://bsd-hardware.info/?probe=0ab44e95df) | May 12, 2021 |
| Notebook      | NL5xRU                      | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Dell          | G5 5505                     | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Acer          | Predator PH517-61           | [9e03a76684](https://bsd-hardware.info/?probe=9e03a76684) | May 08, 2021 |
| Dell          | Latitude 5500               | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Toshiba       | TECRA M11                   | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| Dell          | G5 5505                     | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| HP            | Laptop 17-by0xxx            | [10af242f8b](https://bsd-hardware.info/?probe=10af242f8b) | May 07, 2021 |
| Lenovo        | ThinkPad X220 4290NE3       | [9d15dab449](https://bsd-hardware.info/?probe=9d15dab449) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | [b0b4ca9f27](https://bsd-hardware.info/?probe=b0b4ca9f27) | May 07, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [d5adf152a7](https://bsd-hardware.info/?probe=d5adf152a7) | May 05, 2021 |
| Pegatron      | T12Ah                       | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Lenovo        | ThinkPad T440p 20AW0049L... | [7660f9b6db](https://bsd-hardware.info/?probe=7660f9b6db) | May 02, 2021 |
| Acer          | Aspire V5-531               | [edbf1ff1c6](https://bsd-hardware.info/?probe=edbf1ff1c6) | May 01, 2021 |
| Acer          | Aspire V5-531               | [8282b3e5fb](https://bsd-hardware.info/?probe=8282b3e5fb) | May 01, 2021 |
| HP            | Laptop 17-by0xxx            | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Toshiba       | Satellite C655D             | [6398601e16](https://bsd-hardware.info/?probe=6398601e16) | Apr 29, 2021 |
| Dell          | Inspiron 3793               | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| Dell          | Latitude E5420              | [32f03aa888](https://bsd-hardware.info/?probe=32f03aa888) | Apr 27, 2021 |
| Dell          | Latitude E5420              | [4b4cd45ac7](https://bsd-hardware.info/?probe=4b4cd45ac7) | Apr 26, 2021 |
| Dell          | Latitude E5420              | [6457b99e73](https://bsd-hardware.info/?probe=6457b99e73) | Apr 26, 2021 |
| Dell          | Precision 5510              | [063d746a48](https://bsd-hardware.info/?probe=063d746a48) | Apr 25, 2021 |
| Dell          | Precision 5510              | [6bb3b7aa11](https://bsd-hardware.info/?probe=6bb3b7aa11) | Apr 25, 2021 |
| HP            | Compaq Presario CQ71        | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| Dell          | Inspiron 3793               | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Dell          | Inspiron N5050              | [2939c4cb17](https://bsd-hardware.info/?probe=2939c4cb17) | Apr 24, 2021 |
| HP            | ProBook 4530s               | [4fb8582dc1](https://bsd-hardware.info/?probe=4fb8582dc1) | Apr 24, 2021 |
| Lenovo        | ThinkPad E14 20RAS0F600     | [94d082c57c](https://bsd-hardware.info/?probe=94d082c57c) | Apr 24, 2021 |
| HP            | Laptop 17-by0xxx            | [4f4a6b1ab0](https://bsd-hardware.info/?probe=4f4a6b1ab0) | Apr 24, 2021 |
| Toshiba       | Satellite L50-C             | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Dell          | Precision 5520              | [7d5f7b5033](https://bsd-hardware.info/?probe=7d5f7b5033) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Alienware     | M15x                        | [0b60c1cb25](https://bsd-hardware.info/?probe=0b60c1cb25) | Apr 22, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| Lenovo        | ThinkPad Edge E320 1298R... | [6a96e2c5b1](https://bsd-hardware.info/?probe=6a96e2c5b1) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [7c7573eb45](https://bsd-hardware.info/?probe=7c7573eb45) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMS0NS00    | [72fb01f474](https://bsd-hardware.info/?probe=72fb01f474) | Apr 22, 2021 |
| HP            | EliteBook 840 G3            | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Dell          | Latitude 5580               | [f967516613](https://bsd-hardware.info/?probe=f967516613) | Apr 20, 2021 |
| Dell          | Latitude E6440              | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| System76      | Lemur Pro                   | [0bd96ef663](https://bsd-hardware.info/?probe=0bd96ef663) | Apr 19, 2021 |
| ASUSTek       | Q500A                       | [c52b593262](https://bsd-hardware.info/?probe=c52b593262) | Apr 17, 2021 |
| Samsung       | NC10                        | [3307e80418](https://bsd-hardware.info/?probe=3307e80418) | Apr 17, 2021 |
| Clevo         | W55xEU                      | [229587fbd5](https://bsd-hardware.info/?probe=229587fbd5) | Apr 16, 2021 |
| HP            | EliteBook Folio 9470m       | [e1837571df](https://bsd-hardware.info/?probe=e1837571df) | Apr 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Dell          | XPS 13 9360                 | [f8bfc70f13](https://bsd-hardware.info/?probe=f8bfc70f13) | Apr 13, 2021 |
| Samsung       | NC10                        | [dd4310d56f](https://bsd-hardware.info/?probe=dd4310d56f) | Apr 13, 2021 |
| Dell          | Latitude E5470              | [af72876fd2](https://bsd-hardware.info/?probe=af72876fd2) | Apr 12, 2021 |
| Dell          | Latitude D610               | [d2cbb1f229](https://bsd-hardware.info/?probe=d2cbb1f229) | Apr 12, 2021 |
| Dell          | Inspiron 3521               | [9050866fb2](https://bsd-hardware.info/?probe=9050866fb2) | Apr 12, 2021 |
| Dell          | Latitude E5570              | [da926f1065](https://bsd-hardware.info/?probe=da926f1065) | Apr 11, 2021 |
| Acer          | Extensa 2540                | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| HUAWEI        | HN-WX9X                     | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bd88655975](https://bsd-hardware.info/?probe=bd88655975) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 23495P8       | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo        | ThinkPad T420 4236NUG       | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [812939c17f](https://bsd-hardware.info/?probe=812939c17f) | Apr 05, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [22b35a127a](https://bsd-hardware.info/?probe=22b35a127a) | Apr 05, 2021 |
| Dell          | G5 5590                     | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [676f16ac86](https://bsd-hardware.info/?probe=676f16ac86) | Apr 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | [2de4bc8337](https://bsd-hardware.info/?probe=2de4bc8337) | Apr 04, 2021 |
| Dell          | Latitude E7440              | [6ec8fd788a](https://bsd-hardware.info/?probe=6ec8fd788a) | Apr 04, 2021 |
| Dell          | Latitude E5420              | [be14a1d28e](https://bsd-hardware.info/?probe=be14a1d28e) | Apr 04, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2376cf30b2](https://bsd-hardware.info/?probe=2376cf30b2) | Apr 03, 2021 |
| Toshiba       | Satellite L50-C             | [ff59142f85](https://bsd-hardware.info/?probe=ff59142f85) | Apr 03, 2021 |
| Lenovo        | ThinkPad X220 4290NE3       | [f466982179](https://bsd-hardware.info/?probe=f466982179) | Apr 01, 2021 |
| Sony          | VGN-FW290J                  | [4a6ca78bc0](https://bsd-hardware.info/?probe=4a6ca78bc0) | Apr 01, 2021 |
| ASUSTek       | 1225B                       | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Toshiba       | Satellite L50-C             | [32f33a7a8b](https://bsd-hardware.info/?probe=32f33a7a8b) | Mar 31, 2021 |
| Samsung       | N145P/N250P/N260P           | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| Lenovo        | ThinkPad X220 4290EE8       | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009FR    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| HP            | EliteBook Folio 9470m       | [57de8a523c](https://bsd-hardware.info/?probe=57de8a523c) | Mar 29, 2021 |
| Packard Be... | AOA110                      | [fbdf068328](https://bsd-hardware.info/?probe=fbdf068328) | Mar 28, 2021 |
| Packard Be... | AOA110                      | [8da75861b4](https://bsd-hardware.info/?probe=8da75861b4) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| Dell          | Precision M4600             | [04fb75b4ea](https://bsd-hardware.info/?probe=04fb75b4ea) | Mar 26, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [beacf76b6a](https://bsd-hardware.info/?probe=beacf76b6a) | Mar 26, 2021 |
| HUAWEI        | MACH-WX9                    | [f7e09652d9](https://bsd-hardware.info/?probe=f7e09652d9) | Mar 25, 2021 |
| HUAWEI        | MACH-WX9                    | [f9fdc75b45](https://bsd-hardware.info/?probe=f9fdc75b45) | Mar 25, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Dell          | Latitude 7390               | [2ad87768af](https://bsd-hardware.info/?probe=2ad87768af) | Mar 25, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [3e9aab9818](https://bsd-hardware.info/?probe=3e9aab9818) | Mar 25, 2021 |
| Lenovo        | ThinkPad L590 20Q7000YSP    | [038fbabfe8](https://bsd-hardware.info/?probe=038fbabfe8) | Mar 24, 2021 |
| MSI           | GE75 Raider 10SGS           | [fea3cdb5d1](https://bsd-hardware.info/?probe=fea3cdb5d1) | Mar 24, 2021 |
| Lenovo        | ThinkPad R61 77331CU        | [d223a9b1fb](https://bsd-hardware.info/?probe=d223a9b1fb) | Mar 23, 2021 |
| ASUSTek       | 900A                        | [e920222f0e](https://bsd-hardware.info/?probe=e920222f0e) | Mar 23, 2021 |
| Toshiba       | Satellite L50-C             | [70cf274538](https://bsd-hardware.info/?probe=70cf274538) | Mar 23, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [dc40b42864](https://bsd-hardware.info/?probe=dc40b42864) | Mar 22, 2021 |
| Avell High... | A62                         | [df77dd6562](https://bsd-hardware.info/?probe=df77dd6562) | Mar 22, 2021 |
| Notebook      | N85_N87HCHNHZ               | [e84b5b6e5f](https://bsd-hardware.info/?probe=e84b5b6e5f) | Mar 22, 2021 |
| ASUSTek       | 900A                        | [a76303a060](https://bsd-hardware.info/?probe=a76303a060) | Mar 21, 2021 |
| Apple         | MacBookPro6,2               | [d0b3b5da10](https://bsd-hardware.info/?probe=d0b3b5da10) | Mar 21, 2021 |
| Dell          | Latitude 5580               | [175191ccff](https://bsd-hardware.info/?probe=175191ccff) | Mar 18, 2021 |
| Dell          | Latitude 5580               | [f6225cf8d8](https://bsd-hardware.info/?probe=f6225cf8d8) | Mar 18, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [bec05a34de](https://bsd-hardware.info/?probe=bec05a34de) | Mar 18, 2021 |
| Dell          | Inspiron 7566               | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell          | Inspiron 7566               | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Lenovo        | ThinkPad T470 20HES5PK00    | [6b2abd4df5](https://bsd-hardware.info/?probe=6b2abd4df5) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Gateway       | Solo 450                    | [41e40c653e](https://bsd-hardware.info/?probe=41e40c653e) | Mar 16, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b9eeb28ada](https://bsd-hardware.info/?probe=b9eeb28ada) | Mar 16, 2021 |
| Dell          | Latitude E6440              | [a332efd9d9](https://bsd-hardware.info/?probe=a332efd9d9) | Mar 15, 2021 |
| Apple         | MacBook3,1                  | [ed3684513f](https://bsd-hardware.info/?probe=ed3684513f) | Mar 15, 2021 |
| Samsung       | N150P                       | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| HP            | EliteBook 820 G1            | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Lenovo        | ThinkPad E460 20ETA00DCD    | [0a6985f078](https://bsd-hardware.info/?probe=0a6985f078) | Mar 13, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [acbc65fd42](https://bsd-hardware.info/?probe=acbc65fd42) | Mar 10, 2021 |
| Dell          | Latitude 3410               | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| HP            | 255 G3                      | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| Gateway       | Solo 450                    | [5dcb6e0ef6](https://bsd-hardware.info/?probe=5dcb6e0ef6) | Mar 09, 2021 |
| Clevo         | W55xEU                      | [e51ee3b14c](https://bsd-hardware.info/?probe=e51ee3b14c) | Mar 08, 2021 |
| HP            | 255 G3                      | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| Clevo         | W55xEU                      | [d874753fe2](https://bsd-hardware.info/?probe=d874753fe2) | Mar 07, 2021 |
| ASUSTek       | 1015BX                      | [5834a52924](https://bsd-hardware.info/?probe=5834a52924) | Mar 06, 2021 |
| Alienware     | 14                          | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [5375f351a5](https://bsd-hardware.info/?probe=5375f351a5) | Mar 05, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| Dell          | Precision 3541              | [d07a4dc2c7](https://bsd-hardware.info/?probe=d07a4dc2c7) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b60382da32](https://bsd-hardware.info/?probe=b60382da32) | Mar 03, 2021 |
| Acer          | Extensa 5630                | [6a1b523efb](https://bsd-hardware.info/?probe=6a1b523efb) | Mar 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6a4b5b90b7](https://bsd-hardware.info/?probe=6a4b5b90b7) | Mar 02, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [5f4ec887b6](https://bsd-hardware.info/?probe=5f4ec887b6) | Mar 02, 2021 |
| Lenovo        | ThinkPad T530 2429J74       | [8573903191](https://bsd-hardware.info/?probe=8573903191) | Feb 28, 2021 |
| Dell          | Latitude 5580               | [ab4ea78367](https://bsd-hardware.info/?probe=ab4ea78367) | Feb 28, 2021 |
| HP            | Compaq 6820s                | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Toshiba       | Satellite L50-C             | [3af26c7a29](https://bsd-hardware.info/?probe=3af26c7a29) | Feb 25, 2021 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Acer          | Aspire V5-531               | [fc868b6179](https://bsd-hardware.info/?probe=fc868b6179) | Feb 25, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [aacafb6ace](https://bsd-hardware.info/?probe=aacafb6ace) | Feb 24, 2021 |
| Unknown       | Unknown                     | [d11ec93413](https://bsd-hardware.info/?probe=d11ec93413) | Feb 23, 2021 |
| Dell          | Studio 1537                 | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Lenovo        | ThinkPad T450 20BUS08800    | [d783b3b4dd](https://bsd-hardware.info/?probe=d783b3b4dd) | Feb 22, 2021 |
| Lenovo        | ThinkPad X61s 766734A       | [3eb96dce87](https://bsd-hardware.info/?probe=3eb96dce87) | Feb 22, 2021 |
| Dell          | Inspiron 910                | [047950e61b](https://bsd-hardware.info/?probe=047950e61b) | Feb 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7f8c483af1](https://bsd-hardware.info/?probe=7f8c483af1) | Feb 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 4... | [f8f9140d92](https://bsd-hardware.info/?probe=f8f9140d92) | Feb 21, 2021 |
| Gigabyte      | P15FR7                      | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| Dell          | Latitude E6430              | [a7fd669be4](https://bsd-hardware.info/?probe=a7fd669be4) | Feb 20, 2021 |
| Fujitsu       | FMVNF70YJ                   | [ac880c0076](https://bsd-hardware.info/?probe=ac880c0076) | Feb 20, 2021 |
| Dell          | Latitude E7450              | [0a8e2a2e29](https://bsd-hardware.info/?probe=0a8e2a2e29) | Feb 19, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a9604cfdb8](https://bsd-hardware.info/?probe=a9604cfdb8) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [893c17f73a](https://bsd-hardware.info/?probe=893c17f73a) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [d0f504fad2](https://bsd-hardware.info/?probe=d0f504fad2) | Feb 19, 2021 |
| ASUSTek       | G73Jh                       | [ba7fb8e83c](https://bsd-hardware.info/?probe=ba7fb8e83c) | Feb 19, 2021 |
| Lenovo        | ThinkPad X220 4290NE3       | [a6a1824172](https://bsd-hardware.info/?probe=a6a1824172) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| ASUSTek       | G73Jh                       | [35164ad41b](https://bsd-hardware.info/?probe=35164ad41b) | Feb 17, 2021 |
| Acer          | Aspire V5-531               | [ad4634140e](https://bsd-hardware.info/?probe=ad4634140e) | Feb 16, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| Acer          | Spin SP111-32N              | [dd7644026b](https://bsd-hardware.info/?probe=dd7644026b) | Feb 16, 2021 |
| Lenovo        | ThinkPad Edge 03282UA       | [0735d22638](https://bsd-hardware.info/?probe=0735d22638) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| MOTILE        | M142                        | [5ec101bb3e](https://bsd-hardware.info/?probe=5ec101bb3e) | Feb 15, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [be88e8f865](https://bsd-hardware.info/?probe=be88e8f865) | Feb 15, 2021 |
| HP            | EliteBook 8460p             | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| HP            | ENVY dv7                    | [4637a9eeff](https://bsd-hardware.info/?probe=4637a9eeff) | Feb 14, 2021 |
| ASUSTek       | X553MA                      | [cfc7d86b5a](https://bsd-hardware.info/?probe=cfc7d86b5a) | Feb 14, 2021 |
| Dell          | G7 7500                     | [a1c2eaee5f](https://bsd-hardware.info/?probe=a1c2eaee5f) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| ASUSTek       | E200HA                      | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c2c9931f74](https://bsd-hardware.info/?probe=c2c9931f74) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c9e6341e78](https://bsd-hardware.info/?probe=c9e6341e78) | Feb 12, 2021 |
| Lenovo        | ThinkPad Edge 03282UA       | [f215fd8377](https://bsd-hardware.info/?probe=f215fd8377) | Feb 11, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [f6ec2858a5](https://bsd-hardware.info/?probe=f6ec2858a5) | Feb 10, 2021 |
| Dell          | Latitude E6230              | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| Lenovo        | ThinkPad Edge 03282UA       | [d48a95ffc2](https://bsd-hardware.info/?probe=d48a95ffc2) | Feb 09, 2021 |
| HP            | EliteBook 8570p             | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| Lenovo        | 20QD0000US                  | [8d1c80c2cb](https://bsd-hardware.info/?probe=8d1c80c2cb) | Feb 09, 2021 |
| Dell          | Latitude 7370               | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [55debb2f24](https://bsd-hardware.info/?probe=55debb2f24) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | 20QD0000US                  | [77e80759a0](https://bsd-hardware.info/?probe=77e80759a0) | Feb 08, 2021 |
| System76      | Lemur Pro                   | [3071c04a4b](https://bsd-hardware.info/?probe=3071c04a4b) | Feb 08, 2021 |
| System76      | Galago Pro                  | [8f39c38e2e](https://bsd-hardware.info/?probe=8f39c38e2e) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Toshiba       | Satellite L50-C             | [7a5a694be1](https://bsd-hardware.info/?probe=7a5a694be1) | Feb 06, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [0bc3ba767e](https://bsd-hardware.info/?probe=0bc3ba767e) | Feb 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [045a80d8bc](https://bsd-hardware.info/?probe=045a80d8bc) | Feb 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [3754dfb89c](https://bsd-hardware.info/?probe=3754dfb89c) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [5d6a8a51d0](https://bsd-hardware.info/?probe=5d6a8a51d0) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [c443decee1](https://bsd-hardware.info/?probe=c443decee1) | Feb 06, 2021 |
| Dell          | Vostro 3750                 | [87b8a38ef9](https://bsd-hardware.info/?probe=87b8a38ef9) | Feb 05, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| Acer          | Aspire E5-576               | [95e841a292](https://bsd-hardware.info/?probe=95e841a292) | Feb 04, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [92879d0781](https://bsd-hardware.info/?probe=92879d0781) | Feb 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3ebe1fd064](https://bsd-hardware.info/?probe=3ebe1fd064) | Feb 03, 2021 |
| System76      | Lemur Pro                   | [e1cc11993d](https://bsd-hardware.info/?probe=e1cc11993d) | Feb 02, 2021 |
| HP            | EliteBook 8570p             | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| Apple         | MacBookPro6,2               | [6174748602](https://bsd-hardware.info/?probe=6174748602) | Feb 01, 2021 |
| Lenovo        | ThinkPad SL510 2847Q9G      | [12e9632d4b](https://bsd-hardware.info/?probe=12e9632d4b) | Jan 31, 2021 |
| Dell          | Vostro V131                 | [897616d9c8](https://bsd-hardware.info/?probe=897616d9c8) | Jan 31, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [dbc05e2913](https://bsd-hardware.info/?probe=dbc05e2913) | Jan 30, 2021 |
| Acer          | Aspire V5-531               | [b917d2b6ad](https://bsd-hardware.info/?probe=b917d2b6ad) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | [98af88dfe6](https://bsd-hardware.info/?probe=98af88dfe6) | Jan 30, 2021 |
| Clevo         | W55xEU                      | [ecacada83f](https://bsd-hardware.info/?probe=ecacada83f) | Jan 29, 2021 |
| Toshiba       | Satellite L50-C             | [f76ea8946b](https://bsd-hardware.info/?probe=f76ea8946b) | Jan 28, 2021 |
| Lenovo        | ThinkPad T570 20HAS0DP00    | [f73844a707](https://bsd-hardware.info/?probe=f73844a707) | Jan 26, 2021 |
| Dell          | Vostro V131                 | [630822a6a1](https://bsd-hardware.info/?probe=630822a6a1) | Jan 25, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [c16cd20c42](https://bsd-hardware.info/?probe=c16cd20c42) | Jan 25, 2021 |
| Acer          | Aspire 5515                 | [d9ef473a7a](https://bsd-hardware.info/?probe=d9ef473a7a) | Jan 25, 2021 |
| Fujitsu       | LIFEBOOK E753               | [9a615ebaf8](https://bsd-hardware.info/?probe=9a615ebaf8) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [ecf07ad5fe](https://bsd-hardware.info/?probe=ecf07ad5fe) | Jan 24, 2021 |
| Acer          | Aspire V5-531               | [41caa6acaa](https://bsd-hardware.info/?probe=41caa6acaa) | Jan 24, 2021 |
| HP            | EliteBook 8570p             | [c2e361eeff](https://bsd-hardware.info/?probe=c2e361eeff) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | [86e5ba4c5b](https://bsd-hardware.info/?probe=86e5ba4c5b) | Jan 22, 2021 |
| Apple         | MacBookPro11,4              | [dad5d994a0](https://bsd-hardware.info/?probe=dad5d994a0) | Jan 20, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 112       | 10.7%   |
| FreeBSD 13.0         | 111       | 10.6%   |
| FreeBSD 14.0-CURRENT | 65        | 6.21%   |
| FreeBSD 12.2         | 59        | 5.64%   |
| FreeBSD 13.1-p5      | 41        | 3.92%   |
| FreeBSD 13.0-p4      | 35        | 3.34%   |
| FreeBSD 12.2-p2      | 34        | 3.25%   |
| FreeBSD 13.0-CURRENT | 31        | 2.96%   |
| FreeBSD 13.0-STABLE  | 28        | 2.67%   |
| FreeBSD 12.1         | 28        | 2.67%   |
| FreeBSD 12.1-p8      | 26        | 2.48%   |
| FreeBSD 13.0-p5      | 25        | 2.39%   |
| FreeBSD 13.0-p3      | 23        | 2.2%    |
| FreeBSD 12.2-p4      | 23        | 2.2%    |
| FreeBSD 12.1-p10     | 23        | 2.2%    |
| FreeBSD 13.1-p2      | 21        | 2.01%   |
| FreeBSD 12.1-p5      | 20        | 1.91%   |
| FreeBSD 13.1-p7      | 19        | 1.81%   |
| FreeBSD 13.0-p7      | 19        | 1.81%   |
| FreeBSD 12.2-p3      | 18        | 1.72%   |
| FreeBSD 13.0-p2      | 17        | 1.62%   |
| FreeBSD 13.1-STABLE  | 15        | 1.43%   |
| FreeBSD 12.1-STABLE  | 15        | 1.43%   |
| FreeBSD 12.1-p7      | 15        | 1.43%   |
| FreeBSD 13.0-p6      | 13        | 1.24%   |
| FreeBSD 12.2-p6      | 12        | 1.15%   |
| FreeBSD 12.2-STABLE  | 10        | 0.96%   |
| FreeBSD 13.1-p4      | 9         | 0.86%   |
| FreeBSD 13.1-p1      | 9         | 0.86%   |
| FreeBSD 13.0-p11     | 9         | 0.86%   |
| FreeBSD 12.1-p9      | 7         | 0.67%   |
| FreeBSD 12.1-p6      | 7         | 0.67%   |
| FreeBSD 12.1-p4      | 7         | 0.67%   |
| FreeBSD 13.1-p3      | 6         | 0.57%   |
| FreeBSD 13.0-p1      | 6         | 0.57%   |
| FreeBSD 13.0-RC5     | 5         | 0.48%   |
| FreeBSD 13.0-RC1     | 5         | 0.48%   |
| FreeBSD 13.0-p10     | 5         | 0.48%   |
| FreeBSD 13.0-BETA1   | 5         | 0.48%   |
| FreeBSD 12.3         | 5         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| FreeBSD | 875       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 832       | 94.98%  |
| i386  | 43        | 4.91%   |
| arm64 | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 214       | 23.31%  |
| KDE5          | 175       | 19.06%  |
| Console       | 108       | 11.76%  |
| TWM           | 84        | 9.15%   |
| GNOME         | 80        | 8.71%   |
| i3            | 70        | 7.63%   |
| MATE          | 62        | 6.75%   |
| Openbox       | 27        | 2.94%   |
| Cinnamon      | 16        | 1.74%   |
| AwesomeWM     | 15        | 1.63%   |
| LXQt          | 13        | 1.42%   |
| Fluxbox       | 9         | 0.98%   |
| Enlightenment | 9         | 0.98%   |
| LXDE          | 8         | 0.87%   |
| Lumina        | 5         | 0.54%   |
| DWM           | 4         | 0.44%   |
| IceWM         | 3         | 0.33%   |
| GNUstep       | 3         | 0.33%   |
| spectrwm      | 2         | 0.22%   |
| Picom         | 2         | 0.22%   |
| Xfwm4         | 1         | 0.11%   |
| X-Cinnamon    | 1         | 0.11%   |
| sway          | 1         | 0.11%   |
| StumpWM       | 1         | 0.11%   |
| helloDesktop  | 1         | 0.11%   |
| ctwm          | 1         | 0.11%   |
| Compton       | 1         | 0.11%   |
| CDE           | 1         | 0.11%   |
| awesome       | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 746       | 83.54%  |
| Console | 120       | 13.44%  |
| Wayland | 27        | 3.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 353       | 38.62%  |
| SDDM    | 187       | 20.46%  |
| SLiM    | 157       | 17.18%  |
| XDM     | 77        | 8.42%   |
| LightDM | 73        | 7.99%   |
| GDM     | 52        | 5.69%   |
| Ly      | 12        | 1.31%   |
| PCDM    | 2         | 0.22%   |
| WDM     | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 400       | 43.29%  |
| Unknown          | 219       | 23.7%   |
| en_US            | 125       | 13.53%  |
| ru_RU            | 35        | 3.79%   |
| fr_FR            | 23        | 2.49%   |
| en_GB            | 16        | 1.73%   |
| de_DE            | 16        | 1.73%   |
| zh_CN            | 11        | 1.19%   |
| pl_PL            | 6         | 0.65%   |
| en_CA            | 6         | 0.65%   |
| pt_BR            | 4         | 0.43%   |
| nb_NO            | 4         | 0.43%   |
| es_ES            | 4         | 0.43%   |
| en_NZ            | 4         | 0.43%   |
| cs_CZ            | 4         | 0.43%   |
| uk_UA            | 3         | 0.32%   |
| en_US.US-ASCII   | 3         | 0.32%   |
| en_US.ISO8859-1  | 3         | 0.32%   |
| ja_JP            | 2         | 0.22%   |
| en_SG            | 2         | 0.22%   |
| en_IE            | 2         | 0.22%   |
| en_AU            | 2         | 0.22%   |
| de_DE.ISO8859-1  | 2         | 0.22%   |
| de_CH            | 2         | 0.22%   |
| zh_TW            | 1         | 0.11%   |
| zh_CN.GB2312     | 1         | 0.11%   |
| sl_SI            | 1         | 0.11%   |
| pt_PT            | 1         | 0.11%   |
| POSIX            | 1         | 0.11%   |
| nl_NL            | 1         | 0.11%   |
| ko_KR            | 1         | 0.11%   |
| it_IT.ISO8859-15 | 1         | 0.11%   |
| it_IT.ISO8859-1  | 1         | 0.11%   |
| it_IT            | 1         | 0.11%   |
| it_CH            | 1         | 0.11%   |
| hu_HU.US-ASCII   | 1         | 0.11%   |
| fi_FI            | 1         | 0.11%   |
| es_AR            | 1         | 0.11%   |
| en_PH            | 1         | 0.11%   |
| en_NZ.US-ASCII   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 627       | 71.33%  |
| BIOS | 252       | 28.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 564       | 63.95%  |
| Ufs  | 316       | 35.83%  |
| Xfs  | 1         | 0.11%   |
| Nfs  | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 780       | 88.64%  |
| MBR     | 95        | 10.8%   |
| BSD     | 4         | 0.45%   |
| Unknown | 1         | 0.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 311       | 35.54%  |
| Dell                   | 169       | 19.31%  |
| Hewlett-Packard        | 76        | 8.69%   |
| ASUSTek Computer       | 62        | 7.09%   |
| Acer                   | 51        | 5.83%   |
| Apple                  | 21        | 2.4%    |
| Toshiba                | 20        | 2.29%   |
| Samsung Electronics    | 16        | 1.83%   |
| System76               | 13        | 1.49%   |
| MSI                    | 11        | 1.26%   |
| HUAWEI                 | 11        | 1.26%   |
| Google                 | 10        | 1.14%   |
| Sony                   | 9         | 1.03%   |
| TUXEDO                 | 7         | 0.8%    |
| IBM                    | 6         | 0.69%   |
| Fujitsu                | 6         | 0.69%   |
| Notebook               | 5         | 0.57%   |
| Framework              | 5         | 0.57%   |
| Panasonic              | 4         | 0.46%   |
| Intel                  | 4         | 0.46%   |
| Gigabyte Technology    | 4         | 0.46%   |
| Alienware              | 4         | 0.46%   |
| Unknown                | 4         | 0.46%   |
| Timi                   | 3         | 0.34%   |
| Gateway                | 3         | 0.34%   |
| Deciso                 | 3         | 0.34%   |
| Avell High Performance | 3         | 0.34%   |
| Schenker               | 2         | 0.23%   |
| Medion                 | 2         | 0.23%   |
| LG Electronics         | 2         | 0.23%   |
| GPD                    | 2         | 0.23%   |
| Fujitsu Siemens        | 2         | 0.23%   |
| F-Plus Mobile          | 2         | 0.23%   |
| Clevo                  | 2         | 0.23%   |
| BANGHO                 | 2         | 0.23%   |
| WOOKING                | 1         | 0.11%   |
| VIT                    | 1         | 0.11%   |
| Valve                  | 1         | 0.11%   |
| TOXIC by BTO           | 1         | 0.11%   |
| SLIMBOOK               | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 7         | 0.8%    |
| HP EliteBook 840 G3                      | 5         | 0.57%   |
| Framework Laptop                         | 5         | 0.57%   |
| Dell Latitude E7240                      | 5         | 0.57%   |
| System76 Lemur Pro                       | 4         | 0.46%   |
| Dell Latitude E6430                      | 4         | 0.46%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 3         | 0.34%   |
| HUAWEI MACH-WX9                          | 3         | 0.34%   |
| HP EliteBook 8570p                       | 3         | 0.34%   |
| Google Peppy                             | 3         | 0.34%   |
| Dell XPS 13 9360                         | 3         | 0.34%   |
| Dell XPS 13 9343                         | 3         | 0.34%   |
| Dell Precision M4800                     | 3         | 0.34%   |
| Dell Latitude E7450                      | 3         | 0.34%   |
| Dell Latitude E7440                      | 3         | 0.34%   |
| Dell Latitude E6420                      | 3         | 0.34%   |
| Dell Latitude E5470                      | 3         | 0.34%   |
| Dell Latitude E5420                      | 3         | 0.34%   |
| Dell Latitude 7390                       | 3         | 0.34%   |
| Dell Latitude 2100                       | 3         | 0.34%   |
| Dell Inspiron 3521                       | 3         | 0.34%   |
| Dell Inspiron 15 7000 Gaming             | 3         | 0.34%   |
| Toshiba Satellite A300                   | 2         | 0.23%   |
| System76 Gazelle                         | 2         | 0.23%   |
| System76 Galago Pro                      | 2         | 0.23%   |
| System76 Bonobo Extreme                  | 2         | 0.23%   |
| Samsung NC10                             | 2         | 0.23%   |
| Samsung 340XAA/350XAA/550XAA             | 2         | 0.23%   |
| Lenovo ThinkPad X220 42915CG             | 2         | 0.23%   |
| Lenovo ThinkPad X220 42872WU             | 2         | 0.23%   |
| Lenovo ThinkPad X220 4286CTO             | 2         | 0.23%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 2         | 0.23%   |
| Lenovo ThinkPad T60 20076PU              | 2         | 0.23%   |
| Lenovo ThinkPad T410s 291245G            | 2         | 0.23%   |
| Lenovo ThinkPad E490 20N8CTO1WW          | 2         | 0.23%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW     | 2         | 0.23%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 2         | 0.23%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 2         | 0.23%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 2         | 0.23%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 245       | 28%     |
| Dell Latitude     | 72        | 8.23%   |
| Dell Inspiron     | 43        | 4.91%   |
| Lenovo IdeaPad    | 31        | 3.54%   |
| Acer Aspire       | 30        | 3.43%   |
| Dell Precision    | 18        | 2.06%   |
| HP ProBook        | 16        | 1.83%   |
| HP EliteBook      | 15        | 1.71%   |
| Dell XPS          | 15        | 1.71%   |
| Toshiba Satellite | 13        | 1.49%   |
| Dell Vostro       | 13        | 1.49%   |
| HP Pavilion       | 9         | 1.03%   |
| HP Laptop         | 8         | 0.91%   |
| HP Compaq         | 8         | 0.91%   |
| Lenovo Legion     | 7         | 0.8%    |
| ASUS ZenBook      | 7         | 0.8%    |
| Unknown           | 7         | 0.8%    |
| IBM ThinkPad      | 6         | 0.69%   |
| ASUS ASUS         | 6         | 0.69%   |
| Fujitsu LIFEBOOK  | 5         | 0.57%   |
| Framework Laptop  | 5         | 0.57%   |
| ASUS VivoBook     | 5         | 0.57%   |
| Acer Swift        | 5         | 0.57%   |
| System76 Lemur    | 4         | 0.46%   |
| Lenovo Yoga       | 4         | 0.46%   |
| HP ZBook          | 4         | 0.46%   |
| HP ENVY           | 4         | 0.46%   |
| Apple MacBookPro8 | 4         | 0.46%   |
| Acer TravelMate   | 4         | 0.46%   |
| HUAWEI MACH-WX9   | 3         | 0.34%   |
| Google Peppy      | 3         | 0.34%   |
| Dell Studio       | 3         | 0.34%   |
| Acer Nitro        | 3         | 0.34%   |
| Acer Extensa      | 3         | 0.34%   |
| TUXEDO Pulse      | 2         | 0.23%   |
| Toshiba TECRA     | 2         | 0.23%   |
| Toshiba PORTEGE   | 2         | 0.23%   |
| System76 Gazelle  | 2         | 0.23%   |
| System76 Galago   | 2         | 0.23%   |
| System76 Bonobo   | 2         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 112       | 12.8%   |
| 2019 | 96        | 10.97%  |
| 2021 | 79        | 9.03%   |
| 2011 | 77        | 8.8%    |
| 2018 | 70        | 8%      |
| 2015 | 57        | 6.51%   |
| 2016 | 55        | 6.29%   |
| 2022 | 48        | 5.49%   |
| 2012 | 47        | 5.37%   |
| 2013 | 44        | 5.03%   |
| 2017 | 42        | 4.8%    |
| 2010 | 39        | 4.46%   |
| 2014 | 29        | 3.31%   |
| 2008 | 25        | 2.86%   |
| 2009 | 21        | 2.4%    |
| 2007 | 13        | 1.49%   |
| 2006 | 10        | 1.14%   |
| 2003 | 3         | 0.34%   |
| 2023 | 2         | 0.23%   |
| 2005 | 2         | 0.23%   |
| 2004 | 2         | 0.23%   |
| 2002 | 2         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 875       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 854       | 97.6%   |
| Yes  | 21        | 2.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 285       | 32.06%  |
| 16.01-24.0  | 269       | 30.26%  |
| 4.01-8.0    | 148       | 16.65%  |
| 32.01-64.0  | 73        | 8.21%   |
| 2.01-3.0    | 46        | 5.17%   |
| 24.01-32.0  | 16        | 1.8%    |
| 3.01-4.0    | 15        | 1.69%   |
| 64.01-256.0 | 14        | 1.57%   |
| 0.51-1.0    | 11        | 1.24%   |
| 1.01-2.0    | 8         | 0.9%    |
| 0.01-0.5    | 4         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 371       | 41.59%  |
| 0.51-1.0   | 301       | 33.74%  |
| 1.01-2.0   | 138       | 15.47%  |
| 2.01-3.0   | 36        | 4.04%   |
| 4.01-8.0   | 17        | 1.91%   |
| 8.01-16.0  | 13        | 1.46%   |
| 3.01-4.0   | 5         | 0.56%   |
| 16.01-24.0 | 4         | 0.45%   |
| 24.01-32.0 | 3         | 0.34%   |
| 32.01-64.0 | 2         | 0.22%   |
| 0          | 2         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 657       | 73.57%  |
| 2      | 180       | 20.16%  |
| 0      | 29        | 3.25%   |
| 3      | 24        | 2.69%   |
| 4      | 2         | 0.22%   |
| 58     | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 640       | 72.48%  |
| Yes       | 243       | 27.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 724       | 82.74%  |
| No        | 151       | 17.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 855       | 97.38%  |
| No        | 23        | 2.62%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 611       | 68.96%  |
| No        | 275       | 31.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 197       | 22.29%  |
| Germany     | 84        | 9.5%    |
| Russia      | 76        | 8.6%    |
| France      | 54        | 6.11%   |
| UK          | 32        | 3.62%   |
| China       | 32        | 3.62%   |
| Canada      | 26        | 2.94%   |
| Brazil      | 24        | 2.71%   |
| Ukraine     | 23        | 2.6%    |
| Poland      | 23        | 2.6%    |
| Austria     | 20        | 2.26%   |
| Switzerland | 17        | 1.92%   |
| Netherlands | 16        | 1.81%   |
| India       | 16        | 1.81%   |
| Spain       | 15        | 1.7%    |
| Czechia     | 15        | 1.7%    |
| Australia   | 15        | 1.7%    |
| Indonesia   | 11        | 1.24%   |
| Japan       | 10        | 1.13%   |
| Italy       | 10        | 1.13%   |
| Sweden      | 8         | 0.9%    |
| Romania     | 8         | 0.9%    |
| Thailand    | 7         | 0.79%   |
| Portugal    | 7         | 0.79%   |
| Argentina   | 7         | 0.79%   |
| Norway      | 6         | 0.68%   |
| New Zealand | 6         | 0.68%   |
| Greece      | 6         | 0.68%   |
| Finland     | 6         | 0.68%   |
| Denmark     | 6         | 0.68%   |
| Mexico      | 5         | 0.57%   |
| Ireland     | 5         | 0.57%   |
| Vietnam     | 4         | 0.45%   |
| Slovenia    | 4         | 0.45%   |
| Philippines | 4         | 0.45%   |
| Iran        | 4         | 0.45%   |
| Hungary     | 4         | 0.45%   |
| Bulgaria    | 4         | 0.45%   |
| Belgium     | 4         | 0.45%   |
| Turkey      | 3         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 32        | 3.35%   |
| Brooklyn      | 20        | 2.1%    |
| Vienna        | 19        | 1.99%   |
| Berlin        | 11        | 1.15%   |
| Kyiv          | 10        | 1.05%   |
| Paris         | 9         | 0.94%   |
| Zurich        | 8         | 0.84%   |
| St Petersburg | 8         | 0.84%   |
| Warsaw        | 7         | 0.73%   |
| Brighton      | 7         | 0.73%   |
| Shanghai      | 6         | 0.63%   |
| Jakarta       | 6         | 0.63%   |
| Amsterdam     | 6         | 0.63%   |
| Sydney        | 5         | 0.52%   |
| Seattle       | 5         | 0.52%   |
| Montreal      | 5         | 0.52%   |
| London        | 5         | 0.52%   |
| Dublin        | 5         | 0.52%   |
| Chicago       | 5         | 0.52%   |
| Barcelona     | 5         | 0.52%   |
| New York      | 4         | 0.42%   |
| Christchurch  | 4         | 0.42%   |
| Bucharest     | 4         | 0.42%   |
| Brno          | 4         | 0.42%   |
| Wernigerode   | 3         | 0.31%   |
| Vancouver     | 3         | 0.31%   |
| Ulyanovsk     | 3         | 0.31%   |
| Tuklaty       | 3         | 0.31%   |
| Tehran        | 3         | 0.31%   |
| Stockholm     | 3         | 0.31%   |
| Singapore     | 3         | 0.31%   |
| Shenzhen      | 3         | 0.31%   |
| Portland      | 3         | 0.31%   |
| Perth         | 3         | 0.31%   |
| Ostrava       | 3         | 0.31%   |
| Novosibirsk   | 3         | 0.31%   |
| Munich        | 3         | 0.31%   |
| Midvale       | 3         | 0.31%   |
| Manaus        | 3         | 0.31%   |
| Madrid        | 3         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 221       | 306    | 21.05%  |
| WDC                 | 152       | 198    | 14.48%  |
| Seagate             | 80        | 100    | 7.62%   |
| Toshiba             | 75        | 119    | 7.14%   |
| Crucial             | 65        | 91     | 6.19%   |
| Kingston            | 59        | 82     | 5.62%   |
| SanDisk             | 43        | 56     | 4.1%    |
| Intel               | 39        | 53     | 3.71%   |
| Hitachi             | 37        | 45     | 3.52%   |
| SK hynix            | 31        | 35     | 2.95%   |
| HGST                | 24        | 79     | 2.29%   |
| Transcend           | 23        | 27     | 2.19%   |
| Micron Technology   | 22        | 26     | 2.1%    |
| A-DATA Technology   | 20        | 24     | 1.9%    |
| KIOXIA              | 13        | 13     | 1.24%   |
| Fujitsu             | 10        | 15     | 0.95%   |
| Phison              | 9         | 14     | 0.86%   |
| Gigabyte Technology | 8         | 10     | 0.76%   |
| OWC                 | 7         | 8      | 0.67%   |
| LITEON              | 7         | 12     | 0.67%   |
| KingSpec            | 7         | 9      | 0.67%   |
| Apple               | 7         | 7      | 0.67%   |
| SPCC                | 6         | 8      | 0.57%   |
| PNY                 | 6         | 7      | 0.57%   |
| Hewlett-Packard     | 5         | 5      | 0.48%   |
| China               | 5         | 6      | 0.48%   |
| SSSTC               | 4         | 4      | 0.38%   |
| Silicon Motion      | 4         | 4      | 0.38%   |
| Hikvision           | 4         | 4      | 0.38%   |
| Corsair             | 4         | 4      | 0.38%   |
| Union Memory        | 3         | 3      | 0.29%   |
| OCZ                 | 3         | 4      | 0.29%   |
| Mushkin             | 3         | 3      | 0.29%   |
| Lenovo              | 3         | 3      | 0.29%   |
| BIWIN               | 3         | 4      | 0.29%   |
| Zheino              | 2         | 3      | 0.19%   |
| UMIS                | 2         | 2      | 0.19%   |
| Team                | 2         | 3      | 0.19%   |
| Lexar               | 2         | 8      | 0.19%   |
| FORESEE             | 2         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 17        | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB     | 13        | 1.19%   |
| Toshiba MQ01ABD100 1TB             | 12        | 1.1%    |
| Samsung SSD 860 EVO 500GB          | 12        | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 1.01%   |
| Crucial CT500MX500SSD1 500GB       | 11        | 1.01%   |
| Toshiba MQ01ABF050 500GB           | 10        | 0.92%   |
| HGST HTS721010A9E630 1TB           | 10        | 0.92%   |
| Seagate ST500LT012-1DG142 500GB    | 8         | 0.73%   |
| Samsung SSD 850 EVO 500GB          | 8         | 0.73%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB | 7         | 0.64%   |
| Samsung SSD 970 EVO Plus 1TB       | 7         | 0.64%   |
| Samsung SSD 970 EVO 500GB          | 7         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB        | 7         | 0.64%   |
| SanDisk SSD PLUS 240GB             | 6         | 0.55%   |
| Samsung SSD 850 EVO 250GB          | 6         | 0.55%   |
| Intel SSDPEKKF512G8L 512GB         | 6         | 0.55%   |
| HGST HTS725050A7E630 500GB         | 6         | 0.55%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 5         | 0.46%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 5         | 0.46%   |
| Toshiba MQ04ABF100 1TB             | 5         | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB     | 5         | 0.46%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 5         | 0.46%   |
| Samsung MZVLB512HAJQ-000L7 512GB   | 5         | 0.46%   |
| Crucial CT2000MX500SSD1 2TB        | 5         | 0.46%   |
| Crucial CT1000P1SSD8 1TB           | 5         | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB           | 4         | 0.37%   |
| Seagate ST9500420AS 500GB          | 4         | 0.37%   |
| Seagate ST9500325AS 500GB          | 4         | 0.37%   |
| Samsung SSD 970 EVO Plus 2TB       | 4         | 0.37%   |
| Samsung SSD 860 EVO 1TB            | 4         | 0.37%   |
| Samsung SSD 850 EVO 1TB            | 4         | 0.37%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 4         | 0.37%   |
| Samsung MZVLB1T0HBLR-000L2 1TB     | 4         | 0.37%   |
| Samsung MZALQ512HBLU-00BL1 512GB   | 4         | 0.37%   |
| Samsung MZ7TY256HDHP-000L7 256GB   | 4         | 0.37%   |
| Phison PCIe SSD 256GB              | 4         | 0.37%   |
| KIOXIA KBG40ZNS512G NVMe 512GB     | 4         | 0.37%   |
| Kingston SA400S37120G 120GB        | 4         | 0.37%   |
| Intel SSDPEKKF256G8L 256GB         | 4         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 84        | 102    | 28.57%  |
| Seagate             | 79        | 99     | 26.87%  |
| Toshiba             | 51        | 82     | 17.35%  |
| Hitachi             | 37        | 45     | 12.59%  |
| HGST                | 24        | 79     | 8.16%   |
| Fujitsu             | 10        | 15     | 3.4%    |
| Samsung Electronics | 7         | 7      | 2.38%   |
| IBM/Hitachi         | 1         | 1      | 0.34%   |
| HPE                 | 1         | 5      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 111       | 155    | 24.94%  |
| Crucial             | 52        | 72     | 11.69%  |
| Kingston            | 49        | 70     | 11.01%  |
| SanDisk             | 43        | 56     | 9.66%   |
| WDC                 | 21        | 35     | 4.72%   |
| Transcend           | 20        | 23     | 4.49%   |
| Intel               | 19        | 30     | 4.27%   |
| A-DATA Technology   | 11        | 14     | 2.47%   |
| Toshiba             | 10        | 10     | 2.25%   |
| SK hynix            | 9         | 10     | 2.02%   |
| Micron Technology   | 9         | 10     | 2.02%   |
| OWC                 | 7         | 8      | 1.57%   |
| KingSpec            | 7         | 9      | 1.57%   |
| Apple               | 7         | 7      | 1.57%   |
| LITEON              | 6         | 11     | 1.35%   |
| Hewlett-Packard     | 5         | 5      | 1.12%   |
| Gigabyte Technology | 5         | 6      | 1.12%   |
| China               | 5         | 6      | 1.12%   |
| SPCC                | 4         | 5      | 0.9%    |
| PNY                 | 4         | 5      | 0.9%    |
| Corsair             | 4         | 4      | 0.9%    |
| OCZ                 | 3         | 4      | 0.67%   |
| Zheino              | 2         | 3      | 0.45%   |
| Team                | 2         | 3      | 0.45%   |
| Mushkin             | 2         | 2      | 0.45%   |
| Lexar               | 2         | 8      | 0.45%   |
| Lenovo              | 2         | 2      | 0.45%   |
| Hikvision           | 2         | 2      | 0.45%   |
| BIWIN               | 2         | 3      | 0.45%   |
| Apacer              | 2         | 2      | 0.45%   |
| ZTC                 | 1         | 1      | 0.22%   |
| Verbatim            | 1         | 1      | 0.22%   |
| TCSUNBOW            | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 1      | 0.22%   |
| SMI                 | 1         | 1      | 0.22%   |
| Seagate             | 1         | 1      | 0.22%   |
| Phison              | 1         | 1      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| Netac               | 1         | 1      | 0.22%   |
| MicroDream          | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 399       | 599    | 41.05%  |
| NVMe | 299       | 405    | 30.76%  |
| HDD  | 274       | 435    | 28.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 617       | 1034   | 67.36%  |
| NVMe | 299       | 405    | 32.64%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 472       | 703    | 69.93%  |
| 0.51-1.0   | 163       | 230    | 24.15%  |
| 1.01-2.0   | 35        | 47     | 5.19%   |
| 3.01-4.0   | 3         | 51     | 0.44%   |
| 2.01-3.0   | 1         | 2      | 0.15%   |
| 4.01-10.0  | 1         | 1      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 326       | 35.78%  |
| 251-500        | 255       | 27.99%  |
| 501-1000       | 127       | 13.94%  |
| 51-100         | 88        | 9.66%   |
| 21-50          | 57        | 6.26%   |
| 1001-2000      | 27        | 2.96%   |
| 1-20           | 24        | 2.63%   |
| 2001-3000      | 3         | 0.33%   |
| Unknown        | 3         | 0.33%   |
| More than 3000 | 1         | 0.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 670       | 73.22%  |
| 21-50          | 135       | 14.75%  |
| 51-100         | 46        | 5.03%   |
| 101-250        | 42        | 4.59%   |
| 251-500        | 11        | 1.2%    |
| 501-1000       | 7         | 0.77%   |
| Unknown        | 3         | 0.33%   |
| More than 3000 | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 6         | 6      | 4.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 2.76%   |
| HGST HTS725050A7E630 500GB         | 4         | 8      | 2.76%   |
| Toshiba MQ01ABF050 500GB           | 3         | 3      | 2.07%   |
| Toshiba MQ01ABD100 1TB             | 3         | 3      | 2.07%   |
| Seagate ST9500420AS 500GB          | 3         | 4      | 2.07%   |
| Seagate ST500LT012-9WS142 500GB    | 3         | 6      | 2.07%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 2         | 2      | 1.38%   |
| Toshiba MK2546GSX 250GB            | 2         | 2      | 1.38%   |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 2      | 1.38%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 2      | 1.38%   |
| Micron Technology 1100 SATA 256GB  | 2         | 2      | 1.38%   |
| Kingston SNS4151S316GD 16GB        | 2         | 2      | 1.38%   |
| Intel SSDSCKKF256G8H 256GB         | 2         | 5      | 1.38%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 1.38%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 3      | 1.38%   |
| Hitachi HTS541612J9SA00 120GB      | 2         | 2      | 1.38%   |
| HGST HTS721010A9E630 1TB           | 2         | 14     | 1.38%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 1      | 0.69%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1         | 1      | 0.69%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 1      | 0.69%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 1      | 0.69%   |
| WDC WD5000B 500GB                  | 1         | 1      | 0.69%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BPVT-75JJ5T0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BEKT-22PVMT0 320GB       | 1         | 1      | 0.69%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 0.69%   |
| WDC WD2000JB-00GVC0 200GB          | 1         | 1      | 0.69%   |
| WDC WD15EARS-00Z5B1 1.5TB          | 1         | 1      | 0.69%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 0.69%   |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 0.69%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 1      | 0.69%   |
| Transcend TS256GSSD320 256GB       | 1         | 1      | 0.69%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.69%   |
| Toshiba MQ01ABF032 320GB           | 1         | 2      | 0.69%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 0.69%   |
| Toshiba MQ01ABD032 320GB           | 1         | 2      | 0.69%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 0.69%   |
| Toshiba MK3265GSXN 320GB           | 1         | 5      | 0.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 42     | 22.14%  |
| Hitachi             | 19        | 22     | 13.57%  |
| Toshiba             | 18        | 26     | 12.86%  |
| WDC                 | 16        | 17     | 11.43%  |
| Samsung Electronics | 11        | 12     | 7.86%   |
| Kingston            | 10        | 12     | 7.14%   |
| Intel               | 6         | 9      | 4.29%   |
| HGST                | 6         | 23     | 4.29%   |
| SanDisk             | 3         | 3      | 2.14%   |
| Micron Technology   | 3         | 3      | 2.14%   |
| Crucial             | 3         | 3      | 2.14%   |
| SK hynix            | 2         | 2      | 1.43%   |
| Fujitsu             | 2         | 5      | 1.43%   |
| A-DATA Technology   | 2         | 3      | 1.43%   |
| Transcend           | 1         | 1      | 0.71%   |
| SSSTC               | 1         | 1      | 0.71%   |
| SMI                 | 1         | 1      | 0.71%   |
| OCZ                 | 1         | 1      | 0.71%   |
| IBM/Hitachi         | 1         | 1      | 0.71%   |
| Hewlett-Packard     | 1         | 1      | 0.71%   |
| Fanxiang            | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 42     | 32.29%  |
| Hitachi             | 19        | 22     | 19.79%  |
| Toshiba             | 18        | 26     | 18.75%  |
| WDC                 | 16        | 17     | 16.67%  |
| HGST                | 6         | 23     | 6.25%   |
| Samsung Electronics | 3         | 3      | 3.13%   |
| Fujitsu             | 2         | 5      | 2.08%   |
| IBM/Hitachi         | 1         | 1      | 1.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 92        | 139    | 67.65%  |
| SSD  | 41        | 48     | 30.15%  |
| NVMe | 3         | 3      | 2.21%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 128GB                | 1         | 1      | 50%     |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 753       | 1238   | 83.76%  |
| Malfunc  | 136       | 190    | 15.13%  |
| Detected | 8         | 9      | 0.89%   |
| Failed   | 2         | 2      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 624       | 61.36%  |
| Samsung Electronics                     | 115       | 11.31%  |
| AMD                                     | 78        | 7.67%   |
| SanDisk                                 | 49        | 4.82%   |
| SK hynix                                | 22        | 2.16%   |
| Toshiba                                 | 17        | 1.67%   |
| Phison Electronics                      | 15        | 1.47%   |
| Micron Technology                       | 13        | 1.28%   |
| Silicon Motion                          | 12        | 1.18%   |
| Micron/Crucial Technology               | 11        | 1.08%   |
| KIOXIA                                  | 11        | 1.08%   |
| Kingston Technology Company             | 9         | 0.88%   |
| ADATA Technology                        | 7         | 0.69%   |
| Nvidia                                  | 5         | 0.49%   |
| Union Memory (Shenzhen)                 | 4         | 0.39%   |
| Solid State Storage Technology          | 4         | 0.39%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.29%   |
| Shenzhen Longsys Electronics            | 3         | 0.29%   |
| Realtek Semiconductor                   | 3         | 0.29%   |
| Transcend                               | 2         | 0.2%    |
| MAXIO Technology (Hangzhou)             | 2         | 0.2%    |
| JMicron Technology                      | 2         | 0.2%    |
| ULi Electronics                         | 1         | 0.1%    |
| Shenzhen Unionmemory Information System | 1         | 0.1%    |
| Lite-On Technology                      | 1         | 0.1%    |
| Lenovo                                  | 1         | 0.1%    |
| Broadcom / LSI                          | 1         | 0.1%    |
| Apple                                   | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 80        | 7.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 72        | 6.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 71        | 6.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 64        | 5.91%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 64        | 5.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 45        | 4.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 31        | 2.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 28        | 2.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 28        | 2.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 23        | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 23        | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 23        | 2.13%   |
| Unknown                                                                          | 23        | 2.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 22        | 2.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 21        | 1.94%   |
| Samsung NVMe SSD Controller 980                                                  | 20        | 1.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 18        | 1.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 15        | 1.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 15        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 14        | 1.29%   |
| Micron NVMe Storage Controller                                                   | 13        | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 13        | 1.2%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 11        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 11        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 10        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 9         | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9         | 0.83%   |
| Phison E12 NVMe Controller                                                       | 9         | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 8         | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 8         | 0.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 7         | 0.65%   |
| SK hynix BC511                                                                   | 7         | 0.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 621       | 59.65%  |
| NVMe | 299       | 28.72%  |
| IDE  | 83        | 7.97%   |
| RAID | 37        | 3.55%   |
| SAS  | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 753       | 85.86%  |
| AMD    | 123       | 14.03%  |
| ARM    | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 23        | 2.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 17        | 1.93%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 17        | 1.93%   |
| Intel CPU Version                       | 16        | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 16        | 1.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 14        | 1.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 13        | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 1.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 12        | 1.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 12        | 1.36%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 11        | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 11        | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 10        | 1.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 9         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 1.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 1.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 9         | 1.02%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 8         | 0.91%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 8         | 0.91%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 8         | 0.91%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 0.91%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 8         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 7         | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 0.79%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 7         | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 7         | 0.79%   |
| Intel Core 2 Duo                        | 7         | 0.79%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 7         | 0.79%   |
| Intel Pentium M processor               | 6         | 0.68%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 6         | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 6         | 0.68%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 6         | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 6         | 0.68%   |
| Intel Atom CPU N270 @ 1.60GHz           | 6         | 0.68%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 6         | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 6         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 266       | 30.26%  |
| Intel Core i7           | 233       | 26.51%  |
| Other                   | 70        | 7.96%   |
| Intel Core i3           | 41        | 4.66%   |
| Intel Core 2 Duo        | 38        | 4.32%   |
| AMD Ryzen 7             | 36        | 4.1%    |
| Intel Celeron           | 30        | 3.41%   |
| AMD Ryzen 5             | 27        | 3.07%   |
| Intel Atom              | 17        | 1.93%   |
| Intel Pentium M         | 12        | 1.37%   |
| Intel Pentium           | 12        | 1.37%   |
| AMD Ryzen 7 PRO         | 11        | 1.25%   |
| AMD Ryzen 5 PRO         | 7         | 0.8%    |
| Intel Core 2            | 6         | 0.68%   |
| AMD Ryzen 3             | 6         | 0.68%   |
| AMD E                   | 6         | 0.68%   |
| Intel Pentium Silver    | 5         | 0.57%   |
| Intel Pentium Dual      | 5         | 0.57%   |
| Intel Genuine           | 4         | 0.46%   |
| AMD A8                  | 4         | 0.46%   |
| AMD A6                  | 4         | 0.46%   |
| Intel Xeon              | 3         | 0.34%   |
| Intel Pentium 4         | 3         | 0.34%   |
| Intel Core i9           | 3         | 0.34%   |
| AMD E2                  | 3         | 0.34%   |
| Intel Core m3           | 2         | 0.23%   |
| Intel Celeron M         | 2         | 0.23%   |
| AMD Ryzen 9             | 2         | 0.23%   |
| AMD EPYC                | 2         | 0.23%   |
| AMD C-50                | 2         | 0.23%   |
| AMD A4                  | 2         | 0.23%   |
| Intel Pentium Dual-Core | 1         | 0.11%   |
| Intel Mobile Pentium 4  | 1         | 0.11%   |
| Intel Core Solo         | 1         | 0.11%   |
| Intel Core m7           | 1         | 0.11%   |
| Intel Core M            | 1         | 0.11%   |
| Intel Core Duo          | 1         | 0.11%   |
| Intel Core 2 Extreme    | 1         | 0.11%   |
| Intel Celeron Dual-Core | 1         | 0.11%   |
| ARM Cortex              | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 384       | 43.69%  |
| 4       | 269       | 30.6%   |
| Unknown | 55        | 6.26%   |
| 8       | 43        | 4.89%   |
| 16      | 37        | 4.21%   |
| 6       | 36        | 4.1%    |
| 1       | 34        | 3.87%   |
| 12      | 16        | 1.82%   |
| 10      | 3         | 0.34%   |
| 24      | 1         | 0.11%   |
| 20      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 869       | 99.2%   |
| 2       | 6         | 0.68%   |
| Unknown | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 603       | 68.68%  |
| 1       | 204       | 23.23%  |
| Unknown | 71        | 8.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 190       | 21.66%  |
| SandyBridge     | 82        | 9.35%   |
| IvyBridge       | 74        | 8.44%   |
| Skylake         | 61        | 6.96%   |
| Haswell         | 58        | 6.61%   |
| Broadwell       | 48        | 5.47%   |
| Unknown         | 35        | 3.99%   |
| TigerLake       | 31        | 3.53%   |
| Penryn          | 31        | 3.53%   |
| Core            | 31        | 3.53%   |
| Bonnell         | 29        | 3.31%   |
| Westmere        | 28        | 3.19%   |
| Zen 2           | 26        | 2.96%   |
| Zen+            | 22        | 2.51%   |
| CometLake       | 17        | 1.94%   |
| Zen 3           | 16        | 1.82%   |
| Silvermont      | 16        | 1.82%   |
| P6              | 15        | 1.71%   |
| Zen             | 11        | 1.25%   |
| Goldmont plus   | 9         | 1.03%   |
| Puma            | 8         | 0.91%   |
| IceLake         | 8         | 0.91%   |
| Bobcat          | 8         | 0.91%   |
| Excavator       | 6         | 0.68%   |
| NetBurst        | 4         | 0.46%   |
| Goldmont        | 3         | 0.34%   |
| Nehalem         | 2         | 0.23%   |
| K8 Hammer       | 2         | 0.23%   |
| K8 & K10 hybrid | 2         | 0.23%   |
| Piledriver      | 1         | 0.11%   |
| K10 Llano       | 1         | 0.11%   |
| K10             | 1         | 0.11%   |
| Jaguar          | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 686       | 65.27%  |
| Nvidia                           | 194       | 18.46%  |
| AMD                              | 168       | 15.98%  |
| Silicon Integrated Systems [SiS] | 2         | 0.19%   |
| Silicon Motion                   | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 72        | 6.54%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 68        | 6.18%   |
| Intel HD Graphics 5500                                                                   | 44        | 4%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 42        | 3.81%   |
| Intel UHD Graphics 620                                                                   | 41        | 3.72%   |
| Intel HD Graphics 620                                                                    | 38        | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 2.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 2.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 2.45%   |
| AMD Renoir                                                                               | 25        | 2.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 23        | 2.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 1.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.54%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 15        | 1.36%   |
| AMD Lucienne                                                                             | 15        | 1.36%   |
| Intel HD Graphics 530                                                                    | 14        | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.27%   |
| Intel HD Graphics 630                                                                    | 13        | 1.18%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 13        | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 13        | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.91%   |
| Nvidia TU117M                                                                            | 10        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 0.91%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.54%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.54%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 450       | 51.02%  |
| Intel + Nvidia           | 134       | 15.19%  |
| 1 x AMD                  | 123       | 13.95%  |
| 2 x Intel                | 78        | 8.84%   |
| 1 x Nvidia               | 44        | 4.99%   |
| Intel + AMD              | 22        | 2.49%   |
| AMD + Nvidia             | 15        | 1.7%    |
| 2 x AMD                  | 7         | 0.79%   |
| Other                    | 3         | 0.34%   |
| 2 x Nvidia               | 2         | 0.23%   |
| 1 x SiS                  | 2         | 0.23%   |
| 1 x Silicon Motion       | 1         | 0.11%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 784       | 88.59%  |
| Proprietary | 92        | 10.4%   |
| Unknown     | 9         | 1.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 736       | 82.79%  |
| 0.01-0.5   | 62        | 6.97%   |
| 1.01-2.0   | 38        | 4.27%   |
| 0.51-1.0   | 25        | 2.81%   |
| 3.01-4.0   | 15        | 1.69%   |
| 7.01-8.0   | 7         | 0.79%   |
| 2.01-3.0   | 3         | 0.34%   |
| 5.01-6.0   | 2         | 0.22%   |
| 8.01-16.0  | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 146       | 20.25%  |
| LG Display              | 131       | 18.17%  |
| BOE                     | 76        | 10.54%  |
| Chimei Innolux          | 73        | 10.12%  |
| Samsung Electronics     | 55        | 7.63%   |
| Lenovo                  | 36        | 4.99%   |
| Sharp                   | 24        | 3.33%   |
| Dell                    | 16        | 2.22%   |
| Apple                   | 12        | 1.66%   |
| Hewlett-Packard         | 11        | 1.53%   |
| Chi Mei Optoelectronics | 11        | 1.53%   |
| AOC                     | 10        | 1.39%   |
| InfoVision              | 9         | 1.25%   |
| Goldstar                | 8         | 1.11%   |
| Philips                 | 7         | 0.97%   |
| LGD                     | 7         | 0.97%   |
| Acer                    | 7         | 0.97%   |
| PANDA                   | 6         | 0.83%   |
| LG Philips              | 5         | 0.69%   |
| JDI                     | 5         | 0.69%   |
| BenQ                    | 5         | 0.69%   |
| ViewSonic               | 4         | 0.55%   |
| Toshiba                 | 4         | 0.55%   |
| Sceptre Tech            | 4         | 0.55%   |
| Iiyama                  | 4         | 0.55%   |
| CSO                     | 4         | 0.55%   |
| CPT                     | 4         | 0.55%   |
| Ancor Communications    | 4         | 0.55%   |
| HannStar                | 3         | 0.42%   |
| ASUSTek Computer        | 3         | 0.42%   |
| Vizio                   | 2         | 0.28%   |
| Unknown                 | 2         | 0.28%   |
| Panasonic               | 2         | 0.28%   |
| HKC                     | 2         | 0.28%   |
| Eizo                    | 2         | 0.28%   |
| YTH                     | 1         | 0.14%   |
| USR                     | 1         | 0.14%   |
| Unknown (XXX)           | 1         | 0.14%   |
| SDC                     | 1         | 0.14%   |
| Nvidia                  | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 10        | 1.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 6         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 6         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 5         | 0.69%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 5         | 0.69%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.55%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.55%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.55%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 4         | 0.55%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 4         | 0.55%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 4         | 0.55%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.55%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 4         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 4         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 4         | 0.55%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 4         | 0.55%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 4         | 0.55%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 4         | 0.55%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 4         | 0.55%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 3         | 0.41%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 3         | 0.41%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 3         | 0.41%   |
| LGD LCD Monitor 1920x1080                                            | 3         | 0.41%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 3         | 0.41%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 3         | 0.41%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 0.41%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 3         | 0.41%   |
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                | 3         | 0.41%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 3         | 0.41%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 3         | 0.41%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 3         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 295       | 42.32%  |
| 1366x768 (WXGA)    | 172       | 24.68%  |
| 1600x900 (HD+)     | 43        | 6.17%   |
| 1280x800 (WXGA)    | 33        | 4.73%   |
| 3840x2160 (4K)     | 30        | 4.3%    |
| 2560x1440 (QHD)    | 24        | 3.44%   |
| 1024x600           | 15        | 2.15%   |
| 1920x1200 (WUXGA)  | 13        | 1.87%   |
| 1440x900 (WXGA+)   | 11        | 1.58%   |
| 2560x1080          | 7         | 1%      |
| 2256x1504          | 6         | 0.86%   |
| 3440x1440          | 4         | 0.57%   |
| 3200x1800 (QHD+)   | 4         | 0.57%   |
| 2560x1600          | 4         | 0.57%   |
| 1280x1024 (SXGA)   | 4         | 0.57%   |
| Unknown            | 4         | 0.57%   |
| 3000x2000          | 3         | 0.43%   |
| 2160x1440          | 3         | 0.43%   |
| 1680x1050 (WSXGA+) | 3         | 0.43%   |
| 2880x1800          | 2         | 0.29%   |
| 2880x1620          | 2         | 0.29%   |
| 1920x540           | 2         | 0.29%   |
| 1400x1050          | 2         | 0.29%   |
| 1024x768 (XGA)     | 2         | 0.29%   |
| 5760x1080          | 1         | 0.14%   |
| 4480x1080          | 1         | 0.14%   |
| 3840x1200          | 1         | 0.14%   |
| 3520x1080          | 1         | 0.14%   |
| 2520x1680          | 1         | 0.14%   |
| 2240x1400          | 1         | 0.14%   |
| 1360x768           | 1         | 0.14%   |
| 1280x720 (HD)      | 1         | 0.14%   |
| 1080x2160          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 230       | 32.12%  |
| 15      | 212       | 29.61%  |
| 12      | 61        | 8.52%   |
| 17      | 27        | 3.77%   |
| 24      | 26        | 3.63%   |
| 27      | 23        | 3.21%   |
| 14      | 23        | 3.21%   |
| Unknown | 22        | 3.07%   |
| 23      | 15        | 2.09%   |
| 11      | 13        | 1.82%   |
| 10      | 12        | 1.68%   |
| 34      | 7         | 0.98%   |
| 21      | 7         | 0.98%   |
| 19      | 6         | 0.84%   |
| 31      | 5         | 0.7%    |
| 29      | 3         | 0.42%   |
| 18      | 3         | 0.42%   |
| 9       | 3         | 0.42%   |
| 64      | 2         | 0.28%   |
| 22      | 2         | 0.28%   |
| 49      | 1         | 0.14%   |
| 48      | 1         | 0.14%   |
| 46      | 1         | 0.14%   |
| 43      | 1         | 0.14%   |
| 42      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 35      | 1         | 0.14%   |
| 33      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |
| 26      | 1         | 0.14%   |
| 20      | 1         | 0.14%   |
| 16      | 1         | 0.14%   |
| 8       | 1         | 0.14%   |
| 5       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 384       | 53.86%  |
| 201-300     | 171       | 23.98%  |
| 501-600     | 58        | 8.13%   |
| 351-400     | 29        | 4.07%   |
| Unknown     | 22        | 3.09%   |
| 401-500     | 16        | 2.24%   |
| 601-700     | 12        | 1.68%   |
| 701-800     | 9         | 1.26%   |
| 1001-1500   | 6         | 0.84%   |
| 801-900     | 2         | 0.28%   |
| 101-200     | 2         | 0.28%   |
| 901-1000    | 1         | 0.14%   |
| 1-100       | 1         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 522       | 80.43%  |
| 16/10   | 67        | 10.32%  |
| Unknown | 20        | 3.08%   |
| 3/2     | 12        | 1.85%   |
| 21/9    | 11        | 1.69%   |
| 4/3     | 8         | 1.23%   |
| 5/4     | 4         | 0.62%   |
| 6/5     | 1         | 0.15%   |
| 3.18    | 1         | 0.15%   |
| 11/10   | 1         | 0.15%   |
| 1.96    | 1         | 0.15%   |
| 0.46    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 209       | 29.11%  |
| 91-100         | 168       | 23.4%   |
| 61-70          | 61        | 8.5%    |
| 101-110        | 50        | 6.96%   |
| 201-250        | 44        | 6.13%   |
| 71-80          | 37        | 5.15%   |
| 301-350        | 26        | 3.62%   |
| 121-130        | 25        | 3.48%   |
| Unknown        | 22        | 3.06%   |
| 351-500        | 15        | 2.09%   |
| 41-50          | 14        | 1.95%   |
| 51-60          | 13        | 1.81%   |
| 251-300        | 8         | 1.11%   |
| 151-200        | 7         | 0.97%   |
| 501-1000       | 5         | 0.7%    |
| 141-150        | 4         | 0.56%   |
| More than 1000 | 3         | 0.42%   |
| 1-40           | 3         | 0.42%   |
| 131-140        | 3         | 0.42%   |
| 111-120        | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 306       | 43.34%  |
| 101-120       | 171       | 24.22%  |
| 51-100        | 101       | 14.31%  |
| 161-240       | 79        | 11.19%  |
| More than 240 | 24        | 3.4%    |
| Unknown       | 22        | 3.12%   |
| 1-50          | 3         | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 581       | 64.41%  |
| 0     | 224       | 24.83%  |
| 2     | 91        | 10.09%  |
| 3     | 5         | 0.55%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 615       | 44.89%  |
| Realtek Semiconductor             | 347       | 25.33%  |
| Qualcomm Atheros                  | 166       | 12.12%  |
| Broadcom                          | 85        | 6.2%    |
| Ralink Technology                 | 16        | 1.17%   |
| Marvell Technology Group          | 16        | 1.17%   |
| TP-Link                           | 14        | 1.02%   |
| Edimax Technology                 | 12        | 0.88%   |
| MediaTek                          | 8         | 0.58%   |
| Ericsson Business Mobile Networks | 8         | 0.58%   |
| Sierra Wireless                   | 7         | 0.51%   |
| Xiaomi                            | 6         | 0.44%   |
| Samsung Electronics               | 6         | 0.44%   |
| Hewlett-Packard                   | 6         | 0.44%   |
| Ralink                            | 5         | 0.36%   |
| Google                            | 5         | 0.36%   |
| Nvidia                            | 4         | 0.29%   |
| Dell                              | 4         | 0.29%   |
| D-Link System                     | 4         | 0.29%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.22%   |
| NetGear                           | 3         | 0.22%   |
| D-Link                            | 3         | 0.22%   |
| AMD                               | 3         | 0.22%   |
| Qualcomm                          | 2         | 0.15%   |
| Lenovo                            | 2         | 0.15%   |
| JMicron Technology                | 2         | 0.15%   |
| Huawei Technologies               | 2         | 0.15%   |
| Arduino SA                        | 2         | 0.15%   |
| Van Ooijen Technische Informatica | 1         | 0.07%   |
| ULi Electronics                   | 1         | 0.07%   |
| Shenzhen Goodix Technology        | 1         | 0.07%   |
| Sagem                             | 1         | 0.07%   |
| Realtek                           | 1         | 0.07%   |
| OPPO Electronics                  | 1         | 0.07%   |
| OpenMoko                          | 1         | 0.07%   |
| National Semiconductor            | 1         | 0.07%   |
| HMD Global                        | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |
| dog hunter                        | 1         | 0.07%   |
| BUFFALO                           | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 222       | 12.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 84        | 4.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 72        | 4.12%   |
| Intel Wireless 8265 / 8275                                              | 69        | 3.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 3.37%   |
| Intel Wireless 8260                                                     | 42        | 2.4%    |
| Intel Wireless 7265                                                     | 37        | 2.12%   |
| Intel Wireless 7260                                                     | 34        | 1.94%   |
| Intel Wi-Fi 6 AX200                                                     | 34        | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 33        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 1.54%   |
| Intel Wireless-AC 9260                                                  | 27        | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 1.49%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 1.26%   |
| Intel Ethernet Connection I219-LM                                       | 22        | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                                   | 22        | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                                   | 22        | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 21        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 21        | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 18        | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                    | 17        | 0.97%   |
| Intel Wireless 3165                                                     | 16        | 0.91%   |
| Intel Ethernet Connection I217-LM                                       | 16        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 0.74%   |
| Intel Ethernet Connection I218-LM                                       | 13        | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 12        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                                | 12        | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.63%   |
| Intel Wireless 3160                                                     | 11        | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 10        | 0.57%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 578       | 60.84%  |
| Qualcomm Atheros      | 145       | 15.26%  |
| Realtek Semiconductor | 88        | 9.26%   |
| Broadcom              | 63        | 6.63%   |
| Ralink Technology     | 16        | 1.68%   |
| TP-Link               | 14        | 1.47%   |
| Edimax Technology     | 12        | 1.26%   |
| MediaTek              | 8         | 0.84%   |
| Sierra Wireless       | 5         | 0.53%   |
| Ralink                | 5         | 0.53%   |
| D-Link System         | 4         | 0.42%   |
| NetGear               | 3         | 0.32%   |
| Dell                  | 3         | 0.32%   |
| D-Link                | 3         | 0.32%   |
| Sagem                 | 1         | 0.11%   |
| BUFFALO               | 1         | 0.11%   |
| Atheros               | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 69        | 7.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 6.17%   |
| Intel Wireless 8260                                                     | 42        | 4.39%   |
| Intel Wireless 7265                                                     | 37        | 3.87%   |
| Intel Wireless 7260                                                     | 34        | 3.56%   |
| Intel Wi-Fi 6 AX200                                                     | 34        | 3.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 33        | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 2.82%   |
| Intel Wireless-AC 9260                                                  | 27        | 2.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 2.72%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 2.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 21        | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 21        | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.09%   |
| Intel Centrino Ultimate-N 6300                                          | 17        | 1.78%   |
| Intel Wireless 3165                                                     | 16        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 1.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 1.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 12        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 1.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 1.15%   |
| Intel Wireless 3160                                                     | 11        | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 1.15%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 10        | 1.05%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 10        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 9         | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.84%   |
| Ralink RT5370 Wireless Adapter                                          | 8         | 0.84%   |
| Intel WiFi Link 5100                                                    | 8         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 309       | 41.31%  |
| Realtek Semiconductor            | 302       | 40.37%  |
| Qualcomm Atheros                 | 44        | 5.88%   |
| Broadcom                         | 41        | 5.48%   |
| Marvell Technology Group         | 16        | 2.14%   |
| Xiaomi                           | 6         | 0.8%    |
| Samsung Electronics              | 6         | 0.8%    |
| Nvidia                           | 4         | 0.53%   |
| Google                           | 4         | 0.53%   |
| AMD                              | 3         | 0.4%    |
| Silicon Integrated Systems [SiS] | 2         | 0.27%   |
| Qualcomm                         | 2         | 0.27%   |
| Lenovo                           | 2         | 0.27%   |
| JMicron Technology               | 2         | 0.27%   |
| Realtek                          | 1         | 0.13%   |
| OPPO Electronics                 | 1         | 0.13%   |
| National Semiconductor           | 1         | 0.13%   |
| HMD Global                       | 1         | 0.13%   |
| Aquantia                         | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 222       | 29.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 84        | 11.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 72        | 9.61%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 2.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 2.94%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 2.14%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 1.74%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 9         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                          | 9         | 1.2%    |
| Intel Ethernet Connection I219-V                                  | 8         | 1.07%   |
| Intel Ethernet Connection (6) I219-LM                             | 8         | 1.07%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.8%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.67%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.67%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.67%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 5         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.53%   |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.4%    |
| Intel Ethernet Connection (5) I219-V                              | 3         | 0.4%    |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.4%    |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.4%    |
| Intel 82562GT 10/100 Network Connection                           | 3         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 857       | 52.67%  |
| Ethernet | 726       | 44.62%  |
| Modem    | 31        | 1.91%   |
| Unknown  | 13        | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 644       | 52.53%  |
| Ethernet | 574       | 46.82%  |
| Modem    | 5         | 0.41%   |
| Unknown  | 3         | 0.24%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 686       | 78.22%  |
| 1     | 170       | 19.38%  |
| 3     | 13        | 1.48%   |
| 0     | 5         | 0.57%   |
| 6     | 2         | 0.23%   |
| 5     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 812       | 91.13%  |
| Yes  | 79        | 8.87%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 372       | 60.29%  |
| Broadcom                        | 55        | 8.91%   |
| Qualcomm Atheros Communications | 45        | 7.29%   |
| Realtek Semiconductor           | 31        | 5.02%   |
| Apple                           | 21        | 3.4%    |
| Foxconn / Hon Hai               | 20        | 3.24%   |
| IMC Networks                    | 15        | 2.43%   |
| Dell                            | 14        | 2.27%   |
| Lite-On Technology              | 12        | 1.94%   |
| Hewlett-Packard                 | 10        | 1.62%   |
| Skylight Digital                | 5         | 0.81%   |
| ASUSTek Computer                | 5         | 0.81%   |
| Alps Electric                   | 4         | 0.65%   |
| Cambridge Silicon Radio         | 3         | 0.49%   |
| Toshiba                         | 1         | 0.16%   |
| Ralink                          | 1         | 0.16%   |
| Opticis                         | 1         | 0.16%   |
| Esel International              | 1         | 0.16%   |
| Creative Technology             | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 160       | 25.93%  |
| Intel AX201 Bluetooth                                       | 58        | 9.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 53        | 8.59%   |
| Intel AX200 Bluetooth                                       | 33        | 5.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 22        | 3.57%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 21        | 3.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 20        | 3.24%   |
| Apple Bluetooth Host Controller                             | 14        | 2.27%   |
| Realtek Bluetooth Adapter                                   | 13        | 2.11%   |
| Intel Wireless-AC 3168 Bluetooth                            | 12        | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 12        | 1.94%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 12        | 1.94%   |
| Intel AX210 Bluetooth                                       | 11        | 1.78%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 10        | 1.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 1.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 7         | 1.13%   |
| Dell DW375 Bluetooth Module                                 | 7         | 1.13%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 0.97%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 5         | 0.81%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.81%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 0.65%   |
| Realtek Bluetooth 4.0 Adapter                               | 4         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 4         | 0.65%   |
| Intel Wireless Bluetooth                                    | 4         | 0.65%   |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 0.65%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 4         | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 3         | 0.49%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 0.49%   |
| IMC Networks Bluetooth module                               | 3         | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 0.49%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 3         | 0.49%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 3         | 0.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 0.49%   |
| ASUS BT-253 Bluetooth Adapter                               | 3         | 0.49%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 0.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 740       | 72.41%  |
| AMD                                  | 141       | 13.8%   |
| Nvidia                               | 85        | 8.32%   |
| Lenovo                               | 12        | 1.17%   |
| Realtek Semiconductor                | 5         | 0.49%   |
| Logitech                             | 4         | 0.39%   |
| GN Netcom                            | 4         | 0.39%   |
| C-Media Electronics                  | 4         | 0.39%   |
| Texas Instruments                    | 3         | 0.29%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.29%   |
| Plantronics                          | 3         | 0.29%   |
| SteelSeries ApS                      | 2         | 0.2%    |
| Kingston Technology                  | 2         | 0.2%    |
| JMTek                                | 2         | 0.2%    |
| ASUSTek Computer                     | 2         | 0.2%    |
| ULi Electronics                      | 1         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.1%    |
| Sony                                 | 1         | 0.1%    |
| Microsoft                            | 1         | 0.1%    |
| M-Audio                              | 1         | 0.1%    |
| Hewlett-Packard                      | 1         | 0.1%    |
| Generalplus Technology               | 1         | 0.1%    |
| ESS Technology                       | 1         | 0.1%    |
| Creative Technology                  | 1         | 0.1%    |
| CMX Systems                          | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 128       | 10.45%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 85        | 6.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 79        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 77        | 6.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 49        | 4%      |
| Intel Broadwell-U Audio Controller                                                                | 48        | 3.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 45        | 3.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 41        | 3.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 32        | 2.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 32        | 2.61%   |
| Intel 8 Series HD Audio Controller                                                                | 32        | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 32        | 2.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 31        | 2.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 2.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26        | 2.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26        | 2.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 25        | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 25        | 2.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 1.55%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 1.39%   |
| Intel CM238 HD Audio Controller                                                                   | 16        | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 0.98%   |
| AMD FCH Azalia Controller                                                                         | 12        | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.57%   |
| Lenovo Realtek USB Audio                                                                          | 7         | 0.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.49%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 0.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.49%   |
| Unknown                                                                                           | 6         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.41%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 301       | 28.69%  |
| SK hynix              | 228       | 21.73%  |
| Micron Technology     | 108       | 10.3%   |
| Kingston              | 93        | 8.87%   |
| Unknown               | 80        | 7.63%   |
| Crucial               | 51        | 4.86%   |
| Ramaxel Technology    | 26        | 2.48%   |
| Unknown               | 25        | 2.38%   |
| Elpida                | 18        | 1.72%   |
| Corsair               | 18        | 1.72%   |
| A-DATA Technology     | 13        | 1.24%   |
| Nanya Technology      | 11        | 1.05%   |
| G.Skill               | 8         | 0.76%   |
| Transcend             | 7         | 0.67%   |
| Team                  | 7         | 0.67%   |
| Smart                 | 5         | 0.48%   |
| Neo Forza             | 5         | 0.48%   |
| PNY                   | 4         | 0.38%   |
| GOODRAM               | 4         | 0.38%   |
| Avant                 | 4         | 0.38%   |
| 48spaces              | 4         | 0.38%   |
| Unknown (ABCD)        | 3         | 0.29%   |
| Goldkey               | 3         | 0.29%   |
| Super Talent          | 2         | 0.19%   |
| PUSKILL               | 2         | 0.19%   |
| Patriot               | 2         | 0.19%   |
| KomputerBay           | 2         | 0.19%   |
| V-GeN                 | 1         | 0.1%    |
| V-Color               | 1         | 0.1%    |
| Teikon                | 1         | 0.1%    |
| Qimonda               | 1         | 0.1%    |
| Magnum Tech           | 1         | 0.1%    |
| Kllisre               | 1         | 0.1%    |
| KingTiger             | 1         | 0.1%    |
| Kingmax Semiconductor | 1         | 0.1%    |
| Golden Empire         | 1         | 0.1%    |
| Gold Key              | 1         | 0.1%    |
| CSX                   | 1         | 0.1%    |
| Apacer                | 1         | 0.1%    |
| AMD                   | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 25        | 2.21%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 19        | 1.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 17        | 1.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 16        | 1.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 16        | 1.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 15        | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 14        | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 14        | 1.24%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 12        | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s       | 11        | 0.97%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 10        | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 9         | 0.8%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 9         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.8%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 8         | 0.71%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 8         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 7         | 0.62%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 7         | 0.62%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 7         | 0.62%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 7         | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 6         | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s            | 6         | 0.53%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s         | 6         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 6         | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 6         | 0.53%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 6         | 0.53%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 6         | 0.53%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 6         | 0.53%   |
| Unknown RAM Module 512MB SODIMM DDR                         | 5         | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 5         | 0.44%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s       | 5         | 0.44%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 5         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 5         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 5         | 0.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s      | 5         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 5         | 0.44%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s     | 5         | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 5         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 356       | 40.32%  |
| DDR4    | 352       | 39.86%  |
| DDR2    | 68        | 7.7%    |
| LPDDR3  | 38        | 4.3%    |
| LPDDR4  | 24        | 2.72%   |
| DDR     | 17        | 1.93%   |
| SDRAM   | 9         | 1.02%   |
| Unknown | 8         | 0.91%   |
| LPDDR5  | 4         | 0.45%   |
| DDR5    | 3         | 0.34%   |
| DRAM    | 2         | 0.23%   |
| SRAM    | 1         | 0.11%   |
| RAM     | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 791       | 88.88%  |
| Row Of Chips | 66        | 7.42%   |
| Chip         | 23        | 2.58%   |
| Unknown      | 7         | 0.79%   |
| DIMM         | 3         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 344       | 35.43%  |
| 4096  | 285       | 29.35%  |
| 2048  | 135       | 13.9%   |
| 16384 | 127       | 13.08%  |
| 1024  | 44        | 4.53%   |
| 32768 | 21        | 2.16%   |
| 512   | 10        | 1.03%   |
| 256   | 4         | 0.41%   |
| 2560  | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 220       | 23.21%  |
| 2667    | 128       | 13.5%   |
| 3200    | 109       | 11.5%   |
| 2400    | 100       | 10.55%  |
| 2133    | 72        | 7.59%   |
| 1333    | 71        | 7.49%   |
| 1334    | 46        | 4.85%   |
| 667     | 36        | 3.8%    |
| Unknown | 33        | 3.48%   |
| 1867    | 31        | 3.27%   |
| 800     | 18        | 1.9%    |
| 4267    | 15        | 1.58%   |
| 533     | 15        | 1.58%   |
| 1067    | 14        | 1.48%   |
| 1066    | 9         | 0.95%   |
| 975     | 6         | 0.63%   |
| 4266    | 4         | 0.42%   |
| 6400    | 3         | 0.32%   |
| 4800    | 3         | 0.32%   |
| 2933    | 2         | 0.21%   |
| 2048    | 2         | 0.21%   |
| 1866    | 2         | 0.21%   |
| 2666    | 1         | 0.11%   |
| 1596    | 1         | 0.11%   |
| 1200    | 1         | 0.11%   |
| 666     | 1         | 0.11%   |
| 333     | 1         | 0.11%   |
| 266     | 1         | 0.11%   |
| 200     | 1         | 0.11%   |
| 166     | 1         | 0.11%   |
| 100     | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 66.67%  |
| Samsung ML-1610 Mono Laser Printer | 1         | 33.33%  |

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
| Chicony Electronics                    | 207       | 30.62%  |
| IMC Networks                           | 80        | 11.83%  |
| Microdia                               | 65        | 9.62%   |
| Bison Electronics                      | 64        | 9.47%   |
| Realtek Semiconductor                  | 55        | 8.14%   |
| Sunplus Innovation Technology          | 44        | 6.51%   |
| Suyin                                  | 21        | 3.11%   |
| Lite-On Technology                     | 21        | 3.11%   |
| Syntek                                 | 15        | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 2.22%   |
| Quanta                                 | 11        | 1.63%   |
| Apple                                  | 9         | 1.33%   |
| Silicon Motion                         | 8         | 1.18%   |
| Luxvisions Innotech Limited            | 7         | 1.04%   |
| Lenovo                                 | 7         | 1.04%   |
| Logitech                               | 6         | 0.89%   |
| ALi                                    | 5         | 0.74%   |
| Z-Star Microelectronics                | 4         | 0.59%   |
| Importek                               | 4         | 0.59%   |
| Alcor Micro                            | 4         | 0.59%   |
| Supreme Electronics                    | 3         | 0.44%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.44%   |
| Ricoh                                  | 3         | 0.44%   |
| Primax Electronics                     | 2         | 0.3%    |
| Pixart Imaging                         | 2         | 0.3%    |
| Jiangxi Shinetech Optical              | 2         | 0.3%    |
| Intel                                  | 2         | 0.3%    |
| USB Camera                             | 1         | 0.15%   |
| Unknown                                | 1         | 0.15%   |
| OmniVision Technologies                | 1         | 0.15%   |
| Goodong Industry                       | 1         | 0.15%   |
| Genesys Logic                          | 1         | 0.15%   |
| DigiTech                               | 1         | 0.15%   |
| Cubeternet                             | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 65        | 9.49%   |
| Bison Integrated Camera                       | 33        | 4.82%   |
| IMC Networks Integrated Camera                | 28        | 4.09%   |
| Realtek Integrated_Webcam_HD                  | 18        | 2.63%   |
| Microdia Integrated_Webcam_HD                 | 18        | 2.63%   |
| Microdia Integrated Webcam                    | 18        | 2.63%   |
| Chicony HD WebCam                             | 17        | 2.48%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 15        | 2.19%   |
| Sunplus Integrated_Webcam_HD                  | 14        | 2.04%   |
| Lite-On Integrated Camera                     | 13        | 1.9%    |
| Chicony Integrated Camera (1280x720@30)       | 12        | 1.75%   |
| Realtek USB 2.0 PC Camera                     | 11        | 1.61%   |
| IMC Networks Realtek PC Camera                | 10        | 1.46%   |
| IMC Networks EasyCamera                       | 9         | 1.31%   |
| Chicony Chicony USB2.0 Camera                 | 8         | 1.17%   |
| Syntek Integrated Camera                      | 7         | 1.02%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 7         | 1.02%   |
| Chicony ThinkPad T490 Webcam                  | 7         | 1.02%   |
| Bison SunplusIT Integrated Camera             | 7         | 1.02%   |
| Sunplus HD WebCam                             | 6         | 0.88%   |
| Microdia Integrated Webcam HD                 | 6         | 0.88%   |
| IMC Networks Integrated Webcam                | 6         | 0.88%   |
| Chicony Realtek DMFT RGB                      | 6         | 0.88%   |
| Chicony Integrated IR Camera                  | 6         | 0.88%   |
| Bison Lenovo EasyCamera                       | 6         | 0.88%   |
| Syntek EasyCamera                             | 5         | 0.73%   |
| Sunplus Laptop Integrated WebCam HD           | 5         | 0.73%   |
| Quanta HD Webcam                              | 5         | 0.73%   |
| Lenovo Integrated Webcam [R5U877]             | 5         | 0.73%   |
| IMC Networks UVC VGA Webcam                   | 5         | 0.73%   |
| Chicony Integrated Camera [ThinkPad]          | 5         | 0.73%   |
| Bison ThinkPad Integrated Camera              | 5         | 0.73%   |
| Apple FaceTime HD Camera                      | 5         | 0.73%   |
| Realtek Integrated Webcam                     | 4         | 0.58%   |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 0.58%   |
| Luxvisions Innotech Limited Integrated Camera | 4         | 0.58%   |
| Lite-On HP HD Camera                          | 4         | 0.58%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 0.58%   |
| Chicony USB2.0 VGA UVC WebCam                 | 4         | 0.58%   |
| Chicony USB 2.0 Camera                        | 4         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 66        | 32.51%  |
| Synaptics                  | 51        | 25.12%  |
| Shenzhen Goodix Technology | 28        | 13.79%  |
| Upek                       | 18        | 8.87%   |
| STMicroelectronics         | 10        | 4.93%   |
| AuthenTec                  | 10        | 4.93%   |
| Broadcom                   | 8         | 3.94%   |
| LighTuning Technology      | 6         | 2.96%   |
| FocalTech Systems          | 3         | 1.48%   |
| Elan Microelectronics      | 2         | 0.99%   |
| Samsung Electronics        | 1         | 0.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 24        | 11.82%  |
| Shenzhen Goodix Fingerprint Reader                                           | 21        | 10.34%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 20        | 9.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 18        | 8.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 18        | 8.87%   |
| Validity Sensors Synaptics WBDI                                              | 15        | 7.39%   |
| STMicroelectronics Fingerprint Reader                                        | 10        | 4.93%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 8         | 3.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 3.94%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 7         | 3.45%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 2.96%   |
| Shenzhen Goodix  Fingerprint Device                                          | 5         | 2.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 5         | 2.46%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 4         | 1.97%   |
| AuthenTec AES1660                                                            | 4         | 1.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 3         | 1.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 1.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 0.99%   |
| Validity Sensors VFS Fingerprint sensor                                      | 2         | 0.99%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 2         | 0.99%   |
| Synaptics UWP WBDI                                                           | 2         | 0.99%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 2         | 0.99%   |
| FocalTech Systems Fingerprint Reader                                         | 2         | 0.99%   |
| Elan Fingerprint Sensor                                                      | 2         | 0.99%   |
| AuthenTec AES2810                                                            | 2         | 0.99%   |
| Validity Sensors VFS491                                                      | 1         | 0.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 0.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.49%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.49%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.49%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 0.49%   |
| FocalTech Systems FocalTech Fingerprint Device                               | 1         | 0.49%   |
| AuthenTec AES2660                                                            | 1         | 0.49%   |

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
| 2     | 273       | 29.71%  |
| 1     | 273       | 29.71%  |
| 3     | 182       | 19.8%   |
| 0     | 86        | 9.36%   |
| 4     | 78        | 8.49%   |
| 5     | 17        | 1.85%   |
| 6     | 8         | 0.87%   |
| 9     | 1         | 0.11%   |
| 7     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 624       | 38.66%  |
| Bluetooth                | 267       | 16.54%  |
| Card reader              | 199       | 12.33%  |
| Fingerprint reader       | 197       | 12.21%  |
| Net/wireless             | 184       | 11.4%   |
| Firewire controller      | 77        | 4.77%   |
| Storage                  | 20        | 1.24%   |
| Modem                    | 14        | 0.87%   |
| Network                  | 12        | 0.74%   |
| Sound                    | 11        | 0.68%   |
| Net/ethernet             | 7         | 0.43%   |
| Storage/nvme             | 1         | 0.06%   |
| Graphics card            | 1         | 0.06%   |

