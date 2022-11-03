helloSystem - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for helloSystem.

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

Total: 634

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | Pavilion g6                 | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Apple         | MacBook4,1                  | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| Lenovo        | G500 20236                  | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Lenovo        | ThinkPad T61 765912G        | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| HP            | Laptop 15q-bu0xx            | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Dell          | Latitude E6420              | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK U904               | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| Acer          | Aspire F5-573               | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| HP            | ProBook 4540s               | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Dell          | Precision 7710              | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Apple         | MacBook5,2                  | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Apple         | MacBookPro5,1               | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Dell          | Latitude E5550              | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| Dell          | Precision 7710              | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| Dell          | Precision 5540              | [0c5089634d](https://bsd-hardware.info/?probe=0c5089634d) | Aug 30, 2022 |
| Dell          | Precision 5540              | [afb80a84fb](https://bsd-hardware.info/?probe=afb80a84fb) | Aug 30, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Toshiba       | Satellite S55t-B            | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Dell          | Studio 1537                 | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| HP            | ProBook 4540s               | [0a7891d53f](https://bsd-hardware.info/?probe=0a7891d53f) | Aug 06, 2022 |
| eMachines     | eME728                      | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| HP            | ProBook 430 G4              | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| HP            | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Lenovo        | ThinkPad L412 0585AD9       | [cba0fc2340](https://bsd-hardware.info/?probe=cba0fc2340) | Jul 20, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| HP            | OMEN by Laptop              | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| Dell          | Inspiron MP061              | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| Apple         | MacBook4,1                  | [db03ba8975](https://bsd-hardware.info/?probe=db03ba8975) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| MSI           | GF63 Thin 10SC              | [139855ab73](https://bsd-hardware.info/?probe=139855ab73) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Fujitsu       | LIFEBOOK A555               | [1062220932](https://bsd-hardware.info/?probe=1062220932) | Jul 07, 2022 |
| HP            | 250 G6 Notebook PC          | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Lenovo        | ThinkPad T430s 2356CV6      | [20df9d5df2](https://bsd-hardware.info/?probe=20df9d5df2) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Lenovo        | ThinkPad T460 20FN004CUK    | [18b5875c95](https://bsd-hardware.info/?probe=18b5875c95) | Jun 26, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| HP            | Unknown                     | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Alienware     | M18xR2                      | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Lenovo        | G40-30 80FY                 | [f478f5edc1](https://bsd-hardware.info/?probe=f478f5edc1) | Jun 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| HP            | ProBook 4230s               | [8c853f8ca9](https://bsd-hardware.info/?probe=8c853f8ca9) | Jun 11, 2022 |
| Acer          | Aspire E5-571               | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| HP            | Pavilion g4                 | [79d8ca2681](https://bsd-hardware.info/?probe=79d8ca2681) | Jun 04, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [9e2661b9e0](https://bsd-hardware.info/?probe=9e2661b9e0) | May 24, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| HP            | Pavilion dv6                | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Acer          | Aspire E1-522               | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| Acer          | Aspire E1-522               | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [34ac291019](https://bsd-hardware.info/?probe=34ac291019) | May 11, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| HP            | ProBook 4340s               | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Unknown       | W1415A                      | [1b2c63a845](https://bsd-hardware.info/?probe=1b2c63a845) | May 07, 2022 |
| Sony          | VGN-NW25GF_S                | [84b50ca3f1](https://bsd-hardware.info/?probe=84b50ca3f1) | May 06, 2022 |
| Toshiba       | Satellite P300              | [fca7b38039](https://bsd-hardware.info/?probe=fca7b38039) | May 04, 2022 |
| Lenovo        | B470 HuronRiver Platform    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| HP            | Pavilion m6                 | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Acer          | Aspire A315-41              | [c59d8482e8](https://bsd-hardware.info/?probe=c59d8482e8) | May 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | [807676e010](https://bsd-hardware.info/?probe=807676e010) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | [4b5603b38b](https://bsd-hardware.info/?probe=4b5603b38b) | Apr 29, 2022 |
| Apple         | MacBookPro3,1               | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| Dell          | Inspiron 5437               | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| HP            | 2000                        | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| ASUSTek       | X556UJ                      | [ca63749774](https://bsd-hardware.info/?probe=ca63749774) | Apr 19, 2022 |
| Lenovo        | G51-35 80M8                 | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| Sony          | SVZ1311C5E                  | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [a3da09ae5e](https://bsd-hardware.info/?probe=a3da09ae5e) | Apr 15, 2022 |
| System76      | Lemur Pro                   | [276ee4e96e](https://bsd-hardware.info/?probe=276ee4e96e) | Apr 13, 2022 |
| Lenovo        | ThinkPad X61 7675K2U        | [24f93b9532](https://bsd-hardware.info/?probe=24f93b9532) | Apr 10, 2022 |
| ASUSTek       | 1001PX                      | [b47a498f2e](https://bsd-hardware.info/?probe=b47a498f2e) | Apr 08, 2022 |
| Panasonic     | CF-B11JWCYS                 | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| HP            | Pavilion 11                 | [a13373b255](https://bsd-hardware.info/?probe=a13373b255) | Apr 07, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Dell          | Latitude E5470              | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| Sony          | VGN-AW21S_B                 | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| LG Electro... | E300-A.CP20T                | [304701f666](https://bsd-hardware.info/?probe=304701f666) | Apr 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
| PCSTICK       | Unknown                     | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Dell          | Vostro 3490                 | [34956934f5](https://bsd-hardware.info/?probe=34956934f5) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| HP            | Pavilion dv6                | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 4293B43       | [148a268a0f](https://bsd-hardware.info/?probe=148a268a0f) | Mar 16, 2022 |
| HASEE Comp... | CW35S                       | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| Dell          | Latitude E6540              | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| Acer          | Aspire E1-421               | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Itautec       | Infoway w7535               | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| HUAWEI        | BOD-WXX9                    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| HP            | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Acer          | V5-131                      | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| Acer          | V5-131                      | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude 7480               | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| Dell          | Latitude E4310              | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple         | MacBook4,1                  | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude E5470              | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| PCSTICK       | Unknown                     | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| TUXEDO        | InfinityBook13V3            | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| ASUSTek       | 1001PX                      | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung       | N100                        | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| Timi          | RedmiBook Pro 15            | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Apple         | MacBook5,2                  | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Apple         | MacBookPro4,1               | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| Lenovo        | G580 20150                  | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Acer          | Aspire E5-511G              | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD      | U12CT                       | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Dell          | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Sony          | VPCEB1J1E                   | [04c5ee02da](https://bsd-hardware.info/?probe=04c5ee02da) | Feb 05, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| HP            | G62                         | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Sony          | VPCEB1J1E                   | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| Apple         | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung       | N150P/N210P/N220P           | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Apple         | MacBook5,2                  | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer          | Aspire 5930                 | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| Dell          | Latitude 7280               | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Acer          | Aspire ES1-311              | [83addddaa5](https://bsd-hardware.info/?probe=83addddaa5) | Jan 22, 2022 |
| Dell          | Latitude E6540              | [529768f8c8](https://bsd-hardware.info/?probe=529768f8c8) | Jan 21, 2022 |
| Toshiba       | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| HP            | EliteBook 2560p             | [4d04ececbb](https://bsd-hardware.info/?probe=4d04ececbb) | Jan 19, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| Gateway       | NE56R                       | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f4c9b911fe](https://bsd-hardware.info/?probe=f4c9b911fe) | Jan 16, 2022 |
| Lenovo        | ThinkPad T440 20B7000PHV    | [9584ae69fa](https://bsd-hardware.info/?probe=9584ae69fa) | Jan 16, 2022 |
| Apple         | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| Acer          | V5-131                      | [e4d0f66ff8](https://bsd-hardware.info/?probe=e4d0f66ff8) | Jan 13, 2022 |
| Acer          | Aspire ES1-533              | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440 20B7A0B7MS    | [be30041f4e](https://bsd-hardware.info/?probe=be30041f4e) | Jan 10, 2022 |
| Acer          | Aspire E5-476G              | [2a8624ee35](https://bsd-hardware.info/?probe=2a8624ee35) | Jan 10, 2022 |
| Sony          | VPCYB45JB                   | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Lenovo        | G480 20149                  | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| Dell          | Latitude E6530              | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | G550 2958                   | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MX     | [0fa4700d17](https://bsd-hardware.info/?probe=0fa4700d17) | Jan 07, 2022 |
| HP            | Laptop 14-dk0xxx            | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| Notebook      | N15_17RD                    | [47c30b962d](https://bsd-hardware.info/?probe=47c30b962d) | Jan 05, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| HP            | EliteBook 820 G1            | [362940acbb](https://bsd-hardware.info/?probe=362940acbb) | Jan 03, 2022 |
| Dell          | Latitude 7380               | [590b374836](https://bsd-hardware.info/?probe=590b374836) | Jan 02, 2022 |
| Dell          | Latitude E6540              | [f5a43a9f8b](https://bsd-hardware.info/?probe=f5a43a9f8b) | Jan 02, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| Dell          | Latitude E6540              | [97d152656e](https://bsd-hardware.info/?probe=97d152656e) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Acer          | Aspire 5742G                | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Lenovo        | ThinkPad E580 20KS005BRI    | [b533989df5](https://bsd-hardware.info/?probe=b533989df5) | Dec 29, 2021 |
| Dell          | Inspiron 3521               | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | [5f17e74f2f](https://bsd-hardware.info/?probe=5f17e74f2f) | Dec 27, 2021 |
| Acer          | Aspire 5742G                | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Acer          | TravelMate 5760G            | [46204b90d0](https://bsd-hardware.info/?probe=46204b90d0) | Dec 24, 2021 |
| Lenovo        | ThinkPad SL510 2847R96      | [b0a9802877](https://bsd-hardware.info/?probe=b0a9802877) | Dec 22, 2021 |
| Lenovo        | ThinkPad T410 2537EA8       | [8b457cd635](https://bsd-hardware.info/?probe=8b457cd635) | Dec 22, 2021 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| Toshiba       | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Acer          | Aspire E1-421               | [b2aea3de1b](https://bsd-hardware.info/?probe=b2aea3de1b) | Dec 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba       | Satellite L550              | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek       | N56VB                       | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| Dell          | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Lenovo        | G500 20236                  | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [9efeb9ee24](https://bsd-hardware.info/?probe=9efeb9ee24) | Dec 16, 2021 |
| Dell          | Inspiron 3521               | [d8bcea438a](https://bsd-hardware.info/?probe=d8bcea438a) | Dec 15, 2021 |
| HP            | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| ASUSTek       | X502CA                      | [45f61ab19e](https://bsd-hardware.info/?probe=45f61ab19e) | Dec 14, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| HP            | EliteBook 2560p             | [a064edad4b](https://bsd-hardware.info/?probe=a064edad4b) | Dec 10, 2021 |
| Acer          | Aspire 5749Z                | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Apple         | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| Philco        | 10B                         | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| ASUSTek       | UX31A                       | [9febab6c01](https://bsd-hardware.info/?probe=9febab6c01) | Dec 05, 2021 |
| HP            | Laptop 15-dw0xxx            | [4903f23b62](https://bsd-hardware.info/?probe=4903f23b62) | Dec 05, 2021 |
| ASUSTek       | X540LA                      | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek       | X540LA                      | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer          | Swift SF314-52              | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [e4b923d500](https://bsd-hardware.info/?probe=e4b923d500) | Dec 02, 2021 |
| ASUSTek       | X540LA                      | [0680188ca4](https://bsd-hardware.info/?probe=0680188ca4) | Dec 01, 2021 |
| HP            | Laptop 15-db0xxx            | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| Toshiba       | Satellite S55t-B            | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Lenovo        | V310-14IKB 80T2             | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| HP            | EliteBook 2560p             | [8fe8caf37d](https://bsd-hardware.info/?probe=8fe8caf37d) | Nov 21, 2021 |
| Toshiba       | Satellite C640              | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba       | Satellite C640              | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Dell          | Inspiron 5566               | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| Lenovo        | ThinkPad T60 1951FEG        | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| Apple         | MacBookPro9,2               | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| HP            | EliteBook 840 G5            | [a1ece36be8](https://bsd-hardware.info/?probe=a1ece36be8) | Nov 11, 2021 |
| Dell          | Studio 1747                 | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Acer          | Aspire 5742G                | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| ASUSTek       | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [748312bfbf](https://bsd-hardware.info/?probe=748312bfbf) | Nov 07, 2021 |
| ASUSTek       | K52Jc                       | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| HP            | 14                          | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP            | EliteBook 840 G3            | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z360                | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430u 3352AA5      | [8619bcca35](https://bsd-hardware.info/?probe=8619bcca35) | Nov 01, 2021 |
| Apple         | MacBookAir5,1               | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| HP            | Presario CQ43               | [b97d9ff563](https://bsd-hardware.info/?probe=b97d9ff563) | Oct 30, 2021 |
| Chuwi         | MiniBook                    | [4ce05f93a8](https://bsd-hardware.info/?probe=4ce05f93a8) | Oct 28, 2021 |
| Dell          | Precision M4600             | [2f848fd2c0](https://bsd-hardware.info/?probe=2f848fd2c0) | Oct 27, 2021 |
| Sony          | SVS1511AJB                  | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Apple         | MacBookPro4,1               | [10861818b2](https://bsd-hardware.info/?probe=10861818b2) | Oct 20, 2021 |
| HP            | Unknown                     | [ad95186d17](https://bsd-hardware.info/?probe=ad95186d17) | Oct 19, 2021 |
| Dell          | Studio 1747                 | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| HP            | 15                          | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| HP            | ProBook 470 G4              | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| Lenovo        | G500s 20245                 | [e6141c9ab3](https://bsd-hardware.info/?probe=e6141c9ab3) | Oct 16, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [48169f1d3c](https://bsd-hardware.info/?probe=48169f1d3c) | Oct 16, 2021 |
| HP            | Pavilion dv3                | [7f0b7f520f](https://bsd-hardware.info/?probe=7f0b7f520f) | Oct 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek       | U33Jc                       | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| HP            | ProBook 470 G4              | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| MSI           | MS-16F1                     | [72b9db306a](https://bsd-hardware.info/?probe=72b9db306a) | Oct 09, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| Lenovo        | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| Acer          | Aspire 5741                 | [fd4e40a8d9](https://bsd-hardware.info/?probe=fd4e40a8d9) | Oct 07, 2021 |
| Lenovo        | ThinkPad R500 2718W92       | [384f10861a](https://bsd-hardware.info/?probe=384f10861a) | Oct 05, 2021 |
| Toshiba       | dynabook Satellite B453/... | [e621531452](https://bsd-hardware.info/?probe=e621531452) | Oct 05, 2021 |
| ASUSTek       | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| ASUSTek       | X441BA                      | [2fcb818b78](https://bsd-hardware.info/?probe=2fcb818b78) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| Dell          | Latitude E4300              | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| Dell          | Inspiron 3521               | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Lenovo        | ThinkPad T490s 20NYS3TU0... | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efdfee9023](https://bsd-hardware.info/?probe=efdfee9023) | Oct 01, 2021 |
| Toshiba       | dynabook RX3 SM240E/3HD     | [2fe863dff4](https://bsd-hardware.info/?probe=2fe863dff4) | Oct 01, 2021 |
| Toshiba       | Satellite S55t-B            | [445fe665b8](https://bsd-hardware.info/?probe=445fe665b8) | Oct 01, 2021 |
| HP            | Pavilion dm4                | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| Lenovo        | ThinkPad X230 2325O76       | [b8729e39e1](https://bsd-hardware.info/?probe=b8729e39e1) | Sep 29, 2021 |
| Toshiba       | Satellite P300              | [13e4aa7026](https://bsd-hardware.info/?probe=13e4aa7026) | Sep 29, 2021 |
| Lenovo        | ThinkPad L520 78594KM       | [7905093412](https://bsd-hardware.info/?probe=7905093412) | Sep 26, 2021 |
| Lenovo        | ThinkPad T410 2537E82       | [4ccdde7b89](https://bsd-hardware.info/?probe=4ccdde7b89) | Sep 20, 2021 |
| Lenovo        | G500s 20245                 | [88cd1ca7bd](https://bsd-hardware.info/?probe=88cd1ca7bd) | Sep 18, 2021 |
| Lenovo        | ThinkPad T61 64607EU        | [34e48b691d](https://bsd-hardware.info/?probe=34e48b691d) | Sep 17, 2021 |
| HP            | G42                         | [738ccd1adf](https://bsd-hardware.info/?probe=738ccd1adf) | Sep 15, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| Kraftway      | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Dell          | Latitude 3540               | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| Itautec       | Infoway w7530               | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Apple         | MacBookAir7,2               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
| Itautec       | Infoway w7530               | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| Toshiba       | Satellite S55t-B            | [5aaacec4ad](https://bsd-hardware.info/?probe=5aaacec4ad) | Aug 23, 2021 |
| Toshiba       | Satellite S55t-B            | [d74035a8e7](https://bsd-hardware.info/?probe=d74035a8e7) | Aug 23, 2021 |
| HP            | Pavilion dv6                | [8054d6310f](https://bsd-hardware.info/?probe=8054d6310f) | Aug 19, 2021 |
| MSI           | GF65 Thin 10SDR             | [7e5ebc9c82](https://bsd-hardware.info/?probe=7e5ebc9c82) | Aug 18, 2021 |
| Toshiba       | Satellite L855              | [116ce6af18](https://bsd-hardware.info/?probe=116ce6af18) | Aug 18, 2021 |
| Dell          | Latitude E5530 non-vPro     | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| ASUSTek       | X55CR                       | [c7c812c2c9](https://bsd-hardware.info/?probe=c7c812c2c9) | Aug 15, 2021 |
| HP            | 250 G4                      | [24e8c3de59](https://bsd-hardware.info/?probe=24e8c3de59) | Aug 13, 2021 |
| HP            | 625                         | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| HP            | 250 G4                      | [43a7b112ba](https://bsd-hardware.info/?probe=43a7b112ba) | Aug 11, 2021 |
| Lenovo        | ThinkPad X230 2330A48       | [791c826f7d](https://bsd-hardware.info/?probe=791c826f7d) | Aug 11, 2021 |
| HP            | Pavilion 11                 | [5300a49632](https://bsd-hardware.info/?probe=5300a49632) | Aug 10, 2021 |
| Dell          | G3 3579                     | [91c803fdf2](https://bsd-hardware.info/?probe=91c803fdf2) | Aug 09, 2021 |
| NEC Comput... | PC-VK17HBBCD                | [1e23da04c0](https://bsd-hardware.info/?probe=1e23da04c0) | Aug 08, 2021 |
| Dell          | Inspiron 15-3567            | [9073f1975d](https://bsd-hardware.info/?probe=9073f1975d) | Aug 07, 2021 |
| ASUSTek       | K55VD                       | [6896c37580](https://bsd-hardware.info/?probe=6896c37580) | Aug 06, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| Apple         | MacBookPro3,1               | [3566222830](https://bsd-hardware.info/?probe=3566222830) | Aug 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS4JH00    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| Sony          | VPCEJ1E1E                   | [c471fb3f82](https://bsd-hardware.info/?probe=c471fb3f82) | Aug 01, 2021 |
| Lenovo        | G550 2958                   | [86880c29cf](https://bsd-hardware.info/?probe=86880c29cf) | Jul 31, 2021 |
| Lenovo        | G550 2958                   | [4fe522eaf3](https://bsd-hardware.info/?probe=4fe522eaf3) | Jul 31, 2021 |
| HP            | 15                          | [c2da1dd654](https://bsd-hardware.info/?probe=c2da1dd654) | Jul 30, 2021 |
| Lenovo        | ThinkPad SL 2746M3C         | [aa10433581](https://bsd-hardware.info/?probe=aa10433581) | Jul 28, 2021 |
| Apple         | MacBookPro6,2               | [7f25ab7c67](https://bsd-hardware.info/?probe=7f25ab7c67) | Jul 26, 2021 |
| Lenovo        | G500 20236                  | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| HP            | Stream 11 Pro G4 EE         | [bd2bf6b0a0](https://bsd-hardware.info/?probe=bd2bf6b0a0) | Jul 20, 2021 |
| Apple         | MacBookPro9,2               | [6cca4dee6f](https://bsd-hardware.info/?probe=6cca4dee6f) | Jul 15, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Alienware     | 17                          | [aff2be63cd](https://bsd-hardware.info/?probe=aff2be63cd) | Jul 10, 2021 |
| MouseCompu... | W331AU                      | [f9a4733911](https://bsd-hardware.info/?probe=f9a4733911) | Jul 06, 2021 |
| MouseCompu... | W331AU                      | [4adfeaa072](https://bsd-hardware.info/?probe=4adfeaa072) | Jul 06, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| eMachines     | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| Lenovo        | B590 62743PG                | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| HP            | ProBook 4440s               | [4aac49bc1e](https://bsd-hardware.info/?probe=4aac49bc1e) | Jul 01, 2021 |
| Lenovo        | ThinkPad X200 7458VP4       | [42100d8ea1](https://bsd-hardware.info/?probe=42100d8ea1) | Jun 30, 2021 |
| HP            | Pavilion 17                 | [9929e0c39b](https://bsd-hardware.info/?probe=9929e0c39b) | Jun 30, 2021 |
| Dell          | Latitude E6410              | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [aba7b76575](https://bsd-hardware.info/?probe=aba7b76575) | Jun 27, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [1697ebb0a5](https://bsd-hardware.info/?probe=1697ebb0a5) | Jun 25, 2021 |
| Acer          | Aspire 5750                 | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Dell          | Precision 7710              | [33653d0c28](https://bsd-hardware.info/?probe=33653d0c28) | Jun 22, 2021 |
| Lenovo        | ThinkPad X230 2325WWB       | [786669cc9c](https://bsd-hardware.info/?probe=786669cc9c) | Jun 21, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| Dell          | Inspiron 3542               | [bb13e61de1](https://bsd-hardware.info/?probe=bb13e61de1) | Jun 21, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [d5e4c49986](https://bsd-hardware.info/?probe=d5e4c49986) | Jun 21, 2021 |
| Acer          | Aspire 5750                 | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Toshiba       | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Gateway       | NE56R                       | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0fe1337b93](https://bsd-hardware.info/?probe=0fe1337b93) | Jun 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [902b4298d4](https://bsd-hardware.info/?probe=902b4298d4) | Jun 19, 2021 |
| WYSE          | Z CLASS                     | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Dell          | Latitude E5420              | [1ed3ff35f6](https://bsd-hardware.info/?probe=1ed3ff35f6) | Jun 19, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [0e448af5f5](https://bsd-hardware.info/?probe=0e448af5f5) | Jun 18, 2021 |
| Dell          | Latitude 7280               | [8fd335f46f](https://bsd-hardware.info/?probe=8fd335f46f) | Jun 18, 2021 |
| Dell          | Vostro 3560                 | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Lenovo        | ThinkPad Edge E530 62724... | [78abd376db](https://bsd-hardware.info/?probe=78abd376db) | Jun 18, 2021 |
| Lenovo        | ThinkPad T420 4236FJ1       | [808f58228e](https://bsd-hardware.info/?probe=808f58228e) | Jun 17, 2021 |
| Toshiba       | PORTEGE R930                | [db520e9382](https://bsd-hardware.info/?probe=db520e9382) | Jun 15, 2021 |
| Toshiba       | Satellite C640              | [ec0d93d08c](https://bsd-hardware.info/?probe=ec0d93d08c) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude 5400               | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| Dell          | Inspiron 15-3567            | [53049dff12](https://bsd-hardware.info/?probe=53049dff12) | Jun 14, 2021 |
| HP            | OMEN by Laptop              | [abc94e9198](https://bsd-hardware.info/?probe=abc94e9198) | Jun 13, 2021 |
| HP            | 255 G2                      | [31177d9e0f](https://bsd-hardware.info/?probe=31177d9e0f) | Jun 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | [ca15c7d742](https://bsd-hardware.info/?probe=ca15c7d742) | Jun 13, 2021 |
| Gateway       | NE56R                       | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Latitude E4300              | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Lenovo        | ThinkPad X240 20AMS39F0K    | [65564434a9](https://bsd-hardware.info/?probe=65564434a9) | Jun 12, 2021 |
| ASUSTek       | UX330UAK                    | [430c90b88d](https://bsd-hardware.info/?probe=430c90b88d) | Jun 12, 2021 |
| Pegatron      | T12Ah                       | [50d37406df](https://bsd-hardware.info/?probe=50d37406df) | Jun 06, 2021 |
| HP            | Pavilion dv4                | [27f912e4e4](https://bsd-hardware.info/?probe=27f912e4e4) | May 28, 2021 |
| Dell          | Inspiron 3442               | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | Latitude E6410              | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Dell          | Inspiron 3442               | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| HP            | 240 G5 Notebook PC          | [f9c67b360f](https://bsd-hardware.info/?probe=f9c67b360f) | May 08, 2021 |
| Dell          | Latitude E5570              | [c8477da717](https://bsd-hardware.info/?probe=c8477da717) | May 07, 2021 |
| Apple         | MacBookPro11,3              | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Notebook      | W65KJ1_KK1                  | [d4d0b819bc](https://bsd-hardware.info/?probe=d4d0b819bc) | Apr 24, 2021 |
| Gateway       | NE56R                       | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Dell          | Latitude E7240              | [1dbd9a5cee](https://bsd-hardware.info/?probe=1dbd9a5cee) | Apr 13, 2021 |
| Lenovo        | ThinkPad T400 7417TPU       | [981517a51a](https://bsd-hardware.info/?probe=981517a51a) | Apr 13, 2021 |
| Apple         | MacBookPro8,1               | [5d3d014284](https://bsd-hardware.info/?probe=5d3d014284) | Apr 12, 2021 |
| Apple         | MacBookPro8,1               | [ffcc46ea0b](https://bsd-hardware.info/?probe=ffcc46ea0b) | Apr 12, 2021 |
| Gateway       | NE56R                       | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| ASUSTek       | TP500LNG                    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Panasonic     | CF-NX1GDHYS                 | [6bbadba65d](https://bsd-hardware.info/?probe=6bbadba65d) | Apr 04, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Dell          | Vostro 14-3468              | [219133fc53](https://bsd-hardware.info/?probe=219133fc53) | Mar 30, 2021 |
| Dell          | Vostro 14-3468              | [2c61fcee12](https://bsd-hardware.info/?probe=2c61fcee12) | Mar 30, 2021 |
| ASUSTek       | X540UP                      | [a9c4506364](https://bsd-hardware.info/?probe=a9c4506364) | Mar 28, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Toshiba       | Satellite L500              | [e07fd4edd9](https://bsd-hardware.info/?probe=e07fd4edd9) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | [42ecf97502](https://bsd-hardware.info/?probe=42ecf97502) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | [88e98e18a5](https://bsd-hardware.info/?probe=88e98e18a5) | Mar 25, 2021 |
| ASUSTek       | G75VW                       | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [10c79ea427](https://bsd-hardware.info/?probe=10c79ea427) | Mar 22, 2021 |
| Dell          | Inspiron 7370               | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| Dell          | Inspiron 7520               | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Dell          | Inspiron 3442               | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Packard Be... | EasyNote MH36               | [2a98cae4e8](https://bsd-hardware.info/?probe=2a98cae4e8) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [cf75f7c9cb](https://bsd-hardware.info/?probe=cf75f7c9cb) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [b90180457c](https://bsd-hardware.info/?probe=b90180457c) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [bcb99d0f09](https://bsd-hardware.info/?probe=bcb99d0f09) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [ee894449af](https://bsd-hardware.info/?probe=ee894449af) | Mar 13, 2021 |
| Dell          | Inspiron 7520               | [0054ef2511](https://bsd-hardware.info/?probe=0054ef2511) | Mar 13, 2021 |
| Dell          | Inspiron 3543               | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| Acer          | Aspire 4810T                | [14af887195](https://bsd-hardware.info/?probe=14af887195) | Mar 11, 2021 |
| Lenovo        | B41-80 80LG                 | [d598cc6240](https://bsd-hardware.info/?probe=d598cc6240) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| Lenovo        | ThinkPad T530 2392ASU       | [39f3a4f234](https://bsd-hardware.info/?probe=39f3a4f234) | Mar 09, 2021 |
| Toshiba       | Satellite Pro U400          | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| ASUSTek       | X556UA                      | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Dell          | Latitude E6500              | [d25dacc162](https://bsd-hardware.info/?probe=d25dacc162) | Mar 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [5e5632d9b6](https://bsd-hardware.info/?probe=5e5632d9b6) | Mar 07, 2021 |
| Lenovo        | 3000 N200 0769AP2           | [6b81593de9](https://bsd-hardware.info/?probe=6b81593de9) | Mar 06, 2021 |
| Dell          | Latitude E5570              | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b03cb1f957](https://bsd-hardware.info/?probe=b03cb1f957) | Mar 05, 2021 |
| HP            | EliteBook 820 G1            | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d129752b43](https://bsd-hardware.info/?probe=d129752b43) | Mar 04, 2021 |
| ASUSTek       | X55CR                       | [e887ee2ff5](https://bsd-hardware.info/?probe=e887ee2ff5) | Mar 03, 2021 |
| ASUSTek       | X55CR                       | [e1e4548d22](https://bsd-hardware.info/?probe=e1e4548d22) | Mar 03, 2021 |
| Acer          | Aspire 8730                 | [33e7d80b63](https://bsd-hardware.info/?probe=33e7d80b63) | Mar 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| ASUSTek       | G1S                         | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Hampoo        | B3W6_NA123C Reserved        | [bc138c0580](https://bsd-hardware.info/?probe=bc138c0580) | Feb 27, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| ASUSTek       | X555LAB                     | [b0364fffaf](https://bsd-hardware.info/?probe=b0364fffaf) | Feb 25, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [cbaa19611e](https://bsd-hardware.info/?probe=cbaa19611e) | Feb 24, 2021 |
| ASUSTek       | X555LAB                     | [45d57c2be0](https://bsd-hardware.info/?probe=45d57c2be0) | Feb 24, 2021 |
| Dell          | XPS 13 9333                 | [7c78b3d42a](https://bsd-hardware.info/?probe=7c78b3d42a) | Feb 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7f35ef7fa9](https://bsd-hardware.info/?probe=7f35ef7fa9) | Feb 23, 2021 |
| Lenovo        | Z50-70 20354                | [d3d9dc620f](https://bsd-hardware.info/?probe=d3d9dc620f) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Dell          | Latitude E7240              | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| Lenovo        | G470 20078                  | [b8e35aacdb](https://bsd-hardware.info/?probe=b8e35aacdb) | Feb 22, 2021 |
| Apple         | MacBookPro9,2               | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| ASUSTek       | X751LN                      | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [5d86c90af1](https://bsd-hardware.info/?probe=5d86c90af1) | Feb 21, 2021 |
| HP            | EliteBook 8540p             | [78d9a31074](https://bsd-hardware.info/?probe=78d9a31074) | Feb 21, 2021 |
| Toshiba       | Satellite U500              | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [aa98e655f3](https://bsd-hardware.info/?probe=aa98e655f3) | Feb 20, 2021 |
| Packard Be... | EasyNote TS11HR             | [1adcd64182](https://bsd-hardware.info/?probe=1adcd64182) | Feb 20, 2021 |
| ASUSTek       | X556UA                      | [6bbf9d6e29](https://bsd-hardware.info/?probe=6bbf9d6e29) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| Apple         | MacBook5,1                  | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| HP            | ProBook 440 G2              | [63038d613f](https://bsd-hardware.info/?probe=63038d613f) | Feb 19, 2021 |
| Acer          | Aspire ES1-533              | [045cf81f15](https://bsd-hardware.info/?probe=045cf81f15) | Feb 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| Lenovo        | ZIUS6                       | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Dell          | Inspiron 3521               | [10490aef33](https://bsd-hardware.info/?probe=10490aef33) | Feb 17, 2021 |
| Dell          | Latitude E6330              | [abe1869a95](https://bsd-hardware.info/?probe=abe1869a95) | Feb 17, 2021 |
| Fujitsu       | LIFEBOOK E744               | [fc2f449a8a](https://bsd-hardware.info/?probe=fc2f449a8a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [12c985b708](https://bsd-hardware.info/?probe=12c985b708) | Feb 17, 2021 |
| HP            | Pavilion Laptop 14-ce2xx... | [c355a6280b](https://bsd-hardware.info/?probe=c355a6280b) | Feb 17, 2021 |
| Dell          | Latitude 7390               | [3fe6eff89a](https://bsd-hardware.info/?probe=3fe6eff89a) | Feb 17, 2021 |
| Dell          | Venue 11 Pro 7140           | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| HP            | OMEN by Laptop              | [bb8beb97be](https://bsd-hardware.info/?probe=bb8beb97be) | Feb 17, 2021 |
| Dell          | Latitude E4300              | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Lenovo        | U310                        | [ccec69b736](https://bsd-hardware.info/?probe=ccec69b736) | Feb 16, 2021 |
| Lenovo        | U310                        | [83805a17c5](https://bsd-hardware.info/?probe=83805a17c5) | Feb 16, 2021 |
| Lenovo        | U310                        | [111385095d](https://bsd-hardware.info/?probe=111385095d) | Feb 16, 2021 |
| Apple         | MacBookAir4,2               | [7d8419c918](https://bsd-hardware.info/?probe=7d8419c918) | Feb 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [19f307ff6d](https://bsd-hardware.info/?probe=19f307ff6d) | Feb 16, 2021 |
| Lenovo        | ThinkPad T430 23427YU       | [79d1896352](https://bsd-hardware.info/?probe=79d1896352) | Feb 16, 2021 |
| eMachines     | eME732ZG                    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | EliteBook 8440p             | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Dell          | Inspiron 3421               | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| HP            | EliteBook 840 G3            | [0d35b2f5d8](https://bsd-hardware.info/?probe=0d35b2f5d8) | Feb 15, 2021 |
| ASUSTek       | X75VC                       | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5a393bc680](https://bsd-hardware.info/?probe=5a393bc680) | Feb 15, 2021 |
| Medion        | P6812                       | [c2c592bca8](https://bsd-hardware.info/?probe=c2c592bca8) | Feb 15, 2021 |
| Medion        | P6812                       | [afa43a6aab](https://bsd-hardware.info/?probe=afa43a6aab) | Feb 15, 2021 |
| Apple         | MacBookPro6,2               | [4d83633f97](https://bsd-hardware.info/?probe=4d83633f97) | Feb 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| Dell          | Latitude E4300              | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGC       | [f8ce633ed7](https://bsd-hardware.info/?probe=f8ce633ed7) | Feb 14, 2021 |
| HP            | ProBook 470 G4              | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| Lenovo        | ThinkPad T580 20LAS2TG00    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| Lenovo        | ThinkPad X200 7459ZLW       | [9fbba84be0](https://bsd-hardware.info/?probe=9fbba84be0) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [6da4116499](https://bsd-hardware.info/?probe=6da4116499) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [d212f58dd2](https://bsd-hardware.info/?probe=d212f58dd2) | Feb 13, 2021 |
| Dell          | Inspiron 3442               | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Samsung       | 910S3K/9310SK/910S3P/911... | [bdf7452299](https://bsd-hardware.info/?probe=bdf7452299) | Feb 13, 2021 |
| Apple         | MacBookPro8,1               | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude E6420              | [6bf1f5fe84](https://bsd-hardware.info/?probe=6bf1f5fe84) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| Clevo         | C41X0                       | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| Lenovo        | ThinkPad T460s 20F90037L... | [8325c794b3](https://bsd-hardware.info/?probe=8325c794b3) | Feb 12, 2021 |
| Apple         | MacBook5,2                  | [f1bc2178a9](https://bsd-hardware.info/?probe=f1bc2178a9) | Feb 12, 2021 |
| Lenovo        | ThinkPad T440s 20ARS10P0... | [bfee99bebd](https://bsd-hardware.info/?probe=bfee99bebd) | Feb 12, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2b0f35d7a9](https://bsd-hardware.info/?probe=2b0f35d7a9) | Feb 12, 2021 |
| Lenovo        | G500 20236                  | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | [3a73ecd855](https://bsd-hardware.info/?probe=3a73ecd855) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | [afd71fdf87](https://bsd-hardware.info/?probe=afd71fdf87) | Feb 12, 2021 |
| Dell          | Latitude 7380               | [1aa2a3a541](https://bsd-hardware.info/?probe=1aa2a3a541) | Feb 12, 2021 |
| Dell          | Latitude 7380               | [4814701c0e](https://bsd-hardware.info/?probe=4814701c0e) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| ASUSTek       | S551LN                      | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Dell          | Latitude 7280               | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Apple         | MacBook6,1                  | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| ASUSTek       | K50IJ                       | [8cd0aedd3a](https://bsd-hardware.info/?probe=8cd0aedd3a) | Feb 11, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [b2bf9a977b](https://bsd-hardware.info/?probe=b2bf9a977b) | Feb 11, 2021 |
| Dell          | Latitude 3410               | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z        | [270ca253a3](https://bsd-hardware.info/?probe=270ca253a3) | Feb 11, 2021 |
| Dell          | Inspiron 3521               | [b3569ebb39](https://bsd-hardware.info/?probe=b3569ebb39) | Feb 11, 2021 |
| Lenovo        | ThinkPad L470 20J5S09500    | [b17963cd30](https://bsd-hardware.info/?probe=b17963cd30) | Feb 10, 2021 |
| Lenovo        | ThinkPad T410 253722U       | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| ASUSTek       | K50IJ                       | [52a30e2478](https://bsd-hardware.info/?probe=52a30e2478) | Feb 10, 2021 |
| Toshiba       | TECRA M11                   | [468d16d496](https://bsd-hardware.info/?probe=468d16d496) | Feb 10, 2021 |
| Lenovo        | ThinkPad L512 25975XU       | [b4d22f4179](https://bsd-hardware.info/?probe=b4d22f4179) | Feb 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [ca369843a9](https://bsd-hardware.info/?probe=ca369843a9) | Feb 09, 2021 |
| ASUSTek       | X550LC                      | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell          | Latitude 5280               | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| ASUSTek       | X510UQ                      | [9da77349b9](https://bsd-hardware.info/?probe=9da77349b9) | Feb 07, 2021 |
| ASUSTek       | X502CA                      | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| Samsung       | 300E5M/300E5L               | [a667296c17](https://bsd-hardware.info/?probe=a667296c17) | Feb 03, 2021 |
| Fujitsu       | LIFEBOOK E753               | [37245aca21](https://bsd-hardware.info/?probe=37245aca21) | Feb 03, 2021 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [faa7becf82](https://bsd-hardware.info/?probe=faa7becf82) | Feb 01, 2021 |
| HP            | EliteBook 8570p             | [b3eb492602](https://bsd-hardware.info/?probe=b3eb492602) | Jan 31, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Clevo         | W55xEU                      | [e17285783e](https://bsd-hardware.info/?probe=e17285783e) | Jan 29, 2021 |
| Dell          | Latitude E6440              | [ed46852cfa](https://bsd-hardware.info/?probe=ed46852cfa) | Jan 26, 2021 |
| Dell          | Latitude E5570              | [bcf60e66d7](https://bsd-hardware.info/?probe=bcf60e66d7) | Jan 26, 2021 |
| Pegatron      | T12Ah                       | [e9c5982872](https://bsd-hardware.info/?probe=e9c5982872) | Jan 23, 2021 |
| Apple         | MacBook4,1                  | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| HP            | ProBook 470 G4              | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3444A... | [b659b95d1a](https://bsd-hardware.info/?probe=b659b95d1a) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| Lenovo        | ThinkPad T480s 20L8S6G21... | [a8508f91de](https://bsd-hardware.info/?probe=a8508f91de) | Jan 14, 2021 |
| HP            | ProBook 470 G4              | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| Lenovo        | ThinkPad T410 2537N96       | [8b54f3995d](https://bsd-hardware.info/?probe=8b54f3995d) | Jan 12, 2021 |
| Apple         | MacBookPro5,2               | [e2768ec168](https://bsd-hardware.info/?probe=e2768ec168) | Jan 10, 2021 |
| Apple         | MacBookPro5,2               | [56414400c1](https://bsd-hardware.info/?probe=56414400c1) | Jan 10, 2021 |
| HP            | EliteBook 8570p             | [97a3ac7e36](https://bsd-hardware.info/?probe=97a3ac7e36) | Jan 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34484... | [6133b45179](https://bsd-hardware.info/?probe=6133b45179) | Jan 05, 2021 |
| Fujitsu       | LIFEBOOK E744               | [9d50133c85](https://bsd-hardware.info/?probe=9d50133c85) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [1b0cc7506e](https://bsd-hardware.info/?probe=1b0cc7506e) | Jan 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3JY0... | [c51f274f90](https://bsd-hardware.info/?probe=c51f274f90) | Jan 02, 2021 |
| Apple         | MacBookPro10,2              | [e43a26be8d](https://bsd-hardware.info/?probe=e43a26be8d) | Jan 01, 2021 |
| HP            | EliteBook 8570p             | [60d9540d35](https://bsd-hardware.info/?probe=60d9540d35) | Dec 31, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/helloSystem/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| helloSystem 0.7.0 | 186       | 35.36%  |
| helloSystem 0.5.0 | 115       | 21.86%  |
| helloSystem 0.4.0 | 92        | 17.49%  |
| helloSystem 0.6.0 | 71        | 13.5%   |
| helloSystem 0.8.0 | 47        | 8.94%   |
| helloSystem 0.3.0 | 14        | 2.66%   |
| helloSystem       | 1         | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 492       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 492       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 485       | 98.18%  |
| GNOME        | 4         | 0.81%   |
| KDE5         | 3         | 0.61%   |
| XFCE         | 1         | 0.2%    |
| Cinnamon     | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 492       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 491       | 99.39%  |
| SDDM | 2         | 0.4%    |
| GDM  | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 472       | 95.74%  |
| de_DE   | 5         | 1.01%   |
| fr_FR   | 4         | 0.81%   |
| es_ES   | 4         | 0.81%   |
| C       | 3         | 0.61%   |
| it_IT   | 2         | 0.41%   |
| uk_UA   | 1         | 0.2%    |
| ru_RU   | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 440       | 88.53%  |
| BIOS | 57        | 11.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 379       | 75.65%  |
| Cd9660 | 122       | 24.35%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 491       | 99.8%   |
| MBR  | 1         | 0.2%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 153       | 31.1%   |
| Dell                | 73        | 14.84%  |
| Hewlett-Packard     | 70        | 14.23%  |
| ASUSTek Computer    | 42        | 8.54%   |
| Apple               | 34        | 6.91%   |
| Acer                | 29        | 5.89%   |
| Toshiba             | 17        | 3.46%   |
| Samsung Electronics | 10        | 2.03%   |
| Sony                | 7         | 1.42%   |
| Packard Bell        | 5         | 1.02%   |
| MSI                 | 5         | 1.02%   |
| Fujitsu             | 5         | 1.02%   |
| TUXEDO              | 4         | 0.81%   |
| eMachines           | 3         | 0.61%   |
| Timi                | 2         | 0.41%   |
| Panasonic           | 2         | 0.41%   |
| Notebook            | 2         | 0.41%   |
| LG Electronics      | 2         | 0.41%   |
| Itautec             | 2         | 0.41%   |
| Gateway             | 2         | 0.41%   |
| Alienware           | 2         | 0.41%   |
| WYSE                | 1         | 0.2%    |
| TWINHEAD            | 1         | 0.2%    |
| Semp Toshiba        | 1         | 0.2%    |
| Razer               | 1         | 0.2%    |
| Positivo            | 1         | 0.2%    |
| Philco              | 1         | 0.2%    |
| Pegatron            | 1         | 0.2%    |
| PCSTICK             | 1         | 0.2%    |
| NEC Computers       | 1         | 0.2%    |
| MouseComputer       | 1         | 0.2%    |
| Medion              | 1         | 0.2%    |
| Kraftway            | 1         | 0.2%    |
| HUAWEI              | 1         | 0.2%    |
| HASEE Computer      | 1         | 0.2%    |
| Hampoo              | 1         | 0.2%    |
| Google              | 1         | 0.2%    |
| Fujitsu Siemens     | 1         | 0.2%    |
| DNS                 | 1         | 0.2%    |
| Clevo               | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Apple MacBook4,1                        | 5         | 1.02%   |
| Unknown                                 | 4         | 0.81%   |
| HP Pavilion dv6                         | 3         | 0.61%   |
| Dell Precision 7710                     | 3         | 0.61%   |
| Dell Latitude 7280                      | 3         | 0.61%   |
| Dell Inspiron 15-3567                   | 3         | 0.61%   |
| Apple MacBookPro9,2                     | 3         | 0.61%   |
| Apple MacBookPro5,5                     | 3         | 0.61%   |
| Apple MacBook6,1                        | 3         | 0.61%   |
| TUXEDO Aura 15 Gen1                     | 2         | 0.41%   |
| Lenovo Z50-70 20354                     | 2         | 0.41%   |
| Lenovo ThinkPad X250 20CLS1WP01         | 2         | 0.41%   |
| Lenovo IdeaPad 110S-11IBR 80WG          | 2         | 0.41%   |
| Lenovo G550 2958                        | 2         | 0.41%   |
| Lenovo G500 20236                       | 2         | 0.41%   |
| HP ProBook 4540s                        | 2         | 0.41%   |
| HP Pavilion Notebook                    | 2         | 0.41%   |
| HP Pavilion g6                          | 2         | 0.41%   |
| HP EliteBook 840 G3                     | 2         | 0.41%   |
| HP 250 G6 Notebook PC                   | 2         | 0.41%   |
| HP 15                                   | 2         | 0.41%   |
| Gateway NE56R                           | 2         | 0.41%   |
| Fujitsu LIFEBOOK A555                   | 2         | 0.41%   |
| Dell Venue 11 Pro 7140                  | 2         | 0.41%   |
| Dell Latitude E7240                     | 2         | 0.41%   |
| Dell Latitude E6540                     | 2         | 0.41%   |
| Dell Latitude E6420                     | 2         | 0.41%   |
| Dell Latitude E6410                     | 2         | 0.41%   |
| Dell Latitude E5570                     | 2         | 0.41%   |
| Dell Latitude E5470                     | 2         | 0.41%   |
| Dell Latitude E4300                     | 2         | 0.41%   |
| Dell Latitude 7380                      | 2         | 0.41%   |
| Dell Inspiron 7520                      | 2         | 0.41%   |
| Dell Inspiron 3521                      | 2         | 0.41%   |
| Dell Inspiron 3442                      | 2         | 0.41%   |
| Dell Inspiron 15-3552                   | 2         | 0.41%   |
| ASUS X556UA                             | 2         | 0.41%   |
| ASUS X502CA                             | 2         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X712DAP_M712DA | 2         | 0.41%   |
| Apple MacBookPro8,1                     | 2         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 109       | 22.15%  |
| Dell Latitude         | 37        | 7.52%   |
| Acer Aspire           | 25        | 5.08%   |
| Dell Inspiron         | 21        | 4.27%   |
| HP Pavilion           | 19        | 3.86%   |
| Lenovo IdeaPad        | 15        | 3.05%   |
| HP EliteBook          | 11        | 2.24%   |
| Toshiba Satellite     | 10        | 2.03%   |
| HP ProBook            | 10        | 2.03%   |
| HP Laptop             | 6         | 1.22%   |
| Packard Bell EasyNote | 5         | 1.02%   |
| Fujitsu LIFEBOOK      | 5         | 1.02%   |
| Dell Precision        | 5         | 1.02%   |
| ASUS VivoBook         | 5         | 1.02%   |
| Apple MacBookPro5     | 5         | 1.02%   |
| Apple MacBook4        | 5         | 1.02%   |
| Toshiba PORTEGE       | 4         | 0.81%   |
| Lenovo Legion         | 4         | 0.81%   |
| Unknown               | 4         | 0.81%   |
| HP 250                | 3         | 0.61%   |
| HP 15                 | 3         | 0.61%   |
| Dell Vostro           | 3         | 0.61%   |
| Apple MacBookPro9     | 3         | 0.61%   |
| Apple MacBook6        | 3         | 0.61%   |
| Apple MacBook5        | 3         | 0.61%   |
| TUXEDO Aura           | 2         | 0.41%   |
| Toshiba dynabook      | 2         | 0.41%   |
| MSI GF65              | 2         | 0.41%   |
| Lenovo Z50-70         | 2         | 0.41%   |
| Lenovo Yoga           | 2         | 0.41%   |
| Lenovo G550           | 2         | 0.41%   |
| Lenovo G500           | 2         | 0.41%   |
| Itautec Infoway       | 2         | 0.41%   |
| HP OMEN               | 2         | 0.41%   |
| HP Compaq             | 2         | 0.41%   |
| Gateway NE56R         | 2         | 0.41%   |
| Dell XPS              | 2         | 0.41%   |
| Dell Venue            | 2         | 0.41%   |
| Dell Studio           | 2         | 0.41%   |
| ASUS X556UA           | 2         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 52        | 10.57%  |
| 2020    | 43        | 8.74%   |
| 2015    | 40        | 8.13%   |
| 2012    | 39        | 7.93%   |
| 2011    | 38        | 7.72%   |
| 2016    | 36        | 7.32%   |
| 2018    | 35        | 7.11%   |
| 2019    | 33        | 6.71%   |
| 2009    | 33        | 6.71%   |
| 2010    | 31        | 6.3%    |
| 2014    | 30        | 6.1%    |
| 2017    | 23        | 4.67%   |
| 2021    | 20        | 4.07%   |
| 2008    | 19        | 3.86%   |
| 2007    | 12        | 2.44%   |
| 2022    | 5         | 1.02%   |
| 2006    | 2         | 0.41%   |
| Unknown | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 492       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 490       | 99.59%  |
| Yes  | 2         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 195       | 39.63%  |
| 8.01-16.0   | 180       | 36.59%  |
| 16.01-24.0  | 79        | 16.06%  |
| 2.01-3.0    | 18        | 3.66%   |
| 32.01-64.0  | 9         | 1.83%   |
| 3.01-4.0    | 7         | 1.42%   |
| 24.01-32.0  | 3         | 0.61%   |
| 64.01-256.0 | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 331       | 67%     |
| 0.51-1.0  | 129       | 26.11%  |
| 1.01-2.0  | 20        | 4.05%   |
| 2.01-3.0  | 13        | 2.63%   |
| 8.01-16.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 384       | 76.95%  |
| 2      | 82        | 16.43%  |
| 0      | 26        | 5.21%   |
| 3      | 6         | 1.2%    |
| 4      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 270       | 54.66%  |
| Yes       | 224       | 45.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 439       | 89.23%  |
| No        | 53        | 10.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 484       | 98.37%  |
| No        | 8         | 1.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 323       | 65.25%  |
| No        | 172       | 34.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 71        | 14.37%  |
| Germany      | 48        | 9.72%   |
| Brazil       | 40        | 8.1%    |
| Italy        | 25        | 5.06%   |
| Russia       | 24        | 4.86%   |
| UK           | 21        | 4.25%   |
| Netherlands  | 19        | 3.85%   |
| China        | 19        | 3.85%   |
| Spain        | 17        | 3.44%   |
| France       | 14        | 2.83%   |
| Ukraine      | 13        | 2.63%   |
| Mexico       | 11        | 2.23%   |
| Poland       | 9         | 1.82%   |
| Indonesia    | 9         | 1.82%   |
| Hungary      | 9         | 1.82%   |
| Canada       | 9         | 1.82%   |
| Sweden       | 8         | 1.62%   |
| India        | 8         | 1.62%   |
| Romania      | 6         | 1.21%   |
| Australia    | 6         | 1.21%   |
| Portugal     | 5         | 1.01%   |
| Japan        | 5         | 1.01%   |
| Greece       | 5         | 1.01%   |
| Switzerland  | 4         | 0.81%   |
| Norway       | 4         | 0.81%   |
| New Zealand  | 4         | 0.81%   |
| Lithuania    | 4         | 0.81%   |
| Chile        | 4         | 0.81%   |
| Vietnam      | 3         | 0.61%   |
| UAE          | 3         | 0.61%   |
| South Korea  | 3         | 0.61%   |
| Slovakia     | 3         | 0.61%   |
| Finland      | 3         | 0.61%   |
| Czechia      | 3         | 0.61%   |
| Croatia      | 3         | 0.61%   |
| Colombia     | 3         | 0.61%   |
| Bulgaria     | 3         | 0.61%   |
| Turkey       | 2         | 0.4%    |
| Taiwan       | 2         | 0.4%    |
| South Africa | 2         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 6         | 1.16%   |
| Guangzhou         | 5         | 0.97%   |
| Wroclaw           | 4         | 0.78%   |
| Utrecht           | 4         | 0.78%   |
| Frankfurt am Main | 4         | 0.78%   |
| Curitiba          | 4         | 0.78%   |
| Berlin            | 4         | 0.78%   |
| Athens            | 4         | 0.78%   |
| Vilnius           | 3         | 0.58%   |
| Surabaya          | 3         | 0.58%   |
| New York          | 3         | 0.58%   |
| Leatherhead       | 3         | 0.58%   |
| Kyiv              | 3         | 0.58%   |
| Jakarta           | 3         | 0.58%   |
| Hanoi             | 3         | 0.58%   |
| Franconville      | 3         | 0.58%   |
| Budapest          | 3         | 0.58%   |
| Bengaluru         | 3         | 0.58%   |
| Amsterdam         | 3         | 0.58%   |
| Zurich            | 2         | 0.39%   |
| Washington        | 2         | 0.39%   |
| Warsaw            | 2         | 0.39%   |
| VÃ¤sterÃ¥s    | 2         | 0.39%   |
| Vancouver         | 2         | 0.39%   |
| Ufa               | 2         | 0.39%   |
| Turin             | 2         | 0.39%   |
| Tula de Allende   | 2         | 0.39%   |
| SГЈo Paulo      | 2         | 0.39%   |
| St Petersburg     | 2         | 0.39%   |
| SÃ£o Paulo      | 2         | 0.39%   |
| Santiago          | 2         | 0.39%   |
| Rome              | 2         | 0.39%   |
| Rio de Janeiro    | 2         | 0.39%   |
| Riga              | 2         | 0.39%   |
| Rho               | 2         | 0.39%   |
| Pleidelsheim      | 2         | 0.39%   |
| Oklahoma City     | 2         | 0.39%   |
| Oegstgeest        | 2         | 0.39%   |
| Odessa            | 2         | 0.39%   |
| Nesttun           | 2         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 86        | 92     | 15.22%  |
| Samsung Electronics | 83        | 98     | 14.69%  |
| Seagate             | 72        | 84     | 12.74%  |
| Toshiba             | 44        | 53     | 7.79%   |
| Kingston            | 37        | 41     | 6.55%   |
| Crucial             | 33        | 35     | 5.84%   |
| SanDisk             | 29        | 30     | 5.13%   |
| Hitachi             | 24        | 27     | 4.25%   |
| Intel               | 20        | 22     | 3.54%   |
| HGST                | 12        | 13     | 2.12%   |
| A-DATA Technology   | 12        | 13     | 2.12%   |
| Micron Technology   | 10        | 10     | 1.77%   |
| Fujitsu             | 9         | 10     | 1.59%   |
| SPCC                | 7         | 8      | 1.24%   |
| Apple               | 7         | 7      | 1.24%   |
| Transcend           | 5         | 6      | 0.88%   |
| SK hynix            | 5         | 5      | 0.88%   |
| OCZ                 | 5         | 5      | 0.88%   |
| LITEON              | 5         | 5      | 0.88%   |
| KingSpec            | 5         | 5      | 0.88%   |
| Intenso             | 5         | 5      | 0.88%   |
| Patriot             | 4         | 7      | 0.71%   |
| Corsair             | 4         | 4      | 0.71%   |
| SSSTC               | 3         | 3      | 0.53%   |
| Lexar               | 3         | 3      | 0.53%   |
| PNY                 | 2         | 2      | 0.35%   |
| LITEONIT            | 2         | 2      | 0.35%   |
| Leven               | 2         | 2      | 0.35%   |
| KIOXIA              | 2         | 2      | 0.35%   |
| Hewlett-Packard     | 2         | 3      | 0.35%   |
| China               | 2         | 2      | 0.35%   |
| Apacer              | 2         | 2      | 0.35%   |
| Zheino              | 1         | 1      | 0.18%   |
| Team                | 1         | 1      | 0.18%   |
| Smartbuy            | 1         | 1      | 0.18%   |
| Smart               | 1         | 1      | 0.18%   |
| Silicon Motion      | 1         | 1      | 0.18%   |
| Plextor             | 1         | 1      | 0.18%   |
| Pioneer             | 1         | 1      | 0.18%   |
| Netac               | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB              | 9         | 1.55%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 1.38%   |
| Toshiba MQ01ABF050 500GB            | 7         | 1.21%   |
| WDC WDS240G2G0A-00JH30 240GB        | 6         | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 1.03%   |
| Kingston SA400S37120G 120GB         | 6         | 1.03%   |
| Crucial CT500MX500SSD1 500GB        | 6         | 1.03%   |
| WDC WDS120G2G0A-00JH30 120GB        | 5         | 0.86%   |
| Seagate ST9500325AS 500GB           | 5         | 0.86%   |
| Samsung SSD 860 EVO 500GB           | 5         | 0.86%   |
| Samsung SSD 860 EVO 250GB           | 5         | 0.86%   |
| Kingston SA400S37240G 240GB         | 5         | 0.86%   |
| HGST HTS545050A7E680 500GB          | 5         | 0.86%   |
| Crucial CT240BX500SSD1 240GB        | 5         | 0.86%   |
| Seagate ST9500420AS 500GB           | 4         | 0.69%   |
| Samsung SSD 850 EVO 500GB           | 4         | 0.69%   |
| Samsung SSD 850 EVO 250GB           | 4         | 0.69%   |
| Samsung MZVLW256HEHP-000L7 256GB    | 4         | 0.69%   |
| Micron 1100 SATA 256GB              | 4         | 0.69%   |
| Seagate ST9320423AS 320GB           | 3         | 0.52%   |
| Seagate ST9320325AS 320GB           | 3         | 0.52%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.52%   |
| Seagate ST1000LM049-2GH172 1TB      | 3         | 0.52%   |
| Samsung SSD 860 EVO 1TB             | 3         | 0.52%   |
| Samsung SSD 840 EVO 250GB           | 3         | 0.52%   |
| Kingston SV300S37A120G 120GB        | 3         | 0.52%   |
| Kingston SA400S37480G 480GB         | 3         | 0.52%   |
| Hitachi HTS545032B9A300 320GB       | 3         | 0.52%   |
| Crucial CT1000MX500SSD1 1TB         | 3         | 0.52%   |
| A-DATA SU650 240GB                  | 3         | 0.52%   |
| WDC WDS120G1G0A-00SS50 120GB        | 2         | 0.34%   |
| WDC WDBNCE5000PNC 500GB             | 2         | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.34%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 0.34%   |
| WDC WD5000BPKT-00PK4T0 500GB        | 2         | 0.34%   |
| WDC WD3200BEVT-60ZCT1 320GB         | 2         | 0.34%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 0.34%   |
| WDC WD1600BEVS-08VAT2 160GB         | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 84     | 33.03%  |
| WDC                 | 59        | 62     | 27.06%  |
| Toshiba             | 35        | 44     | 16.06%  |
| Hitachi             | 24        | 27     | 11.01%  |
| HGST                | 12        | 13     | 5.5%    |
| Fujitsu             | 8         | 8      | 3.67%   |
| Samsung Electronics | 7         | 7      | 3.21%   |
| Apple               | 1         | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 62        | 69     | 21.38%  |
| Kingston            | 33        | 36     | 11.38%  |
| Crucial             | 31        | 33     | 10.69%  |
| SanDisk             | 29        | 30     | 10%     |
| WDC                 | 19        | 19     | 6.55%   |
| Intel               | 14        | 15     | 4.83%   |
| A-DATA Technology   | 8         | 9      | 2.76%   |
| SPCC                | 7         | 8      | 2.41%   |
| Micron Technology   | 6         | 6      | 2.07%   |
| Apple               | 6         | 6      | 2.07%   |
| Transcend           | 5         | 6      | 1.72%   |
| OCZ                 | 5         | 5      | 1.72%   |
| LITEON              | 5         | 5      | 1.72%   |
| KingSpec            | 5         | 5      | 1.72%   |
| Intenso             | 5         | 5      | 1.72%   |
| Patriot             | 4         | 7      | 1.38%   |
| Corsair             | 4         | 4      | 1.38%   |
| Toshiba             | 3         | 3      | 1.03%   |
| SK hynix            | 3         | 3      | 1.03%   |
| Lexar               | 3         | 3      | 1.03%   |
| PNY                 | 2         | 2      | 0.69%   |
| LITEONIT            | 2         | 2      | 0.69%   |
| Leven               | 2         | 2      | 0.69%   |
| Hewlett-Packard     | 2         | 3      | 0.69%   |
| China               | 2         | 2      | 0.69%   |
| Apacer              | 2         | 2      | 0.69%   |
| Zheino              | 1         | 1      | 0.34%   |
| Team                | 1         | 1      | 0.34%   |
| SSSTC               | 1         | 1      | 0.34%   |
| Smartbuy            | 1         | 1      | 0.34%   |
| Smart               | 1         | 1      | 0.34%   |
| Plextor             | 1         | 1      | 0.34%   |
| Pioneer             | 1         | 1      | 0.34%   |
| Netac               | 1         | 1      | 0.34%   |
| MyDigitalSSD        | 1         | 1      | 0.34%   |
| Mushkin             | 1         | 1      | 0.34%   |
| KingDian            | 1         | 1      | 0.34%   |
| Integral            | 1         | 1      | 0.34%   |
| INDMEM              | 1         | 1      | 0.34%   |
| HPE                 | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 259       | 313    | 49.15%  |
| HDD  | 205       | 246    | 38.9%   |
| NVMe | 63        | 70     | 11.95%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 431       | 559    | 87.25%  |
| NVMe | 63        | 70     | 12.75%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 358       | 450    | 78.51%  |
| 0.51-1.0   | 87        | 98     | 19.08%  |
| 1.01-2.0   | 10        | 10     | 2.19%   |
| 4.01-10.0  | 1         | 1      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 289       | 56.67%  |
| 101-250    | 102       | 20%     |
| 251-500    | 66        | 12.94%  |
| 501-1000   | 31        | 6.08%   |
| 51-100     | 10        | 1.96%   |
| 21-50      | 9         | 1.76%   |
| Unknown    | 2         | 0.39%   |
| 1001-2000  | 1         | 0.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 485       | 98.58%  |
| 21-50   | 2         | 0.41%   |
| 101-250 | 2         | 0.41%   |
| Unknown | 2         | 0.41%   |
| 51-100  | 1         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 4         | 4      | 3.31%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 2.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 4      | 2.48%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 1.65%   |
| Toshiba MQ01ABF050 500GB           | 2         | 4      | 1.65%   |
| Toshiba MQ01ABD075 752GB           | 2         | 2      | 1.65%   |
| Toshiba MK3261GSYN 320GB           | 2         | 4      | 1.65%   |
| Seagate ST9500325AS 500GB          | 2         | 3      | 1.65%   |
| Seagate ST9320423AS 320GB          | 2         | 2      | 1.65%   |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.65%   |
| Seagate ST9160821AS 160GB          | 2         | 2      | 1.65%   |
| Seagate ST9160412AS 160GB          | 2         | 2      | 1.65%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 2      | 1.65%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 2      | 1.65%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.65%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 2      | 1.65%   |
| Hitachi HTS545025B9SA02 250GB      | 2         | 4      | 1.65%   |
| Hitachi HTS541612J9SA00 120GB      | 2         | 2      | 1.65%   |
| WDC WDS200T2B0A 2TB                | 1         | 1      | 0.83%   |
| WDC WD5000LPVX-60V0TT0 500GB       | 1         | 1      | 0.83%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 0.83%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 0.83%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 2      | 0.83%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 0.83%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.83%   |
| WDC WD3200BPVT-55ZEST0 320GB       | 1         | 1      | 0.83%   |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 1      | 0.83%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 1      | 0.83%   |
| WDC WD3200BEKT-60V5T1 320GB        | 1         | 1      | 0.83%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 0.83%   |
| WDC WD1600BEVS-60RST0 160GB        | 1         | 1      | 0.83%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 0.83%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 0.83%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 0.83%   |
| WDC WD10JMVW-11AJGS0 1TB           | 1         | 1      | 0.83%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 0.83%   |
| Toshiba MQ02ABF050H-SSHD-8GB       | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD100H 1TB            | 1         | 1      | 0.83%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 39     | 28.1%   |
| Toshiba             | 22        | 28     | 18.18%  |
| WDC                 | 20        | 21     | 16.53%  |
| Hitachi             | 15        | 17     | 12.4%   |
| Samsung Electronics | 5         | 5      | 4.13%   |
| HGST                | 5         | 6      | 4.13%   |
| Kingston            | 3         | 3      | 2.48%   |
| Fujitsu             | 3         | 3      | 2.48%   |
| SanDisk             | 2         | 2      | 1.65%   |
| Micron Technology   | 2         | 2      | 1.65%   |
| LITEON              | 2         | 2      | 1.65%   |
| Corsair             | 2         | 2      | 1.65%   |
| SSSTC               | 1         | 1      | 0.83%   |
| Hewlett-Packard     | 1         | 1      | 0.83%   |
| Crucial             | 1         | 3      | 0.83%   |
| China               | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| AGI                 | 1         | 1      | 0.83%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 39     | 33.66%  |
| Toshiba             | 21        | 27     | 20.79%  |
| WDC                 | 19        | 20     | 18.81%  |
| Hitachi             | 15        | 17     | 14.85%  |
| HGST                | 5         | 6      | 4.95%   |
| Samsung Electronics | 3         | 3      | 2.97%   |
| Fujitsu             | 3         | 3      | 2.97%   |
| Apple               | 1         | 1      | 0.99%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 96        | 116    | 82.76%  |
| SSD  | 19        | 21     | 16.38%  |
| NVMe | 1         | 1      | 0.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| HPE MK000480GWUGF 480GB       | 1         | 1      | 50%     |
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HPE     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 384       | 487    | 76.34%  |
| Malfunc  | 115       | 138    | 22.86%  |
| Detected | 2         | 2      | 0.4%    |
| Failed   | 2         | 2      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 417       | 78.68%  |
| AMD                              | 40        | 7.55%   |
| Samsung Electronics              | 19        | 3.58%   |
| SanDisk                          | 11        | 2.08%   |
| Nvidia                           | 11        | 2.08%   |
| Toshiba                          | 4         | 0.75%   |
| Micron Technology                | 4         | 0.75%   |
| KIOXIA                           | 4         | 0.75%   |
| Silicon Motion                   | 3         | 0.57%   |
| Realtek Semiconductor            | 3         | 0.57%   |
| Kingston Technology Company      | 3         | 0.57%   |
| Solid State Storage Technology   | 2         | 0.38%   |
| SK hynix                         | 2         | 0.38%   |
| Silicon Integrated Systems [SiS] | 2         | 0.38%   |
| Micron/Crucial Technology        | 2         | 0.38%   |
| JMicron Technology               | 2         | 0.38%   |
| ADATA Technology                 | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 73        | 12.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 56        | 9.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 39        | 6.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 34        | 5.84%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 32        | 5.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 30        | 5.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 3.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 22        | 3.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 21        | 3.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 3.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 20        | 3.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 2.23%   |
| Unknown                                                                          | 13        | 2.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 2.06%   |
| Nvidia MCP79 AHCI Controller                                                     | 11        | 1.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 0.69%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 4         | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.52%   |
| Intel SSD 660P Series                                                            | 3         | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 3         | 0.52%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.52%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.52%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 3         | 0.52%   |
| AMD SB600 IDE                                                                    | 3         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 427       | 75.71%  |
| NVMe | 62        | 10.99%  |
| IDE  | 49        | 8.69%   |
| RAID | 26        | 4.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 448       | 91.06%  |
| AMD    | 44        | 8.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel CPU Version                    | 14        | 2.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 13        | 2.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 12        | 2.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 11        | 2.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 9         | 1.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 8         | 1.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 8         | 1.63%   |
| Intel Core i5-3317U CPU @ 1.70GHz    | 8         | 1.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 8         | 1.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 7         | 1.42%   |
| Intel Core i5 CPU M 520 @ 2.40GHz    | 7         | 1.42%   |
| Intel Core i3-6006U CPU @ 2.00GHz    | 7         | 1.42%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 6         | 1.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz    | 6         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz    | 6         | 1.22%   |
| Intel Core i3-3110M CPU @ 2.40GHz    | 6         | 1.22%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz | 6         | 1.22%   |
| Intel Genuine CPU                    | 5         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 5         | 1.02%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz | 5         | 1.02%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 5         | 1.02%   |
| Intel Core i7-7600U CPU @ 2.80GHz    | 4         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 4         | 0.81%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 4         | 0.81%   |
| Intel Core i7-3520M CPU @ 2.90GHz    | 4         | 0.81%   |
| Intel Core i5-4300M CPU @ 2.60GHz    | 4         | 0.81%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 4         | 0.81%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 4         | 0.81%   |
| Intel Core i3 CPU M 330 @ 2.13GHz    | 4         | 0.81%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz | 4         | 0.81%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz | 4         | 0.81%   |
| Intel Core 2 Duo                     | 4         | 0.81%   |
| Intel Atom CPU N450 @ 1.66GHz        | 4         | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 3         | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 3         | 0.61%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 3         | 0.61%   |
| Intel Core i7-4510U CPU @ 2.00GHz    | 3         | 0.61%   |
| Intel Core i7-3632QM CPU @ 2.20GHz   | 3         | 0.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz   | 3         | 0.61%   |
| Intel Core i7-3612QM CPU @ 2.10GHz   | 3         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 166       | 33.74%  |
| Intel Core i7           | 86        | 17.48%  |
| Intel Core 2 Duo        | 54        | 10.98%  |
| Intel Core i3           | 53        | 10.77%  |
| Intel Celeron           | 28        | 5.69%   |
| Other                   | 19        | 3.86%   |
| Intel Pentium           | 16        | 3.25%   |
| Intel Atom              | 8         | 1.63%   |
| AMD Ryzen 5             | 8         | 1.63%   |
| AMD Ryzen 7             | 7         | 1.42%   |
| AMD A6                  | 7         | 1.42%   |
| Intel Genuine           | 5         | 1.02%   |
| AMD E1                  | 4         | 0.81%   |
| Intel Pentium Dual-Core | 3         | 0.61%   |
| AMD Ryzen 3             | 3         | 0.61%   |
| Intel Pentium Silver    | 2         | 0.41%   |
| Intel Core M            | 2         | 0.41%   |
| Intel Core 2            | 2         | 0.41%   |
| AMD E2                  | 2         | 0.41%   |
| AMD E                   | 2         | 0.41%   |
| AMD A8                  | 2         | 0.41%   |
| AMD A10                 | 2         | 0.41%   |
| Intel Xeon              | 1         | 0.2%    |
| Intel Pentium M         | 1         | 0.2%    |
| Intel Core m3           | 1         | 0.2%    |
| Intel Core 2 Solo       | 1         | 0.2%    |
| Intel Celeron Dual-Core | 1         | 0.2%    |
| AMD Turion 64 X2 Mobile | 1         | 0.2%    |
| AMD Phenom II           | 1         | 0.2%    |
| AMD G                   | 1         | 0.2%    |
| AMD C-60                | 1         | 0.2%    |
| AMD Athlon II           | 1         | 0.2%    |
| AMD Athlon 64 X2        | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 319       | 64.84%  |
| 4       | 89        | 18.09%  |
| Unknown | 55        | 11.18%  |
| 6       | 10        | 2.03%   |
| 8       | 7         | 1.42%   |
| 1       | 5         | 1.02%   |
| 16      | 4         | 0.81%   |
| 12      | 3         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 469       | 95.33%  |
| 2       | 21        | 4.27%   |
| Unknown | 2         | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 319       | 64.84%  |
| 1       | 117       | 23.78%  |
| Unknown | 56        | 11.38%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 71        | 14.43%  |
| KabyLake      | 63        | 12.8%   |
| Penryn        | 54        | 10.98%  |
| SandyBridge   | 50        | 10.16%  |
| Haswell       | 50        | 10.16%  |
| Skylake       | 41        | 8.33%   |
| Westmere      | 36        | 7.32%   |
| Broadwell     | 22        | 4.47%   |
| Core          | 21        | 4.27%   |
| Silvermont    | 17        | 3.46%   |
| Zen 2         | 8         | 1.63%   |
| Zen+          | 7         | 1.42%   |
| Bobcat        | 7         | 1.42%   |
| Bonnell       | 6         | 1.22%   |
| Goldmont      | 5         | 1.02%   |
| CometLake     | 5         | 1.02%   |
| Jaguar        | 4         | 0.81%   |
| Excavator     | 4         | 0.81%   |
| TigerLake     | 3         | 0.61%   |
| Piledriver    | 3         | 0.61%   |
| Goldmont plus | 3         | 0.61%   |
| Zen 3         | 2         | 0.41%   |
| Zen           | 2         | 0.41%   |
| Puma          | 2         | 0.41%   |
| K8 Hammer     | 2         | 0.41%   |
| K10           | 2         | 0.41%   |
| Nehalem       | 1         | 0.2%    |
| K10 Llano     | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 394       | 68.4%   |
| Nvidia                           | 105       | 18.23%  |
| AMD                              | 76        | 13.19%  |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 11.28%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 8.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 35        | 5.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 5.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 4.71%   |
| Intel HD Graphics 620                                                                    | 25        | 4.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 4.04%   |
| Intel HD Graphics 5500                                                                   | 17        | 2.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 2.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 2.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 2.19%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 1.68%   |
| Intel HD Graphics 530                                                                    | 10        | 1.68%   |
| Nvidia C79 [GeForce 9400M]                                                               | 9         | 1.52%   |
| Intel UHD Graphics 620                                                                   | 9         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.35%   |
| AMD Renoir                                                                               | 8         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.18%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 6         | 1.01%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.01%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 5         | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.84%   |
| Nvidia TU117M                                                                            | 4         | 0.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.67%   |
| Intel HD Graphics 630                                                                    | 4         | 0.67%   |
| Intel HD Graphics 500                                                                    | 4         | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.51%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.51%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.51%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.51%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 3         | 0.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.51%   |
| Intel HD Graphics 5300                                                                   | 3         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 272       | 55.28%  |
| Intel + Nvidia | 58        | 11.79%  |
| 1 x AMD        | 50        | 10.16%  |
| 2 x Intel      | 45        | 9.15%   |
| 1 x Nvidia     | 39        | 7.93%   |
| Intel + AMD    | 18        | 3.66%   |
| AMD + Nvidia   | 6         | 1.22%   |
| 2 x Nvidia     | 2         | 0.41%   |
| 2 x AMD        | 1         | 0.2%    |
| 1 x SiS        | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 432       | 86.75%  |
| Unknown     | 42        | 8.43%   |
| Proprietary | 24        | 4.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 433       | 87.3%   |
| 0.01-0.5   | 43        | 8.67%   |
| 0.51-1.0   | 11        | 2.22%   |
| 1.01-2.0   | 5         | 1.01%   |
| 5.01-6.0   | 2         | 0.4%    |
| 3.01-4.0   | 2         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 94        | 20.98%  |
| AU Optronics            | 83        | 18.53%  |
| Chimei Innolux          | 65        | 14.51%  |
| Samsung Electronics     | 47        | 10.49%  |
| BOE                     | 42        | 9.38%   |
| Lenovo                  | 32        | 7.14%   |
| Apple                   | 23        | 5.13%   |
| Chi Mei Optoelectronics | 12        | 2.68%   |
| InfoVision              | 8         | 1.79%   |
| LG Philips              | 4         | 0.89%   |
| Sharp                   | 3         | 0.67%   |
| Philips                 | 3         | 0.67%   |
| Goldstar                | 3         | 0.67%   |
| Dell                    | 3         | 0.67%   |
| Sony                    | 2         | 0.45%   |
| PANDA                   | 2         | 0.45%   |
| Hewlett-Packard         | 2         | 0.45%   |
| Fujitsu Siemens         | 2         | 0.45%   |
| BenQ                    | 2         | 0.45%   |
| AOC                     | 2         | 0.45%   |
| Ancor Communications    | 2         | 0.45%   |
| Vestel Elektronik       | 1         | 0.22%   |
| Toshiba                 | 1         | 0.22%   |
| TMX                     | 1         | 0.22%   |
| SLD                     | 1         | 0.22%   |
| Nvidia                  | 1         | 0.22%   |
| Lenovo Group Limited    | 1         | 0.22%   |
| LED                     | 1         | 0.22%   |
| KTC                     | 1         | 0.22%   |
| HannStar                | 1         | 0.22%   |
| Eizo                    | 1         | 0.22%   |
| CPT                     | 1         | 0.22%   |
| Acer                    | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 6         | 1.33%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 6         | 1.33%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 5         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 4         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 4         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 0.89%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 0.89%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 4         | 0.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch  | 3         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 3         | 0.67%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 3         | 0.67%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 0.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 3         | 0.67%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 3         | 0.67%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch           | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch         | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 0.67%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.44%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 2         | 0.44%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 2         | 0.44%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch              | 2         | 0.44%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch               | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 2         | 0.44%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 204       | 46.15%  |
| 1920x1080 (FHD)    | 118       | 26.7%   |
| 1280x800 (WXGA)    | 45        | 10.18%  |
| 1600x900 (HD+)     | 32        | 7.24%   |
| 1440x900 (WXGA+)   | 7         | 1.58%   |
| 3840x2160 (4K)     | 5         | 1.13%   |
| 1280x1024 (SXGA)   | 5         | 1.13%   |
| 1024x600           | 5         | 1.13%   |
| 2560x1440 (QHD)    | 4         | 0.9%    |
| 1920x1200 (WUXGA)  | 4         | 0.9%    |
| 3200x1800 (QHD+)   | 3         | 0.68%   |
| 1024x768 (XGA)     | 3         | 0.68%   |
| 1920x540           | 2         | 0.45%   |
| 1680x1050 (WSXGA+) | 2         | 0.45%   |
| 3200x2000          | 1         | 0.23%   |
| 2560x1600          | 1         | 0.23%   |
| 2560x1080          | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 170       | 37.69%  |
| 13      | 138       | 30.6%   |
| 12      | 42        | 9.31%   |
| 17      | 22        | 4.88%   |
| 14      | 18        | 3.99%   |
| 11      | 14        | 3.1%    |
| 24      | 7         | 1.55%   |
| 10      | 7         | 1.55%   |
| 27      | 6         | 1.33%   |
| 19      | 5         | 1.11%   |
| 23      | 4         | 0.89%   |
| 21      | 3         | 0.67%   |
| 31      | 2         | 0.44%   |
| 22      | 2         | 0.44%   |
| 20      | 2         | 0.44%   |
| 18      | 2         | 0.44%   |
| 64      | 1         | 0.22%   |
| 54      | 1         | 0.22%   |
| 42      | 1         | 0.22%   |
| 40      | 1         | 0.22%   |
| 34      | 1         | 0.22%   |
| 16      | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 267       | 59.33%  |
| 201-300     | 123       | 27.33%  |
| 351-400     | 24        | 5.33%   |
| 501-600     | 15        | 3.33%   |
| 401-500     | 11        | 2.44%   |
| 601-700     | 4         | 0.89%   |
| 1001-1500   | 2         | 0.44%   |
| 801-900     | 1         | 0.22%   |
| 701-800     | 1         | 0.22%   |
| 901-1000    | 1         | 0.22%   |
| Unknown     | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 355       | 82.56%  |
| 16/10   | 59        | 13.72%  |
| 3/2     | 6         | 1.4%    |
| 5/4     | 5         | 1.16%   |
| 4/3     | 3         | 0.7%    |
| 21/9    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 134       | 29.71%  |
| 91-100         | 131       | 29.05%  |
| 61-70          | 42        | 9.31%   |
| 101-110        | 39        | 8.65%   |
| 71-80          | 22        | 4.88%   |
| 121-130        | 18        | 3.99%   |
| 201-250        | 14        | 3.1%    |
| 51-60          | 13        | 2.88%   |
| 41-50          | 7         | 1.55%   |
| 151-200        | 7         | 1.55%   |
| 301-350        | 6         | 1.33%   |
| 141-150        | 4         | 0.89%   |
| 351-500        | 3         | 0.67%   |
| More than 1000 | 2         | 0.44%   |
| 251-300        | 2         | 0.44%   |
| 131-140        | 2         | 0.44%   |
| 111-120        | 2         | 0.44%   |
| 501-1000       | 2         | 0.44%   |
| Unknown        | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 190       | 42.79%  |
| 121-160       | 171       | 38.51%  |
| 51-100        | 59        | 13.29%  |
| 161-240       | 20        | 4.5%    |
| More than 240 | 3         | 0.68%   |
| Unknown       | 1         | 0.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 404       | 81.12%  |
| 0     | 62        | 12.45%  |
| 2     | 32        | 6.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 279       | 35.95%  |
| Realtek Semiconductor             | 201       | 25.9%   |
| Qualcomm Atheros                  | 118       | 15.21%  |
| Broadcom                          | 80        | 10.31%  |
| Marvell Technology Group          | 19        | 2.45%   |
| Nvidia                            | 11        | 1.42%   |
| Ralink                            | 9         | 1.16%   |
| JMicron Technology                | 7         | 0.9%    |
| Sierra Wireless                   | 6         | 0.77%   |
| Ericsson Business Mobile Networks | 6         | 0.77%   |
| Ralink Technology                 | 5         | 0.64%   |
| Xiaomi                            | 4         | 0.52%   |
| Huawei Technologies               | 4         | 0.52%   |
| Samsung Electronics               | 3         | 0.39%   |
| Hewlett-Packard                   | 3         | 0.39%   |
| Edimax Technology                 | 3         | 0.39%   |
| TP-Link                           | 2         | 0.26%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.26%   |
| NetGear                           | 2         | 0.26%   |
| Google                            | 2         | 0.26%   |
| Dell                              | 2         | 0.26%   |
| D-Link System                     | 2         | 0.26%   |
| Toshiba                           | 1         | 0.13%   |
| OPPO Electronics                  | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.13%   |
| Mercucys                          | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| AboCom Systems                    | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 131       | 13.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 50        | 5.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 40        | 4.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 3.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 2.72%   |
| Intel Wireless 7260                                                     | 27        | 2.72%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.52%   |
| Intel Wireless 8260                                                     | 23        | 2.32%   |
| Intel Wireless 7265                                                     | 23        | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 1.71%   |
| Intel Centrino Advanced-N 6200                                          | 15        | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.41%   |
| Intel 82577LM Gigabit Network Connection                                | 14        | 1.41%   |
| Intel WiFi Link 5100                                                    | 13        | 1.31%   |
| Intel Ethernet Connection I218-LM                                       | 13        | 1.31%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 1.21%   |
| Nvidia MCP79 Ethernet                                                   | 11        | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                   | 11        | 1.11%   |
| Intel Ethernet Connection I217-LM                                       | 10        | 1.01%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 10        | 1.01%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 9         | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.91%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 9         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 0.81%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 0.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.81%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                                | 8         | 0.81%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 8         | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 268       | 51.54%  |
| Qualcomm Atheros      | 108       | 20.77%  |
| Broadcom              | 59        | 11.35%  |
| Realtek Semiconductor | 54        | 10.38%  |
| Ralink                | 9         | 1.73%   |
| Sierra Wireless       | 5         | 0.96%   |
| Ralink Technology     | 5         | 0.96%   |
| Edimax Technology     | 3         | 0.58%   |
| TP-Link               | 2         | 0.38%   |
| NetGear               | 2         | 0.38%   |
| Mercucys              | 1         | 0.19%   |
| Dell                  | 1         | 0.19%   |
| D-Link System         | 1         | 0.19%   |
| D-Link                | 1         | 0.19%   |
| AboCom Systems        | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 6.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 5.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 5.1%    |
| Intel Wireless 7260                                                     | 27        | 5.1%    |
| Intel Wireless 8265 / 8275                                              | 25        | 4.73%   |
| Intel Wireless 8260                                                     | 23        | 4.35%   |
| Intel Wireless 7265                                                     | 23        | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 3.21%   |
| Intel Centrino Advanced-N 6200                                          | 15        | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2.65%   |
| Intel WiFi Link 5100                                                    | 13        | 2.46%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 10        | 1.89%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 1.7%    |
| Broadcom BCM4321 802.11a/b/g/n                                          | 9         | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.51%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 1.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 1.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 8         | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 1.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 6         | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.95%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.95%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 4         | 0.76%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 4         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 183       | 40.76%  |
| Intel                            | 149       | 33.18%  |
| Broadcom                         | 33        | 7.35%   |
| Qualcomm Atheros                 | 32        | 7.13%   |
| Marvell Technology Group         | 19        | 4.23%   |
| Nvidia                           | 11        | 2.45%   |
| JMicron Technology               | 7         | 1.56%   |
| Xiaomi                           | 4         | 0.89%   |
| Samsung Electronics              | 3         | 0.67%   |
| Silicon Integrated Systems [SiS] | 2         | 0.45%   |
| Huawei Technologies              | 2         | 0.45%   |
| Google                           | 2         | 0.45%   |
| OPPO Electronics                 | 1         | 0.22%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 131       | 29.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 50        | 11.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 8.91%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 3.12%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 2.9%    |
| Intel Ethernet Connection I219-LM                                 | 12        | 2.67%   |
| Nvidia MCP79 Ethernet                                             | 11        | 2.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 2.45%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 2.23%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 9         | 2%      |
| Intel 82566MM Gigabit Network Connection                          | 8         | 1.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.34%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.34%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 1.34%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 1.34%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.67%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.67%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.45%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.45%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 485       | 51.6%   |
| Ethernet | 440       | 46.81%  |
| Modem    | 9         | 0.96%   |
| Unknown  | 6         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 376       | 49.67%  |
| Ethernet | 371       | 49.01%  |
| Modem    | 5         | 0.66%   |
| Unknown  | 5         | 0.66%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 426       | 86.59%  |
| 1     | 64        | 13.01%  |
| 0     | 2         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 470       | 94.76%  |
| Yes  | 26        | 5.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 148       | 45.26%  |
| Broadcom                        | 38        | 11.62%  |
| Apple                           | 31        | 9.48%   |
| Qualcomm Atheros Communications | 27        | 8.26%   |
| Realtek Semiconductor           | 20        | 6.12%   |
| Lite-On Technology              | 13        | 3.98%   |
| IMC Networks                    | 12        | 3.67%   |
| Foxconn / Hon Hai               | 8         | 2.45%   |
| Hewlett-Packard                 | 7         | 2.14%   |
| Ralink                          | 6         | 1.83%   |
| Dell                            | 6         | 1.83%   |
| Cambridge Silicon Radio         | 6         | 1.83%   |
| ASUSTek Computer                | 3         | 0.92%   |
| Alps Electric                   | 2         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 95        | 28.79%  |
| Apple Bluetooth Host Controller                             | 14        | 4.24%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 13        | 3.94%   |
| Intel AX201 Bluetooth                                       | 12        | 3.64%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 12        | 3.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 11        | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 3.03%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 8         | 2.42%   |
| Intel AX200 Bluetooth                                       | 8         | 2.42%   |
| Ralink RT3290 Bluetooth                                     | 6         | 1.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 1.82%   |
| Lite-On Atheros AR3012 Bluetooth                            | 5         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 1.52%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 1.52%   |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 1.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 5         | 1.52%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 5         | 1.52%   |
| Realtek RTL8723B Bluetooth                                  | 4         | 1.21%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 1.21%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 1.21%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 4         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                            | 4         | 1.21%   |
| Realtek  Bluetooth 4.0 Adapter                              | 3         | 0.91%   |
| Realtek Bluetooth Radio                                     | 3         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 3         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 3         | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 0.91%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 3         | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 0.91%   |
| Dell DW375 Bluetooth Module                                 | 3         | 0.91%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.61%   |
| Realtek  Bluetooth Adapter                                  | 2         | 0.61%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 0.61%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 0.61%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 2         | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 434       | 80.67%  |
| AMD                              | 57        | 10.59%  |
| Nvidia                           | 37        | 6.88%   |
| GN Netcom                        | 3         | 0.56%   |
| Silicon Integrated Systems [SiS] | 2         | 0.37%   |
| XMOS                             | 1         | 0.19%   |
| Texas Instruments                | 1         | 0.19%   |
| SteelSeries ApS                  | 1         | 0.19%   |
| Creative Technology              | 1         | 0.19%   |
| C-Media Electronics              | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 81        | 12.52%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 67        | 10.36%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 40        | 6.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 5.72%   |
| Intel 8 Series HD Audio Controller                                                                | 36        | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 5.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 35        | 5.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 3.55%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 3.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 3.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2.16%   |
| AMD FCH Azalia Controller                                                                         | 14        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.01%   |
| Nvidia MCP79 High Definition Audio                                                                | 11        | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.77%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.62%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.46%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.46%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.46%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 149       | 25.13%  |
| SK hynix                     | 117       | 19.73%  |
| Micron Technology            | 58        | 9.78%   |
| Kingston                     | 56        | 9.44%   |
| Unknown                      | 49        | 8.26%   |
| Elpida                       | 26        | 4.38%   |
| Crucial                      | 18        | 3.04%   |
| Ramaxel Technology           | 17        | 2.87%   |
| Smart                        | 14        | 2.36%   |
| Nanya Technology             | 14        | 2.36%   |
| Unknown                      | 12        | 2.02%   |
| A-DATA Technology            | 10        | 1.69%   |
| Teikon                       | 5         | 0.84%   |
| Corsair                      | 5         | 0.84%   |
| Apacer                       | 5         | 0.84%   |
| Smart Brazil                 | 4         | 0.67%   |
| Transcend                    | 3         | 0.51%   |
| High Bridge                  | 3         | 0.51%   |
| ASint Technology             | 3         | 0.51%   |
| Unknown (ABCD)               | 2         | 0.34%   |
| Team                         | 2         | 0.34%   |
| Silicon Power                | 2         | 0.34%   |
| PNY                          | 2         | 0.34%   |
| G.Skill                      | 2         | 0.34%   |
| 48spaces                     | 2         | 0.34%   |
| V-GeN                        | 1         | 0.17%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.17%   |
| Unknown (0x0809)             | 1         | 0.17%   |
| Unknown (08B5)               | 1         | 0.17%   |
| Toshiba                      | 1         | 0.17%   |
| SHARETRONIC                  | 1         | 0.17%   |
| Sesame                       | 1         | 0.17%   |
| PKI/Kingston                 | 1         | 0.17%   |
| Kingmax                      | 1         | 0.17%   |
| GOODRAM                      | 1         | 0.17%   |
| GeIL                         | 1         | 0.17%   |
| Axiom                        | 1         | 0.17%   |
| Avant                        | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 12        | 1.9%    |
| Unknown                                                 | 12        | 1.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 11        | 1.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 10        | 1.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 9         | 1.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 8         | 1.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 8         | 1.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 8         | 1.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 8         | 1.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 7         | 1.11%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 6         | 0.95%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s   | 6         | 0.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 6         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s           | 5         | 0.79%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 5         | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 5         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 5         | 0.79%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 4         | 0.63%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 4         | 0.63%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s   | 4         | 0.63%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s            | 4         | 0.63%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 4         | 0.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 4         | 0.63%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s   | 4         | 0.63%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 4         | 0.63%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s   | 4         | 0.63%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 4         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3                      | 3         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 3         | 0.48%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s   | 3         | 0.48%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s  | 3         | 0.48%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 0.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 3         | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 3         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s  | 3         | 0.48%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s             | 3         | 0.48%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 3         | 0.48%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 3         | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 3         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 3         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 288       | 59.26%  |
| DDR4    | 120       | 24.69%  |
| DDR2    | 53        | 10.91%  |
| LPDDR3  | 10        | 2.06%   |
| Unknown | 8         | 1.65%   |
| LPDDR4  | 3         | 0.62%   |
| DRAM    | 2         | 0.41%   |
| SDRAM   | 1         | 0.21%   |
| DDR     | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 460       | 94.46%  |
| Row Of Chips | 13        | 2.67%   |
| Chip         | 8         | 1.64%   |
| DIMM         | 4         | 0.82%   |
| Unknown      | 2         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 228       | 42.07%  |
| 2048  | 146       | 26.94%  |
| 8192  | 119       | 21.96%  |
| 16384 | 32        | 5.9%    |
| 1024  | 14        | 2.58%   |
| 32768 | 3         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 171       | 31.49%  |
| 1333    | 70        | 12.89%  |
| 2400    | 47        | 8.66%   |
| 2667    | 40        | 7.37%   |
| 1334    | 38        | 7%      |
| 667     | 38        | 7%      |
| 1067    | 32        | 5.89%   |
| 2133    | 31        | 5.71%   |
| 3200    | 23        | 4.24%   |
| 800     | 17        | 3.13%   |
| 1867    | 12        | 2.21%   |
| Unknown | 11        | 2.03%   |
| 975     | 4         | 0.74%   |
| 1066    | 3         | 0.55%   |
| 533     | 2         | 0.37%   |
| 333     | 2         | 0.37%   |
| 4267    | 1         | 0.18%   |
| 1866    | 1         | 0.18%   |

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
| Chicony Electronics                    | 100       | 27.55%  |
| Realtek Semiconductor                  | 37        | 10.19%  |
| Acer                                   | 35        | 9.64%   |
| Microdia                               | 30        | 8.26%   |
| IMC Networks                           | 28        | 7.71%   |
| Sunplus Innovation Technology          | 24        | 6.61%   |
| Suyin                                  | 15        | 4.13%   |
| Lite-On Technology                     | 14        | 3.86%   |
| Syntek                                 | 12        | 3.31%   |
| Quanta                                 | 9         | 2.48%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.2%    |
| Apple                                  | 8         | 2.2%    |
| Silicon Motion                         | 7         | 1.93%   |
| Lenovo                                 | 6         | 1.65%   |
| Alcor Micro                            | 6         | 1.65%   |
| Luxvisions Innotech Limited            | 4         | 1.1%    |
| ALi                                    | 4         | 1.1%    |
| Ricoh                                  | 3         | 0.83%   |
| Importek                               | 3         | 0.83%   |
| Z-Star Microelectronics                | 2         | 0.55%   |
| Logitech                               | 2         | 0.55%   |
| Tripath Technology                     | 1         | 0.28%   |
| Primax Electronics                     | 1         | 0.28%   |
| Holitech                               | 1         | 0.28%   |
| Foxconn / Hon Hai                      | 1         | 0.28%   |
| DigiTech                               | 1         | 0.28%   |
| Creative Technology                    | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 24        | 6.54%   |
| Realtek Realtek USB2.0 PC Camera          | 11        | 3%      |
| Realtek Integrated_Webcam_HD              | 11        | 3%      |
| Acer Integrated Camera                    | 11        | 3%      |
| Lite-On Integrated Camera                 | 9         | 2.45%   |
| Sunplus Integrated_Webcam_HD              | 8         | 2.18%   |
| Chicony HD WebCam                         | 8         | 2.18%   |
| Acer Lenovo EasyCamera                    | 7         | 1.91%   |
| Syntek Lenovo EasyCamera                  | 6         | 1.63%   |
| Microdia Integrated_Webcam_HD             | 6         | 1.63%   |
| Microdia Integrated Webcam                | 6         | 1.63%   |
| IMC Networks USB2.0 HD UVC WebCam         | 6         | 1.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 6         | 1.63%   |
| Realtek USB Camera                        | 5         | 1.36%   |
| IMC Networks Integrated Camera            | 5         | 1.36%   |
| Chicony HP HD Webcam [Fixed]              | 5         | 1.36%   |
| Apple FaceTime HD Camera                  | 5         | 1.36%   |
| Syntek EasyCamera                         | 4         | 1.09%   |
| Microdia Laptop_Integrated_Webcam_HD      | 4         | 1.09%   |
| Microdia Dell Laptop Integrated Webcam HD | 4         | 1.09%   |
| Lenovo Integrated Webcam [R5U877]         | 4         | 1.09%   |
| Chicony USB2.0 VGA UVC WebCam             | 4         | 1.09%   |
| Chicony Lenovo EasyCamera                 | 4         | 1.09%   |
| Acer ThinkPad Integrated Camera           | 4         | 1.09%   |
| Suyin Integrated_Webcam_HD                | 3         | 0.82%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 3         | 0.82%   |
| Sunplus Integrated Camera                 | 3         | 0.82%   |
| Quanta HP Webcam                          | 3         | 0.82%   |
| IMC Networks EasyCamera                   | 3         | 0.82%   |
| Chicony UVC 1.00 device HD UVC WebCam     | 3         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam              | 3         | 0.82%   |
| Chicony Integrated Camera [ThinkPad]      | 3         | 0.82%   |
| Chicony HD WebCam (Acer)                  | 3         | 0.82%   |
| Chicony FJ Camera                         | 3         | 0.82%   |
| Chicony EasyCamera                        | 3         | 0.82%   |
| Chicony Chicony USB 2.0 Camera            | 3         | 0.82%   |
| Alcor Micro Acer Integrated Webcam        | 3         | 0.82%   |
| Acer SunplusIT INC. Integrated Camera     | 3         | 0.82%   |
| Acer Lenovo Integrated Webcam             | 3         | 0.82%   |
| Acer HD Webcam                            | 3         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 40        | 44.44%  |
| AuthenTec                  | 16        | 17.78%  |
| Upek                       | 15        | 16.67%  |
| STMicroelectronics         | 7         | 7.78%   |
| Synaptics                  | 4         | 4.44%   |
| Broadcom                   | 3         | 3.33%   |
| Shenzhen Goodix Technology | 2         | 2.22%   |
| LighTuning Technology      | 2         | 2.22%   |
| Elan Microelectronics      | 1         | 1.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 13        | 14.44%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 9         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                   | 7         | 7.78%   |
| STMicroelectronics Fingerprint Reader                                        | 7         | 7.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 5         | 5.56%   |
| Validity Sensors Synaptics WBDI                                              | 5         | 5.56%   |
| AuthenTec AES2810                                                            | 4         | 4.44%   |
| AuthenTec AES1600                                                            | 4         | 4.44%   |
| Validity Sensors VFS491                                                      | 3         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.33%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 3         | 3.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 3.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 2.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 2.22%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 2         | 2.22%   |
| Validity Sensors Fingerprint scanner                                         | 2         | 2.22%   |
| Upek TCS5B Fingerprint sensor                                                | 2         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 2.22%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 2.22%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 1.11%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 1.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 1.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 1.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 1.11%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 1.11%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 1.11%   |
| AuthenTec AES1660 Fingerprint Sensor                                         | 1         | 1.11%   |
| Unknown                                                                      | 1         | 1.11%   |

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
| 2     | 162       | 31.95%  |
| 1     | 155       | 30.57%  |
| 3     | 77        | 15.19%  |
| 0     | 77        | 15.19%  |
| 4     | 29        | 5.72%   |
| 5     | 5         | 0.99%   |
| 6     | 2         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 348       | 42.96%  |
| Card reader              | 143       | 17.65%  |
| Bluetooth                | 97        | 11.98%  |
| Net/wireless             | 94        | 11.6%   |
| Fingerprint reader       | 88        | 10.86%  |
| Firewire controller      | 17        | 2.1%    |
| Storage                  | 8         | 0.99%   |
| Sound                    | 5         | 0.62%   |
| Network                  | 4         | 0.49%   |
| Storage/raid             | 2         | 0.25%   |
| Net/ethernet             | 2         | 0.25%   |
| Dvb card                 | 2         | 0.25%   |

