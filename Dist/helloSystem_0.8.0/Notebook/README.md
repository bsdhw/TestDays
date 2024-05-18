helloSystem 0.8.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.0.

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

Total: 167

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X220 4286CTO       | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| HP            | ZBook 15 G3                 | [4965fc4251](https://bsd-hardware.info/?probe=4965fc4251) | May 21, 2023 |
| Acer          | Aspire 5745DG               | [2b8bf9802e](https://bsd-hardware.info/?probe=2b8bf9802e) | Mar 31, 2023 |
| MECHREVO S... | S1 Series                   | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Apple         | MacBookAir1,1               | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| Lenovo        | ThinkPad X230 23252G8       | [2ff46d6b7c](https://bsd-hardware.info/?probe=2ff46d6b7c) | Mar 10, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [aafc670aa7](https://bsd-hardware.info/?probe=aafc670aa7) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| Lenovo        | G400s 20244                 | [215f16c5d9](https://bsd-hardware.info/?probe=215f16c5d9) | Mar 05, 2023 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [8037475831](https://bsd-hardware.info/?probe=8037475831) | Mar 05, 2023 |
| Acer          | TravelMate TX50-G2          | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| HP            | G62                         | [18487b3ab2](https://bsd-hardware.info/?probe=18487b3ab2) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Notebook      | N2x0WU                      | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [115bd3bc38](https://bsd-hardware.info/?probe=115bd3bc38) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Toshiba       | dynabook R63/P              | [c41c3adfa4](https://bsd-hardware.info/?probe=c41c3adfa4) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [b3e56e9656](https://bsd-hardware.info/?probe=b3e56e9656) | Feb 25, 2023 |
| Dell          | Latitude 5591               | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| HP            | EliteBook 840 G1            | [0480ce43f2](https://bsd-hardware.info/?probe=0480ce43f2) | Feb 24, 2023 |
| HP            | EliteBook 840 G1            | [77c17e4a2f](https://bsd-hardware.info/?probe=77c17e4a2f) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Acer          | Aspire E1-421               | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [92bca4d026](https://bsd-hardware.info/?probe=92bca4d026) | Feb 19, 2023 |
| Lenovo        | G400s 20244                 | [f2c258a0ae](https://bsd-hardware.info/?probe=f2c258a0ae) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Dell          | Inspiron 5767               | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| Google        | Lulu                        | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| MSI           | GF76 12UE                   | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Sony          | SVF1421E4E                  | [d0a9e97993](https://bsd-hardware.info/?probe=d0a9e97993) | Feb 09, 2023 |
| HP            | Laptop 14-df0xxx            | [1dc503f21d](https://bsd-hardware.info/?probe=1dc503f21d) | Feb 09, 2023 |
| Acer          | Aspire 4739Z                | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| ASUSTek       | N76VZ                       | [3b7e2ee70b](https://bsd-hardware.info/?probe=3b7e2ee70b) | Feb 08, 2023 |
| ASUSTek       | K84L                        | [d58c178c51](https://bsd-hardware.info/?probe=d58c178c51) | Feb 08, 2023 |
| HP            | Notebook                    | [507e85c092](https://bsd-hardware.info/?probe=507e85c092) | Feb 08, 2023 |
| ASUSTek       | 1201N                       | [3f44d6ed3f](https://bsd-hardware.info/?probe=3f44d6ed3f) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| HP            | Notebook                    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [80f8e59cab](https://bsd-hardware.info/?probe=80f8e59cab) | Feb 05, 2023 |
| HP            | 2000                        | [7c997ce022](https://bsd-hardware.info/?probe=7c997ce022) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c771b7daf4](https://bsd-hardware.info/?probe=c771b7daf4) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Lenovo        | B50-80 80EW                 | [97da411601](https://bsd-hardware.info/?probe=97da411601) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [a8ec146fc6](https://bsd-hardware.info/?probe=a8ec146fc6) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| Unknown       | Unknown                     | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| HP            | Mini 210-1000               | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| MSI           | Modern 15 A5M               | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| Dell          | Precision 5540              | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Packard Be... | DOT S                       | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Dell          | Latitude 5400               | [a266199ace](https://bsd-hardware.info/?probe=a266199ace) | Jan 27, 2023 |
| Google        | Cave                        | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| HP            | EliteBook 2560p             | [80c808de34](https://bsd-hardware.info/?probe=80c808de34) | Jan 25, 2023 |
| Timi          | TM1607                      | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | Latitude 3540               | [a180a149f5](https://bsd-hardware.info/?probe=a180a149f5) | Jan 24, 2023 |
| Dell          | Latitude 5580               | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Apple         | MacBookPro9,2               | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| ASUSTek       | K50IN                       | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| HP            | ZBook 15 G4                 | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| Razer         | Blade Stealth               | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Acer          | Aspire 5251                 | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Apple         | MacBook5,2                  | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Dell          | Latitude E5550              | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Toshiba       | Satellite S55t-B            | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| HP            | OMEN by Laptop              | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| HP            | 250 G6 Notebook PC          | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| HP            | Unknown                     | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| TUXEDO        | Aura 15 Gen1                | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | [4b5603b38b](https://bsd-hardware.info/?probe=4b5603b38b) | Apr 29, 2022 |
| ASUSTek       | 1001PX                      | [b47a498f2e](https://bsd-hardware.info/?probe=b47a498f2e) | Apr 08, 2022 |
| Dell          | Latitude E5470              | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| Sony          | VGN-AW21S_B                 | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| PCSTICK       | Unknown                     | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| HUAWEI        | BOD-WXX9                    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| Acer          | V5-131                      | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude 7480               | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| PCSTICK       | Unknown                     | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| ASUSTek       | 1001PX                      | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| Timi          | RedmiBook Pro 15            | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Apple         | MacBook5,2                  | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| Sony          | VPCEB1J1E                   | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| Lenovo        | ThinkPad T440 20B7A0B7MS    | [be30041f4e](https://bsd-hardware.info/?probe=be30041f4e) | Jan 10, 2022 |
| Lenovo        | G480 20149                  | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| HP            | EliteBook 820 G1            | [362940acbb](https://bsd-hardware.info/?probe=362940acbb) | Jan 03, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 134       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 128       | 95.52%  |
| GNOME        | 3         | 2.24%   |
| Window Maker | 1         | 0.75%   |
| IceWM        | 1         | 0.75%   |
| Cinnamon     | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 134       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 133       | 99.25%  |
| GDM  | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 50        | 37.04%  |
| en    | 50        | 37.04%  |
| ru    | 6         | 4.44%   |
| de    | 6         | 4.44%   |
| pt    | 5         | 3.7%    |
| es    | 4         | 2.96%   |
| zh_CN | 3         | 2.22%   |
| es_ES | 3         | 2.22%   |
| it    | 2         | 1.48%   |
| fr    | 2         | 1.48%   |
| sv    | 1         | 0.74%   |
| ru_RU | 1         | 0.74%   |
| pl    | 1         | 0.74%   |
| nl    | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 133       | 99.25%  |
| BIOS | 1         | 0.75%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 80        | 58.82%  |
| Zfs    | 55        | 40.44%  |
| Ufs    | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 133       | 99.25%  |
| MBR  | 1         | 0.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 30        | 22.39%  |
| Hewlett-Packard     | 21        | 15.67%  |
| Dell                | 18        | 13.43%  |
| ASUSTek Computer    | 9         | 6.72%   |
| Acer                | 9         | 6.72%   |
| Apple               | 7         | 5.22%   |
| Toshiba             | 4         | 2.99%   |
| Sony                | 4         | 2.99%   |
| MSI                 | 4         | 2.99%   |
| Timi                | 3         | 2.24%   |
| Google              | 3         | 2.24%   |
| TUXEDO              | 2         | 1.49%   |
| Samsung Electronics | 2         | 1.49%   |
| Packard Bell        | 2         | 1.49%   |
| Notebook            | 2         | 1.49%   |
| MECHREVO S1 Series  | 2         | 1.49%   |
| Star Labs           | 1         | 0.75%   |
| SLIMBOOK            | 1         | 0.75%   |
| PCSTICK             | 1         | 0.75%   |
| Panasonic           | 1         | 0.75%   |
| Kraftway            | 1         | 0.75%   |
| HUAWEI              | 1         | 0.75%   |
| Gigabyte Technology | 1         | 0.75%   |
| Gateway             | 1         | 0.75%   |
| Fujitsu Siemens     | 1         | 0.75%   |
| Fujitsu             | 1         | 0.75%   |
| Clevo               | 1         | 0.75%   |
| Unknown             | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 3         | 2.24%   |
| MSI PS63 Modern 8M                           | 2         | 1.49%   |
| MECHREVO S1 Series S1 Series                 | 2         | 1.49%   |
| HP Notebook                                  | 2         | 1.49%   |
| HP 250 G6 Notebook PC                        | 2         | 1.49%   |
| Apple MacBookAir5,1                          | 2         | 1.49%   |
| Apple MacBook5,2                             | 2         | 1.49%   |
| TUXEDO Pulse 14 Gen1                         | 1         | 0.75%   |
| TUXEDO Aura 15 Gen1                          | 1         | 0.75%   |
| Toshiba TECRA Z40-C-12Z                      | 1         | 0.75%   |
| Toshiba Satellite S55t-B                     | 1         | 0.75%   |
| Toshiba PORTEGE Z930                         | 1         | 0.75%   |
| Toshiba dynabook R63/P                       | 1         | 0.75%   |
| Timi TM1701                                  | 1         | 0.75%   |
| Timi TM1607                                  | 1         | 0.75%   |
| Timi RedmiBook Pro 15                        | 1         | 0.75%   |
| Star Labs StarBook                           | 1         | 0.75%   |
| Sony VPCEB1J1E                               | 1         | 0.75%   |
| Sony VGN-AW21S_B                             | 1         | 0.75%   |
| Sony SVF1421E4E                              | 1         | 0.75%   |
| Sony SVE1511C5E                              | 1         | 0.75%   |
| SLIMBOOK PROX-AMD5                           | 1         | 0.75%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.75%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK          | 1         | 0.75%   |
| Panasonic CF-C1BWFAZ1M                       | 1         | 0.75%   |
| Packard Bell EasyNote_MX52-B-071             | 1         | 0.75%   |
| Packard Bell DOT S                           | 1         | 0.75%   |
| Notebook NV4XMB,ME,MZ                        | 1         | 0.75%   |
| Notebook N2x0WU                              | 1         | 0.75%   |
| MSI Modern 15 A5M                            | 1         | 0.75%   |
| MSI GF76 12UE                                | 1         | 0.75%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00        | 1         | 0.75%   |
| Lenovo ThinkPad X250 20CLS23500              | 1         | 0.75%   |
| Lenovo ThinkPad X250 20CLS1WP01              | 1         | 0.75%   |
| Lenovo ThinkPad X230 23252G8                 | 1         | 0.75%   |
| Lenovo ThinkPad X220 4286CTO                 | 1         | 0.75%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 3448AWU            | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 3444FEU            | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7002FUS     | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 20        | 14.93%  |
| Dell Latitude          | 10        | 7.46%   |
| Acer Aspire            | 8         | 5.97%   |
| Dell Inspiron          | 6         | 4.48%   |
| Lenovo IdeaPad         | 5         | 3.73%   |
| HP EliteBook           | 5         | 3.73%   |
| Unknown                | 3         | 2.24%   |
| MSI PS63               | 2         | 1.49%   |
| MECHREVO S1 Series S1  | 2         | 1.49%   |
| HP ZBook               | 2         | 1.49%   |
| HP OMEN                | 2         | 1.49%   |
| HP Notebook            | 2         | 1.49%   |
| HP Laptop              | 2         | 1.49%   |
| HP 250                 | 2         | 1.49%   |
| ASUS VivoBook          | 2         | 1.49%   |
| Apple MacBookAir5      | 2         | 1.49%   |
| Apple MacBook5         | 2         | 1.49%   |
| TUXEDO Pulse           | 1         | 0.75%   |
| TUXEDO Aura            | 1         | 0.75%   |
| Toshiba TECRA          | 1         | 0.75%   |
| Toshiba Satellite      | 1         | 0.75%   |
| Toshiba PORTEGE        | 1         | 0.75%   |
| Toshiba dynabook       | 1         | 0.75%   |
| Timi TM1701            | 1         | 0.75%   |
| Timi TM1607            | 1         | 0.75%   |
| Timi RedmiBook         | 1         | 0.75%   |
| Star Labs StarBook     | 1         | 0.75%   |
| Sony VPCEB1J1E         | 1         | 0.75%   |
| Sony VGN-AW21S         | 1         | 0.75%   |
| Sony SVF1421E4E        | 1         | 0.75%   |
| Sony SVE1511C5E        | 1         | 0.75%   |
| SLIMBOOK PROX-AMD5     | 1         | 0.75%   |
| Samsung 340XAA         | 1         | 0.75%   |
| Samsung 270E5K         | 1         | 0.75%   |
| Panasonic CF-C1BWFAZ1M | 1         | 0.75%   |
| Packard Bell EasyNote  | 1         | 0.75%   |
| Packard Bell DOT       | 1         | 0.75%   |
| Notebook NV4XMB        | 1         | 0.75%   |
| Notebook N2x0WU        | 1         | 0.75%   |
| MSI Modern             | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 12        | 8.96%   |
| 2020    | 12        | 8.96%   |
| 2019    | 11        | 8.21%   |
| 2012    | 11        | 8.21%   |
| 2018    | 10        | 7.46%   |
| 2017    | 10        | 7.46%   |
| 2016    | 10        | 7.46%   |
| 2015    | 9         | 6.72%   |
| 2013    | 9         | 6.72%   |
| 2011    | 9         | 6.72%   |
| 2014    | 7         | 5.22%   |
| 2010    | 7         | 5.22%   |
| 2021    | 6         | 4.48%   |
| 2009    | 4         | 2.99%   |
| 2023    | 2         | 1.49%   |
| 2008    | 2         | 1.49%   |
| 2007    | 2         | 1.49%   |
| Unknown | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 134       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 97.01%  |
| Yes  | 4         | 2.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 51        | 38.06%  |
| 4.01-8.0    | 40        | 29.85%  |
| 16.01-24.0  | 24        | 17.91%  |
| 2.01-3.0    | 7         | 5.22%   |
| 32.01-64.0  | 6         | 4.48%   |
| 3.01-4.0    | 3         | 2.24%   |
| 64.01-256.0 | 2         | 1.49%   |
| 24.01-32.0  | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 85        | 63.43%  |
| 0.51-1.0 | 33        | 24.63%  |
| 1.01-2.0 | 13        | 9.7%    |
| 2.01-3.0 | 3         | 2.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 97        | 71.85%  |
| 2      | 26        | 19.26%  |
| 0      | 9         | 6.67%   |
| 3      | 3         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 98        | 73.13%  |
| Yes       | 36        | 26.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 78.36%  |
| No        | 29        | 21.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 98.51%  |
| No        | 2         | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 74.63%  |
| No        | 34        | 25.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 22        | 16.42%  |
| Germany                | 11        | 8.21%   |
| Russia                 | 10        | 7.46%   |
| China                  | 8         | 5.97%   |
| Brazil                 | 8         | 5.97%   |
| Spain                  | 6         | 4.48%   |
| Indonesia              | 6         | 4.48%   |
| Netherlands            | 4         | 2.99%   |
| Italy                  | 4         | 2.99%   |
| Hungary                | 4         | 2.99%   |
| France                 | 4         | 2.99%   |
| Ukraine                | 3         | 2.24%   |
| Sweden                 | 3         | 2.24%   |
| Ireland                | 3         | 2.24%   |
| Canada                 | 3         | 2.24%   |
| UK                     | 2         | 1.49%   |
| Romania                | 2         | 1.49%   |
| Portugal               | 2         | 1.49%   |
| Poland                 | 2         | 1.49%   |
| Norway                 | 2         | 1.49%   |
| Mexico                 | 2         | 1.49%   |
| Czechia                | 2         | 1.49%   |
| Belgium                | 2         | 1.49%   |
| Argentina              | 2         | 1.49%   |
| Venezuela              | 1         | 0.75%   |
| Uruguay                | 1         | 0.75%   |
| UAE                    | 1         | 0.75%   |
| Taiwan                 | 1         | 0.75%   |
| Slovenia               | 1         | 0.75%   |
| Slovakia               | 1         | 0.75%   |
| Peru                   | 1         | 0.75%   |
| Panama                 | 1         | 0.75%   |
| Malaysia               | 1         | 0.75%   |
| Kenya                  | 1         | 0.75%   |
| India                  | 1         | 0.75%   |
| Greece                 | 1         | 0.75%   |
| Georgia                | 1         | 0.75%   |
| Costa Rica             | 1         | 0.75%   |
| Bosnia and Herzegovina | 1         | 0.75%   |
| Belarus                | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Moscow                | 4         | 2.99%   |
| Jakarta               | 3         | 2.24%   |
| Hangzhou              | 3         | 2.24%   |
| Valencia              | 2         | 1.49%   |
| Perm                  | 2         | 1.49%   |
| New York              | 2         | 1.49%   |
| Munich                | 2         | 1.49%   |
| Dublin                | 2         | 1.49%   |
| Dover                 | 2         | 1.49%   |
| Bogor                 | 2         | 1.49%   |
| Blomberg              | 2         | 1.49%   |
| Berlin                | 2         | 1.49%   |
| Zwolle                | 1         | 0.75%   |
| Yuzhong Chengguanzhen | 1         | 0.75%   |
| Yunlin                | 1         | 0.75%   |
| Wroclaw               | 1         | 0.75%   |
| Weifang               | 1         | 0.75%   |
| Warendorf             | 1         | 0.75%   |
| Vladivostok           | 1         | 0.75%   |
| Villemomble           | 1         | 0.75%   |
| Vila Nova de Gaia     | 1         | 0.75%   |
| Vigonza               | 1         | 0.75%   |
| Vidnoye               | 1         | 0.75%   |
| Vancouver             | 1         | 0.75%   |
| Utrecht               | 1         | 0.75%   |
| Ufa                   | 1         | 0.75%   |
| Thessaloniki          | 1         | 0.75%   |
| Terrassa              | 1         | 0.75%   |
| Szentistvan           | 1         | 0.75%   |
| Szeged                | 1         | 0.75%   |
| Shenzhen              | 1         | 0.75%   |
| Sevlandsvik           | 1         | 0.75%   |
| Seville               | 1         | 0.75%   |
| Semarang              | 1         | 0.75%   |
| Schoten               | 1         | 0.75%   |
| Sayago                | 1         | 0.75%   |
| Saskatoon             | 1         | 0.75%   |
| Sarajevo              | 1         | 0.75%   |
| Sao Paulo             | 1         | 0.75%   |
| San José             | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 12.26%  |
| Seagate             | 18        | 18     | 11.61%  |
| Kingston            | 16        | 17     | 10.32%  |
| WDC                 | 15        | 15     | 9.68%   |
| Toshiba             | 15        | 15     | 9.68%   |
| Intel               | 8         | 9      | 5.16%   |
| Hitachi             | 7         | 7      | 4.52%   |
| Crucial             | 7         | 7      | 4.52%   |
| SanDisk             | 5         | 5      | 3.23%   |
| SK hynix            | 4         | 4      | 2.58%   |
| A-DATA Technology   | 4         | 4      | 2.58%   |
| HGST                | 3         | 4      | 1.94%   |
| FORESEE             | 3         | 3      | 1.94%   |
| Transcend           | 2         | 2      | 1.29%   |
| SSSTC               | 2         | 2      | 1.29%   |
| PNY                 | 2         | 2      | 1.29%   |
| Patriot             | 2         | 2      | 1.29%   |
| OCZ                 | 2         | 2      | 1.29%   |
| Micron Technology   | 2         | 2      | 1.29%   |
| KIOXIA              | 2         | 2      | 1.29%   |
| GOODRAM             | 2         | 2      | 1.29%   |
| Fujitsu             | 2         | 2      | 1.29%   |
| Apple               | 2         | 2      | 1.29%   |
| XrayDisk            | 1         | 1      | 0.65%   |
| Verbatim            | 1         | 2      | 0.65%   |
| Team                | 1         | 1      | 0.65%   |
| Star Drive          | 1         | 1      | 0.65%   |
| Silicon Motion      | 1         | 1      | 0.65%   |
| OWC                 | 1         | 1      | 0.65%   |
| MyDigitalSSD        | 1         | 1      | 0.65%   |
| Lenovo              | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| Gigabyte Technology | 1         | 1      | 0.65%   |
| Dogfish             | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.52%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.89%   |
| Kingston SA400S37120G 120GB          | 3         | 1.89%   |
| WDC WD10SPZX-35Z10T0 1TB             | 2         | 1.26%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.26%   |
| Samsung SSD 980 1TB                  | 2         | 1.26%   |
| Samsung SSD 970 EVO Plus 250GB       | 2         | 1.26%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.26%   |
| Samsung MZNTY128HDHP-00000 128GB     | 2         | 1.26%   |
| PNY CS900 240GB SSD                  | 2         | 1.26%   |
| Patriot Burst 120GB                  | 2         | 1.26%   |
| OCZ AGILITY3 120GB                   | 2         | 1.26%   |
| Kingston SNV2S500G 500GB             | 2         | 1.26%   |
| Kingston SA400S37240G 240GB          | 2         | 1.26%   |
| HGST HTS545050A7E380 500GB           | 2         | 1.26%   |
| FORESEE P900F256GB                   | 2         | 1.26%   |
| Apple SSD TS128E 121GB               | 2         | 1.26%   |
| A-DATA SX6000LNP 512GB               | 2         | 1.26%   |
| XrayDisk SSD 240GB                   | 1         | 0.63%   |
| WDC WDS500G2B0A 500GB                | 1         | 0.63%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1         | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.63%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.63%   |
| WDC WDBNCE5000PNC 500GB              | 1         | 0.63%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.63%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 0.63%   |
| WDC WD5000BPVT-22A1YT0 500GB         | 1         | 0.63%   |
| WDC WD2500BEVT-35A23T0 250GB         | 1         | 0.63%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.63%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.63%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB | 1         | 0.63%   |
| Verbatim Vi550 S3 SSD 128GB          | 1         | 0.63%   |
| Transcend TS128GMTS400S 128GB        | 1         | 0.63%   |
| Transcend TS120GMTS420S 120GB        | 1         | 0.63%   |
| Toshiba THNSNK128GVN8 128GB          | 1         | 0.63%   |
| Toshiba THNSNJ256GMCY 256GB          | 1         | 0.63%   |
| Toshiba THNSNF128GMCS 128GB          | 1         | 0.63%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 37.5%   |
| WDC                 | 9         | 9      | 18.75%  |
| Toshiba             | 9         | 9      | 18.75%  |
| Hitachi             | 7         | 7      | 14.58%  |
| HGST                | 3         | 4      | 6.25%   |
| Samsung Electronics | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 12     | 16.22%  |
| Samsung Electronics | 11        | 11     | 14.86%  |
| Intel               | 6         | 7      | 8.11%   |
| WDC                 | 5         | 5      | 6.76%   |
| SanDisk             | 5         | 5      | 6.76%   |
| Crucial             | 5         | 5      | 6.76%   |
| Toshiba             | 4         | 4      | 5.41%   |
| Transcend           | 2         | 2      | 2.7%    |
| PNY                 | 2         | 2      | 2.7%    |
| Patriot             | 2         | 2      | 2.7%    |
| OCZ                 | 2         | 2      | 2.7%    |
| GOODRAM             | 2         | 2      | 2.7%    |
| Apple               | 2         | 2      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| XrayDisk            | 1         | 1      | 1.35%   |
| Verbatim            | 1         | 2      | 1.35%   |
| Team                | 1         | 1      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| Silicon Motion      | 1         | 1      | 1.35%   |
| OWC                 | 1         | 1      | 1.35%   |
| MyDigitalSSD        | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 1      | 1.35%   |
| KingSpec            | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| FORESEE             | 1         | 1      | 1.35%   |
| Dogfish             | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 65        | 76     | 45.77%  |
| HDD  | 44        | 49     | 30.99%  |
| NVMe | 33        | 38     | 23.24%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 125    | 75.37%  |
| NVMe | 33        | 38     | 24.63%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 104    | 80.95%  |
| 0.51-1.0   | 19        | 20     | 18.1%   |
| 1.01-2.0   | 1         | 1      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 70        | 51.85%  |
| 101-250    | 32        | 23.7%   |
| 251-500    | 17        | 12.59%  |
| 501-1000   | 8         | 5.93%   |
| 21-50      | 4         | 2.96%   |
| 51-100     | 3         | 2.22%   |
| Unknown    | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 131       | 97.04%  |
| 21-50   | 1         | 0.74%   |
| 101-250 | 1         | 0.74%   |
| 51-100  | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                       | 2         | 2      | 6.9%    |
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 3.45%   |
| WDC WD2500BEVT-35A23T0 250GB                 | 1         | 1      | 3.45%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 3.45%   |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 3.45%   |
| Toshiba MK3261GSYN 320GB                     | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 3.45%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 3.45%   |
| Seagate ST9160412AS 160GB                    | 1         | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 3.45%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 3.45%   |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 3.45%   |
| Seagate ST320LT012-9WS14C 320GB              | 1         | 1      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.45%   |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 3.45%   |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 3.45%   |
| Samsung Electronics HS08XJC 80GB             | 1         | 1      | 3.45%   |
| Kingston SUV400S37240G 240GB                 | 1         | 1      | 3.45%   |
| Kingston SUV400S37120G 120GB                 | 1         | 1      | 3.45%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 3.45%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 3.45%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 3.45%   |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.45%   |
| HGST HTS545050A7E380 500GB                   | 1         | 1      | 3.45%   |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 27.59%  |
| Toshiba             | 6         | 6      | 20.69%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| WDC                 | 2         | 2      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| SanDisk             | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 33.33%  |
| Toshiba             | 6         | 6      | 25%     |
| Hitachi             | 4         | 4      | 16.67%  |
| WDC                 | 2         | 2      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 24     | 81.48%  |
| SSD  | 5         | 5      | 18.52%  |

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
| Works   | 105       | 134    | 80.15%  |
| Malfunc | 26        | 29     | 19.85%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 101       | 66.89%  |
| Samsung Electronics              | 9         | 5.96%   |
| AMD                              | 8         | 5.3%    |
| Nvidia                           | 5         | 3.31%   |
| Kingston Technology Company      | 5         | 3.31%   |
| SK hynix                         | 3         | 1.99%   |
| SanDisk                          | 3         | 1.99%   |
| Solid State Storage Technology   | 2         | 1.32%   |
| Realtek Semiconductor            | 2         | 1.32%   |
| Phison Electronics               | 2         | 1.32%   |
| Micron/Crucial Technology        | 2         | 1.32%   |
| Marvell Technology Group         | 2         | 1.32%   |
| KIOXIA                           | 2         | 1.32%   |
| Toshiba                          | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Micron Technology                | 1         | 0.66%   |
| Lenovo                           | 1         | 0.66%   |
| JMicron Technology               | 1         | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 10.49%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 9.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 6.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 4.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 4.32%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.47%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 2.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.47%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 1.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.85%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.23%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.23%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 2         | 1.23%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.23%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 2         | 1.23%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.23%   |
| Unknown                                                                        | 2         | 1.23%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 0.62%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.62%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.62%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.62%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.62%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.62%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1         | 0.62%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 104       | 67.97%  |
| NVMe | 33        | 21.57%  |
| IDE  | 9         | 5.88%   |
| RAID | 7         | 4.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 123       | 91.79%  |
| AMD    | 11        | 8.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 3.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 2.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 4         | 2.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 2.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 2.24%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.49%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 2         | 1.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 1.49%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 2         | 1.49%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 2         | 1.49%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.49%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 2         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.49%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 1.49%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.49%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 2         | 1.49%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.49%   |
| Intel 12th Gen Core i7-12700H               | 2         | 1.49%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 2         | 1.49%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.49%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.75%   |
| Intel Unknown                               | 1         | 0.75%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.75%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.75%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.75%   |
| Intel Pentium CPU B970 @ 2.30GHz            | 1         | 0.75%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 0.75%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.75%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 0.75%   |
| Intel CPU Version                           | 1         | 0.75%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 0.75%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.75%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.75%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 32.09%  |
| Intel Core i7           | 23        | 17.16%  |
| Intel Core i3           | 13        | 9.7%    |
| Other                   | 12        | 8.96%   |
| Intel Pentium           | 8         | 5.97%   |
| Intel Core 2 Duo        | 7         | 5.22%   |
| Intel Celeron           | 6         | 4.48%   |
| Intel Atom              | 6         | 4.48%   |
| AMD Ryzen 7             | 4         | 2.99%   |
| Intel Core m3           | 2         | 1.49%   |
| Intel Xeon              | 1         | 0.75%   |
| Intel Pentium Silver    | 1         | 0.75%   |
| Intel Pentium Dual-Core | 1         | 0.75%   |
| AMD V120                | 1         | 0.75%   |
| AMD Ryzen 5             | 1         | 0.75%   |
| AMD Ryzen 3             | 1         | 0.75%   |
| AMD E1                  | 1         | 0.75%   |
| AMD Athlon 64 X2        | 1         | 0.75%   |
| AMD A8                  | 1         | 0.75%   |
| AMD A10                 | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 58.96%  |
| 4       | 32        | 23.88%  |
| Unknown | 6         | 4.48%   |
| 16      | 4         | 2.99%   |
| 8       | 4         | 2.99%   |
| 1       | 4         | 2.99%   |
| 10      | 2         | 1.49%   |
| 6       | 2         | 1.49%   |
| 12      | 1         | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 97.01%  |
| 2      | 4         | 2.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 95        | 70.9%   |
| 1       | 32        | 23.88%  |
| Unknown | 7         | 5.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 17.16%  |
| SandyBridge   | 15        | 11.19%  |
| Skylake       | 14        | 10.45%  |
| Broadwell     | 12        | 8.96%   |
| IvyBridge     | 11        | 8.21%   |
| Haswell       | 9         | 6.72%   |
| Unknown       | 8         | 5.97%   |
| Penryn        | 7         | 5.22%   |
| Westmere      | 6         | 4.48%   |
| TigerLake     | 4         | 2.99%   |
| Silvermont    | 4         | 2.99%   |
| Bonnell       | 4         | 2.99%   |
| Zen 2         | 3         | 2.24%   |
| Goldmont plus | 3         | 2.24%   |
| Piledriver    | 2         | 1.49%   |
| Core          | 2         | 1.49%   |
| Zen           | 1         | 0.75%   |
| Nehalem       | 1         | 0.75%   |
| K8 Hammer     | 1         | 0.75%   |
| K10           | 1         | 0.75%   |
| IceLake       | 1         | 0.75%   |
| Goldmont      | 1         | 0.75%   |
| Bobcat        | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 112       | 65.88%  |
| Nvidia                           | 36        | 21.18%  |
| AMD                              | 21        | 12.35%  |
| Silicon Integrated Systems [SiS] | 1         | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 8.77%   |
| Intel HD Graphics 5500                                                                   | 12        | 7.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 6.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 4.68%   |
| Intel HD Graphics 620                                                                    | 7         | 4.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4.09%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.92%   |
| Intel HD Graphics 530                                                                    | 4         | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.34%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 2.34%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.75%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.75%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.17%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 1.17%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 2         | 1.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.17%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 1.17%   |
| Intel HD Graphics 630                                                                    | 2         | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.17%   |
| AMD Lucienne                                                                             | 2         | 1.17%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.58%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.58%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.58%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.58%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.58%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.58%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.58%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.58%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 73        | 54.48%  |
| Intel + Nvidia | 26        | 19.4%   |
| 1 x AMD        | 11        | 8.21%   |
| 1 x Nvidia     | 9         | 6.72%   |
| Intel + AMD    | 9         | 6.72%   |
| 2 x Intel      | 4         | 2.99%   |
| 1 x SiS        | 1         | 0.75%   |
| AMD + Nvidia   | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 119       | 88.81%  |
| Unknown     | 8         | 5.97%   |
| Proprietary | 7         | 5.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 91.79%  |
| 0.01-0.5   | 8         | 5.97%   |
| 0.51-1.0   | 2         | 1.49%   |
| 1.01-2.0   | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 18        | 21.69%  |
| AU Optronics            | 15        | 18.07%  |
| BOE                     | 11        | 13.25%  |
| Chimei Innolux          | 10        | 12.05%  |
| Apple                   | 7         | 8.43%   |
| Samsung Electronics     | 5         | 6.02%   |
| Sharp                   | 3         | 3.61%   |
| Chi Mei Optoelectronics | 2         | 2.41%   |
| TMX                     | 1         | 1.2%    |
| Nvidia                  | 1         | 1.2%    |
| LG Philips              | 1         | 1.2%    |
| Hewlett-Packard         | 1         | 1.2%    |
| HannStar                | 1         | 1.2%    |
| Fujitsu Siemens         | 1         | 1.2%    |
| Dell                    | 1         | 1.2%    |
| CPT                     | 1         | 1.2%    |
| cPATH                   | 1         | 1.2%    |
| BenQ                    | 1         | 1.2%    |
| AOC                     | 1         | 1.2%    |
| Ancor Communications    | 1         | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 2         | 2.41%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 2.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 2         | 2.41%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 2         | 2.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 2         | 2.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.41%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 2         | 2.41%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 2.41%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 2.41%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.2%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 1.2%    |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch               | 1         | 1.2%    |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch               | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 1         | 1.2%    |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.2%    |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD0546 1920x1080 340x190mm 15.3-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.2%    |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 410x260mm 19.1-inch    | 1         | 1.2%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.2%    |
| Fujitsu Siemens XE17-4 FUS0674 1280x1024 340x270mm 17.1-inch          | 1         | 1.2%    |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.2%    |
| CPT LCD Monitor COR17DB 1600x900 290x160mm 13.0-inch                  | 1         | 1.2%    |
| cPATH LCD Monitor 1366x768                                            | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 340x190mm 15.3-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch      | 1         | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 37.04%  |
| 1366x768 (WXGA)    | 28        | 34.57%  |
| 1280x800 (WXGA)    | 6         | 7.41%   |
| 1600x900 (HD+)     | 5         | 6.17%   |
| 3840x2160 (4K)     | 3         | 3.7%    |
| 1024x600           | 2         | 2.47%   |
| 3840x2400          | 1         | 1.23%   |
| 3200x2000          | 1         | 1.23%   |
| 2560x1440 (QHD)    | 1         | 1.23%   |
| 1920x1200 (WUXGA)  | 1         | 1.23%   |
| 1680x1050 (WSXGA+) | 1         | 1.23%   |
| 1440x900 (WXGA+)   | 1         | 1.23%   |
| 1280x1024 (SXGA)   | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 41        | 49.4%   |
| 13      | 19        | 22.89%  |
| 12      | 9         | 10.84%  |
| 17      | 2         | 2.41%   |
| 11      | 2         | 2.41%   |
| 10      | 2         | 2.41%   |
| 40      | 1         | 1.2%    |
| 26      | 1         | 1.2%    |
| 24      | 1         | 1.2%    |
| 20      | 1         | 1.2%    |
| 19      | 1         | 1.2%    |
| 14      | 1         | 1.2%    |
| 9       | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 65.06%  |
| 201-300     | 22        | 26.51%  |
| 501-600     | 2         | 2.41%   |
| 401-500     | 2         | 2.41%   |
| 801-900     | 1         | 1.2%    |
| 351-400     | 1         | 1.2%    |
| Unknown     | 1         | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 65        | 81.25%  |
| 16/10   | 13        | 16.25%  |
| 5/4     | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 33        | 39.76%  |
| 81-90          | 17        | 20.48%  |
| 61-70          | 7         | 8.43%   |
| 101-110        | 6         | 7.23%   |
| 71-80          | 5         | 6.02%   |
| 41-50          | 3         | 3.61%   |
| 51-60          | 2         | 2.41%   |
| 151-200        | 2         | 2.41%   |
| 111-120        | 2         | 2.41%   |
| 301-350        | 1         | 1.2%    |
| 201-250        | 1         | 1.2%    |
| 141-150        | 1         | 1.2%    |
| 121-130        | 1         | 1.2%    |
| 501-1000       | 1         | 1.2%    |
| Unknown        | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 43.37%  |
| 101-120       | 26        | 31.33%  |
| 161-240       | 8         | 9.64%   |
| 51-100        | 8         | 9.64%   |
| More than 240 | 4         | 4.82%   |
| Unknown       | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 118       | 88.06%  |
| 0     | 10        | 7.46%   |
| 2     | 6         | 4.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 86        | 41.55%  |
| Realtek Semiconductor            | 54        | 26.09%  |
| Qualcomm Atheros                 | 28        | 13.53%  |
| Broadcom                         | 18        | 8.7%    |
| Ralink                           | 3         | 1.45%   |
| Nvidia                           | 3         | 1.45%   |
| Google                           | 3         | 1.45%   |
| Sierra Wireless                  | 2         | 0.97%   |
| Samsung Electronics              | 2         | 0.97%   |
| Marvell Technology Group         | 2         | 0.97%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Ralink Technology                | 1         | 0.48%   |
| NetGear                          | 1         | 0.48%   |
| Huawei Technologies              | 1         | 0.48%   |
| D-Link System                    | 1         | 0.48%   |
| BUFFALO                          | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 12.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 5.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 4.74%   |
| Intel Wireless 7265                                                    | 11        | 4.35%   |
| Intel Wireless 8265 / 8275                                             | 9         | 3.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 2.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 1.98%   |
| Intel Wireless 8260                                                    | 5         | 1.98%   |
| Intel Wireless 7260                                                    | 5         | 1.98%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 1.98%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 1.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 1.58%   |
| Intel Wireless 3165                                                    | 4         | 1.58%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.58%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.19%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 1.19%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.19%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.19%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 3         | 1.19%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 3         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 1.19%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.79%   |
| Intel Wireless 3160                                                    | 2         | 0.79%   |
| Intel WiFi Link 5100                                                   | 2         | 0.79%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.79%   |
| Intel Ethernet Connection (3) I218-V                                   | 2         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 55.86%  |
| Qualcomm Atheros      | 26        | 17.93%  |
| Broadcom              | 15        | 10.34%  |
| Realtek Semiconductor | 14        | 9.66%   |
| Ralink                | 3         | 2.07%   |
| Sierra Wireless       | 2         | 1.38%   |
| Ralink Technology     | 1         | 0.69%   |
| NetGear               | 1         | 0.69%   |
| D-Link System         | 1         | 0.69%   |
| BUFFALO               | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 12        | 8.22%   |
| Intel Wireless 7265                                                                           | 11        | 7.53%   |
| Intel Wireless 8265 / 8275                                                                    | 9         | 6.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 6         | 4.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 5         | 3.42%   |
| Intel Wireless 8260                                                                           | 5         | 3.42%   |
| Intel Wireless 7260                                                                           | 5         | 3.42%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 5         | 3.42%   |
| Intel Wi-Fi 6 AX200                                                                           | 5         | 3.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 5         | 3.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4         | 2.74%   |
| Intel Wireless 3165                                                                           | 4         | 2.74%   |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 3         | 2.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                                               | 3         | 2.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3         | 2.05%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 1.37%   |
| Intel Wireless 3160                                                                           | 2         | 1.37%   |
| Intel WiFi Link 5100                                                                          | 2         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.37%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.68%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.68%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.68%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.68%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.68%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.68%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.68%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)         | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 45        | 42.86%  |
| Intel                            | 37        | 35.24%  |
| Qualcomm Atheros                 | 9         | 8.57%   |
| Broadcom                         | 4         | 3.81%   |
| Nvidia                           | 3         | 2.86%   |
| Samsung Electronics              | 2         | 1.9%    |
| Marvell Technology Group         | 2         | 1.9%    |
| Google                           | 2         | 1.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 31        | 29.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 13        | 12.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 6.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 3.81%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 2.86%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 2.86%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 2.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 1.9%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.9%    |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.9%    |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.9%    |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.9%    |
| Google Nexus/Pixel Device (tether)                                             | 2         | 1.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.9%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.95%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.95%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.95%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.95%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.95%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.95%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.95%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 55.23%  |
| Ethernet | 105       | 43.93%  |
| Modem    | 1         | 0.42%   |
| Unknown  | 1         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 58.14%  |
| Ethernet | 54        | 41.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 100       | 74.63%  |
| 1     | 33        | 24.63%  |
| 0     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 120       | 89.55%  |
| Yes  | 14        | 10.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 61.76%  |
| Broadcom                        | 8         | 7.84%   |
| Apple                           | 7         | 6.86%   |
| Realtek Semiconductor           | 5         | 4.9%    |
| Qualcomm Atheros Communications | 4         | 3.92%   |
| IMC Networks                    | 3         | 2.94%   |
| Lite-On Technology              | 2         | 1.96%   |
| Hewlett-Packard                 | 2         | 1.96%   |
| Foxconn / Hon Hai               | 2         | 1.96%   |
| ASUSTek Computer                | 2         | 1.96%   |
| Alps Electric                   | 2         | 1.96%   |
| Ralink                          | 1         | 0.98%   |
| Cambridge Silicon Radio         | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 32        | 30.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 7.69%   |
| Intel AX201 Bluetooth                                       | 6         | 5.77%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 4.81%   |
| Intel AX210 Bluetooth                                       | 5         | 4.81%   |
| Intel AX200 Bluetooth                                       | 4         | 3.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 4         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 2.88%   |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.92%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.92%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 1.92%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.96%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.96%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.96%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.96%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.96%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.96%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.96%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.96%   |
| Intel AX211 Bluetooth                                       | 1         | 0.96%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.96%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.96%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 0.96%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.96%   |
| Foxconn / Hon Hai BCM43142 Bluetooth Adapter                | 1         | 0.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 0.96%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.96%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.96%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 0.96%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.96%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 0.96%   |
| Apple Broadcom Bluetooth 2.1 module                         | 1         | 0.96%   |
| Apple Bluetooth Host Controller                             | 1         | 0.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 116       | 79.45%  |
| AMD                              | 13        | 8.9%    |
| Nvidia                           | 12        | 8.22%   |
| XMOS                             | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| Kingston Technology              | 1         | 0.68%   |
| GN Netcom                        | 1         | 0.68%   |
| C-Media Electronics              | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 13.07%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 9.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 6.82%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 6.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 5.11%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 3.41%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 2.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.27%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.7%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.7%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.7%    |
| AMD FCH Azalia Controller                                                                         | 3         | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.14%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.14%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.57%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.57%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.57%   |
| Intel USB2.0 Device                                                                               | 1         | 0.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 27.22%  |
| SK hynix            | 31        | 19.62%  |
| Micron Technology   | 16        | 10.13%  |
| Unknown             | 14        | 8.86%   |
| Kingston            | 12        | 7.59%   |
| Smart               | 5         | 3.16%   |
| A-DATA Technology   | 5         | 3.16%   |
| Elpida              | 4         | 2.53%   |
| Crucial             | 4         | 2.53%   |
| Nanya Technology    | 3         | 1.9%    |
| G.Skill             | 3         | 1.9%    |
| Unknown             | 3         | 1.9%    |
| Smart Brazil        | 2         | 1.27%   |
| Ramaxel Technology  | 2         | 1.27%   |
| Transcend           | 1         | 0.63%   |
| Teikon              | 1         | 0.63%   |
| Team                | 1         | 0.63%   |
| SHARETRONIC         | 1         | 0.63%   |
| Sesame              | 1         | 0.63%   |
| PNY                 | 1         | 0.63%   |
| Nayna               | 1         | 0.63%   |
| High Bridge         | 1         | 0.63%   |
| GSkill              | 1         | 0.63%   |
| GeIL                | 1         | 0.63%   |
| Essencore           | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s              | 7         | 4.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s             | 4         | 2.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s              | 4         | 2.37%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s             | 4         | 2.37%   |
| Unknown RAM Module 2GB SODIMM DDR3                                 | 3         | 1.78%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                       | 3         | 1.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 3         | 1.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 3         | 1.78%   |
| Unknown                                                            | 3         | 1.78%   |
| Unknown RAM Module 4GB SODIMM DDR3                                 | 2         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                        | 2         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                         | 2         | 1.18%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                         | 2         | 1.18%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s              | 2         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 2         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s             | 2         | 1.18%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 2         | 1.18%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                        | 2         | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s              | 2         | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s              | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s              | 2         | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s             | 2         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s              | 2         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s              | 2         | 1.18%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                        | 1         | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                          | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                        | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                         | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2                                 | 1         | 0.59%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s                         | 1         | 0.59%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s               | 1         | 0.59%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s             | 1         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s               | 1         | 0.59%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s              | 1         | 0.59%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s              | 1         | 0.59%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s              | 1         | 0.59%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s              | 1         | 0.59%   |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s       | 1         | 0.59%   |
| Smart Brazil RAM SDQC8G8W16XCWE9N1T 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 65        | 49.24%  |
| DDR4    | 51        | 38.64%  |
| DDR2    | 9         | 6.82%   |
| SDRAM   | 2         | 1.52%   |
| LPDDR3  | 2         | 1.52%   |
| DRAM    | 1         | 0.76%   |
| DDR5    | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 120       | 88.24%  |
| Row Of Chips | 7         | 5.15%   |
| DIMM         | 3         | 2.21%   |
| Chip         | 3         | 2.21%   |
| Unknown      | 3         | 2.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 57        | 38.78%  |
| 8192  | 35        | 23.81%  |
| 2048  | 31        | 21.09%  |
| 16384 | 18        | 12.24%  |
| 1024  | 5         | 3.4%    |
| 32768 | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 42        | 28.77%  |
| 2667    | 19        | 13.01%  |
| 1333    | 16        | 10.96%  |
| 2400    | 15        | 10.27%  |
| 3200    | 13        | 8.9%    |
| 2133    | 11        | 7.53%   |
| 1334    | 6         | 4.11%   |
| 667     | 5         | 3.42%   |
| Unknown | 5         | 3.42%   |
| 1867    | 3         | 2.05%   |
| 1067    | 3         | 2.05%   |
| 800     | 3         | 2.05%   |
| 2048    | 2         | 1.37%   |
| 4800    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| 333     | 1         | 0.68%   |

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
| Chicony Electronics                    | 30        | 29.13%  |
| Bison Electronics                      | 12        | 11.65%  |
| Microdia                               | 11        | 10.68%  |
| IMC Networks                           | 10        | 9.71%   |
| Sunplus Innovation Technology          | 9         | 8.74%   |
| Realtek Semiconductor                  | 9         | 8.74%   |
| Suyin                                  | 4         | 3.88%   |
| Luxvisions Innotech Limited            | 3         | 2.91%   |
| Apple                                  | 3         | 2.91%   |
| Syntek                                 | 2         | 1.94%   |
| Silicon Motion                         | 2         | 1.94%   |
| Alcor Micro                            | 2         | 1.94%   |
| Z-Star Microelectronics                | 1         | 0.97%   |
| Unknown                                | 1         | 0.97%   |
| Lite-On Technology                     | 1         | 0.97%   |
| Lenovo                                 | 1         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.97%   |
| ALi                                    | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 6         | 5.83%   |
| Chicony Integrated Camera                                   | 5         | 4.85%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 3.88%   |
| Chicony HD WebCam                                           | 4         | 3.88%   |
| Microdia Integrated_Webcam_HD                               | 3         | 2.91%   |
| IMC Networks Integrated Camera                              | 3         | 2.91%   |
| Suyin Integrated_Webcam_HD                                  | 2         | 1.94%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 1.94%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.94%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 1.94%   |
| IMC Networks USB 2.0 UVC VGA WebCam                         | 2         | 1.94%   |
| IMC Networks Realtek DMFT RGB                               | 2         | 1.94%   |
| Chicony XiaoMi USB 2.0 Webcam                               | 2         | 1.94%   |
| Chicony Realtek DMFT RGB                                    | 2         | 1.94%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.94%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.94%   |
| Bison HD Webcam                                             | 2         | 1.94%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 1.94%   |
| Z-Star DataMax USB 2.0 Camera                               | 1         | 0.97%   |
| Unknown Realtek PC Camera                                   | 1         | 0.97%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 0.97%   |
| Syntek Integrated Camera                                    | 1         | 0.97%   |
| Suyin WebCam                                                | 1         | 0.97%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.97%   |
| Sunplus XiaoMi USB 2.0 Webcam                               | 1         | 0.97%   |
| Sunplus Integrated Camera                                   | 1         | 0.97%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.97%   |
| Sunplus HD WebCam                                           | 1         | 0.97%   |
| Sunplus Asus Webcam                                         | 1         | 0.97%   |
| Silicon Motion Realtek DMFT RGB                             | 1         | 0.97%   |
| Silicon Motion HP Webcam-50                                 | 1         | 0.97%   |
| Realtek PC Camera                                           | 1         | 0.97%   |
| Realtek Integrated_Webcam_HD                                | 1         | 0.97%   |
| Realtek Integrated Webcam HD                                | 1         | 0.97%   |
| Realtek HP HD Webcam [Fixed]                                | 1         | 0.97%   |
| Realtek HD WebCam                                           | 1         | 0.97%   |
| Realtek EasyCamera                                          | 1         | 0.97%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 0.97%   |
| Microdia Webcam                                             | 1         | 0.97%   |
| Microdia USB 2.0 Camera                                     | 1         | 0.97%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 46.15%  |
| Synaptics                  | 7         | 26.92%  |
| Elan Microelectronics      | 2         | 7.69%   |
| AuthenTec                  | 2         | 7.69%   |
| STMicroelectronics         | 1         | 3.85%   |
| Shenzhen Goodix Technology | 1         | 3.85%   |
| Broadcom                   | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 4         | 15.38%  |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 7.69%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 7.69%   |
| Elan Fingerprint Sensor                                                      | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 3.85%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 3.85%   |
| Synaptics UWP WBDI Device                                                    | 1         | 3.85%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.85%   |
| AuthenTec AES1660                                                            | 1         | 3.85%   |
| AuthenTec AES1600                                                            | 1         | 3.85%   |

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
| 2     | 44        | 32.84%  |
| 1     | 43        | 32.09%  |
| 3     | 21        | 15.67%  |
| 0     | 18        | 13.43%  |
| 4     | 6         | 4.48%   |
| 5     | 2         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 102       | 47.22%  |
| Bluetooth                | 34        | 15.74%  |
| Card reader              | 27        | 12.5%   |
| Fingerprint reader       | 25        | 11.57%  |
| Net/wireless             | 18        | 8.33%   |
| Sound                    | 7         | 3.24%   |
| Network                  | 2         | 0.93%   |
| Storage                  | 1         | 0.46%   |

