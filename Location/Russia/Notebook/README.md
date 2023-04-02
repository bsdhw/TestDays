BSD in Russia - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

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

Total: 248

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Dell          | G5 5587                     | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| Timi          | TM1607                      | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| MSI           | PS63 Modern 8M              | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| ASUSTek       | K50IN                       | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Acer          | Aspire A114-33              | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| ASUSTek       | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| IBM           | ThinkPad H 1846AQG          | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Kraftway      | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Acer          | Aspire A715-75G             | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| eMachines     | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Acer          | Aspire ES1-132              | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| Acer          | Extensa 2540                | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| ASUSTek       | 1225B                       | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Samsung       | N145P/N250P/N260P           | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Samsung       | N150P                       | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Dell          | Latitude 3410               | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| HP            | 255 G3                      | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| HP            | 255 G3                      | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| HP            | Compaq 6820s                | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Dell          | Studio 1537                 | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Apple         | MacBook5,1                  | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Apple         | MacBook5,1                  | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| ASUSTek       | X101CH                      | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Samsung       | N145P/N250P/N260P           | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| Sony          | SVP1321V9RB                 | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| Sony          | VGN-S150(UC)                | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Toshiba       | Satellite M100              | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| Sony          | SVP1321V9RB                 | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Dell          | Latitude C400               | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [0e99e72ec9](https://bsd-hardware.info/?probe=0e99e72ec9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b9477154b9](https://bsd-hardware.info/?probe=b9477154b9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [19d1c3d086](https://bsd-hardware.info/?probe=19d1c3d086) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bc97c1c0fa](https://bsd-hardware.info/?probe=bc97c1c0fa) | Aug 13, 2020 |
| Dell          | Inspiron 1501               | [9ee3e7cbc2](https://bsd-hardware.info/?probe=9ee3e7cbc2) | Aug 11, 2020 |
| Dell          | Inspiron 1501               | [807aae7095](https://bsd-hardware.info/?probe=807aae7095) | Aug 11, 2020 |
| Dell          | Inspiron 1525               | [d08ea3542e](https://bsd-hardware.info/?probe=d08ea3542e) | Aug 05, 2020 |
| Dell          | Latitude 7490               | [b1d5e8c619](https://bsd-hardware.info/?probe=b1d5e8c619) | Aug 05, 2020 |
| HP            | ProBook 440 G6              | [0227811abb](https://bsd-hardware.info/?probe=0227811abb) | Aug 05, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| HP            | ProBook 430 G2              | [3a33aa0d8c](https://bsd-hardware.info/?probe=3a33aa0d8c) | Jun 30, 2020 |
| HP            | ProBook 430 G2              | [365ebdaf9c](https://bsd-hardware.info/?probe=365ebdaf9c) | Jun 30, 2020 |
| Lenovo        | G570 20079                  | [220313b249](https://bsd-hardware.info/?probe=220313b249) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [c7f3bf660a](https://bsd-hardware.info/?probe=c7f3bf660a) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [b84d1b49d8](https://bsd-hardware.info/?probe=b84d1b49d8) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [0cc3c53651](https://bsd-hardware.info/?probe=0cc3c53651) | Jun 02, 2020 |
| Dell          | Latitude E5400              | [54854343e4](https://bsd-hardware.info/?probe=54854343e4) | Jun 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [68840c222b](https://bsd-hardware.info/?probe=68840c222b) | May 28, 2020 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | [c65cdb97de](https://bsd-hardware.info/?probe=c65cdb97de) | May 28, 2020 |
| Acer          | Aspire 4820T                | [239eea83c6](https://bsd-hardware.info/?probe=239eea83c6) | May 26, 2020 |
| ASUSTek       | GL553VE                     | [dc7bb56859](https://bsd-hardware.info/?probe=dc7bb56859) | May 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9728d93191](https://bsd-hardware.info/?probe=9728d93191) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [709a3db7de](https://bsd-hardware.info/?probe=709a3db7de) | May 25, 2020 |
| Lenovo        | G570 20079                  | [0b7b4083bd](https://bsd-hardware.info/?probe=0b7b4083bd) | May 22, 2020 |
| Lenovo        | G570 20079                  | [f7cb1aa38d](https://bsd-hardware.info/?probe=f7cb1aa38d) | May 21, 2020 |
| Dell          | Latitude E6530              | [04cd35a77b](https://bsd-hardware.info/?probe=04cd35a77b) | May 21, 2020 |
| Lenovo        | G570 20079                  | [dc3c3cff26](https://bsd-hardware.info/?probe=dc3c3cff26) | May 21, 2020 |
| Lenovo        | G570 20079                  | [807f3398e3](https://bsd-hardware.info/?probe=807f3398e3) | May 20, 2020 |
| Lenovo        | G570 20079                  | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | [ab53dfc003](https://bsd-hardware.info/?probe=ab53dfc003) | May 19, 2020 |
| Lenovo        | G570 20079                  | [d3f180e9ef](https://bsd-hardware.info/?probe=d3f180e9ef) | May 17, 2020 |
| Lenovo        | G570 20079                  | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo        | G570 20079                  | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| Lenovo        | G570 20079                  | [4a419328b8](https://bsd-hardware.info/?probe=4a419328b8) | May 16, 2020 |
| ASUSTek       | A3L                         | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| ASUSTek       | A3L                         | [0d292bca2f](https://bsd-hardware.info/?probe=0d292bca2f) | May 15, 2020 |
| ASUSTek       | X71SL                       | [2fd46cb7c7](https://bsd-hardware.info/?probe=2fd46cb7c7) | May 15, 2020 |
| ASUSTek       | X71SL                       | [8a027d0a73](https://bsd-hardware.info/?probe=8a027d0a73) | May 14, 2020 |
| Dell          | Latitude E6530              | [2c5eec6613](https://bsd-hardware.info/?probe=2c5eec6613) | May 09, 2020 |
| Dell          | Latitude E6530              | [1542f8e5a8](https://bsd-hardware.info/?probe=1542f8e5a8) | May 09, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| ASUSTek       | X71SL                       | [7b4d0958ec](https://bsd-hardware.info/?probe=7b4d0958ec) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| ASUSTek       | X71SL                       | [ab5297a63d](https://bsd-hardware.info/?probe=ab5297a63d) | May 07, 2020 |
| ASUSTek       | X71SL                       | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |
| ASUSTek       | X71SL                       | [2aac4c3564](https://bsd-hardware.info/?probe=2aac4c3564) | May 07, 2020 |
| Lenovo        | G570 20079                  | [4909d93faf](https://bsd-hardware.info/?probe=4909d93faf) | May 06, 2020 |
| Lenovo        | G570 20079                  | [fb9c475d48](https://bsd-hardware.info/?probe=fb9c475d48) | May 06, 2020 |
| Lenovo        | G570 20079                  | [2efd2c4c7a](https://bsd-hardware.info/?probe=2efd2c4c7a) | May 06, 2020 |
| Lenovo        | G570 20079                  | [f1c2bcae9d](https://bsd-hardware.info/?probe=f1c2bcae9d) | May 06, 2020 |
| ASUSTek       | A3L                         | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |
| Lenovo        | G570 20079                  | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |
| ASUSTek       | X71SL                       | [b48cb0f2ce](https://bsd-hardware.info/?probe=b48cb0f2ce) | May 05, 2020 |
| Lenovo        | G570 20079                  | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 15        | 8.93%   |
| OpenBSD 6.8          | 10        | 5.95%   |
| helloSystem 0.8.0    | 10        | 5.95%   |
| FreeBSD 13.1         | 10        | 5.95%   |
| helloSystem 0.8.1    | 8         | 4.76%   |
| NomadBSD 1.3.2       | 7         | 4.17%   |
| FreeBSD 14.0-CURRENT | 7         | 4.17%   |
| FreeBSD 13.1-p5      | 7         | 4.17%   |
| FreeBSD 13.0         | 6         | 3.57%   |
| OpenBSD 7.1          | 5         | 2.98%   |
| FreeBSD 13.0-CURRENT | 5         | 2.98%   |
| NomadBSD 5806f915    | 4         | 2.38%   |
| helloSystem 0.6.0    | 4         | 2.38%   |
| FreeBSD 12.1-STABLE  | 4         | 2.38%   |
| OpenBSD 6.9          | 3         | 1.79%   |
| GhostBSD 20.04.02    | 3         | 1.79%   |
| FreeBSD 13.1-p1      | 3         | 1.79%   |
| FreeBSD 12.2-p4      | 3         | 1.79%   |
| OpenBSD 6.7          | 2         | 1.19%   |
| helloSystem 0.8.2    | 2         | 1.19%   |
| FreeBSD 13.2-RC3     | 2         | 1.19%   |
| FreeBSD 13.0-p3      | 2         | 1.19%   |
| FreeBSD 12.3-STABLE  | 2         | 1.19%   |
| FreeBSD 12.2-STABLE  | 2         | 1.19%   |
| FreeBSD 12.2-p3      | 2         | 1.19%   |
| FreeBSD 12.1-p8      | 2         | 1.19%   |
| FreeBSD 12.1-p7      | 2         | 1.19%   |
| FreeBSD 12.1-p5      | 2         | 1.19%   |
| OS108 9.0            | 1         | 0.6%    |
| OpenBSD 7.2          | 1         | 0.6%    |
| OpenBSD 7.0          | 1         | 0.6%    |
| NomadBSD 20221130    | 1         | 0.6%    |
| NomadBSD 1.4         | 1         | 0.6%    |
| NomadBSD 1.3.1       | 1         | 0.6%    |
| NetBSD 9.99.94       | 1         | 0.6%    |
| NetBSD 9.1           | 1         | 0.6%    |
| NetBSD 7.2           | 1         | 0.6%    |
| LibertyBSD 6.1       | 1         | 0.6%    |
| helloSystem 0.3.0    | 1         | 0.6%    |
| GhostBSD 21.08.27    | 1         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 76        | 48.41%  |
| helloSystem | 38        | 24.2%   |
| OpenBSD     | 21        | 13.38%  |
| NomadBSD    | 13        | 8.28%   |
| GhostBSD    | 4         | 2.55%   |
| NetBSD      | 3         | 1.91%   |
| OS108       | 1         | 0.64%   |
| LibertyBSD  | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 134       | 89.93%  |
| i386  | 15        | 10.07%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 43        | 27.39%  |
| KDE5          | 20        | 12.74%  |
| XFCE          | 15        | 9.55%   |
| Console       | 15        | 9.55%   |
| Openbox       | 13        | 8.28%   |
| fvwm          | 13        | 8.28%   |
| GNOME         | 8         | 5.1%    |
| MATE          | 7         | 4.46%   |
| TWM           | 6         | 3.82%   |
| IceWM         | 3         | 1.91%   |
| i3            | 3         | 1.91%   |
| LXQt          | 2         | 1.27%   |
| LXDE          | 2         | 1.27%   |
| AwesomeWM     | 2         | 1.27%   |
| xinitrc       | 1         | 0.64%   |
| StumpWM       | 1         | 0.64%   |
| Lumina        | 1         | 0.64%   |
| Enlightenment | 1         | 0.64%   |
| DWM           | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 132       | 85.71%  |
| Console | 20        | 12.99%  |
| Wayland | 2         | 1.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 62        | 40.26%  |
| Console | 54        | 35.06%  |
| SDDM    | 19        | 12.34%  |
| LightDM | 7         | 4.55%   |
| XDM     | 6         | 3.9%    |
| GDM     | 4         | 2.6%    |
| PCDM    | 1         | 0.65%   |
| Ly      | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 50        | 32.05%  |
| en_US   | 40        | 25.64%  |
| Unknown | 30        | 19.23%  |
| C       | 28        | 17.95%  |
| ru      | 4         | 2.56%   |
| en_GB   | 1         | 0.64%   |
| en_EN   | 1         | 0.64%   |
| en      | 1         | 0.64%   |
| ba_RU   | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 109       | 70.78%  |
| BIOS | 45        | 29.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 64        | 41.03%  |
| Ufs    | 53        | 33.97%  |
| Ffs    | 22        | 14.1%   |
| Cd9660 | 16        | 10.26%  |
| Xfs    | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 120       | 79.47%  |
| MBR     | 28        | 18.54%  |
| Unknown | 2         | 1.32%   |
| BSD     | 1         | 0.66%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 41        | 27.52%  |
| Dell                | 19        | 12.75%  |
| ASUSTek Computer    | 16        | 10.74%  |
| Hewlett-Packard     | 15        | 10.07%  |
| Acer                | 15        | 10.07%  |
| Samsung Electronics | 7         | 4.7%    |
| Sony                | 6         | 4.03%   |
| HUAWEI              | 4         | 2.68%   |
| Toshiba             | 3         | 2.01%   |
| Timi                | 3         | 2.01%   |
| MSI                 | 3         | 2.01%   |
| IBM                 | 2         | 1.34%   |
| F-Plus Mobile       | 2         | 1.34%   |
| Apple               | 2         | 1.34%   |
| Panasonic           | 1         | 0.67%   |
| Packard Bell        | 1         | 0.67%   |
| Kraftway            | 1         | 0.67%   |
| Irbis               | 1         | 0.67%   |
| IP3 Technology      | 1         | 0.67%   |
| Intel               | 1         | 0.67%   |
| HMT                 | 1         | 0.67%   |
| Google              | 1         | 0.67%   |
| eMachines           | 1         | 0.67%   |
| DNS                 | 1         | 0.67%   |
| DEXP                | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung N145P/N250P/N260P                | 2         | 1.34%   |
| MSI PS63 Modern 8M                       | 2         | 1.34%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 2         | 1.34%   |
| Lenovo IdeaPad 320-15ISK 80XH            | 2         | 1.34%   |
| HUAWEI CREM-WXX9                         | 2         | 1.34%   |
| F-Plus Mobile FLAPTOP r                  | 2         | 1.34%   |
| Dell Inspiron 15 7000 Gaming             | 2         | 1.34%   |
| Acer Aspire 4820T                        | 2         | 1.34%   |
| Toshiba Satellite M100                   | 1         | 0.67%   |
| Toshiba Satellite L40                    | 1         | 0.67%   |
| Toshiba Satellite A300                   | 1         | 0.67%   |
| Timi TM1612                              | 1         | 0.67%   |
| Timi TM1607                              | 1         | 0.67%   |
| Timi Redmi Book Pro 14 2022              | 1         | 0.67%   |
| Sony VPCX115KX                           | 1         | 0.67%   |
| Sony VPCM13M1R                           | 1         | 0.67%   |
| Sony VGN-UX1XRN                          | 1         | 0.67%   |
| Sony VGN-S150(UC)                        | 1         | 0.67%   |
| Sony SVP1321V9RB                         | 1         | 0.67%   |
| Sony SVE1713S1RW                         | 1         | 0.67%   |
| Samsung R530/R730/R540                   | 1         | 0.67%   |
| Samsung R468/R418                        | 1         | 0.67%   |
| Samsung Q430/Q530                        | 1         | 0.67%   |
| Samsung N150P                            | 1         | 0.67%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.67%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.67%   |
| Packard Bell EasyNote TE69HW             | 1         | 0.67%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.67%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.67%   |
| Lenovo V580 20147                        | 1         | 0.67%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V      | 1         | 0.67%   |
| Lenovo ThinkPad X240 20AMA52RUK          | 1         | 0.67%   |
| Lenovo ThinkPad X240 20AL00DKRT          | 1         | 0.67%   |
| Lenovo ThinkPad X230 2325Y36             | 1         | 0.67%   |
| Lenovo ThinkPad X220 4291LF6             | 1         | 0.67%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT     | 1         | 0.67%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT     | 1         | 0.67%   |
| Lenovo ThinkPad X121e 3053A52            | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES42E0L | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 23        | 15.44%  |
| Acer Aspire            | 13        | 8.72%   |
| Lenovo IdeaPad         | 11        | 7.38%   |
| Dell Latitude          | 7         | 4.7%    |
| Dell Inspiron          | 7         | 4.7%    |
| HP ProBook             | 6         | 4.03%   |
| Toshiba Satellite      | 3         | 2.01%   |
| HP Laptop              | 3         | 2.01%   |
| ASUS VivoBook          | 3         | 2.01%   |
| Samsung N145P          | 2         | 1.34%   |
| MSI PS63               | 2         | 1.34%   |
| IBM ThinkPad           | 2         | 1.34%   |
| HUAWEI CREM-WXX9       | 2         | 1.34%   |
| F-Plus Mobile FLAPTOP  | 2         | 1.34%   |
| Acer Extensa           | 2         | 1.34%   |
| Timi TM1612            | 1         | 0.67%   |
| Timi TM1607            | 1         | 0.67%   |
| Timi Redmi             | 1         | 0.67%   |
| Sony VPCX115KX         | 1         | 0.67%   |
| Sony VPCM13M1R         | 1         | 0.67%   |
| Sony VGN-UX1XRN        | 1         | 0.67%   |
| Sony VGN-S150(UC)      | 1         | 0.67%   |
| Sony SVP1321V9RB       | 1         | 0.67%   |
| Sony SVE1713S1RW       | 1         | 0.67%   |
| Samsung R530           | 1         | 0.67%   |
| Samsung R468           | 1         | 0.67%   |
| Samsung Q430           | 1         | 0.67%   |
| Samsung N150P          | 1         | 0.67%   |
| Samsung 305E4A         | 1         | 0.67%   |
| Panasonic CF-19AHNC8FN | 1         | 0.67%   |
| Packard Bell EasyNote  | 1         | 0.67%   |
| MSI GE75               | 1         | 0.67%   |
| Lenovo Yoga            | 1         | 0.67%   |
| Lenovo V580            | 1         | 0.67%   |
| Lenovo ThinkBook       | 1         | 0.67%   |
| Lenovo S20-30          | 1         | 0.67%   |
| Lenovo G570            | 1         | 0.67%   |
| Lenovo E31-80          | 1         | 0.67%   |
| Lenovo B50-30          | 1         | 0.67%   |
| Kraftway KW10T         | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 19        | 12.75%  |
| 2020 | 17        | 11.41%  |
| 2011 | 14        | 9.4%    |
| 2021 | 12        | 8.05%   |
| 2022 | 11        | 7.38%   |
| 2018 | 10        | 6.71%   |
| 2012 | 10        | 6.71%   |
| 2017 | 8         | 5.37%   |
| 2010 | 7         | 4.7%    |
| 2016 | 6         | 4.03%   |
| 2009 | 6         | 4.03%   |
| 2008 | 6         | 4.03%   |
| 2015 | 5         | 3.36%   |
| 2014 | 4         | 2.68%   |
| 2013 | 4         | 2.68%   |
| 2007 | 3         | 2.01%   |
| 2006 | 2         | 1.34%   |
| 2005 | 2         | 1.34%   |
| 2004 | 2         | 1.34%   |
| 2003 | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 149       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 148       | 99.33%  |
| Yes  | 1         | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 43        | 28.29%  |
| 4.01-8.0    | 41        | 26.97%  |
| 16.01-24.0  | 36        | 23.68%  |
| 2.01-3.0    | 12        | 7.89%   |
| 0.51-1.0    | 5         | 3.29%   |
| 1.01-2.0    | 4         | 2.63%   |
| 24.01-32.0  | 3         | 1.97%   |
| 0.01-0.5    | 3         | 1.97%   |
| 32.01-64.0  | 2         | 1.32%   |
| 3.01-4.0    | 2         | 1.32%   |
| 64.01-256.0 | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 80        | 51.61%  |
| 0.51-1.0   | 42        | 27.1%   |
| 1.01-2.0   | 12        | 7.74%   |
| 2.01-3.0   | 8         | 5.16%   |
| Unknown    | 5         | 3.23%   |
| 0          | 4         | 2.58%   |
| 4.01-8.0   | 2         | 1.29%   |
| 24.01-32.0 | 1         | 0.65%   |
| 8.01-16.0  | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 69.48%  |
| 2      | 36        | 23.38%  |
| 0      | 6         | 3.9%    |
| 4      | 3         | 1.95%   |
| 3      | 2         | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 81.21%  |
| Yes       | 28        | 18.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 79.19%  |
| No        | 31        | 20.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 96.64%  |
| No        | 5         | 3.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 69.33%  |
| No        | 46        | 30.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 149       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 56        | 37.09%  |
| St Petersburg    | 16        | 10.6%   |
| Vladivostok      | 6         | 3.97%   |
| Yekaterinburg    | 5         | 3.31%   |
| Novosibirsk      | 5         | 3.31%   |
| Ulyanovsk        | 3         | 1.99%   |
| Ufa              | 3         | 1.99%   |
| Tyumen           | 3         | 1.99%   |
| Perm             | 3         | 1.99%   |
| Krasnoyarsk      | 3         | 1.99%   |
| Chelyabinsk      | 3         | 1.99%   |
| Tsarskoye Selo   | 2         | 1.32%   |
| Tolyatti         | 2         | 1.32%   |
| Krasnodar        | 2         | 1.32%   |
| Kirov            | 2         | 1.32%   |
| Chita            | 2         | 1.32%   |
| Zhukovskiy       | 1         | 0.66%   |
| Yoshkar-Ola      | 1         | 0.66%   |
| Yegorlykskaya    | 1         | 0.66%   |
| Yaroslavl        | 1         | 0.66%   |
| Vorkuta          | 1         | 0.66%   |
| Vladimir         | 1         | 0.66%   |
| Vidnoye          | 1         | 0.66%   |
| Ust'-Luga        | 1         | 0.66%   |
| Surgut           | 1         | 0.66%   |
| Smolensk         | 1         | 0.66%   |
| Sevastopol'      | 1         | 0.66%   |
| Rostov-on-Don    | 1         | 0.66%   |
| Pushkino         | 1         | 0.66%   |
| Penza            | 1         | 0.66%   |
| Ozersk           | 1         | 0.66%   |
| Oryol            | 1         | 0.66%   |
| Omsk             | 1         | 0.66%   |
| Obninsk          | 1         | 0.66%   |
| Nizhniy Novgorod | 1         | 0.66%   |
| Minusinsk        | 1         | 0.66%   |
| Michurinsk       | 1         | 0.66%   |
| Kstovo           | 1         | 0.66%   |
| Krasnokamsk      | 1         | 0.66%   |
| Korolyov         | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 39     | 18.54%  |
| Seagate             | 19        | 22     | 10.67%  |
| Samsung Electronics | 19        | 23     | 10.67%  |
| Toshiba             | 13        | 14     | 7.3%    |
| SanDisk             | 11        | 13     | 6.18%   |
| SK hynix            | 9         | 10     | 5.06%   |
| Hitachi             | 9         | 11     | 5.06%   |
| Kingston            | 7         | 9      | 3.93%   |
| Intel               | 7         | 9      | 3.93%   |
| HGST                | 5         | 7      | 2.81%   |
| Transcend           | 4         | 4      | 2.25%   |
| SPCC                | 4         | 5      | 2.25%   |
| Micron Technology   | 4         | 4      | 2.25%   |
| Gigabyte Technology | 3         | 6      | 1.69%   |
| FORESEE             | 3         | 4      | 1.69%   |
| A-DATA Technology   | 3         | 3      | 1.69%   |
| NVMe                | 2         | 2      | 1.12%   |
| KIOXIA              | 2         | 2      | 1.12%   |
| Innostor            | 2         | 2      | 1.12%   |
| USB                 | 1         | 1      | 0.56%   |
| UMIS                | 1         | 1      | 0.56%   |
| UFD 2.0             | 1         | 1      | 0.56%   |
| SSSTC               | 1         | 1      | 0.56%   |
| Smartbuy            | 1         | 1      | 0.56%   |
| Silicon Motion      | 1         | 1      | 0.56%   |
| SETHRISE            | 1         | 1      | 0.56%   |
| Phison              | 1         | 1      | 0.56%   |
| Patriot             | 1         | 1      | 0.56%   |
| OCZ                 | 1         | 2      | 0.56%   |
| Netac               | 1         | 1      | 0.56%   |
| Lenovo              | 1         | 1      | 0.56%   |
| KLLISRE             | 1         | 1      | 0.56%   |
| KINGBANK            | 1         | 1      | 0.56%   |
| Hoodisk             | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |
| Apacer              | 1         | 1      | 0.56%   |
| AMD                 | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 4         | 2.15%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.61%   |
| Kingston SV300S37A120G 120GB         | 3         | 1.61%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.61%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.08%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 2         | 1.08%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 1.08%   |
| WDC WD2500BEVT-22A23T0 250GB         | 2         | 1.08%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 1.08%   |
| WDC PC SN730 SDBPNTY-512G            | 2         | 1.08%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 1.08%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.08%   |
| Seagate ST9500325AS 500GB            | 2         | 1.08%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.08%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.08%   |
| Samsung MZNTY128HDHP-00000 128GB     | 2         | 1.08%   |
| Micron 1100 SATA 256GB               | 2         | 1.08%   |
| Kingston SA400S37120G 120GB          | 2         | 1.08%   |
| Innostor SSD 15GB                    | 2         | 1.08%   |
| Gigabyte GP-AG42TB                   | 2         | 1.08%   |
| FORESEE XP1000F001T 1TB              | 2         | 1.08%   |
| A-DATA SX6000LNP 512GB               | 2         | 1.08%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.54%   |
| WDC WDS240G1G0B-00RC30 240GB         | 1         | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.54%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.54%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.54%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.54%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.54%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 1         | 0.54%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.54%   |
| WDC WD20SPZX-00UA7T0 2TB             | 1         | 0.54%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 0.54%   |
| WDC WD2000JB-00GVC0 200GB            | 1         | 0.54%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.54%   |
| WDC WD10JPVX-08JC3T5 1TB             | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 20     | 27.14%  |
| Seagate             | 19        | 22     | 27.14%  |
| Toshiba             | 12        | 13     | 17.14%  |
| Hitachi             | 9         | 11     | 12.86%  |
| HGST                | 5         | 7      | 7.14%   |
| Samsung Electronics | 2         | 2      | 2.86%   |
| NVMe                | 2         | 2      | 2.86%   |
| USB                 | 1         | 1      | 1.43%   |
| UFD 2.0             | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 18.46%  |
| SanDisk             | 11        | 13     | 16.92%  |
| Kingston            | 6         | 8      | 9.23%   |
| WDC                 | 5         | 6      | 7.69%   |
| SPCC                | 4         | 5      | 6.15%   |
| Intel               | 4         | 6      | 6.15%   |
| Transcend           | 3         | 3      | 4.62%   |
| Micron Technology   | 3         | 3      | 4.62%   |
| SK hynix            | 2         | 2      | 3.08%   |
| Innostor            | 2         | 2      | 3.08%   |
| Smartbuy            | 1         | 1      | 1.54%   |
| SETHRISE            | 1         | 1      | 1.54%   |
| Patriot             | 1         | 1      | 1.54%   |
| OCZ                 | 1         | 2      | 1.54%   |
| Netac               | 1         | 1      | 1.54%   |
| KLLISRE             | 1         | 1      | 1.54%   |
| Hewlett-Packard     | 1         | 1      | 1.54%   |
| Gigabyte Technology | 1         | 3      | 1.54%   |
| FORESEE             | 1         | 2      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |
| Apacer              | 1         | 1      | 1.54%   |
| AMD                 | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 64        | 79     | 38.55%  |
| SSD  | 58        | 79     | 34.94%  |
| NVMe | 44        | 51     | 26.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 108       | 158    | 71.05%  |
| NVMe | 44        | 51     | 28.95%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 90        | 125    | 75%     |
| 0.51-1.0        | 26        | 29     | 21.67%  |
| 1.01-2.0        | 3         | 3      | 2.5%    |
| More than 100.0 | 1         | 1      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 44        | 27.5%   |
| 1-20       | 36        | 22.5%   |
| 251-500    | 35        | 21.88%  |
| 501-1000   | 14        | 8.75%   |
| 21-50      | 13        | 8.13%   |
| 51-100     | 12        | 7.5%    |
| 1001-2000  | 4         | 2.5%    |
| Unknown    | 2         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 115       | 74.68%  |
| 21-50   | 16        | 10.39%  |
| 101-250 | 12        | 7.79%   |
| 51-100  | 7         | 4.55%   |
| 251-500 | 2         | 1.3%    |
| Unknown | 2         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 6.06%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 6.06%   |
| Micron Technology 1100 SATA 256GB   | 2         | 2      | 6.06%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 3.03%   |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 1      | 3.03%   |
| WDC WD2000JB-00GVC0 200GB           | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 3.03%   |
| Toshiba MK7575GSX 752GB             | 1         | 1      | 3.03%   |
| Toshiba MK2546GSX 250GB             | 1         | 1      | 3.03%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 3.03%   |
| Seagate ST9250320AS 250GB           | 1         | 1      | 3.03%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 3.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 3.03%   |
| Samsung Electronics HM080HI 80GB    | 1         | 1      | 3.03%   |
| Kingston SV300S37A120G 120GB        | 1         | 1      | 3.03%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 3.03%   |
| Intel SSDSC2CW060A3 64GB            | 1         | 1      | 3.03%   |
| Intel SSDSC2BB480G7 480GB           | 1         | 1      | 3.03%   |
| Hitachi HTS725025A9A364 250GB       | 1         | 1      | 3.03%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 3.03%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 3.03%   |
| Hitachi HTS541616J9SA00 160GB       | 1         | 1      | 3.03%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 1      | 3.03%   |
| Hitachi HTC426060G9AT00 64GB        | 1         | 1      | 3.03%   |
| Hitachi DK23AA-12 12GB              | 1         | 1      | 3.03%   |
| HGST HTS541075A7E630 752GB          | 1         | 2      | 3.03%   |
| HGST HTE725032A7E630 320GB          | 1         | 1      | 3.03%   |
| Apple SSD SD0128F 121GB             | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 21.21%  |
| Hitachi             | 7         | 7      | 21.21%  |
| Toshiba             | 6         | 6      | 18.18%  |
| WDC                 | 3         | 3      | 9.09%   |
| Intel               | 3         | 3      | 9.09%   |
| Micron Technology   | 2         | 2      | 6.06%   |
| HGST                | 2         | 3      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 26.92%  |
| Hitachi             | 7         | 7      | 26.92%  |
| Toshiba             | 6         | 6      | 23.08%  |
| WDC                 | 3         | 3      | 11.54%  |
| HGST                | 2         | 3      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 27     | 78.79%  |
| SSD  | 7         | 7      | 21.21%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| SanDisk pSSD 128GB            | 1         | 1      | 50%     |
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 120       | 169    | 75.47%  |
| Malfunc  | 33        | 34     | 20.75%  |
| Detected | 4         | 4      | 2.52%   |
| Failed   | 2         | 2      | 1.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 100       | 58.48%  |
| AMD                                     | 23        | 13.45%  |
| SanDisk                                 | 10        | 5.85%   |
| SK hynix                                | 8         | 4.68%   |
| Samsung Electronics                     | 6         | 3.51%   |
| Phison Electronics                      | 4         | 2.34%   |
| Silicon Motion                          | 2         | 1.17%   |
| Shenzhen Longsys Electronics            | 2         | 1.17%   |
| Realtek Semiconductor                   | 2         | 1.17%   |
| Nvidia                                  | 2         | 1.17%   |
| KIOXIA                                  | 2         | 1.17%   |
| Transcend                               | 1         | 0.58%   |
| Toshiba                                 | 1         | 0.58%   |
| Solid State Storage Technology          | 1         | 0.58%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.58%   |
| Shenzhen Unionmemory Information System | 1         | 0.58%   |
| Micron Technology                       | 1         | 0.58%   |
| Marvell Technology Group                | 1         | 0.58%   |
| Lenovo                                  | 1         | 0.58%   |
| Kingston Technology Company             | 1         | 0.58%   |
| JMicron Technology                      | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 20        | 11.17%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 7.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 5.03%   |
| Unknown                                                                          | 8         | 4.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 7         | 3.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 3.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 3.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.79%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 2.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 2.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.23%   |
| SanDisk NVMe Controller                                                          | 3         | 1.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.68%   |
| SK hynix BC511                                                                   | 2         | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 1.12%   |
| Realtek NVMe Controller                                                          | 2         | 1.12%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 1.12%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 1.12%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.12%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.12%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 1.12%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.12%   |
| Intel 82801CAM IDE U100 Controller                                               | 2         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.12%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.56%   |
| SK hynix hynix unknown                                                           | 1         | 0.56%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.56%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 109       | 62.29%  |
| NVMe | 44        | 25.14%  |
| IDE  | 17        | 9.71%   |
| RAID | 5         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 112       | 75.17%  |
| AMD    | 37        | 24.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 6         | 3.97%   |
| Intel CPU Version                                                   | 4         | 2.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 4         | 2.65%   |
| Intel C1                                                            | 3         | 1.99%   |
| AMD Ryzen 7 5800H with Radeon Graphics                              | 3         | 1.99%   |
| Intel Pentium M processor 1.60GHz                                   | 2         | 1.32%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                   | 2         | 1.32%   |
| Intel Genuine CPU                                                   | 2         | 1.32%   |
| Intel Core i7-8665U CPU @ 1.90GHz                                   | 2         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 2         | 1.32%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                                  | 2         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 2         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 2         | 1.32%   |
| Intel Core i5-2430M CPU @ 2.40GHz                                   | 2         | 1.32%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                                   | 2         | 1.32%   |
| Intel Core 2 Duo                                                    | 2         | 1.32%   |
| Intel Celeron CPU N3350 @ 1.10GHz                                   | 2         | 1.32%   |
| Intel Atom CPU N570 @ 1.66GHz                                       | 2         | 1.32%   |
| Intel 686-class                                                     | 2         | 1.32%   |
| AMD Ryzen 7 5825U with Radeon Graphics                              | 2         | 1.32%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 2         | 1.32%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                       | 2         | 1.32%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                       | 2         | 1.32%   |
| Intel Xeon W-10885M CPU @ 2.40GHz                                   | 1         | 0.66%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz                                | 1         | 0.66%   |
| Intel Pentium Silver N6000 @ 1.10GHz                                | 1         | 0.66%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                            | 1         | 0.66%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)        | 1         | 0.66%   |
| Intel Pentium M processor                                           | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                         | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz                         | 1         | 0.66%   |
| Intel Pentium CPU N3700 @ 1.60GHz                                   | 1         | 0.66%   |
| Intel Pentium CPU N3530 @ 2.16GHz                                   | 1         | 0.66%   |
| Intel Pentium CPU 4417U @ 2.30GHz                                   | 1         | 0.66%   |
| Intel Mobile Pentium III CPU - M 1200MHz ("GenuineIntel" 686-class) | 1         | 0.66%   |
| Intel Mobile Pentium III CPU - M 1000MHz ("GenuineIntel" 686-class) | 1         | 0.66%   |
| Intel Genuine CPU U7300 @ 1.30GHz                                   | 1         | 0.66%   |
| Intel Genuine CPU T2                                                | 1         | 0.66%   |
| Intel Core Solo CPU U1500 @ 1.33GHz                                 | 1         | 0.66%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                                    | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 24        | 15.89%  |
| Intel Core i7           | 19        | 12.58%  |
| Other                   | 12        | 7.95%   |
| Intel Core i3           | 12        | 7.95%   |
| AMD Ryzen 7             | 10        | 6.62%   |
| Intel Atom              | 7         | 4.64%   |
| AMD Ryzen 3             | 7         | 4.64%   |
| Intel Core 2 Duo        | 6         | 3.97%   |
| Intel Celeron           | 6         | 3.97%   |
| AMD Ryzen 5             | 6         | 3.97%   |
| Intel Pentium           | 5         | 3.31%   |
| Intel Pentium M         | 4         | 2.65%   |
| Intel Genuine           | 4         | 2.65%   |
| AMD Ryzen 7 PRO         | 3         | 1.99%   |
| AMD E                   | 3         | 1.99%   |
| AMD A6                  | 3         | 1.99%   |
| Intel Xeon              | 2         | 1.32%   |
| Intel Pentium Silver    | 2         | 1.32%   |
| Intel Pentium Dual-Core | 2         | 1.32%   |
| Intel Core m3           | 2         | 1.32%   |
| Intel 686-class         | 2         | 1.32%   |
| Intel Core Solo         | 1         | 0.66%   |
| Intel Core m5           | 1         | 0.66%   |
| Intel Core M            | 1         | 0.66%   |
| Intel Core i9           | 1         | 0.66%   |
| Intel Celeron Dual-Core | 1         | 0.66%   |
| AMD Ryzen 9             | 1         | 0.66%   |
| AMD E2                  | 1         | 0.66%   |
| AMD E1                  | 1         | 0.66%   |
| AMD A8                  | 1         | 0.66%   |
| AMD A10                 | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 60        | 39.47%  |
| 4       | 40        | 26.32%  |
| Unknown | 16        | 10.53%  |
| 1       | 11        | 7.24%   |
| 16      | 10        | 6.58%   |
| 8       | 8         | 5.26%   |
| 12      | 4         | 2.63%   |
| 6       | 3         | 1.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 143       | 94.08%  |
| Unknown | 9         | 5.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 71        | 46.71%  |
| 1       | 58        | 38.16%  |
| Unknown | 23        | 15.13%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 15.33%  |
| Skylake       | 12        | 8%      |
| Penryn        | 10        | 6.67%   |
| Zen 3         | 9         | 6%      |
| SandyBridge   | 9         | 6%      |
| Bonnell       | 9         | 6%      |
| P6            | 8         | 5.33%   |
| IvyBridge     | 7         | 4.67%   |
| Zen 2         | 6         | 4%      |
| Haswell       | 6         | 4%      |
| Unknown       | 6         | 4%      |
| Zen+          | 5         | 3.33%   |
| Silvermont    | 5         | 3.33%   |
| Core          | 5         | 3.33%   |
| Westmere      | 4         | 2.67%   |
| Goldmont      | 4         | 2.67%   |
| Zen           | 3         | 2%      |
| TigerLake     | 3         | 2%      |
| Puma          | 2         | 1.33%   |
| Excavator     | 2         | 1.33%   |
| CometLake     | 2         | 1.33%   |
| Broadwell     | 2         | 1.33%   |
| Bobcat        | 2         | 1.33%   |
| Piledriver    | 1         | 0.67%   |
| K8 Hammer     | 1         | 0.67%   |
| K10 Llano     | 1         | 0.67%   |
| Jaguar        | 1         | 0.67%   |
| IceLake       | 1         | 0.67%   |
| Goldmont plus | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 98        | 56%     |
| AMD    | 50        | 28.57%  |
| Nvidia | 26        | 14.86%  |
| ATI    | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 3.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.3%    |
| AMD Renoir                                                                               | 6         | 3.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.75%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.65%   |
| Intel HD Graphics 630                                                                    | 3         | 1.65%   |
| Intel HD Graphics 520                                                                    | 3         | 1.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.65%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.1%    |
| Intel HD Graphics 620                                                                    | 2         | 1.1%    |
| Intel HD Graphics 515                                                                    | 2         | 1.1%    |
| Intel HD Graphics 500                                                                    | 2         | 1.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.1%    |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2         | 1.1%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.1%    |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 1.1%    |
| AMD Lucienne                                                                             | 2         | 1.1%    |
| AMD Barcelo                                                                              | 2         | 1.1%    |
| Nvidia TU117M                                                                            | 1         | 0.55%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.55%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                         | 1         | 0.55%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.55%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.55%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 60        | 40%     |
| 1 x AMD        | 41        | 27.33%  |
| Intel + Nvidia | 18        | 12%     |
| 2 x Intel      | 16        | 10.67%  |
| 1 x Nvidia     | 6         | 4%      |
| Intel + AMD    | 4         | 2.67%   |
| 2 x AMD        | 3         | 2%      |
| AMD + Nvidia   | 2         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 134       | 88.74%  |
| Proprietary | 10        | 6.62%   |
| Unknown     | 7         | 4.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 75.97%  |
| 0.01-0.5   | 24        | 15.58%  |
| 1.01-2.0   | 6         | 3.9%    |
| 0.51-1.0   | 5         | 3.25%   |
| 3.01-4.0   | 1         | 0.65%   |
| 2.01-3.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 24.32%  |
| LG Display              | 16        | 14.41%  |
| BOE                     | 15        | 13.51%  |
| Chimei Innolux          | 12        | 10.81%  |
| Samsung Electronics     | 11        | 9.91%   |
| InfoVision              | 4         | 3.6%    |
| LG Philips              | 3         | 2.7%    |
| Chi Mei Optoelectronics | 3         | 2.7%    |
| Acer                    | 3         | 2.7%    |
| ViewSonic               | 2         | 1.8%    |
| PANDA                   | 2         | 1.8%    |
| Lenovo                  | 2         | 1.8%    |
| HKC                     | 2         | 1.8%    |
| Toshiba                 | 1         | 0.9%    |
| Panasonic               | 1         | 0.9%    |
| NEC Computers           | 1         | 0.9%    |
| HannStar                | 1         | 0.9%    |
| Goldstar                | 1         | 0.9%    |
| CSO                     | 1         | 0.9%    |
| CPT                     | 1         | 0.9%    |
| Apple                   | 1         | 0.9%    |
| Ancor Communications    | 1         | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 2         | 1.8%    |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 1.8%    |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                    | 2         | 1.8%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 2         | 1.8%    |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 1.8%    |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                    | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 1.8%    |
| Acer K272HUL ACR0524 2560x1440 600x340mm 27.2-inch                       | 2         | 1.8%    |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 0.9%    |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 0.9%    |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 0.9%    |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 0.9%    |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 0.9%    |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 0.9%    |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 0.9%    |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.9%    |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch              | 1         | 0.9%    |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 0.9%    |
| LG Display LCD Monitor LGD06FF 1920x1080 340x190mm 15.3-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD05EE 2560x1440 310x170mm 13.9-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch              | 1         | 0.9%    |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 0.9%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 0.9%    |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 0.9%    |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 0.9%    |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch              | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 46        | 41.44%  |
| 1366x768 (WXGA)   | 30        | 27.03%  |
| 1280x800 (WXGA)   | 6         | 5.41%   |
| 2560x1440 (QHD)   | 5         | 4.5%    |
| 1600x900 (HD+)    | 5         | 4.5%    |
| 1024x600          | 4         | 3.6%    |
| 1440x900 (WXGA+)  | 3         | 2.7%    |
| 3840x2160 (4K)    | 2         | 1.8%    |
| 1280x1024 (SXGA)  | 2         | 1.8%    |
| 3200x1800 (QHD+)  | 1         | 0.9%    |
| 2880x1620         | 1         | 0.9%    |
| 2560x1080         | 1         | 0.9%    |
| 2520x1680         | 1         | 0.9%    |
| 2240x1400         | 1         | 0.9%    |
| 2160x1440         | 1         | 0.9%    |
| 1920x540          | 1         | 0.9%    |
| 1920x1200 (WUXGA) | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 48        | 43.24%  |
| 13     | 27        | 24.32%  |
| 17     | 7         | 6.31%   |
| 14     | 5         | 4.5%    |
| 11     | 5         | 4.5%    |
| 10     | 5         | 4.5%    |
| 12     | 4         | 3.6%    |
| 27     | 2         | 1.8%    |
| 21     | 2         | 1.8%    |
| 54     | 1         | 0.9%    |
| 34     | 1         | 0.9%    |
| 31     | 1         | 0.9%    |
| 23     | 1         | 0.9%    |
| 19     | 1         | 0.9%    |
| 16     | 1         | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 70        | 63.06%  |
| 201-300     | 26        | 23.42%  |
| 351-400     | 7         | 6.31%   |
| 501-600     | 3         | 2.7%    |
| 401-500     | 2         | 1.8%    |
| 701-800     | 1         | 0.9%    |
| 601-700     | 1         | 0.9%    |
| 1001-1500   | 1         | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 87        | 83.65%  |
| 16/10 | 12        | 11.54%  |
| 5/4   | 2         | 1.92%   |
| 3/2   | 2         | 1.92%   |
| 21/9  | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 42        | 37.84%  |
| 81-90          | 25        | 22.52%  |
| 101-110        | 7         | 6.31%   |
| 71-80          | 6         | 5.41%   |
| 51-60          | 5         | 4.5%    |
| 41-50          | 5         | 4.5%    |
| 61-70          | 4         | 3.6%    |
| 121-130        | 4         | 3.6%    |
| 201-250        | 3         | 2.7%    |
| 131-140        | 3         | 2.7%    |
| 351-500        | 2         | 1.8%    |
| 301-350        | 2         | 1.8%    |
| More than 1000 | 1         | 0.9%    |
| 151-200        | 1         | 0.9%    |
| 141-150        | 1         | 0.9%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 41.44%  |
| 101-120       | 34        | 30.63%  |
| 161-240       | 15        | 13.51%  |
| 51-100        | 14        | 12.61%  |
| More than 240 | 2         | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 116       | 73.42%  |
| 0     | 32        | 20.25%  |
| 2     | 10        | 6.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 81        | 31.76%  |
| Realtek Semiconductor             | 72        | 28.24%  |
| Qualcomm Atheros                  | 43        | 16.86%  |
| Broadcom                          | 15        | 5.88%   |
| Marvell Technology Group          | 10        | 3.92%   |
| TP-Link                           | 5         | 1.96%   |
| Ralink Technology                 | 4         | 1.57%   |
| Samsung Electronics               | 2         | 0.78%   |
| Ralink                            | 2         | 0.78%   |
| MediaTek                          | 2         | 0.78%   |
| Fibocom                           | 2         | 0.78%   |
| Ericsson Business Mobile Networks | 2         | 0.78%   |
| Arduino SA                        | 2         | 0.78%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.39%   |
| Shenzhen Goodix Technology        | 1         | 0.39%   |
| Realtek                           | 1         | 0.39%   |
| Nvidia                            | 1         | 0.39%   |
| Mercucys                          | 1         | 0.39%   |
| JMicron Technology                | 1         | 0.39%   |
| Huawei Technologies               | 1         | 0.39%   |
| Dell                              | 1         | 0.39%   |
| D-Link                            | 1         | 0.39%   |
| BUFFALO                           | 1         | 0.39%   |
| Attansic                          | 1         | 0.39%   |
| Atheros                           | 1         | 0.39%   |
| 3Com                              | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 48        | 15.89%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 4.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.65%   |
| Intel Wireless 7265                                                     | 8         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 2.65%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.99%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 6         | 1.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 1.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.66%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.32%   |
| Intel Wireless 8260                                                     | 4         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.99%   |
| Intel Wireless 3165                                                     | 3         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.99%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.66%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.66%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 2         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.66%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.66%   |
| Intel Wireless 7260                                                     | 2         | 0.66%   |
| Intel WiFi Link 5100                                                    | 2         | 0.66%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.66%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.66%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.66%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                                   | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 77        | 46.95%  |
| Qualcomm Atheros      | 36        | 21.95%  |
| Realtek Semiconductor | 25        | 15.24%  |
| Broadcom              | 9         | 5.49%   |
| TP-Link               | 5         | 3.05%   |
| Ralink Technology     | 4         | 2.44%   |
| Ralink                | 2         | 1.22%   |
| MediaTek              | 2         | 1.22%   |
| Mercucys              | 1         | 0.61%   |
| D-Link                | 1         | 0.61%   |
| BUFFALO               | 1         | 0.61%   |
| Atheros               | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.76%   |
| Intel Wireless 7265                                                     | 8         | 4.76%   |
| Intel Wireless 8265 / 8275                                              | 7         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 3.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.98%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.38%   |
| Intel Wireless 8260                                                     | 4         | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.79%   |
| Intel Wireless 3165                                                     | 3         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 1.19%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.19%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.19%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.19%   |
| Intel Wireless 7260                                                     | 2         | 1.19%   |
| Intel WiFi Link 5100                                                    | 2         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.19%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.19%   |
| TP-Link Wireless USB Adapter                                            | 1         | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.6%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]     | 1         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.6%    |
| Realtek Bluetooth Adapter                                               | 1         | 0.6%    |
| Ralink RT3572 Wireless Adapter                                          | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 59        | 48.76%  |
| Intel                            | 25        | 20.66%  |
| Qualcomm Atheros                 | 12        | 9.92%   |
| Marvell Technology Group         | 10        | 8.26%   |
| Broadcom                         | 7         | 5.79%   |
| Samsung Electronics              | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Realtek                          | 1         | 0.83%   |
| Nvidia                           | 1         | 0.83%   |
| JMicron Technology               | 1         | 0.83%   |
| Attansic                         | 1         | 0.83%   |
| 3Com                             | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 39.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 7.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 6.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 4.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 2.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.65%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.65%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.65%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.65%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.65%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.83%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.83%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.83%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.83%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.83%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.83%   |
| Intel PRO/100 VM Network Connection                               | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.83%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 0.83%   |
| Intel 82801CAM (ICH3) PRO/100 VM (KM) Ethernet Controller         | 1         | 0.83%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.83%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.83%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.83%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 52.36%  |
| Ethernet | 118       | 42.91%  |
| Unknown  | 7         | 2.55%   |
| Modem    | 6         | 2.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 54.05%  |
| Ethernet | 83        | 44.86%  |
| Unknown  | 2         | 1.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 112       | 75.17%  |
| 1     | 35        | 23.49%  |
| 3     | 1         | 0.67%   |
| 0     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 147       | 98%     |
| Yes  | 3         | 2%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 49.52%  |
| Qualcomm Atheros Communications | 11        | 10.48%  |
| Realtek Semiconductor           | 9         | 8.57%   |
| Broadcom                        | 6         | 5.71%   |
| IMC Networks                    | 5         | 4.76%   |
| Skylight Digital                | 3         | 2.86%   |
| Lite-On Technology              | 3         | 2.86%   |
| Foxconn / Hon Hai               | 3         | 2.86%   |
| ASUSTek Computer                | 3         | 2.86%   |
| Alps Electric                   | 3         | 2.86%   |
| Hewlett-Packard                 | 2         | 1.9%    |
| Apple                           | 2         | 1.9%    |
| Ralink                          | 1         | 0.95%   |
| Opticis                         | 1         | 0.95%   |
| Dell                            | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 22        | 20.95%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 7.62%   |
| Intel AX201 Bluetooth                                       | 7         | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 6         | 5.71%   |
| Intel AX200 Bluetooth                                       | 5         | 4.76%   |
| Realtek Bluetooth Adapter                                   | 4         | 3.81%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 4         | 3.81%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 3         | 2.86%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 2.86%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.9%    |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 1.9%    |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.9%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 1.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.9%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.9%    |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.95%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.95%   |
| Qualcomm Atheros QCA9565 Bluetooth 4.0 + HS Adapter         | 1         | 0.95%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.95%   |
| Opticis Realtek Bluetooth Adapter                           | 1         | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.95%   |
| Intel AX210 Bluetooth                                       | 1         | 0.95%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.95%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.95%   |
| IMC Networks Bluetooth module                               | 1         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.95%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.95%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.95%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.95%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.95%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.95%   |
| Broadcom Bluetooth 4.0                                      | 1         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth Module                        | 1         | 0.95%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 0.95%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 108       | 66.26%  |
| AMD                              | 40        | 24.54%  |
| Nvidia                           | 7         | 4.29%   |
| Lenovo                           | 3         | 1.84%   |
| Texas Instruments                | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] | 1         | 0.61%   |
| Generalplus Technology           | 1         | 0.61%   |
| ESS Technology                   | 1         | 0.61%   |
| Creative Technology              | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 12.62%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 9.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 8.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 3.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 3.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.91%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 2.43%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.94%   |
| Lenovo Realtek USB Audio                                                                          | 3         | 1.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.46%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.46%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.97%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.97%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.97%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.97%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.97%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.97%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 0.97%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.97%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.49%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.49%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 24.05%  |
| SK hynix            | 30        | 18.99%  |
| Unknown             | 23        | 14.56%  |
| Kingston            | 19        | 12.03%  |
| Micron Technology   | 15        | 9.49%   |
| Unknown             | 7         | 4.43%   |
| Ramaxel Technology  | 3         | 1.9%    |
| Elpida              | 3         | 1.9%    |
| Crucial             | 3         | 1.9%    |
| A-DATA Technology   | 3         | 1.9%    |
| 48spaces            | 3         | 1.9%    |
| Transcend           | 2         | 1.27%   |
| Corsair             | 2         | 1.27%   |
| Unknown (ABCD)      | 1         | 0.63%   |
| Unknown (0x0809)    | 1         | 0.63%   |
| Silicon Power       | 1         | 0.63%   |
| PUSKILL             | 1         | 0.63%   |
| GeIL                | 1         | 0.63%   |
| Apacer              | 1         | 0.63%   |
| AMD                 | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 7         | 4.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 5         | 2.96%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 1.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 3         | 1.78%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 1.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 1.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 3         | 1.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 3         | 1.78%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 3         | 1.78%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 1.18%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 2         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.18%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.18%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.18%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                     | 1         | 0.59%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                       | 1         | 0.59%   |
| Unknown RAM Module 256MB SODIMM DRAM                                      | 1         | 0.59%   |
| Unknown RAM Module 256MB SODIMM DDR 100MT/s                               | 1         | 0.59%   |
| Unknown RAM Module 2560MB SODIMM DDR                                      | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR 800MT/s                              | 1         | 0.59%   |
| Unknown RAM Module 1GB SODIMM DDR2                                        | 1         | 0.59%   |
| Unknown RAM Module 128MB SODIMM DRAM                                      | 1         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s                            | 1         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266(3.8ns)MT/s                     | 1         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                     | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 59        | 43.7%   |
| DDR3    | 36        | 26.67%  |
| DDR2    | 14        | 10.37%  |
| LPDDR3  | 7         | 5.19%   |
| DDR     | 5         | 3.7%    |
| Unknown | 4         | 2.96%   |
| SDRAM   | 3         | 2.22%   |
| DRAM    | 3         | 2.22%   |
| RAM     | 1         | 0.74%   |
| LPDDR5  | 1         | 0.74%   |
| LPDDR4  | 1         | 0.74%   |
| DDR5    | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 122       | 90.37%  |
| Row Of Chips | 9         | 6.67%   |
| DIMM         | 3         | 2.22%   |
| Chip         | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 54        | 35.53%  |
| 4096  | 40        | 26.32%  |
| 2048  | 30        | 19.74%  |
| 16384 | 9         | 5.92%   |
| 1024  | 9         | 5.92%   |
| 512   | 4         | 2.63%   |
| 32768 | 2         | 1.32%   |
| 256   | 2         | 1.32%   |
| 2560  | 1         | 0.66%   |
| 128   | 1         | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 22        | 15.71%  |
| 2667    | 21        | 15%     |
| 1600    | 19        | 13.57%  |
| 2400    | 13        | 9.29%   |
| 667     | 12        | 8.57%   |
| 1333    | 11        | 7.86%   |
| Unknown | 11        | 7.86%   |
| 2133    | 7         | 5%      |
| 1867    | 6         | 4.29%   |
| 800     | 6         | 4.29%   |
| 1067    | 3         | 2.14%   |
| 1334    | 2         | 1.43%   |
| 6400    | 1         | 0.71%   |
| 4800    | 1         | 0.71%   |
| 2933    | 1         | 0.71%   |
| 2048    | 1         | 0.71%   |
| 975     | 1         | 0.71%   |
| 266     | 1         | 0.71%   |
| 100     | 1         | 0.71%   |

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
| Chicony Electronics                    | 29        | 24.58%  |
| IMC Networks                           | 16        | 13.56%  |
| Realtek Semiconductor                  | 12        | 10.17%  |
| Microdia                               | 12        | 10.17%  |
| Bison Electronics                      | 7         | 5.93%   |
| Suyin                                  | 5         | 4.24%   |
| Quanta                                 | 5         | 4.24%   |
| Lite-On Technology                     | 4         | 3.39%   |
| ALi                                    | 4         | 3.39%   |
| Syntek                                 | 3         | 2.54%   |
| Sunplus Innovation Technology          | 3         | 2.54%   |
| Silicon Motion                         | 3         | 2.54%   |
| Luxvisions Innotech Limited            | 2         | 1.69%   |
| Jiangxi Shinetech Optical              | 2         | 1.69%   |
| DigiTech                               | 2         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.69%   |
| Z-Star Microelectronics                | 1         | 0.85%   |
| Y Media                                | 1         | 0.85%   |
| Supreme Electronics                    | 1         | 0.85%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.85%   |
| Ricoh                                  | 1         | 0.85%   |
| Intel                                  | 1         | 0.85%   |
| Denron                                 | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                              | 11        | 9.17%   |
| Microdia Integrated_Webcam_HD                          | 6         | 5%      |
| IMC Networks Integrated Camera                         | 5         | 4.17%   |
| Silicon Motion WebCam SCX Series                       | 3         | 2.5%    |
| Realtek USB 2.0 PC Camera                              | 3         | 2.5%    |
| Realtek Acer 640 x 480 laptop camera                   | 3         | 2.5%    |
| Quanta VGA WebCam                                      | 3         | 2.5%    |
| IMC Networks EasyCamera                                | 3         | 2.5%    |
| Bison Lenovo EasyCamera                                | 3         | 2.5%    |
| ALi Gateway Webcam                                     | 3         | 2.5%    |
| Syntek EasyCamera                                      | 2         | 1.67%   |
| Sunplus HD WebCam                                      | 2         | 1.67%   |
| Realtek Integrated Webcam                              | 2         | 1.67%   |
| Microdia USB Camera                                    | 2         | 1.67%   |
| Microdia Integrated Webcam                             | 2         | 1.67%   |
| Lite-On Integrated Camera                              | 2         | 1.67%   |
| Lite-On HP HD Camera                                   | 2         | 1.67%   |
| Jiangxi Shinetech Optical HD Camera                    | 2         | 1.67%   |
| IMC Networks UVC VGA Webcam                            | 2         | 1.67%   |
| IMC Networks Realtek DMFT RGB                          | 2         | 1.67%   |
| DigiTech WebCam SCB-0350M                              | 2         | 1.67%   |
| Chicony XiaoMi USB 2.0 Webcam                          | 2         | 1.67%   |
| Z-Star Webcam                                          | 1         | 0.83%   |
| Y Media USB Camera                                     | 1         | 0.83%   |
| Syntek Lenovo EasyCamera                               | 1         | 0.83%   |
| Suyin USB 2.0 UVC 1.3M WebCam                          | 1         | 0.83%   |
| Suyin HP Webcam                                        | 1         | 0.83%   |
| Suyin HD WebCam                                        | 1         | 0.83%   |
| Suyin HD Video WebCam                                  | 1         | 0.83%   |
| Suyin Acer Crystal Eye webcam                          | 1         | 0.83%   |
| Supreme Integrated Camera                              | 1         | 0.83%   |
| Sunplus Integrated_Webcam_HD                           | 1         | 0.83%   |
| Shenzhen Kingcome Optoelectronic XiaoMi USB 2.0 Webcam | 1         | 0.83%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870]    | 1         | 0.83%   |
| Realtek USB2.0 VGA UVC WebCam                          | 1         | 0.83%   |
| Realtek USB2.0 HD UVC WebCam                           | 1         | 0.83%   |
| Realtek USB Webcam                                     | 1         | 0.83%   |
| Realtek Integrated_Webcam_FHD                          | 1         | 0.83%   |
| Realtek Integrated_Webcam_8M                           | 1         | 0.83%   |
| Quanta Realtek PC Camera                               | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 32.35%  |
| Validity Sensors           | 10        | 29.41%  |
| STMicroelectronics         | 3         | 8.82%   |
| Shenzhen Goodix Technology | 3         | 8.82%   |
| Upek                       | 2         | 5.88%   |
| FocalTech Systems          | 2         | 5.88%   |
| AuthenTec                  | 2         | 5.88%   |
| Broadcom                   | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 6         | 17.65%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 8.82%   |
| STMicroelectronics Fingerprint Reader                                        | 3         | 8.82%   |
| Shenzhen Goodix  Fingerprint Device                                          | 3         | 8.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 5.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 2         | 5.88%   |
| FocalTech Systems Fingerprint Reader                                         | 2         | 5.88%   |
| AuthenTec AES1600                                                            | 2         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 2.94%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.94%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 2.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.94%   |

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
| 1     | 58        | 36.02%  |
| 2     | 40        | 24.84%  |
| 0     | 21        | 13.04%  |
| 3     | 19        | 11.8%   |
| 4     | 18        | 11.18%  |
| 9     | 1         | 0.62%   |
| 8     | 1         | 0.62%   |
| 7     | 1         | 0.62%   |
| 6     | 1         | 0.62%   |
| 5     | 1         | 0.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 75        | 29.53%  |
| Net/wireless             | 43        | 16.93%  |
| Bluetooth                | 35        | 13.78%  |
| Card reader              | 31        | 12.2%   |
| Fingerprint reader       | 30        | 11.81%  |
| Firewire controller      | 12        | 4.72%   |
| Sound                    | 7         | 2.76%   |
| Graphics card            | 7         | 2.76%   |
| Storage                  | 5         | 1.97%   |
| Network                  | 5         | 1.97%   |
| Modem                    | 3         | 1.18%   |
| Storage/ata              | 1         | 0.39%   |

