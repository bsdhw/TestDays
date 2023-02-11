helloSystem 0.8.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.8.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.8.0/Notebook/README.md).

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

Total: 187

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| HP            | 1496                        | Desktop     | [fae90baa23](https://bsd-hardware.info/?probe=fae90baa23) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [cd4202e58b](https://bsd-hardware.info/?probe=cd4202e58b) | Jan 30, 2023 |
| Dell          | Precision 5540              | Notebook    | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Unknown       | TJ41G-A80 v2 Series         | All in one  | [c44ac785cc](https://bsd-hardware.info/?probe=c44ac785cc) | Jan 29, 2023 |
| Unknown       | TJ41G-A80 v2 Series         | All in one  | [a5bc81b507](https://bsd-hardware.info/?probe=a5bc81b507) | Jan 29, 2023 |
| Packard Be... | DOT S                       | Notebook    | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | Notebook    | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | Notebook    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [a266199ace](https://bsd-hardware.info/?probe=a266199ace) | Jan 27, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6b63a16799](https://bsd-hardware.info/?probe=6b63a16799) | Jan 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6685066b6e](https://bsd-hardware.info/?probe=6685066b6e) | Jan 26, 2023 |
| ASUSTek       | H81M-D R2.0                 | Desktop     | [07982549ac](https://bsd-hardware.info/?probe=07982549ac) | Jan 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9a307961ed](https://bsd-hardware.info/?probe=9a307961ed) | Jan 26, 2023 |
| Google        | Cave                        | Notebook    | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1c97950ce9](https://bsd-hardware.info/?probe=1c97950ce9) | Jan 25, 2023 |
| Lenovo        | ThinkPad X1 Tablet 20GHS... | Tablet      | [cd05b84425](https://bsd-hardware.info/?probe=cd05b84425) | Jan 25, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [80c808de34](https://bsd-hardware.info/?probe=80c808de34) | Jan 25, 2023 |
| Timi          | TM1607                      | Notebook    | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| HP            | 802E                        | Desktop     | [1f3bf517af](https://bsd-hardware.info/?probe=1f3bf517af) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Google        | Panther                     | Desktop     | [73d3147166](https://bsd-hardware.info/?probe=73d3147166) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | Notebook    | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | Notebook    | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | Latitude 3540               | Notebook    | [a180a149f5](https://bsd-hardware.info/?probe=a180a149f5) | Jan 24, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [23415b954f](https://bsd-hardware.info/?probe=23415b954f) | Jan 24, 2023 |
| Dell          | Latitude 5580               | Notebook    | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| HP            | 1495                        | Desktop     | [69faf0563a](https://bsd-hardware.info/?probe=69faf0563a) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [9cd4d2810a](https://bsd-hardware.info/?probe=9cd4d2810a) | Jan 23, 2023 |
| ASUSTek       | K50IN                       | Notebook    | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Star Labs     | StarBook                    | Notebook    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | Notebook    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| ASRock        | Z390 Pro4                   | Desktop     | [b9d64a7496](https://bsd-hardware.info/?probe=b9d64a7496) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6cf4f6761e](https://bsd-hardware.info/?probe=6cf4f6761e) | Jan 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [27ea626000](https://bsd-hardware.info/?probe=27ea626000) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [abc17c6fc6](https://bsd-hardware.info/?probe=abc17c6fc6) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [006553f965](https://bsd-hardware.info/?probe=006553f965) | Jan 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4b3a05fc2a](https://bsd-hardware.info/?probe=4b3a05fc2a) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [6662cab62d](https://bsd-hardware.info/?probe=6662cab62d) | Jan 22, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [2b94c3efae](https://bsd-hardware.info/?probe=2b94c3efae) | Jan 22, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [28088f7e94](https://bsd-hardware.info/?probe=28088f7e94) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | Notebook    | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | Notebook    | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| Razer         | Blade Stealth               | Notebook    | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [379b59f079](https://bsd-hardware.info/?probe=379b59f079) | Jan 05, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | Notebook    | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| ASUSTek       | CM1530                      | Desktop     | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Dell          | 009Y81 A01                  | All in one  | [75132e6886](https://bsd-hardware.info/?probe=75132e6886) | Nov 25, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek       | P5KPL-VM-TWPC               | Desktop     | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| Acer          | Aspire 5251                 | Notebook    | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| HP            | 1998                        | Desktop     | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| HP            | 843B                        | Desktop     | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [17f444775b](https://bsd-hardware.info/?probe=17f444775b) | Oct 28, 2022 |
| HP            | 843B                        | Desktop     | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Google        | Edgar                       | Notebook    | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | PS63 Modern 8M              | Notebook    | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| HP            | 86FC MVB                    | Desktop     | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| Kraftway      | KW10T                       | Notebook    | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | Notebook    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Dell          | Latitude E5550              | Notebook    | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| Toshiba       | Satellite S55t-B            | Notebook    | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [3de3724488](https://bsd-hardware.info/?probe=3de3724488) | Aug 12, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | Notebook    | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| ASUSTek       | K30AM-J                     | Desktop     | [470ced8f30](https://bsd-hardware.info/?probe=470ced8f30) | Aug 05, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a80b1c4f3c](https://bsd-hardware.info/?probe=a80b1c4f3c) | Jul 17, 2022 |
| HP            | 1998                        | Desktop     | [e4fda48283](https://bsd-hardware.info/?probe=e4fda48283) | Jul 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Biostar       | G41D3C                      | Desktop     | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| HP            | Unknown                     | Notebook    | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | Notebook    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Timi          | TM1701                      | Notebook    | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Dell          | Studio 1747                 | Notebook    | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| ASUSTek       | K30AM-J                     | Desktop     | [f4352f7897](https://bsd-hardware.info/?probe=f4352f7897) | May 16, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | Notebook    | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [4b5603b38b](https://bsd-hardware.info/?probe=4b5603b38b) | Apr 29, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [b47a498f2e](https://bsd-hardware.info/?probe=b47a498f2e) | Apr 08, 2022 |
| Dell          | Latitude E5470              | Notebook    | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| Sony          | VGN-AW21S_B                 | Notebook    | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| PCSTICK       | Unknown                     | Notebook    | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Gateway       | NE56R                       | Notebook    | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| MSI           | B350M BAZOOKA               | Desktop     | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | Desktop     | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Acer          | V5-131                      | Notebook    | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| PCSTICK       | Unknown                     | Notebook    | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| AMD           | X64                         | Desktop     | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| MACHINIST     | X99-k9 V2.0                 | Desktop     | [0a36d71db1](https://bsd-hardware.info/?probe=0a36d71db1) | Feb 10, 2022 |
| Sony          | VPCEB1J1E                   | Notebook    | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [2036093b68](https://bsd-hardware.info/?probe=2036093b68) | Jan 25, 2022 |
| HP            | 8648                        | Desktop     | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| Dell          | 0593VH A00                  | Desktop     | [484d14dbef](https://bsd-hardware.info/?probe=484d14dbef) | Jan 22, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| Dell          | 0YF8P5 A00                  | Desktop     | [913b2a7483](https://bsd-hardware.info/?probe=913b2a7483) | Jan 18, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| Lenovo        | ThinkPad T440 20B7A0B7MS    | Notebook    | [be30041f4e](https://bsd-hardware.info/?probe=be30041f4e) | Jan 10, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5de4d8c93e](https://bsd-hardware.info/?probe=5de4d8c93e) | Jan 09, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [7c49bc84a7](https://bsd-hardware.info/?probe=7c49bc84a7) | Jan 08, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [362940acbb](https://bsd-hardware.info/?probe=362940acbb) | Jan 03, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 155       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 149       | 96.13%  |
| GNOME        | 2         | 1.29%   |
| Window Maker | 1         | 0.65%   |
| KDE5         | 1         | 0.65%   |
| IceWM        | 1         | 0.65%   |
| Cinnamon     | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 155       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 154       | 99.35%  |
| GDM  | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 89        | 57.05%  |
| en    | 34        | 21.79%  |
| ru    | 10        | 6.41%   |
| de    | 5         | 3.21%   |
| pt    | 3         | 1.92%   |
| fr    | 3         | 1.92%   |
| es_ES | 3         | 1.92%   |
| es    | 3         | 1.92%   |
| zh_TW | 1         | 0.64%   |
| zh_CN | 1         | 0.64%   |
| ru_RU | 1         | 0.64%   |
| it    | 1         | 0.64%   |
| en_GB | 1         | 0.64%   |
| de_DE | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 154       | 99.35%  |
| BIOS | 1         | 0.65%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 105       | 67.31%  |
| Zfs    | 50        | 32.05%  |
| Ufs    | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 154       | 99.35%  |
| MBR  | 1         | 0.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 26        | 16.77%  |
| Lenovo              | 20        | 12.9%   |
| Hewlett-Packard     | 20        | 12.9%   |
| ASUSTek Computer    | 20        | 12.9%   |
| Gigabyte Technology | 13        | 8.39%   |
| MSI                 | 7         | 4.52%   |
| Apple               | 7         | 4.52%   |
| Acer                | 5         | 3.23%   |
| Intel               | 4         | 2.58%   |
| ASRock              | 4         | 2.58%   |
| Toshiba             | 3         | 1.94%   |
| Timi                | 3         | 1.94%   |
| Google              | 3         | 1.94%   |
| TUXEDO              | 2         | 1.29%   |
| Sony                | 2         | 1.29%   |
| Pegatron            | 2         | 1.29%   |
| Packard Bell        | 2         | 1.29%   |
| Star Labs           | 1         | 0.65%   |
| Samsung Electronics | 1         | 0.65%   |
| PCSTICK             | 1         | 0.65%   |
| Panasonic           | 1         | 0.65%   |
| MACHINIST           | 1         | 0.65%   |
| Kraftway            | 1         | 0.65%   |
| HUAWEI              | 1         | 0.65%   |
| Gateway             | 1         | 0.65%   |
| Fujitsu             | 1         | 0.65%   |
| Biostar             | 1         | 0.65%   |
| AMD                 | 1         | 0.65%   |
| Unknown             | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 3         | 1.94%   |
| Unknown                                      | 3         | 1.94%   |
| MSI PS63 Modern 8M                           | 2         | 1.29%   |
| MSI MS-7A38                                  | 2         | 1.29%   |
| HP 250 G6 Notebook PC                        | 2         | 1.29%   |
| Apple MacBookAir5,1                          | 2         | 1.29%   |
| Apple MacBook5,2                             | 2         | 1.29%   |
| TUXEDO Pulse 14 Gen1                         | 1         | 0.65%   |
| TUXEDO Aura 15 Gen1                          | 1         | 0.65%   |
| Toshiba TECRA Z40-C-12Z                      | 1         | 0.65%   |
| Toshiba Satellite S55t-B                     | 1         | 0.65%   |
| Toshiba PORTEGE Z930                         | 1         | 0.65%   |
| Timi TM1701                                  | 1         | 0.65%   |
| Timi TM1607                                  | 1         | 0.65%   |
| Timi RedmiBook Pro 15                        | 1         | 0.65%   |
| Star Labs StarBook                           | 1         | 0.65%   |
| Sony VPCEB1J1E                               | 1         | 0.65%   |
| Sony VGN-AW21S_B                             | 1         | 0.65%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.65%   |
| Pegatron IPPPV-D3G                           | 1         | 0.65%   |
| Pegatron IPM41-D3                            | 1         | 0.65%   |
| Panasonic CF-C1BWFAZ1M                       | 1         | 0.65%   |
| Packard Bell EasyNote_MX52-B-071             | 1         | 0.65%   |
| Packard Bell DOT S                           | 1         | 0.65%   |
| MSI MS-7C37                                  | 1         | 0.65%   |
| MSI MS-7B89                                  | 1         | 0.65%   |
| MSI Modern 15 A5M                            | 1         | 0.65%   |
| MACHINIST X99-k9 V2.0                        | 1         | 0.65%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00        | 1         | 0.65%   |
| Lenovo ThinkPad X250 20CLS23500              | 1         | 0.65%   |
| Lenovo ThinkPad X250 20CLS1WP01              | 1         | 0.65%   |
| Lenovo ThinkPad X1 Tablet 20GHS1UK00         | 1         | 0.65%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon 3448AWU            | 1         | 0.65%   |
| Lenovo ThinkPad W541 20EF000NUS              | 1         | 0.65%   |
| Lenovo ThinkPad T440 20B7A0B7MS              | 1         | 0.65%   |
| Lenovo ThinkPad T420 4178A72                 | 1         | 0.65%   |
| Lenovo ThinkPad P51 20HH001RMX               | 1         | 0.65%   |
| Lenovo ThinkPad P50 20EN0041MX               | 1         | 0.65%   |
| Lenovo ThinkPad P15v Gen 2i 21AAS28T00       | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 8.39%   |
| Dell Latitude          | 9         | 5.81%   |
| Dell Inspiron          | 7         | 4.52%   |
| Dell OptiPlex          | 5         | 3.23%   |
| Acer Aspire            | 5         | 3.23%   |
| HP EliteBook           | 4         | 2.58%   |
| Lenovo ThinkCentre     | 3         | 1.94%   |
| Dell Precision         | 3         | 1.94%   |
| ASUS All               | 3         | 1.94%   |
| Unknown                | 3         | 1.94%   |
| MSI PS63               | 2         | 1.29%   |
| MSI MS-7A38            | 2         | 1.29%   |
| HP Pavilion            | 2         | 1.29%   |
| HP EliteDesk           | 2         | 1.29%   |
| HP Compaq              | 2         | 1.29%   |
| HP 250                 | 2         | 1.29%   |
| Dell Studio            | 2         | 1.29%   |
| ASUS PRIME             | 2         | 1.29%   |
| Apple MacBookAir5      | 2         | 1.29%   |
| Apple MacBook5         | 2         | 1.29%   |
| TUXEDO Pulse           | 1         | 0.65%   |
| TUXEDO Aura            | 1         | 0.65%   |
| Toshiba TECRA          | 1         | 0.65%   |
| Toshiba Satellite      | 1         | 0.65%   |
| Toshiba PORTEGE        | 1         | 0.65%   |
| Timi TM1701            | 1         | 0.65%   |
| Timi TM1607            | 1         | 0.65%   |
| Timi RedmiBook         | 1         | 0.65%   |
| Star Labs StarBook     | 1         | 0.65%   |
| Sony VPCEB1J1E         | 1         | 0.65%   |
| Sony VGN-AW21S         | 1         | 0.65%   |
| Samsung 340XAA         | 1         | 0.65%   |
| Pegatron IPPPV-D3G     | 1         | 0.65%   |
| Pegatron IPM41-D3      | 1         | 0.65%   |
| Panasonic CF-C1BWFAZ1M | 1         | 0.65%   |
| Packard Bell EasyNote  | 1         | 0.65%   |
| Packard Bell DOT       | 1         | 0.65%   |
| MSI MS-7C37            | 1         | 0.65%   |
| MSI MS-7B89            | 1         | 0.65%   |
| MSI Modern             | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 20        | 12.9%   |
| 2020 | 19        | 12.26%  |
| 2018 | 12        | 7.74%   |
| 2022 | 11        | 7.1%    |
| 2015 | 11        | 7.1%    |
| 2013 | 11        | 7.1%    |
| 2014 | 10        | 6.45%   |
| 2012 | 10        | 6.45%   |
| 2011 | 10        | 6.45%   |
| 2021 | 9         | 5.81%   |
| 2017 | 8         | 5.16%   |
| 2010 | 7         | 4.52%   |
| 2009 | 7         | 4.52%   |
| 2016 | 5         | 3.23%   |
| 2008 | 3         | 1.94%   |
| 2023 | 1         | 0.65%   |
| 2007 | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 85        | 54.84%  |
| Desktop     | 63        | 40.65%  |
| All in one  | 3         | 1.94%   |
| Mini pc     | 2         | 1.29%   |
| Tablet      | 1         | 0.65%   |
| Convertible | 1         | 0.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 151       | 97.42%  |
| Yes  | 4         | 2.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 46        | 29.68%  |
| 4.01-8.0    | 45        | 29.03%  |
| 16.01-24.0  | 40        | 25.81%  |
| 32.01-64.0  | 10        | 6.45%   |
| 2.01-3.0    | 7         | 4.52%   |
| 64.01-256.0 | 4         | 2.58%   |
| 24.01-32.0  | 2         | 1.29%   |
| 3.01-4.0    | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 84        | 54.19%  |
| 0.51-1.0  | 42        | 27.1%   |
| 1.01-2.0  | 21        | 13.55%  |
| 2.01-3.0  | 6         | 3.87%   |
| 4.01-8.0  | 1         | 0.65%   |
| 8.01-16.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 101       | 64.74%  |
| 2      | 32        | 20.51%  |
| 3      | 10        | 6.41%   |
| 0      | 7         | 4.49%   |
| 5      | 3         | 1.92%   |
| 4      | 2         | 1.28%   |
| 6      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 72.9%   |
| Yes       | 42        | 27.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 86.45%  |
| No        | 21        | 13.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 71.15%  |
| No        | 45        | 28.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 55.48%  |
| No        | 69        | 44.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 24        | 15.48%  |
| Russia       | 22        | 14.19%  |
| Germany      | 14        | 9.03%   |
| Brazil       | 9         | 5.81%   |
| Spain        | 7         | 4.52%   |
| Taiwan       | 6         | 3.87%   |
| China        | 6         | 3.87%   |
| UK           | 5         | 3.23%   |
| Italy        | 5         | 3.23%   |
| France       | 5         | 3.23%   |
| Canada       | 4         | 2.58%   |
| Ukraine      | 3         | 1.94%   |
| Poland       | 3         | 1.94%   |
| Mexico       | 3         | 1.94%   |
| Argentina    | 3         | 1.94%   |
| Sweden       | 2         | 1.29%   |
| Portugal     | 2         | 1.29%   |
| Norway       | 2         | 1.29%   |
| Ireland      | 2         | 1.29%   |
| Indonesia    | 2         | 1.29%   |
| Hungary      | 2         | 1.29%   |
| Bulgaria     | 2         | 1.29%   |
| Venezuela    | 1         | 0.65%   |
| Uruguay      | 1         | 0.65%   |
| UAE          | 1         | 0.65%   |
| South Africa | 1         | 0.65%   |
| Slovenia     | 1         | 0.65%   |
| Slovakia     | 1         | 0.65%   |
| Serbia       | 1         | 0.65%   |
| Romania      | 1         | 0.65%   |
| Peru         | 1         | 0.65%   |
| Panama       | 1         | 0.65%   |
| Netherlands  | 1         | 0.65%   |
| Nepal        | 1         | 0.65%   |
| Kenya        | 1         | 0.65%   |
| India        | 1         | 0.65%   |
| Greece       | 1         | 0.65%   |
| Georgia      | 1         | 0.65%   |
| Czechia      | 1         | 0.65%   |
| Cyprus       | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 7         | 4.46%   |
| Aquan          | 4         | 2.55%   |
| Berlin         | 3         | 1.91%   |
| Voronezh       | 2         | 1.27%   |
| Volgograd      | 2         | 1.27%   |
| Temple         | 2         | 1.27%   |
| Saratov        | 2         | 1.27%   |
| Perm           | 2         | 1.27%   |
| Munich         | 2         | 1.27%   |
| LogroÃ±o     | 2         | 1.27%   |
| Dublin         | 2         | 1.27%   |
| Dover          | 2         | 1.27%   |
| Blomberg       | 2         | 1.27%   |
| Zhengzhou      | 1         | 0.64%   |
| Yunlin         | 1         | 0.64%   |
| Yekaterinburg  | 1         | 0.64%   |
| Winnipeg       | 1         | 0.64%   |
| Willingboro    | 1         | 0.64%   |
| Weifang        | 1         | 0.64%   |
| Warendorf      | 1         | 0.64%   |
| Vladivostok    | 1         | 0.64%   |
| Villemomble    | 1         | 0.64%   |
| Vidnoye        | 1         | 0.64%   |
| Veliko Tarnovo | 1         | 0.64%   |
| Vancouver      | 1         | 0.64%   |
| Valencia       | 1         | 0.64%   |
| Utrecht        | 1         | 0.64%   |
| Ufa            | 1         | 0.64%   |
| Trieste        | 1         | 0.64%   |
| Tasikmalaya    | 1         | 0.64%   |
| Szeged         | 1         | 0.64%   |
| Surrey         | 1         | 0.64%   |
| Sumaré        | 1         | 0.64%   |
| Southminster   | 1         | 0.64%   |
| Smolyan        | 1         | 0.64%   |
| Shenzhen       | 1         | 0.64%   |
| Seville        | 1         | 0.64%   |
| Sayago         | 1         | 0.64%   |
| Sarajevo       | 1         | 0.64%   |
| Sao Paulo      | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 35     | 15.24%  |
| WDC                 | 27        | 33     | 12.86%  |
| Samsung Electronics | 27        | 32     | 12.86%  |
| Kingston            | 20        | 20     | 9.52%   |
| Toshiba             | 16        | 16     | 7.62%   |
| Hitachi             | 12        | 12     | 5.71%   |
| SanDisk             | 8         | 9      | 3.81%   |
| Intel               | 7         | 7      | 3.33%   |
| Crucial             | 7         | 8      | 3.33%   |
| SK hynix            | 5         | 5      | 2.38%   |
| A-DATA Technology   | 5         | 5      | 2.38%   |
| PNY                 | 4         | 4      | 1.9%    |
| Patriot             | 4         | 4      | 1.9%    |
| KIOXIA              | 3         | 3      | 1.43%   |
| SPCC                | 2         | 2      | 0.95%   |
| OCZ                 | 2         | 2      | 0.95%   |
| KingSpec            | 2         | 2      | 0.95%   |
| Fujitsu             | 2         | 2      | 0.95%   |
| Apple               | 2         | 2      | 0.95%   |
| XrayDisk            | 1         | 1      | 0.48%   |
| Verbatim            | 1         | 1      | 0.48%   |
| Transcend           | 1         | 1      | 0.48%   |
| Star Drive          | 1         | 1      | 0.48%   |
| SSSTC               | 1         | 1      | 0.48%   |
| Silicon Motion      | 1         | 1      | 0.48%   |
| Plextor             | 1         | 1      | 0.48%   |
| Pioneer             | 1         | 1      | 0.48%   |
| OWC                 | 1         | 1      | 0.48%   |
| MidasForce          | 1         | 1      | 0.48%   |
| Lexar               | 1         | 2      | 0.48%   |
| Lenovo              | 1         | 1      | 0.48%   |
| LDLC                | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| Hewlett-Packard     | 1         | 1      | 0.48%   |
| GOODRAM             | 1         | 1      | 0.48%   |
| Gigabyte Technology | 1         | 1      | 0.48%   |
| FORESEE             | 1         | 1      | 0.48%   |
| Fanxiang            | 1         | 1      | 0.48%   |
| Emtec               | 1         | 1      | 0.48%   |
| Dogfish             | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 5         | 2.22%   |
| Kingston SA400S37120G 120GB        | 4         | 1.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.33%   |
| Kingston SA400S37240G 240GB        | 3         | 1.33%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.89%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.89%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.89%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.89%   |
| Toshiba HDWD110 1TB                | 2         | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB     | 2         | 0.89%   |
| Samsung SSD 970 EVO 250GB          | 2         | 0.89%   |
| Samsung SSD 860 PRO 512GB          | 2         | 0.89%   |
| Samsung SSD 860 EVO 1TB            | 2         | 0.89%   |
| Samsung MZNTY128HDHP-00000 128GB   | 2         | 0.89%   |
| PNY CS900 240GB SSD                | 2         | 0.89%   |
| Patriot Burst 120GB                | 2         | 0.89%   |
| Kingston SV300S37A120G 120GB       | 2         | 0.89%   |
| Hitachi HDS721616PLA380 160GB      | 2         | 0.89%   |
| Apple SSD TS128E 121GB             | 2         | 0.89%   |
| A-DATA SX6000LNP 512GB             | 2         | 0.89%   |
| XrayDisk SSD 256GB                 | 1         | 0.44%   |
| WDC WDS500G2X0C-00L350 500GB       | 1         | 0.44%   |
| WDC WDS500G2B0A 500GB              | 1         | 0.44%   |
| WDC WDS500G1B0C-00S6U0 500GB       | 1         | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB       | 1         | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB         | 1         | 0.44%   |
| WDC WDBNCE5000PNC 500GB            | 1         | 0.44%   |
| WDC WD80EFAX-68KNBN0 8TB           | 1         | 0.44%   |
| WDC WD5000LPLX-08ZNTT0 500GB       | 1         | 0.44%   |
| WDC WD5000BPVT-22A1YT0 500GB       | 1         | 0.44%   |
| WDC WD5000AZLX-60K2TA1 500GB       | 1         | 0.44%   |
| WDC WD5000AVVS-63H0B1 500GB        | 1         | 0.44%   |
| WDC WD5000AAKS-00YGA0 500GB        | 1         | 0.44%   |
| WDC WD40NPZZ-00A9JT0 4TB           | 1         | 0.44%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1         | 0.44%   |
| WDC WD2500BEVT-75A23T0 250GB       | 1         | 0.44%   |
| WDC WD2500BEVT-35A23T0 250GB       | 1         | 0.44%   |
| WDC WD20EZAZ-22L9GB0 2TB           | 1         | 0.44%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1         | 0.44%   |
| WDC WD20EARS-00MVWB0 2TB           | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 35     | 39.02%  |
| WDC                 | 22        | 26     | 26.83%  |
| Hitachi             | 12        | 12     | 14.63%  |
| Toshiba             | 11        | 11     | 13.41%  |
| Samsung Electronics | 3         | 3      | 3.66%   |
| Hewlett-Packard     | 1         | 1      | 1.22%   |
| Fujitsu             | 1         | 1      | 1.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 19     | 17.53%  |
| Kingston            | 16        | 16     | 16.49%  |
| SanDisk             | 8         | 9      | 8.25%   |
| Crucial             | 6         | 7      | 6.19%   |
| Intel               | 5         | 5      | 5.15%   |
| WDC                 | 4         | 4      | 4.12%   |
| Toshiba             | 4         | 4      | 4.12%   |
| PNY                 | 4         | 4      | 4.12%   |
| Patriot             | 4         | 4      | 4.12%   |
| A-DATA Technology   | 3         | 3      | 3.09%   |
| SPCC                | 2         | 2      | 2.06%   |
| OCZ                 | 2         | 2      | 2.06%   |
| KingSpec            | 2         | 2      | 2.06%   |
| Apple               | 2         | 2      | 2.06%   |
| XrayDisk            | 1         | 1      | 1.03%   |
| Verbatim            | 1         | 1      | 1.03%   |
| Transcend           | 1         | 1      | 1.03%   |
| SK hynix            | 1         | 1      | 1.03%   |
| Plextor             | 1         | 1      | 1.03%   |
| Pioneer             | 1         | 1      | 1.03%   |
| OWC                 | 1         | 1      | 1.03%   |
| MidasForce          | 1         | 1      | 1.03%   |
| Lexar               | 1         | 1      | 1.03%   |
| Intenso             | 1         | 1      | 1.03%   |
| GOODRAM             | 1         | 1      | 1.03%   |
| Gigabyte Technology | 1         | 1      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |
| FORESEE             | 1         | 1      | 1.03%   |
| Fanxiang            | 1         | 1      | 1.03%   |
| Emtec               | 1         | 1      | 1.03%   |
| Dogfish             | 1         | 1      | 1.03%   |
| China               | 1         | 1      | 1.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 81        | 101    | 44.02%  |
| HDD  | 68        | 89     | 36.96%  |
| NVMe | 35        | 37     | 19.02%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 132       | 190    | 79.04%  |
| NVMe | 35        | 37     | 20.96%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 104       | 135    | 69.33%  |
| 0.51-1.0   | 31        | 35     | 20.67%  |
| 1.01-2.0   | 11        | 15     | 7.33%   |
| 3.01-4.0   | 2         | 2      | 1.33%   |
| 2.01-3.0   | 1         | 2      | 0.67%   |
| 4.01-10.0  | 1         | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 94        | 60.65%  |
| 101-250    | 28        | 18.06%  |
| 251-500    | 18        | 11.61%  |
| 501-1000   | 7         | 4.52%   |
| 21-50      | 3         | 1.94%   |
| 1001-2000  | 2         | 1.29%   |
| 51-100     | 2         | 1.29%   |
| Unknown    | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 148       | 95.48%  |
| 101-250  | 3         | 1.94%   |
| 21-50    | 1         | 0.65%   |
| 501-1000 | 1         | 0.65%   |
| 51-100   | 1         | 0.65%   |
| Unknown  | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                 | 2         | 2      | 6.25%   |
| WDC WD5000AVVS-63H0B1 500GB                  | 1         | 1      | 3.13%   |
| WDC WD2500BEVT-35A23T0 250GB                 | 1         | 1      | 3.13%   |
| WDC WD10EZRZ-00HTKB0 1TB                     | 1         | 1      | 3.13%   |
| WDC WD10EADS-65M2BX 1TB                      | 1         | 1      | 3.13%   |
| WDC WD10EACS-00D6B1 1TB                      | 1         | 1      | 3.13%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 3.13%   |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 3.13%   |
| Toshiba MK3261GSYN 320GB                     | 1         | 1      | 3.13%   |
| Toshiba MK1255GSX H 120GB                    | 1         | 1      | 3.13%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 3.13%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 3.13%   |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 3.13%   |
| Seagate ST320LT012-9WS14C 320GB              | 1         | 1      | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.13%   |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 3.13%   |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 3.13%   |
| Samsung Electronics HD501LJ 500GB            | 1         | 1      | 3.13%   |
| Pioneer APS-SL3N-240 240GB                   | 1         | 1      | 3.13%   |
| OCZ VERTEX3 240GB                            | 1         | 1      | 3.13%   |
| MidasForce SSD 120GB                         | 1         | 1      | 3.13%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 3.13%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 3.13%   |
| Hitachi HTS541680J9SA00 80GB                 | 1         | 1      | 3.13%   |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 3.13%   |
| Hitachi HDS721616PLA380 160GB                | 1         | 1      | 3.13%   |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 21.88%  |
| Seagate             | 7         | 7      | 21.88%  |
| Hitachi             | 6         | 6      | 18.75%  |
| Toshiba             | 5         | 5      | 15.63%  |
| Samsung Electronics | 2         | 2      | 6.25%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Pioneer             | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| MidasForce          | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 25.93%  |
| Seagate             | 7         | 7      | 25.93%  |
| Hitachi             | 6         | 6      | 22.22%  |
| Toshiba             | 5         | 5      | 18.52%  |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 27     | 83.33%  |
| SSD  | 5         | 5      | 16.67%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 124       | 185    | 79.49%  |
| Malfunc  | 27        | 32     | 17.31%  |
| Detected | 5         | 10     | 3.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 112       | 60.22%  |
| AMD                            | 26        | 13.98%  |
| Samsung Electronics            | 9         | 4.84%   |
| Nvidia                         | 5         | 2.69%   |
| SK hynix                       | 4         | 2.15%   |
| SanDisk                        | 4         | 2.15%   |
| Kingston Technology Company    | 4         | 2.15%   |
| JMicron Technology             | 4         | 2.15%   |
| Realtek Semiconductor          | 3         | 1.61%   |
| Toshiba                        | 2         | 1.08%   |
| Silicon Motion                 | 2         | 1.08%   |
| Phison Electronics             | 2         | 1.08%   |
| KIOXIA                         | 2         | 1.08%   |
| Solid State Storage Technology | 1         | 0.54%   |
| Shenzhen Longsys Electronics   | 1         | 0.54%   |
| Micron/Crucial Technology      | 1         | 0.54%   |
| Marvell Technology Group       | 1         | 0.54%   |
| Lite-On IT Corp. / Plextor     | 1         | 0.54%   |
| Lenovo                         | 1         | 0.54%   |
| ASMedia Technology             | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 7.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 6.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 4.25%   |
| Unknown                                                                                 | 7         | 3.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 2.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 2.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.83%   |
| Nvidia MCP79 AHCI Controller                                                            | 5         | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 2.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 5         | 2.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 2.36%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 2.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.89%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 1.42%   |
| Toshiba XG6 NVMe SSD Controller                                                         | 2         | 0.94%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.94%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.94%   |
| JMicron JMB368 IDE controller                                                           | 2         | 0.94%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 0.94%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 0.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 0.94%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 0.94%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2         | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 123       | 65.78%  |
| NVMe | 36        | 19.25%  |
| IDE  | 23        | 12.3%   |
| RAID | 5         | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 127       | 81.94%  |
| AMD    | 28        | 18.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.29%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 2         | 1.29%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 2         | 1.29%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 1.29%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 2         | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.29%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 2         | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.29%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.29%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.29%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 1.29%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2         | 1.29%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.29%   |
| Intel Core 2 Duo                            | 2         | 1.29%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2         | 1.29%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.29%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2         | 1.29%   |
| AMD Phenom II X4 945 Processor              | 2         | 1.29%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1         | 0.65%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1         | 0.65%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1         | 0.65%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.65%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1         | 0.65%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.65%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1         | 0.65%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.65%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.65%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.65%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.65%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.65%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.65%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.65%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.65%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 0.65%   |
| Intel CPU Version                           | 1         | 0.65%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 25.81%  |
| Intel Core i7           | 23        | 14.84%  |
| Intel Core i3           | 12        | 7.74%   |
| Intel Core 2 Duo        | 9         | 5.81%   |
| Intel Celeron           | 9         | 5.81%   |
| Other                   | 8         | 5.16%   |
| Intel Atom              | 6         | 3.87%   |
| AMD Ryzen 5             | 6         | 3.87%   |
| Intel Xeon              | 5         | 3.23%   |
| Intel Pentium Dual-Core | 5         | 3.23%   |
| Intel Pentium           | 4         | 2.58%   |
| AMD Ryzen 7             | 4         | 2.58%   |
| AMD Ryzen 3             | 3         | 1.94%   |
| AMD Phenom II X4        | 3         | 1.94%   |
| Intel Pentium Silver    | 2         | 1.29%   |
| Intel Core m3           | 2         | 1.29%   |
| AMD FX                  | 2         | 1.29%   |
| AMD A10                 | 2         | 1.29%   |
| Intel Core m7           | 1         | 0.65%   |
| Intel Core 2 Quad       | 1         | 0.65%   |
| Intel Core 2            | 1         | 0.65%   |
| AMD V120                | 1         | 0.65%   |
| AMD Ryzen Threadripper  | 1         | 0.65%   |
| AMD Ryzen 9             | 1         | 0.65%   |
| AMD Ryzen 5 PRO         | 1         | 0.65%   |
| AMD Athlon II X4        | 1         | 0.65%   |
| AMD Athlon 64 X2        | 1         | 0.65%   |
| AMD A8                  | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 64        | 41.29%  |
| 4       | 51        | 32.9%   |
| 6       | 9         | 5.81%   |
| 8       | 8         | 5.16%   |
| Unknown | 8         | 5.16%   |
| 16      | 5         | 3.23%   |
| 12      | 5         | 3.23%   |
| 1       | 3         | 1.94%   |
| 24      | 1         | 0.65%   |
| 10      | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 151       | 97.42%  |
| 2      | 4         | 2.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 76        | 49.03%  |
| 1       | 71        | 45.81%  |
| Unknown | 8         | 5.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 16.13%  |
| Skylake       | 15        | 9.68%   |
| Penryn        | 14        | 9.03%   |
| Haswell       | 14        | 9.03%   |
| SandyBridge   | 12        | 7.74%   |
| IvyBridge     | 10        | 6.45%   |
| Broadwell     | 8         | 5.16%   |
| Zen 2         | 6         | 3.87%   |
| Silvermont    | 6         | 3.87%   |
| Unknown       | 6         | 3.87%   |
| K10           | 5         | 3.23%   |
| Zen           | 4         | 2.58%   |
| Piledriver    | 4         | 2.58%   |
| Goldmont plus | 4         | 2.58%   |
| Bonnell       | 4         | 2.58%   |
| Zen+          | 3         | 1.94%   |
| Core          | 3         | 1.94%   |
| Zen 3         | 2         | 1.29%   |
| Westmere      | 2         | 1.29%   |
| TigerLake     | 2         | 1.29%   |
| CometLake     | 2         | 1.29%   |
| Nehalem       | 1         | 0.65%   |
| K8 Hammer     | 1         | 0.65%   |
| Goldmont      | 1         | 0.65%   |
| Excavator     | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 98        | 55.06%  |
| Nvidia | 49        | 27.53%  |
| AMD    | 31        | 17.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 5.62%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.81%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.25%   |
| Intel HD Graphics 530                                                                    | 4         | 2.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.69%   |
| Intel HD Graphics 630                                                                    | 3         | 1.69%   |
| Intel HD Graphics 620                                                                    | 3         | 1.69%   |
| AMD Renoir                                                                               | 3         | 1.69%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2         | 1.12%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 1.12%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 1.12%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.12%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 1.12%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.12%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.12%   |
| Intel HD Graphics 515                                                                    | 2         | 1.12%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.12%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.12%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 2         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.12%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.12%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.12%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.12%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 46.45%  |
| 1 x Nvidia     | 33        | 21.29%  |
| 1 x AMD        | 23        | 14.84%  |
| Intel + Nvidia | 15        | 9.68%   |
| Intel + AMD    | 7         | 4.52%   |
| 2 x Intel      | 4         | 2.58%   |
| AMD + Nvidia   | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 121       | 78.06%  |
| Proprietary | 25        | 16.13%  |
| Unknown     | 9         | 5.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 72.9%   |
| 0.01-0.5   | 13        | 8.39%   |
| 1.01-2.0   | 10        | 6.45%   |
| 0.51-1.0   | 6         | 3.87%   |
| 5.01-6.0   | 5         | 3.23%   |
| 3.01-4.0   | 5         | 3.23%   |
| 7.01-8.0   | 3         | 1.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 12.21%  |
| AU Optronics            | 16        | 12.21%  |
| Samsung Electronics     | 11        | 8.4%    |
| BOE                     | 11        | 8.4%    |
| Chimei Innolux          | 10        | 7.63%   |
| Goldstar                | 8         | 6.11%   |
| Apple                   | 8         | 6.11%   |
| Dell                    | 7         | 5.34%   |
| Hewlett-Packard         | 6         | 4.58%   |
| Acer                    | 6         | 4.58%   |
| Sharp                   | 3         | 2.29%   |
| Philips                 | 3         | 2.29%   |
| MSI                     | 3         | 2.29%   |
| BenQ                    | 3         | 2.29%   |
| AOC                     | 3         | 2.29%   |
| Chi Mei Optoelectronics | 2         | 1.53%   |
| Vizio                   | 1         | 0.76%   |
| ViewSonic               | 1         | 0.76%   |
| Toshiba                 | 1         | 0.76%   |
| TMX                     | 1         | 0.76%   |
| Nvidia                  | 1         | 0.76%   |
| NEC Computers           | 1         | 0.76%   |
| LG Philips              | 1         | 0.76%   |
| Insignia                | 1         | 0.76%   |
| Iiyama                  | 1         | 0.76%   |
| HannStar                | 1         | 0.76%   |
| Fujitsu Siemens         | 1         | 0.76%   |
| CPT                     | 1         | 0.76%   |
| CHD                     | 1         | 0.76%   |
| ASUSTek Computer        | 1         | 0.76%   |
| Ancor Communications    | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 2         | 1.5%    |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2         | 1.5%    |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 1.5%    |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch           | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 2         | 1.5%    |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 1.5%    |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 1.5%    |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2         | 1.5%    |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1         | 0.75%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch            | 1         | 0.75%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1         | 0.75%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 0.75%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 0.75%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch               | 1         | 0.75%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch               | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1         | 0.75%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1         | 0.75%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1         | 0.75%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4244 2160x1440 250x170mm 11.9-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 0.75%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1         | 0.75%   |
| Philips LCD Monitor PHL0868 1680x1050 470x290mm 21.7-inch             | 1         | 0.75%   |
| Philips 237EQPH PHLC091 1920x1080 510x290mm 23.1-inch                 | 1         | 0.75%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 0.75%   |
| NEC Computers LCD175VXM+ NEC66C0 1280x1024 340x270mm 17.1-inch        | 1         | 0.75%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1         | 0.75%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0546 1920x1080 340x190mm 15.3-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 61        | 46.92%  |
| 1366x768 (WXGA)    | 27        | 20.77%  |
| 1600x900 (HD+)     | 7         | 5.38%   |
| 1680x1050 (WSXGA+) | 6         | 4.62%   |
| 1280x800 (WXGA)    | 6         | 4.62%   |
| 2560x1440 (QHD)    | 4         | 3.08%   |
| 3840x2160 (4K)     | 3         | 2.31%   |
| 2560x1080          | 3         | 2.31%   |
| 1280x1024 (SXGA)   | 3         | 2.31%   |
| 3440x1440          | 2         | 1.54%   |
| 1440x900 (WXGA+)   | 2         | 1.54%   |
| 1024x600           | 2         | 1.54%   |
| 3840x2400          | 1         | 0.77%   |
| 3200x2000          | 1         | 0.77%   |
| 2160x1440          | 1         | 0.77%   |
| 1920x1200 (WUXGA)  | 1         | 0.77%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 40        | 30.08%  |
| 13      | 20        | 15.04%  |
| 23      | 8         | 6.02%   |
| 21      | 8         | 6.02%   |
| 12      | 8         | 6.02%   |
| 24      | 7         | 5.26%   |
| 31      | 6         | 4.51%   |
| 27      | 5         | 3.76%   |
| 19      | 5         | 3.76%   |
| 34      | 4         | 3.01%   |
| 17      | 3         | 2.26%   |
| 11      | 3         | 2.26%   |
| 22      | 2         | 1.5%    |
| 20      | 2         | 1.5%    |
| 14      | 2         | 1.5%    |
| 10      | 2         | 1.5%    |
| Unknown | 2         | 1.5%    |
| 50      | 1         | 0.75%   |
| 41      | 1         | 0.75%   |
| 33      | 1         | 0.75%   |
| 26      | 1         | 0.75%   |
| 18      | 1         | 0.75%   |
| 9       | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 41.35%  |
| 201-300     | 23        | 17.29%  |
| 501-600     | 21        | 15.79%  |
| 401-500     | 17        | 12.78%  |
| 601-700     | 6         | 4.51%   |
| 701-800     | 5         | 3.76%   |
| 351-400     | 2         | 1.5%    |
| Unknown     | 2         | 1.5%    |
| 1001-1500   | 1         | 0.75%   |
| 901-1000    | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 100       | 77.52%  |
| 16/10 | 19        | 14.73%  |
| 21/9  | 5         | 3.88%   |
| 5/4   | 3         | 2.33%   |
| 4/3   | 1         | 0.78%   |
| 3/2   | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 33        | 24.81%  |
| 201-250        | 23        | 17.29%  |
| 81-90          | 18        | 13.53%  |
| 351-500        | 11        | 8.27%   |
| 61-70          | 7         | 5.26%   |
| 151-200        | 7         | 5.26%   |
| 301-350        | 6         | 4.51%   |
| 101-110        | 6         | 4.51%   |
| 71-80          | 5         | 3.76%   |
| 41-50          | 3         | 2.26%   |
| 141-150        | 3         | 2.26%   |
| 51-60          | 2         | 1.5%    |
| 251-300        | 2         | 1.5%    |
| 111-120        | 2         | 1.5%    |
| Unknown        | 2         | 1.5%    |
| More than 1000 | 1         | 0.75%   |
| 121-130        | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 32.58%  |
| 101-120       | 37        | 28.03%  |
| 121-160       | 36        | 27.27%  |
| 161-240       | 9         | 6.82%   |
| More than 240 | 4         | 3.03%   |
| Unknown       | 2         | 1.52%   |
| 1-50          | 1         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 131       | 84.52%  |
| 0     | 18        | 11.61%  |
| 2     | 6         | 3.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 86        | 39.09%  |
| Realtek Semiconductor    | 69        | 31.36%  |
| Qualcomm Atheros         | 25        | 11.36%  |
| Broadcom                 | 14        | 6.36%   |
| Nvidia                   | 4         | 1.82%   |
| Ralink Technology        | 3         | 1.36%   |
| Google                   | 3         | 1.36%   |
| TP-Link                  | 2         | 0.91%   |
| Sierra Wireless          | 2         | 0.91%   |
| Samsung Electronics      | 2         | 0.91%   |
| Ralink                   | 2         | 0.91%   |
| Marvell Technology Group | 2         | 0.91%   |
| OPPO Electronics         | 1         | 0.45%   |
| IMC Networks             | 1         | 0.45%   |
| Huawei Technologies      | 1         | 0.45%   |
| Edimax Technology        | 1         | 0.45%   |
| D-Link System            | 1         | 0.45%   |
| ASUSTek Computer         | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 21.32%  |
| Intel Wireless 8265 / 8275                                        | 11        | 4.26%   |
| Intel Wireless 7265                                               | 9         | 3.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.71%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.33%   |
| Intel Wireless 8260                                               | 5         | 1.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.55%   |
| Nvidia MCP79 Ethernet                                             | 4         | 1.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.16%   |
| Intel Wireless 3165                                               | 3         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 1.16%   |
| Sierra Wireless EM7455                                            | 2         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.78%   |
| Intel Wireless 7260                                               | 2         | 0.78%   |
| Intel Wireless 3160                                               | 2         | 0.78%   |
| Intel WiFi Link 5100                                              | 2         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.78%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.78%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 52.54%  |
| Qualcomm Atheros      | 21        | 17.8%   |
| Realtek Semiconductor | 11        | 9.32%   |
| Broadcom              | 11        | 9.32%   |
| Ralink Technology     | 3         | 2.54%   |
| TP-Link               | 2         | 1.69%   |
| Sierra Wireless       | 2         | 1.69%   |
| Ralink                | 2         | 1.69%   |
| IMC Networks          | 1         | 0.85%   |
| Edimax Technology     | 1         | 0.85%   |
| D-Link System         | 1         | 0.85%   |
| ASUSTek Computer      | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 11        | 9.24%   |
| Intel Wireless 7265                                                     | 9         | 7.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 6.72%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 5.04%   |
| Intel Wireless 8260                                                     | 5         | 4.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 3.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.52%   |
| Intel Wireless 3165                                                     | 3         | 2.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.52%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 2.52%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2.52%   |
| Sierra Wireless EM7455                                                  | 2         | 1.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 1.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.68%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.68%   |
| Intel Wireless 7260                                                     | 2         | 1.68%   |
| Intel Wireless 3160                                                     | 2         | 1.68%   |
| Intel WiFi Link 5100                                                    | 2         | 1.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.68%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.68%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.84%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.84%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.84%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.84%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.84%   |
| Intel Wireless Gigabit 17265                                            | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 46.67%  |
| Intel                    | 50        | 37.04%  |
| Qualcomm Atheros         | 7         | 5.19%   |
| Nvidia                   | 4         | 2.96%   |
| Broadcom                 | 4         | 2.96%   |
| Samsung Electronics      | 2         | 1.48%   |
| Marvell Technology Group | 2         | 1.48%   |
| Google                   | 2         | 1.48%   |
| OPPO Electronics         | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 55        | 40.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 5.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 5.11%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 4.38%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 3.65%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 2.92%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 2.92%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 2.19%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 1.46%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.46%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.46%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.46%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.46%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.46%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.46%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.46%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 1.46%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 1.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.73%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.73%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.73%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                                 | 1         | 0.73%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.73%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.73%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.73%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.73%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.73%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 134       | 54.47%  |
| WiFi     | 110       | 44.72%  |
| Modem    | 1         | 0.41%   |
| Unknown  | 1         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 94        | 61.44%  |
| WiFi     | 59        | 38.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 82        | 52.9%   |
| 1     | 72        | 46.45%  |
| 0     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 147       | 94.84%  |
| Yes  | 8         | 5.16%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 55.68%  |
| Cambridge Silicon Radio         | 8         | 9.09%   |
| Apple                           | 8         | 9.09%   |
| Realtek Semiconductor           | 3         | 3.41%   |
| Qualcomm Atheros Communications | 3         | 3.41%   |
| IMC Networks                    | 3         | 3.41%   |
| Broadcom                        | 3         | 3.41%   |
| Lite-On Technology              | 2         | 2.27%   |
| Hewlett-Packard                 | 2         | 2.27%   |
| Alps Electric                   | 2         | 2.27%   |
| Toshiba                         | 1         | 1.14%   |
| Ralink                          | 1         | 1.14%   |
| Integrated System Solution      | 1         | 1.14%   |
| Bluetooth Device                | 1         | 1.14%   |
| ASUSTek Computer                | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 29        | 32.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 8         | 8.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 5         | 5.56%   |
| Intel AX200 Bluetooth                                    | 5         | 5.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 5         | 5.56%   |
| Intel AX201 Bluetooth                                    | 4         | 4.44%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2         | 2.22%   |
| Intel AX210 Bluetooth                                    | 2         | 2.22%   |
| HP Broadcom 2070 Bluetooth Combo                         | 2         | 2.22%   |
| Apple Built-in iSight (no firmware loaded)               | 2         | 2.22%   |
| Apple Apple Broadcom Built-in Bluetooth                  | 2         | 2.22%   |
| Toshiba Bluetooth V4.0 Module (BCM43142Y)                | 1         | 1.11%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1         | 1.11%   |
| Ralink RT3290 Bluetooth                                  | 1         | 1.11%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                  | 1         | 1.11%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth            | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1         | 1.11%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 1.11%   |
| Integrated System Solution Bluetooth Device              | 1         | 1.11%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 1.11%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS  | 1         | 1.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 1.11%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 1         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 1.11%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1         | 1.11%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 1.11%   |
| Apple Bluetooth Host Controller                          | 1         | 1.11%   |
| Alps Electric UGTZ4 Bluetooth                            | 1         | 1.11%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 119       | 59.8%   |
| AMD                 | 33        | 16.58%  |
| Nvidia              | 31        | 15.58%  |
| C-Media Electronics | 5         | 2.51%   |
| Logitech            | 2         | 1.01%   |
| Google              | 2         | 1.01%   |
| Yamaha              | 1         | 0.5%    |
| XMOS                | 1         | 0.5%    |
| Texas Instruments   | 1         | 0.5%    |
| RME                 | 1         | 0.5%    |
| Kingston Technology | 1         | 0.5%    |
| GN Netcom           | 1         | 0.5%    |
| Creative Technology | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 7.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 4.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 4.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.99%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 2.14%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 2.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.14%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.71%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.71%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.28%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.28%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.28%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.28%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.28%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.28%   |
| Unknown                                                                                           | 3         | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Logitech HD Webcam C510                                                                           | 2         | 0.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 37        | 19.47%  |
| Samsung Electronics | 33        | 17.37%  |
| Kingston            | 23        | 12.11%  |
| Unknown             | 22        | 11.58%  |
| Micron Technology   | 19        | 10%     |
| Crucial             | 10        | 5.26%   |
| Unknown             | 6         | 3.16%   |
| G.Skill             | 5         | 2.63%   |
| Transcend           | 4         | 2.11%   |
| A-DATA Technology   | 4         | 2.11%   |
| Smart               | 3         | 1.58%   |
| Ramaxel Technology  | 3         | 1.58%   |
| Nanya Technology    | 3         | 1.58%   |
| Elpida              | 3         | 1.58%   |
| GOODRAM             | 2         | 1.05%   |
| Corsair             | 2         | 1.05%   |
| Unknown (ABCD)      | 1         | 0.53%   |
| Teikon              | 1         | 0.53%   |
| Team                | 1         | 0.53%   |
| Smart Brazil        | 1         | 0.53%   |
| SHARETRONIC         | 1         | 0.53%   |
| Sesame              | 1         | 0.53%   |
| PNY                 | 1         | 0.53%   |
| Patriot             | 1         | 0.53%   |
| GSkill              | 1         | 0.53%   |
| GLOWAY              | 1         | 0.53%   |
| GeIL                | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 6         | 2.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 4         | 1.95%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 3         | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 3         | 1.46%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s         | 3         | 1.46%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2         | 0.98%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 2         | 0.98%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2         | 0.98%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 2         | 0.98%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s              | 2         | 0.98%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.98%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 2         | 0.98%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s          | 2         | 0.98%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 2         | 0.98%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s           | 2         | 0.98%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s           | 2         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                             | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s                     | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.49%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s           | 1         | 0.49%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s           | 1         | 0.49%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s              | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 66        | 42.86%  |
| DDR4    | 64        | 41.56%  |
| DDR2    | 12        | 7.79%   |
| SDRAM   | 4         | 2.6%    |
| Unknown | 4         | 2.6%    |
| LPDDR3  | 3         | 1.95%   |
| LPDDR4  | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 55.77%  |
| DIMM         | 59        | 37.82%  |
| Row Of Chips | 4         | 2.56%   |
| Unknown      | 3         | 1.92%   |
| Chip         | 2         | 1.28%   |
| RIMM         | 1         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 58        | 32.77%  |
| 8192  | 52        | 29.38%  |
| 2048  | 40        | 22.6%   |
| 16384 | 23        | 12.99%  |
| 1024  | 3         | 1.69%   |
| 32768 | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 39        | 23.49%  |
| 2400    | 23        | 13.86%  |
| 1333    | 23        | 13.86%  |
| 3200    | 16        | 9.64%   |
| 2667    | 15        | 9.04%   |
| 2133    | 13        | 7.83%   |
| 800     | 8         | 4.82%   |
| Unknown | 6         | 3.61%   |
| 2666    | 4         | 2.41%   |
| 1867    | 4         | 2.41%   |
| 1334    | 3         | 1.81%   |
| 1067    | 3         | 1.81%   |
| 667     | 3         | 1.81%   |
| 2933    | 2         | 1.2%    |
| 2048    | 1         | 0.6%    |
| 1866    | 1         | 0.6%    |
| 1066    | 1         | 0.6%    |
| 333     | 1         | 0.6%    |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 26.67%  |
| Microdia                               | 12        | 16%     |
| IMC Networks                           | 8         | 10.67%  |
| Sunplus Innovation Technology          | 6         | 8%      |
| Realtek Semiconductor                  | 6         | 8%      |
| Acer                                   | 5         | 6.67%   |
| Apple                                  | 3         | 4%      |
| Z-Star Microelectronics                | 2         | 2.67%   |
| Syntek                                 | 2         | 2.67%   |
| Suyin                                  | 2         | 2.67%   |
| Logitech                               | 2         | 2.67%   |
| Silicon Motion                         | 1         | 1.33%   |
| Luxvisions Innotech Limited            | 1         | 1.33%   |
| Lite-On Technology                     | 1         | 1.33%   |
| Genesys Logic                          | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.33%   |
| Arkmicro Technologies                  | 1         | 1.33%   |
| Alcor Micro                            | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 4         | 5.33%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 4%      |
| Microdia Integrated_Webcam_HD                               | 3         | 4%      |
| Chicony HD Webcam                                           | 3         | 4%      |
| Acer Integrated Camera                                      | 3         | 4%      |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 2.67%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 2.67%   |
| Logitech HD Pro Webcam C920                                 | 2         | 2.67%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 2         | 2.67%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 2.67%   |
| Chicony XiaoMi USB 2.0 Webcam                               | 2         | 2.67%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 2.67%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 2.67%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 1.33%   |
| Z-Star DataMax USB2.0 Camera                                | 1         | 1.33%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 1.33%   |
| Syntek Integrated Camera                                    | 1         | 1.33%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 1.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.33%   |
| Sunplus XiaoMi USB 2.0 Webcam                               | 1         | 1.33%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 1.33%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.33%   |
| Silicon Motion Web Camera                                   | 1         | 1.33%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.33%   |
| Realtek HP HD Webcam [Fixed]                                | 1         | 1.33%   |
| Realtek HD WebCam                                           | 1         | 1.33%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 1.33%   |
| Microdia Webcam                                             | 1         | 1.33%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.33%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 1.33%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 1.33%   |
| Microdia Integrated Webcam HD                               | 1         | 1.33%   |
| Microdia Integrated Webcam                                  | 1         | 1.33%   |
| Microdia Camera                                             | 1         | 1.33%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.33%   |
| Lite-On HP HD Webcam [Fixed]                                | 1         | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 1.33%   |
| IMC Networks Integrated RGB Camera                          | 1         | 1.33%   |
| IMC Networks Integrated Camera                              | 1         | 1.33%   |
| IMC Networks HD Camera                                      | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 56.25%  |
| Synaptics                  | 3         | 18.75%  |
| AuthenTec                  | 2         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| Broadcom                   | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 18.75%  |
| Validity Sensors Synaptics WBDI                                              | 2         | 12.5%   |
| Unknown                                                                      | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 6.25%   |
| AuthenTec AES1600                                                            | 1         | 6.25%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 39.35%  |
| 0     | 42        | 27.1%   |
| 2     | 31        | 20%     |
| 3     | 17        | 10.97%  |
| 4     | 3         | 1.94%   |
| 5     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 95        | 51.35%  |
| Bluetooth                | 29        | 15.68%  |
| Net/wireless             | 20        | 10.81%  |
| Card reader              | 17        | 9.19%   |
| Fingerprint reader       | 15        | 8.11%   |
| Sound                    | 5         | 2.7%    |
| Network                  | 3         | 1.62%   |
| Storage                  | 1         | 0.54%   |

