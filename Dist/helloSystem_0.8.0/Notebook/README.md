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

Total: 153

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 122       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 116       | 95.08%  |
| GNOME        | 3         | 2.46%   |
| Window Maker | 1         | 0.82%   |
| IceWM        | 1         | 0.82%   |
| Cinnamon     | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 122       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 121       | 99.18%  |
| GDM  | 1         | 0.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 50        | 40.65%  |
| en    | 41        | 33.33%  |
| ru    | 6         | 4.88%   |
| de    | 6         | 4.88%   |
| pt    | 5         | 4.07%   |
| es_ES | 3         | 2.44%   |
| es    | 3         | 2.44%   |
| it    | 2         | 1.63%   |
| fr    | 2         | 1.63%   |
| zh_CN | 1         | 0.81%   |
| sv    | 1         | 0.81%   |
| ru_RU | 1         | 0.81%   |
| pl    | 1         | 0.81%   |
| nl    | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 122       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 76        | 61.29%  |
| Zfs    | 47        | 37.9%   |
| Ufs    | 1         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 122       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 21.31%  |
| Hewlett-Packard     | 19        | 15.57%  |
| Dell                | 18        | 14.75%  |
| ASUSTek Computer    | 9         | 7.38%   |
| Acer                | 7         | 5.74%   |
| Apple               | 6         | 4.92%   |
| Toshiba             | 4         | 3.28%   |
| MSI                 | 4         | 3.28%   |
| Timi                | 3         | 2.46%   |
| Sony                | 3         | 2.46%   |
| Google              | 3         | 2.46%   |
| TUXEDO              | 2         | 1.64%   |
| Samsung Electronics | 2         | 1.64%   |
| Packard Bell        | 2         | 1.64%   |
| Notebook            | 2         | 1.64%   |
| Star Labs           | 1         | 0.82%   |
| SLIMBOOK            | 1         | 0.82%   |
| PCSTICK             | 1         | 0.82%   |
| Panasonic           | 1         | 0.82%   |
| MECHREVO S1 Series  | 1         | 0.82%   |
| Kraftway            | 1         | 0.82%   |
| HUAWEI              | 1         | 0.82%   |
| Gigabyte Technology | 1         | 0.82%   |
| Gateway             | 1         | 0.82%   |
| Fujitsu Siemens     | 1         | 0.82%   |
| Fujitsu             | 1         | 0.82%   |
| Unknown             | 1         | 0.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 3         | 2.46%   |
| MSI PS63 Modern 8M                           | 2         | 1.64%   |
| HP Notebook                                  | 2         | 1.64%   |
| HP 250 G6 Notebook PC                        | 2         | 1.64%   |
| Apple MacBookAir5,1                          | 2         | 1.64%   |
| Apple MacBook5,2                             | 2         | 1.64%   |
| TUXEDO Pulse 14 Gen1                         | 1         | 0.82%   |
| TUXEDO Aura 15 Gen1                          | 1         | 0.82%   |
| Toshiba TECRA Z40-C-12Z                      | 1         | 0.82%   |
| Toshiba Satellite S55t-B                     | 1         | 0.82%   |
| Toshiba PORTEGE Z930                         | 1         | 0.82%   |
| Toshiba dynabook R63/P                       | 1         | 0.82%   |
| Timi TM1701                                  | 1         | 0.82%   |
| Timi TM1607                                  | 1         | 0.82%   |
| Timi RedmiBook Pro 15                        | 1         | 0.82%   |
| Star Labs StarBook                           | 1         | 0.82%   |
| Sony VPCEB1J1E                               | 1         | 0.82%   |
| Sony VGN-AW21S_B                             | 1         | 0.82%   |
| Sony SVF1421E4E                              | 1         | 0.82%   |
| SLIMBOOK PROX-AMD5                           | 1         | 0.82%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.82%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK          | 1         | 0.82%   |
| Panasonic CF-C1BWFAZ1M                       | 1         | 0.82%   |
| Packard Bell EasyNote_MX52-B-071             | 1         | 0.82%   |
| Packard Bell DOT S                           | 1         | 0.82%   |
| Notebook NV4XMB,ME,MZ                        | 1         | 0.82%   |
| Notebook N2x0WU                              | 1         | 0.82%   |
| MSI Modern 15 A5M                            | 1         | 0.82%   |
| MSI GF76 12UE                                | 1         | 0.82%   |
| MECHREVO S1 Series S1 Series                 | 1         | 0.82%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00        | 1         | 0.82%   |
| Lenovo ThinkPad X250 20CLS23500              | 1         | 0.82%   |
| Lenovo ThinkPad X250 20CLS1WP01              | 1         | 0.82%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 0.82%   |
| Lenovo ThinkPad X1 Carbon 3448AWU            | 1         | 0.82%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7002FUS     | 1         | 0.82%   |
| Lenovo ThinkPad W541 20EF000NUS              | 1         | 0.82%   |
| Lenovo ThinkPad T61p 6457UN2                 | 1         | 0.82%   |
| Lenovo ThinkPad T440 20B7A0B7MS              | 1         | 0.82%   |
| Lenovo ThinkPad T420 4178A72                 | 1         | 0.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 13.93%  |
| Dell Latitude          | 10        | 8.2%    |
| Acer Aspire            | 7         | 5.74%   |
| Dell Inspiron          | 6         | 4.92%   |
| HP EliteBook           | 5         | 4.1%    |
| Lenovo IdeaPad         | 4         | 3.28%   |
| Unknown                | 3         | 2.46%   |
| MSI PS63               | 2         | 1.64%   |
| HP OMEN                | 2         | 1.64%   |
| HP Notebook            | 2         | 1.64%   |
| HP Laptop              | 2         | 1.64%   |
| HP 250                 | 2         | 1.64%   |
| ASUS VivoBook          | 2         | 1.64%   |
| Apple MacBookAir5      | 2         | 1.64%   |
| Apple MacBook5         | 2         | 1.64%   |
| TUXEDO Pulse           | 1         | 0.82%   |
| TUXEDO Aura            | 1         | 0.82%   |
| Toshiba TECRA          | 1         | 0.82%   |
| Toshiba Satellite      | 1         | 0.82%   |
| Toshiba PORTEGE        | 1         | 0.82%   |
| Toshiba dynabook       | 1         | 0.82%   |
| Timi TM1701            | 1         | 0.82%   |
| Timi TM1607            | 1         | 0.82%   |
| Timi RedmiBook         | 1         | 0.82%   |
| Star Labs StarBook     | 1         | 0.82%   |
| Sony VPCEB1J1E         | 1         | 0.82%   |
| Sony VGN-AW21S         | 1         | 0.82%   |
| Sony SVF1421E4E        | 1         | 0.82%   |
| SLIMBOOK PROX-AMD5     | 1         | 0.82%   |
| Samsung 340XAA         | 1         | 0.82%   |
| Samsung 270E5K         | 1         | 0.82%   |
| Panasonic CF-C1BWFAZ1M | 1         | 0.82%   |
| Packard Bell EasyNote  | 1         | 0.82%   |
| Packard Bell DOT       | 1         | 0.82%   |
| Notebook NV4XMB        | 1         | 0.82%   |
| Notebook N2x0WU        | 1         | 0.82%   |
| MSI Modern             | 1         | 0.82%   |
| MSI GF76               | 1         | 0.82%   |
| MECHREVO S1 Series S1  | 1         | 0.82%   |
| Lenovo Legion          | 1         | 0.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 13        | 10.66%  |
| 2022    | 12        | 9.84%   |
| 2019    | 11        | 9.02%   |
| 2018    | 10        | 8.2%    |
| 2013    | 9         | 7.38%   |
| 2017    | 8         | 6.56%   |
| 2015    | 8         | 6.56%   |
| 2012    | 8         | 6.56%   |
| 2011    | 8         | 6.56%   |
| 2016    | 7         | 5.74%   |
| 2014    | 7         | 5.74%   |
| 2021    | 6         | 4.92%   |
| 2010    | 5         | 4.1%    |
| 2009    | 4         | 3.28%   |
| 2023    | 2         | 1.64%   |
| 2007    | 2         | 1.64%   |
| 2008    | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 122       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 118       | 96.72%  |
| Yes  | 4         | 3.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 47        | 38.52%  |
| 4.01-8.0    | 37        | 30.33%  |
| 16.01-24.0  | 22        | 18.03%  |
| 32.01-64.0  | 6         | 4.92%   |
| 2.01-3.0    | 5         | 4.1%    |
| 3.01-4.0    | 2         | 1.64%   |
| 64.01-256.0 | 2         | 1.64%   |
| 24.01-32.0  | 1         | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 77        | 63.11%  |
| 0.51-1.0 | 29        | 23.77%  |
| 1.01-2.0 | 13        | 10.66%  |
| 2.01-3.0 | 3         | 2.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 87        | 70.73%  |
| 2      | 24        | 19.51%  |
| 0      | 9         | 7.32%   |
| 3      | 3         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 73.77%  |
| Yes       | 32        | 26.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 79.51%  |
| No        | 25        | 20.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 98.36%  |
| No        | 2         | 1.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 73.77%  |
| No        | 32        | 26.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 19        | 15.57%  |
| Germany                | 11        | 9.02%   |
| Russia                 | 10        | 8.2%    |
| Brazil                 | 8         | 6.56%   |
| China                  | 6         | 4.92%   |
| Spain                  | 5         | 4.1%    |
| Netherlands            | 4         | 3.28%   |
| Italy                  | 4         | 3.28%   |
| Indonesia              | 4         | 3.28%   |
| Hungary                | 4         | 3.28%   |
| France                 | 4         | 3.28%   |
| Ukraine                | 3         | 2.46%   |
| Sweden                 | 3         | 2.46%   |
| Ireland                | 3         | 2.46%   |
| Canada                 | 3         | 2.46%   |
| UK                     | 2         | 1.64%   |
| Romania                | 2         | 1.64%   |
| Poland                 | 2         | 1.64%   |
| Mexico                 | 2         | 1.64%   |
| Czechia                | 2         | 1.64%   |
| Argentina              | 2         | 1.64%   |
| Venezuela              | 1         | 0.82%   |
| Uruguay                | 1         | 0.82%   |
| UAE                    | 1         | 0.82%   |
| Taiwan                 | 1         | 0.82%   |
| Slovenia               | 1         | 0.82%   |
| Slovakia               | 1         | 0.82%   |
| Portugal               | 1         | 0.82%   |
| Peru                   | 1         | 0.82%   |
| Panama                 | 1         | 0.82%   |
| Norway                 | 1         | 0.82%   |
| Malaysia               | 1         | 0.82%   |
| Kenya                  | 1         | 0.82%   |
| India                  | 1         | 0.82%   |
| Georgia                | 1         | 0.82%   |
| Costa Rica             | 1         | 0.82%   |
| Bosnia and Herzegovina | 1         | 0.82%   |
| Belgium                | 1         | 0.82%   |
| Belarus                | 1         | 0.82%   |
| Albania                | 1         | 0.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 4         | 3.28%   |
| Valencia             | 2         | 1.64%   |
| Perm                 | 2         | 1.64%   |
| Munich               | 2         | 1.64%   |
| Jakarta              | 2         | 1.64%   |
| Hangzhou             | 2         | 1.64%   |
| Dublin               | 2         | 1.64%   |
| Dover                | 2         | 1.64%   |
| Blomberg             | 2         | 1.64%   |
| Berlin               | 2         | 1.64%   |
| Zwolle               | 1         | 0.82%   |
| Yunlin               | 1         | 0.82%   |
| Wroclaw              | 1         | 0.82%   |
| Weifang              | 1         | 0.82%   |
| Warendorf            | 1         | 0.82%   |
| Vladivostok          | 1         | 0.82%   |
| Villemomble          | 1         | 0.82%   |
| Vigonza              | 1         | 0.82%   |
| Vidnoye              | 1         | 0.82%   |
| Vancouver            | 1         | 0.82%   |
| Utrecht              | 1         | 0.82%   |
| Ufa                  | 1         | 0.82%   |
| Szentistvan          | 1         | 0.82%   |
| Szeged               | 1         | 0.82%   |
| Shenzhen             | 1         | 0.82%   |
| Seville              | 1         | 0.82%   |
| Semarang             | 1         | 0.82%   |
| Sayago               | 1         | 0.82%   |
| Saskatoon            | 1         | 0.82%   |
| Sarajevo             | 1         | 0.82%   |
| Sao Paulo            | 1         | 0.82%   |
| San José            | 1         | 0.82%   |
| San Carlos del Zulia | 1         | 0.82%   |
| Roscommon            | 1         | 0.82%   |
| Rockville            | 1         | 0.82%   |
| Rio das Ostras       | 1         | 0.82%   |
| Rho                  | 1         | 0.82%   |
| Redondela            | 1         | 0.82%   |
| Rathmore             | 1         | 0.82%   |
| Queensbury           | 1         | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 12.77%  |
| Samsung Electronics | 18        | 22     | 12.77%  |
| Kingston            | 15        | 16     | 10.64%  |
| WDC                 | 14        | 14     | 9.93%   |
| Toshiba             | 13        | 13     | 9.22%   |
| Intel               | 7         | 8      | 4.96%   |
| Hitachi             | 6         | 6      | 4.26%   |
| Crucial             | 6         | 6      | 4.26%   |
| SK hynix            | 4         | 4      | 2.84%   |
| SanDisk             | 4         | 4      | 2.84%   |
| A-DATA Technology   | 4         | 4      | 2.84%   |
| Transcend           | 2         | 2      | 1.42%   |
| SSSTC               | 2         | 2      | 1.42%   |
| PNY                 | 2         | 2      | 1.42%   |
| Patriot             | 2         | 2      | 1.42%   |
| OCZ                 | 2         | 2      | 1.42%   |
| KIOXIA              | 2         | 2      | 1.42%   |
| HGST                | 2         | 2      | 1.42%   |
| GOODRAM             | 2         | 2      | 1.42%   |
| Fujitsu             | 2         | 2      | 1.42%   |
| FORESEE             | 2         | 2      | 1.42%   |
| Apple               | 2         | 2      | 1.42%   |
| Verbatim            | 1         | 2      | 0.71%   |
| Star Drive          | 1         | 1      | 0.71%   |
| Silicon Motion      | 1         | 1      | 0.71%   |
| OWC                 | 1         | 1      | 0.71%   |
| MyDigitalSSD        | 1         | 1      | 0.71%   |
| Micron Technology   | 1         | 1      | 0.71%   |
| Lenovo              | 1         | 1      | 0.71%   |
| KingSpec            | 1         | 1      | 0.71%   |
| Gigabyte Technology | 1         | 1      | 0.71%   |
| Dogfish             | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.76%   |
| Toshiba MQ01ABF050 500GB             | 3         | 2.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 2.07%   |
| Kingston SA400S37120G 120GB          | 3         | 2.07%   |
| WDC WD10SPZX-35Z10T0 1TB             | 2         | 1.38%   |
| Samsung SSD 980 1TB                  | 2         | 1.38%   |
| Samsung SSD 970 EVO Plus 250GB       | 2         | 1.38%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.38%   |
| Samsung MZNTY128HDHP-00000 128GB     | 2         | 1.38%   |
| PNY CS900 240GB SSD                  | 2         | 1.38%   |
| Patriot Burst 120GB                  | 2         | 1.38%   |
| OCZ AGILITY3 120GB                   | 2         | 1.38%   |
| Kingston SNV2S500G 500GB             | 2         | 1.38%   |
| Kingston SA400S37240G 240GB          | 2         | 1.38%   |
| Apple SSD TS128E 121GB               | 2         | 1.38%   |
| A-DATA SX6000LNP 512GB               | 2         | 1.38%   |
| WDC WDS500G2B0A 500GB                | 1         | 0.69%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1         | 0.69%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.69%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.69%   |
| WDC WDBNCE5000PNC 500GB              | 1         | 0.69%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.69%   |
| WDC WD5000BPVT-22A1YT0 500GB         | 1         | 0.69%   |
| WDC WD2500BEVT-35A23T0 250GB         | 1         | 0.69%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.69%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.69%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB | 1         | 0.69%   |
| Verbatim Vi550 S3 SSD 512GB          | 1         | 0.69%   |
| Transcend TS128GMTS400S 128GB        | 1         | 0.69%   |
| Transcend TS120GMTS420S 120GB        | 1         | 0.69%   |
| Toshiba THNSNJ256GMCY 256GB          | 1         | 0.69%   |
| Toshiba THNSNF128GMCS 128GB          | 1         | 0.69%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.69%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.69%   |
| Toshiba MK8034GSX 80GB               | 1         | 0.69%   |
| Toshiba MK5065GSXF 500GB             | 1         | 0.69%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.69%   |
| Toshiba KXG60ZNV256G NVMe 256GB      | 1         | 0.69%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 18     | 41.86%  |
| WDC     | 8         | 8      | 18.6%   |
| Toshiba | 8         | 8      | 18.6%   |
| Hitachi | 6         | 6      | 13.95%  |
| HGST    | 2         | 2      | 4.65%   |
| Fujitsu | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 11     | 16.42%  |
| Kingston            | 11        | 11     | 16.42%  |
| Intel               | 6         | 7      | 8.96%   |
| WDC                 | 5         | 5      | 7.46%   |
| SanDisk             | 4         | 4      | 5.97%   |
| Crucial             | 4         | 4      | 5.97%   |
| Toshiba             | 3         | 3      | 4.48%   |
| Transcend           | 2         | 2      | 2.99%   |
| PNY                 | 2         | 2      | 2.99%   |
| Patriot             | 2         | 2      | 2.99%   |
| OCZ                 | 2         | 2      | 2.99%   |
| GOODRAM             | 2         | 2      | 2.99%   |
| Apple               | 2         | 2      | 2.99%   |
| A-DATA Technology   | 2         | 2      | 2.99%   |
| Verbatim            | 1         | 2      | 1.49%   |
| SK hynix            | 1         | 1      | 1.49%   |
| Silicon Motion      | 1         | 1      | 1.49%   |
| OWC                 | 1         | 1      | 1.49%   |
| MyDigitalSSD        | 1         | 1      | 1.49%   |
| KingSpec            | 1         | 1      | 1.49%   |
| Fujitsu             | 1         | 1      | 1.49%   |
| FORESEE             | 1         | 1      | 1.49%   |
| Dogfish             | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 58        | 69     | 45.31%  |
| HDD  | 39        | 43     | 30.47%  |
| NVMe | 31        | 36     | 24.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 91        | 112    | 74.59%  |
| NVMe | 31        | 36     | 25.41%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 91     | 79.79%  |
| 0.51-1.0   | 18        | 20     | 19.15%  |
| 1.01-2.0   | 1         | 1      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 67        | 54.47%  |
| 101-250    | 26        | 21.14%  |
| 251-500    | 15        | 12.2%   |
| 501-1000   | 8         | 6.5%    |
| 21-50      | 4         | 3.25%   |
| 51-100     | 2         | 1.63%   |
| Unknown    | 1         | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 119       | 96.75%  |
| 21-50   | 1         | 0.81%   |
| 101-250 | 1         | 0.81%   |
| 51-100  | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 4%      |
| WDC WD2500BEVT-35A23T0 250GB                 | 1         | 1      | 4%      |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 4%      |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 4%      |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 4%      |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 4%      |
| Toshiba MK3261GSYN 320GB                     | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 4%      |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 4%      |
| Seagate ST9160412AS 160GB                    | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 4%      |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 4%      |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 4%      |
| Seagate ST320LT012-9WS14C 320GB              | 1         | 1      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 4%      |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 4%      |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 4%      |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 4%      |
| Kingston SUV400S37240G 240GB                 | 1         | 1      | 4%      |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 4%      |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 4%      |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 4%      |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 4%      |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 32%     |
| Toshiba             | 5         | 5      | 20%     |
| Hitachi             | 4         | 4      | 16%     |
| WDC                 | 2         | 2      | 8%      |
| Samsung Electronics | 2         | 2      | 8%      |
| SanDisk             | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 38.1%   |
| Toshiba | 5         | 5      | 23.81%  |
| Hitachi | 4         | 4      | 19.05%  |
| WDC     | 2         | 2      | 9.52%   |
| HGST    | 1         | 1      | 4.76%   |
| Fujitsu | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 21     | 82.61%  |
| SSD  | 4         | 4      | 17.39%  |

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
| Works   | 96        | 123    | 81.36%  |
| Malfunc | 22        | 25     | 18.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 90        | 64.75%  |
| Samsung Electronics              | 9         | 6.47%   |
| AMD                              | 8         | 5.76%   |
| Nvidia                           | 5         | 3.6%    |
| Kingston Technology Company      | 5         | 3.6%    |
| SK hynix                         | 3         | 2.16%   |
| SanDisk                          | 3         | 2.16%   |
| Solid State Storage Technology   | 2         | 1.44%   |
| Realtek Semiconductor            | 2         | 1.44%   |
| Phison Electronics               | 2         | 1.44%   |
| Micron/Crucial Technology        | 2         | 1.44%   |
| KIOXIA                           | 2         | 1.44%   |
| Toshiba                          | 1         | 0.72%   |
| Silicon Integrated Systems [SiS] | 1         | 0.72%   |
| Micron Technology                | 1         | 0.72%   |
| Marvell Technology Group         | 1         | 0.72%   |
| Lenovo                           | 1         | 0.72%   |
| JMicron Technology               | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 9.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 8.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 7.53%   |
| Unknown                                                                        | 9         | 6.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 4.79%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 4.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.74%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.74%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 2.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.05%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.37%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.37%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 0.68%   |
| SK hynix hynix unknown                                                         | 1         | 0.68%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.68%   |
| SK hynix BC511                                                                 | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.68%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.68%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1         | 0.68%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 0.68%   |
| Lenovo unknown                                                                 | 1         | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.68%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.68%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.68%   |
| JMicron JMB368 IDE controller                                                  | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 94        | 67.63%  |
| NVMe | 31        | 22.3%   |
| RAID | 7         | 5.04%   |
| IDE  | 7         | 5.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 111       | 90.98%  |
| AMD    | 11        | 9.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 4.1%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 4         | 3.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 2.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.64%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 2         | 1.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 1.64%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 2         | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.64%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 2         | 1.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.64%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 1.64%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.64%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.64%   |
| Intel 12th Gen Core i7-12700H               | 2         | 1.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 2         | 1.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.64%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.82%   |
| Intel Unknown                               | 1         | 0.82%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.82%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.82%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.82%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.82%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.82%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 0.82%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.82%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 0.82%   |
| Intel CPU Version                           | 1         | 0.82%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 0.82%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.82%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.82%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.82%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.82%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 31.15%  |
| Intel Core i7           | 20        | 16.39%  |
| Intel Core i3           | 13        | 10.66%  |
| Other                   | 12        | 9.84%   |
| Intel Pentium           | 6         | 4.92%   |
| Intel Core 2 Duo        | 6         | 4.92%   |
| Intel Atom              | 6         | 4.92%   |
| Intel Celeron           | 5         | 4.1%    |
| AMD Ryzen 7             | 4         | 3.28%   |
| Intel Core m3           | 2         | 1.64%   |
| Intel Xeon              | 1         | 0.82%   |
| Intel Pentium Silver    | 1         | 0.82%   |
| Intel Pentium Dual-Core | 1         | 0.82%   |
| AMD V120                | 1         | 0.82%   |
| AMD Ryzen 5             | 1         | 0.82%   |
| AMD Ryzen 3             | 1         | 0.82%   |
| AMD E1                  | 1         | 0.82%   |
| AMD Athlon 64 X2        | 1         | 0.82%   |
| AMD A8                  | 1         | 0.82%   |
| AMD A10                 | 1         | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 70        | 57.38%  |
| 4       | 30        | 24.59%  |
| Unknown | 5         | 4.1%    |
| 16      | 4         | 3.28%   |
| 8       | 4         | 3.28%   |
| 1       | 4         | 3.28%   |
| 10      | 2         | 1.64%   |
| 6       | 2         | 1.64%   |
| 12      | 1         | 0.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 97.54%  |
| 2      | 3         | 2.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 87        | 71.31%  |
| 1       | 29        | 23.77%  |
| Unknown | 6         | 4.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 16.39%  |
| Skylake       | 13        | 10.66%  |
| SandyBridge   | 12        | 9.84%   |
| Broadwell     | 12        | 9.84%   |
| IvyBridge     | 9         | 7.38%   |
| Haswell       | 9         | 7.38%   |
| Unknown       | 8         | 6.56%   |
| Penryn        | 7         | 5.74%   |
| Westmere      | 4         | 3.28%   |
| TigerLake     | 4         | 3.28%   |
| Silvermont    | 4         | 3.28%   |
| Bonnell       | 4         | 3.28%   |
| Zen 2         | 3         | 2.46%   |
| Goldmont plus | 3         | 2.46%   |
| Piledriver    | 2         | 1.64%   |
| Zen           | 1         | 0.82%   |
| Nehalem       | 1         | 0.82%   |
| K8 Hammer     | 1         | 0.82%   |
| K10           | 1         | 0.82%   |
| IceLake       | 1         | 0.82%   |
| Goldmont      | 1         | 0.82%   |
| Core          | 1         | 0.82%   |
| Bobcat        | 1         | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 101       | 65.58%  |
| Nvidia                           | 32        | 20.78%  |
| AMD                              | 20        | 12.99%  |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 12        | 7.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 7.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 5.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 5.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4.55%   |
| Intel HD Graphics 620                                                                    | 5         | 3.25%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 2.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.95%   |
| Intel HD Graphics 530                                                                    | 3         | 1.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.95%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.95%   |
| AMD Renoir                                                                               | 3         | 1.95%   |
| Nvidia TU117M                                                                            | 2         | 1.3%    |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.3%    |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 1.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.3%    |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 1.3%    |
| Intel HD Graphics 630                                                                    | 2         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.3%    |
| AMD Lucienne                                                                             | 2         | 1.3%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.65%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.65%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.65%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.65%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.65%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.65%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.65%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.65%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 67        | 54.92%  |
| Intel + Nvidia | 23        | 18.85%  |
| 1 x AMD        | 11        | 9.02%   |
| 1 x Nvidia     | 8         | 6.56%   |
| Intel + AMD    | 8         | 6.56%   |
| 2 x Intel      | 3         | 2.46%   |
| 1 x SiS        | 1         | 0.82%   |
| AMD + Nvidia   | 1         | 0.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 88.52%  |
| Unknown     | 8         | 6.56%   |
| Proprietary | 6         | 4.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 112       | 91.8%   |
| 0.01-0.5   | 8         | 6.56%   |
| 1.01-2.0   | 1         | 0.82%   |
| 0.51-1.0   | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 20.25%  |
| AU Optronics            | 15        | 18.99%  |
| BOE                     | 11        | 13.92%  |
| Chimei Innolux          | 10        | 12.66%  |
| Apple                   | 7         | 8.86%   |
| Samsung Electronics     | 4         | 5.06%   |
| Sharp                   | 3         | 3.8%    |
| Chi Mei Optoelectronics | 2         | 2.53%   |
| TMX                     | 1         | 1.27%   |
| Nvidia                  | 1         | 1.27%   |
| LG Philips              | 1         | 1.27%   |
| Hewlett-Packard         | 1         | 1.27%   |
| HannStar                | 1         | 1.27%   |
| Fujitsu Siemens         | 1         | 1.27%   |
| Dell                    | 1         | 1.27%   |
| CPT                     | 1         | 1.27%   |
| BenQ                    | 1         | 1.27%   |
| AOC                     | 1         | 1.27%   |
| Ancor Communications    | 1         | 1.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 2         | 2.53%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 2.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 2         | 2.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 2         | 2.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.53%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 2         | 2.53%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 2.53%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 2.53%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.27%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 1.27%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch               | 1         | 1.27%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch               | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 1         | 1.27%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.27%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0546 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.27%   |
| Hewlett-Packard LCD Monitor HWP26A4 1440x900 410x260mm 19.1-inch      | 1         | 1.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.27%   |
| Fujitsu Siemens XE17-4 FUS0674 1280x1024 340x270mm 17.1-inch          | 1         | 1.27%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.27%   |
| CPT LCD Monitor COR17DB 1600x900 290x160mm 13.0-inch                  | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 340x190mm 15.3-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 340x190mm 15.3-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN14E9 1920x1080 310x170mm 13.9-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 1         | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 37.18%  |
| 1366x768 (WXGA)    | 26        | 33.33%  |
| 1280x800 (WXGA)    | 6         | 7.69%   |
| 1600x900 (HD+)     | 5         | 6.41%   |
| 3840x2160 (4K)     | 3         | 3.85%   |
| 1024x600           | 2         | 2.56%   |
| 3840x2400          | 1         | 1.28%   |
| 3200x2000          | 1         | 1.28%   |
| 2560x1440 (QHD)    | 1         | 1.28%   |
| 1920x1200 (WUXGA)  | 1         | 1.28%   |
| 1680x1050 (WSXGA+) | 1         | 1.28%   |
| 1440x900 (WXGA+)   | 1         | 1.28%   |
| 1280x1024 (SXGA)   | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 40        | 50.63%  |
| 13     | 19        | 24.05%  |
| 12     | 8         | 10.13%  |
| 17     | 2         | 2.53%   |
| 11     | 2         | 2.53%   |
| 10     | 2         | 2.53%   |
| 26     | 1         | 1.27%   |
| 24     | 1         | 1.27%   |
| 20     | 1         | 1.27%   |
| 19     | 1         | 1.27%   |
| 14     | 1         | 1.27%   |
| 9      | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 67.09%  |
| 201-300     | 21        | 26.58%  |
| 501-600     | 2         | 2.53%   |
| 401-500     | 2         | 2.53%   |
| 351-400     | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 81.82%  |
| 16/10 | 13        | 16.88%  |
| 5/4   | 1         | 1.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 33        | 41.77%  |
| 81-90          | 17        | 21.52%  |
| 61-70          | 6         | 7.59%   |
| 71-80          | 5         | 6.33%   |
| 101-110        | 5         | 6.33%   |
| 41-50          | 3         | 3.8%    |
| 51-60          | 2         | 2.53%   |
| 151-200        | 2         | 2.53%   |
| 111-120        | 2         | 2.53%   |
| 301-350        | 1         | 1.27%   |
| 201-250        | 1         | 1.27%   |
| 141-150        | 1         | 1.27%   |
| 121-130        | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 43.04%  |
| 101-120       | 26        | 32.91%  |
| 161-240       | 8         | 10.13%  |
| 51-100        | 7         | 8.86%   |
| More than 240 | 4         | 5.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 107       | 87.7%   |
| 0     | 10        | 8.2%    |
| 2     | 5         | 4.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 80        | 41.88%  |
| Realtek Semiconductor            | 48        | 25.13%  |
| Qualcomm Atheros                 | 26        | 13.61%  |
| Broadcom                         | 16        | 8.38%   |
| Ralink                           | 3         | 1.57%   |
| Nvidia                           | 3         | 1.57%   |
| Google                           | 3         | 1.57%   |
| Sierra Wireless                  | 2         | 1.05%   |
| Samsung Electronics              | 2         | 1.05%   |
| Marvell Technology Group         | 2         | 1.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |
| Ralink Technology                | 1         | 0.52%   |
| NetGear                          | 1         | 0.52%   |
| Huawei Technologies              | 1         | 0.52%   |
| D-Link System                    | 1         | 0.52%   |
| BUFFALO                          | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 11.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 5.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 4.74%   |
| Intel Wireless 7265                                               | 11        | 4.74%   |
| Intel Wireless 8265 / 8275                                        | 9         | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.16%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.72%   |
| Intel Wireless 8260                                               | 4         | 1.72%   |
| Intel Wireless 7260                                               | 4         | 1.72%   |
| Intel Wireless 3165                                               | 4         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.29%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.29%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.29%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 1.29%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.29%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.86%   |
| Intel Wireless 3160                                               | 2         | 0.86%   |
| Intel WiFi Link 5100                                              | 2         | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.86%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 56.82%  |
| Qualcomm Atheros      | 24        | 18.18%  |
| Broadcom              | 13        | 9.85%   |
| Realtek Semiconductor | 11        | 8.33%   |
| Ralink                | 3         | 2.27%   |
| Sierra Wireless       | 2         | 1.52%   |
| Ralink Technology     | 1         | 0.76%   |
| NetGear               | 1         | 0.76%   |
| D-Link System         | 1         | 0.76%   |
| BUFFALO               | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 11        | 8.27%   |
| Intel Wireless 7265                                                                           | 11        | 8.27%   |
| Intel Wireless 8265 / 8275                                                                    | 9         | 6.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 5         | 3.76%   |
| Intel Wi-Fi 6 AX200                                                                           | 5         | 3.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4         | 3.01%   |
| Intel Wireless 8260                                                                           | 4         | 3.01%   |
| Intel Wireless 7260                                                                           | 4         | 3.01%   |
| Intel Wireless 3165                                                                           | 4         | 3.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 4         | 3.01%   |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 3.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4         | 3.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 4         | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 3         | 2.26%   |
| Broadcom BCM43224 802.11a/b/g/n                                                               | 3         | 2.26%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3         | 2.26%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 1.5%    |
| Intel Wireless 3160                                                                           | 2         | 1.5%    |
| Intel WiFi Link 5100                                                                          | 2         | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.5%    |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                                 | 1         | 0.75%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.75%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.75%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.75%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.75%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)         | 1         | 0.75%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                                         | 1         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.75%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 1         | 0.75%   |
| Intel Wireless-AC 9260                                                                        | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 40        | 41.24%  |
| Intel                            | 35        | 36.08%  |
| Qualcomm Atheros                 | 8         | 8.25%   |
| Broadcom                         | 4         | 4.12%   |
| Nvidia                           | 3         | 3.09%   |
| Samsung Electronics              | 2         | 2.06%   |
| Marvell Technology Group         | 2         | 2.06%   |
| Google                           | 2         | 2.06%   |
| Silicon Integrated Systems [SiS] | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 27        | 27.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 12.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 5.15%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 4.12%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 3.09%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 3.09%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 3.09%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 3.09%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 2.06%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 2.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 2.06%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.06%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 2.06%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.06%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 2.06%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.06%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 2.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.06%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.03%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.03%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.03%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.03%   |
| Intel Ethernet Connection I218-V                                               | 1         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.03%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.03%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.03%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 54.79%  |
| Ethernet | 97        | 44.29%  |
| Modem    | 1         | 0.46%   |
| Unknown  | 1         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 58.47%  |
| Ethernet | 49        | 41.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 92        | 75.41%  |
| 1     | 29        | 23.77%  |
| 0     | 1         | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 111       | 90.98%  |
| Yes  | 11        | 9.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 64.13%  |
| Broadcom                        | 6         | 6.52%   |
| Apple                           | 6         | 6.52%   |
| Qualcomm Atheros Communications | 4         | 4.35%   |
| Realtek Semiconductor           | 3         | 3.26%   |
| IMC Networks                    | 3         | 3.26%   |
| Lite-On Technology              | 2         | 2.17%   |
| Hewlett-Packard                 | 2         | 2.17%   |
| ASUSTek Computer                | 2         | 2.17%   |
| Alps Electric                   | 2         | 2.17%   |
| Ralink                          | 1         | 1.09%   |
| Foxconn / Hon Hai               | 1         | 1.09%   |
| Cambridge Silicon Radio         | 1         | 1.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 30        | 31.91%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 8         | 8.51%   |
| Intel AX201 Bluetooth                                  | 6         | 6.38%   |
| Intel Wireless-AC 3168 Bluetooth                       | 4         | 4.26%   |
| Intel AX210 Bluetooth                                  | 4         | 4.26%   |
| Intel AX200 Bluetooth                                  | 4         | 4.26%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 4         | 4.26%   |
| HP Broadcom 2070 Bluetooth Combo                       | 2         | 2.13%   |
| Broadcom BCM2045B (BDC-2.1)                            | 2         | 2.13%   |
| Apple Built-in iSight (no firmware loaded)             | 2         | 2.13%   |
| Realtek RTL8723B Bluetooth                             | 1         | 1.06%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 1.06%   |
| Realtek  Bluetooth 4.0 Adapter                         | 1         | 1.06%   |
| Ralink RT3290 Bluetooth                                | 1         | 1.06%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                | 1         | 1.06%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth          | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Bluetooth                      | 1         | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth             | 1         | 1.06%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1         | 1.06%   |
| Intel Intel Wireless Bluetooth                         | 1         | 1.06%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 1         | 1.06%   |
| IMC Networks Realtek Bluetooth Adapter                 | 1         | 1.06%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 1.06%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 1.06%   |
| Foxconn / Hon Hai BCM43142 Bluetooth Adapter           | 1         | 1.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 1         | 1.06%   |
| Broadcom BCM43142A0 Bluetooth 4.0                      | 1         | 1.06%   |
| Broadcom BCM43142 Bluetooth 4.0                        | 1         | 1.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 1.06%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]       | 1         | 1.06%   |
| ASUS BT-270 Bluetooth Adapter                          | 1         | 1.06%   |
| ASUS BT-253 Bluetooth Adapter                          | 1         | 1.06%   |
| Apple Bluetooth Host Controller                        | 1         | 1.06%   |
| Apple Apple Broadcom Built-in Bluetooth                | 1         | 1.06%   |
| Alps Electric UGTZ4 Bluetooth                          | 1         | 1.06%   |
| Alps Electric BCM2046 Bluetooth Device                 | 1         | 1.06%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 104       | 78.79%  |
| AMD                              | 12        | 9.09%   |
| Nvidia                           | 11        | 8.33%   |
| XMOS                             | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] | 1         | 0.76%   |
| Kingston Technology              | 1         | 0.76%   |
| GN Netcom                        | 1         | 0.76%   |
| C-Media Electronics              | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 12.35%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 8.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 7.41%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.94%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 4.32%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.7%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 3.7%    |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.47%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.85%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.85%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.23%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.23%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.23%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.62%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.62%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.62%   |
| Intel USB2.0 Device                                                                               | 1         | 0.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.62%   |
| GN Netcom Jabra EVOLVE 20                                                                         | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 27.27%  |
| SK hynix            | 30        | 20.98%  |
| Micron Technology   | 15        | 10.49%  |
| Unknown             | 11        | 7.69%   |
| Kingston            | 10        | 6.99%   |
| Smart               | 5         | 3.5%    |
| A-DATA Technology   | 4         | 2.8%    |
| G.Skill             | 3         | 2.1%    |
| Elpida              | 3         | 2.1%    |
| Crucial             | 3         | 2.1%    |
| Unknown             | 3         | 2.1%    |
| Smart Brazil        | 2         | 1.4%    |
| Ramaxel Technology  | 2         | 1.4%    |
| Nanya Technology    | 2         | 1.4%    |
| Transcend           | 1         | 0.7%    |
| Teikon              | 1         | 0.7%    |
| Team                | 1         | 0.7%    |
| SHARETRONIC         | 1         | 0.7%    |
| Sesame              | 1         | 0.7%    |
| PNY                 | 1         | 0.7%    |
| Nayna               | 1         | 0.7%    |
| High Bridge         | 1         | 0.7%    |
| GSkill              | 1         | 0.7%    |
| GeIL                | 1         | 0.7%    |
| Essencore           | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s              | 7         | 4.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s             | 4         | 2.61%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s             | 4         | 2.61%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                       | 3         | 1.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 3         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s              | 3         | 1.96%   |
| Unknown                                                            | 3         | 1.96%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                        | 2         | 1.31%   |
| Unknown RAM Module 2GB SODIMM DDR3                                 | 2         | 1.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                         | 2         | 1.31%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s              | 2         | 1.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 2         | 1.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 2         | 1.31%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s             | 2         | 1.31%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 2         | 1.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s              | 2         | 1.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s              | 2         | 1.31%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s              | 2         | 1.31%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s              | 2         | 1.31%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s              | 2         | 1.31%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s              | 2         | 1.31%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR3                                 | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                          | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                         | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2                                 | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s                         | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 0.65%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s               | 1         | 0.65%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s             | 1         | 0.65%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s               | 1         | 0.65%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s              | 1         | 0.65%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s              | 1         | 0.65%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s              | 1         | 0.65%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s              | 1         | 0.65%   |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s       | 1         | 0.65%   |
| Smart Brazil RAM SDQC8G8W16XCWE9N1T 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.65%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s             | 1         | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                       | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 58        | 48.33%  |
| DDR4    | 47        | 39.17%  |
| DDR2    | 8         | 6.67%   |
| SDRAM   | 2         | 1.67%   |
| LPDDR3  | 2         | 1.67%   |
| DRAM    | 1         | 0.83%   |
| DDR5    | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 109       | 87.9%   |
| Row Of Chips | 7         | 5.65%   |
| DIMM         | 3         | 2.42%   |
| Unknown      | 3         | 2.42%   |
| Chip         | 2         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 52        | 40%     |
| 8192  | 30        | 23.08%  |
| 2048  | 28        | 21.54%  |
| 16384 | 16        | 12.31%  |
| 1024  | 3         | 2.31%   |
| 32768 | 1         | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 41        | 30.83%  |
| 2400    | 17        | 12.78%  |
| 2667    | 16        | 12.03%  |
| 3200    | 13        | 9.77%   |
| 1333    | 13        | 9.77%   |
| 2133    | 8         | 6.02%   |
| 1334    | 4         | 3.01%   |
| 667     | 4         | 3.01%   |
| Unknown | 4         | 3.01%   |
| 1867    | 3         | 2.26%   |
| 800     | 3         | 2.26%   |
| 2048    | 2         | 1.5%    |
| 1067    | 2         | 1.5%    |
| 4800    | 1         | 0.75%   |
| 1066    | 1         | 0.75%   |
| 333     | 1         | 0.75%   |

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
| Chicony Electronics                    | 27        | 28.13%  |
| Microdia                               | 11        | 11.46%  |
| IMC Networks                           | 10        | 10.42%  |
| Bison Electronics                      | 10        | 10.42%  |
| Sunplus Innovation Technology          | 9         | 9.38%   |
| Realtek Semiconductor                  | 8         | 8.33%   |
| Suyin                                  | 4         | 4.17%   |
| Luxvisions Innotech Limited            | 3         | 3.13%   |
| Apple                                  | 3         | 3.13%   |
| Syntek                                 | 2         | 2.08%   |
| Silicon Motion                         | 2         | 2.08%   |
| Alcor Micro                            | 2         | 2.08%   |
| Z-Star Microelectronics                | 1         | 1.04%   |
| Unknown                                | 1         | 1.04%   |
| Lite-On Technology                     | 1         | 1.04%   |
| Lenovo                                 | 1         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 5         | 5.21%   |
| Bison Integrated Camera                                     | 5         | 5.21%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 4.17%   |
| Microdia Integrated_Webcam_HD                               | 3         | 3.13%   |
| Chicony HD Webcam                                           | 3         | 3.13%   |
| Suyin Integrated_Webcam_HD                                  | 2         | 2.08%   |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 2.08%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 2.08%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 2.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 2.08%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 2         | 2.08%   |
| IMC Networks Integrated Camera                              | 2         | 2.08%   |
| Chicony XiaoMi USB 2.0 Webcam                               | 2         | 2.08%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 2.08%   |
| Chicony Lenovo EasyCamera                                   | 2         | 2.08%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 2.08%   |
| Chicony Chicony USB2.0 Camera                               | 2         | 2.08%   |
| Bison HD Webcam                                             | 2         | 2.08%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 2.08%   |
| Z-Star DataMax USB2.0 Camera                                | 1         | 1.04%   |
| Unknown Realtek PC Camera                                   | 1         | 1.04%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 1.04%   |
| Syntek Integrated Camera                                    | 1         | 1.04%   |
| Suyin WebCam                                                | 1         | 1.04%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.04%   |
| Sunplus XiaoMi USB 2.0 Webcam                               | 1         | 1.04%   |
| Sunplus Integrated Camera                                   | 1         | 1.04%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.04%   |
| Sunplus HD WebCam                                           | 1         | 1.04%   |
| Sunplus Asus Webcam                                         | 1         | 1.04%   |
| Silicon Motion Web Camera                                   | 1         | 1.04%   |
| Silicon Motion HP Webcam-50                                 | 1         | 1.04%   |
| Realtek Realtek PC Camera                                   | 1         | 1.04%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.04%   |
| Realtek Integrated Webcam HD                                | 1         | 1.04%   |
| Realtek HP HD Webcam [Fixed]                                | 1         | 1.04%   |
| Realtek HD WebCam                                           | 1         | 1.04%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 1.04%   |
| Microdia Webcam                                             | 1         | 1.04%   |
| Microdia REDRAGON  Live Camera                              | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 50%     |
| Synaptics                  | 6         | 27.27%  |
| AuthenTec                  | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| Shenzhen Goodix Technology | 1         | 4.55%   |
| Broadcom                   | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 13.64%  |
| Unknown                                                                      | 3         | 13.64%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 9.09%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 4.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 4.55%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 4.55%   |
| Synaptics product 0x00f9                                                     | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 4.55%   |
| AuthenTec AES1600                                                            | 1         | 4.55%   |

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
| 2     | 39        | 31.97%  |
| 1     | 38        | 31.15%  |
| 3     | 20        | 16.39%  |
| 0     | 18        | 14.75%  |
| 4     | 5         | 4.1%    |
| 5     | 2         | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 91        | 46.91%  |
| Bluetooth                | 32        | 16.49%  |
| Card reader              | 25        | 12.89%  |
| Fingerprint reader       | 21        | 10.82%  |
| Net/wireless             | 15        | 7.73%   |
| Sound                    | 7         | 3.61%   |
| Network                  | 2         | 1.03%   |
| Storage                  | 1         | 0.52%   |

