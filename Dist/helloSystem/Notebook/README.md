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

Total: 1421

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 3542               | [7b61355c62](https://bsd-hardware.info/?probe=7b61355c62) | Jan 02, 2026 |
| Lenovo        | ThinkPad T460 20FMA00F00    | [69e4dd0799](https://bsd-hardware.info/?probe=69e4dd0799) | Dec 27, 2025 |
| Apple         | MacBookPro9,2               | [a4a70bd026](https://bsd-hardware.info/?probe=a4a70bd026) | Dec 26, 2025 |
| Dell          | Latitude E6530              | [a59fc2c1a3](https://bsd-hardware.info/?probe=a59fc2c1a3) | Dec 26, 2025 |
| Apple         | MacBookAir7,2               | [f94a1abe6d](https://bsd-hardware.info/?probe=f94a1abe6d) | Dec 25, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [382db82098](https://bsd-hardware.info/?probe=382db82098) | Dec 18, 2025 |
| HP            | ProBook 430 G2              | [db1c1eb244](https://bsd-hardware.info/?probe=db1c1eb244) | Dec 16, 2025 |
| Dell          | Inspiron 3521               | [c8276a8838](https://bsd-hardware.info/?probe=c8276a8838) | Dec 12, 2025 |
| ASUSTek       | UX303LB                     | [837da689bb](https://bsd-hardware.info/?probe=837da689bb) | Nov 30, 2025 |
| Apple         | MacBook7,1                  | [0ef8b03b05](https://bsd-hardware.info/?probe=0ef8b03b05) | Nov 29, 2025 |
| Alienware     | 17 R3                       | [7d28abe778](https://bsd-hardware.info/?probe=7d28abe778) | Nov 22, 2025 |
| Dell          | Precision M4600             | [a6449e24ba](https://bsd-hardware.info/?probe=a6449e24ba) | Nov 20, 2025 |
| Acer          | Aspire ES1-512              | [3bf0ca53c1](https://bsd-hardware.info/?probe=3bf0ca53c1) | Nov 18, 2025 |
| Dell          | Precision 7510              | [e304ad6b53](https://bsd-hardware.info/?probe=e304ad6b53) | Nov 10, 2025 |
| ASUSTek       | K53SC                       | [924b22d35b](https://bsd-hardware.info/?probe=924b22d35b) | Nov 09, 2025 |
| eMachines     | E527                        | [81e8246163](https://bsd-hardware.info/?probe=81e8246163) | Nov 02, 2025 |
| Lenovo        | Unknown                     | [96d1f6a4ad](https://bsd-hardware.info/?probe=96d1f6a4ad) | Oct 31, 2025 |
| Lenovo        | ThinkPad X220 4291ZFR       | [c7e13a8f2d](https://bsd-hardware.info/?probe=c7e13a8f2d) | Oct 31, 2025 |
| Apple         | MacBookPro7,1               | [f4e3b1813c](https://bsd-hardware.info/?probe=f4e3b1813c) | Oct 31, 2025 |
| ASUSTek       | K52JB                       | [831c17b144](https://bsd-hardware.info/?probe=831c17b144) | Oct 28, 2025 |
| Apple         | MacBookAir4,1               | [682e6afdb7](https://bsd-hardware.info/?probe=682e6afdb7) | Oct 21, 2025 |
| eMachines     | eM350                       | [d170a6f699](https://bsd-hardware.info/?probe=d170a6f699) | Oct 17, 2025 |
| Acer          | Aspire E1-570               | [c862bcedb5](https://bsd-hardware.info/?probe=c862bcedb5) | Oct 11, 2025 |
| BenQ          | Joybook Lite U105i          | [ab622b4793](https://bsd-hardware.info/?probe=ab622b4793) | Oct 05, 2025 |
| Dell          | Latitude E6400              | [45c2c1f321](https://bsd-hardware.info/?probe=45c2c1f321) | Sep 30, 2025 |
| ASUSTek       | X555QG                      | [d3ff0c7e7b](https://bsd-hardware.info/?probe=d3ff0c7e7b) | Sep 27, 2025 |
| Acer          | Nitro AN515-43              | [4ca8bb5762](https://bsd-hardware.info/?probe=4ca8bb5762) | Sep 25, 2025 |
| HP            | EliteBook 850 G7 Noteboo... | [e111a98c7e](https://bsd-hardware.info/?probe=e111a98c7e) | Sep 24, 2025 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [1409bf720e](https://bsd-hardware.info/?probe=1409bf720e) | Sep 23, 2025 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [5498e09a7c](https://bsd-hardware.info/?probe=5498e09a7c) | Sep 21, 2025 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [92e349dd86](https://bsd-hardware.info/?probe=92e349dd86) | Sep 20, 2025 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [52687cfcbb](https://bsd-hardware.info/?probe=52687cfcbb) | Sep 06, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [b4dfb3fe25](https://bsd-hardware.info/?probe=b4dfb3fe25) | Sep 04, 2025 |
| Chuwi         | FreeBook                    | [97e46a6e1d](https://bsd-hardware.info/?probe=97e46a6e1d) | Sep 03, 2025 |
| Acidanther... | MacBookPro12,1              | [794c5d7f0a](https://bsd-hardware.info/?probe=794c5d7f0a) | Sep 02, 2025 |
| LG Electro... | 14Z960-GP5IL                | [75c2349878](https://bsd-hardware.info/?probe=75c2349878) | Sep 01, 2025 |
| Toshiba       | Satellite L870              | [116b976cef](https://bsd-hardware.info/?probe=116b976cef) | Sep 01, 2025 |
| Acer          | Aspire E5-574               | [83363756fe](https://bsd-hardware.info/?probe=83363756fe) | Aug 31, 2025 |
| HASEE Comp... | N960Kx                      | [be67a81c28](https://bsd-hardware.info/?probe=be67a81c28) | Aug 29, 2025 |
| Apple         | MacBookAir5,1               | [052f8e7d66](https://bsd-hardware.info/?probe=052f8e7d66) | Aug 27, 2025 |
| Lenovo        | ThinkPad T60 200757U        | [3927aea578](https://bsd-hardware.info/?probe=3927aea578) | Aug 13, 2025 |
| Lenovo        | ThinkPad T60 200757U        | [1d212095eb](https://bsd-hardware.info/?probe=1d212095eb) | Aug 13, 2025 |
| Fujitsu       | CELSIUS H710                | [7a452d60ae](https://bsd-hardware.info/?probe=7a452d60ae) | Aug 06, 2025 |
| Lenovo        | ThinkPad L420 782746U       | [45d26a88f2](https://bsd-hardware.info/?probe=45d26a88f2) | Aug 05, 2025 |
| Apple         | MacBookPro9,2               | [99124c137a](https://bsd-hardware.info/?probe=99124c137a) | Aug 04, 2025 |
| Acer          | Aspire V3-571G              | [6e28f345f2](https://bsd-hardware.info/?probe=6e28f345f2) | Jul 30, 2025 |
| Fujitsu Si... | CELSIUS H270                | [17532c205c](https://bsd-hardware.info/?probe=17532c205c) | Jul 30, 2025 |
| Dell          | Inspiron 5559               | [04e7a6f515](https://bsd-hardware.info/?probe=04e7a6f515) | Jul 28, 2025 |
| Dell          | Inspiron 5559               | [83fb8af9ba](https://bsd-hardware.info/?probe=83fb8af9ba) | Jul 28, 2025 |
| Lenovo        | B470e HuronRiver Platfor... | [a4e9b01ed3](https://bsd-hardware.info/?probe=a4e9b01ed3) | Jul 21, 2025 |
| Lenovo        | IdeaPadFlex 15 20309        | [d8fcb45611](https://bsd-hardware.info/?probe=d8fcb45611) | Jul 16, 2025 |
| Lenovo        | ThinkPad T430 2349CTO       | [2c62e80103](https://bsd-hardware.info/?probe=2c62e80103) | Jul 13, 2025 |
| Dell          | Inspiron 5770               | [dd915fa06f](https://bsd-hardware.info/?probe=dd915fa06f) | Jul 13, 2025 |
| Acer          | Aspire A315-23              | [c99285530d](https://bsd-hardware.info/?probe=c99285530d) | Jul 08, 2025 |
| Acer          | Aspire A315-23              | [2a25ab1af4](https://bsd-hardware.info/?probe=2a25ab1af4) | Jul 08, 2025 |
| Lenovo        | ThinkPad E15 20RD005HUS     | [27bc961fcd](https://bsd-hardware.info/?probe=27bc961fcd) | Jul 05, 2025 |
| Apple         | MacBookAir7,2               | [3a129a1bbc](https://bsd-hardware.info/?probe=3a129a1bbc) | Jul 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9e4e99a77d](https://bsd-hardware.info/?probe=9e4e99a77d) | Jun 26, 2025 |
| Apple         | MacBook4,1                  | [22fdd3b950](https://bsd-hardware.info/?probe=22fdd3b950) | Jun 20, 2025 |
| Dell          | Inspiron 1520               | [6fbe37c316](https://bsd-hardware.info/?probe=6fbe37c316) | Jun 19, 2025 |
| Dell          | Latitude E5540              | [1673f60df4](https://bsd-hardware.info/?probe=1673f60df4) | Jun 16, 2025 |
| HP            | ProBook 440 G3              | [e98046a043](https://bsd-hardware.info/?probe=e98046a043) | May 31, 2025 |
| MSI           | Modern 15 F13MG             | [1e4f28f01d](https://bsd-hardware.info/?probe=1e4f28f01d) | May 28, 2025 |
| ASUSTek       | K84HR                       | [d153180727](https://bsd-hardware.info/?probe=d153180727) | May 11, 2025 |
| Lenovo        | ThinkPad T450 20BUS26K07    | [8c23f251b4](https://bsd-hardware.info/?probe=8c23f251b4) | May 09, 2025 |
| LG Electro... | Z360-G.BG71P1               | [ee691a990c](https://bsd-hardware.info/?probe=ee691a990c) | May 08, 2025 |
| Multilaser    | UB22X                       | [fdc94fecc9](https://bsd-hardware.info/?probe=fdc94fecc9) | May 05, 2025 |
| Toshiba       | PORTEGE R930                | [0a9fabff21](https://bsd-hardware.info/?probe=0a9fabff21) | May 04, 2025 |
| Dell          | Latitude 3350               | [135d776f4f](https://bsd-hardware.info/?probe=135d776f4f) | May 03, 2025 |
| Lenovo        | ThinkPad X240 20AMS7M800    | [e39734e519](https://bsd-hardware.info/?probe=e39734e519) | May 01, 2025 |
| Lenovo        | ThinkPad X61s 76673EJ       | [cfe34864ff](https://bsd-hardware.info/?probe=cfe34864ff) | Apr 24, 2025 |
| Positivo      | S14BW01                     | [4eb5ebcf6d](https://bsd-hardware.info/?probe=4eb5ebcf6d) | Apr 22, 2025 |
| Apple         | MacBookPro11,2              | [e509e895ef](https://bsd-hardware.info/?probe=e509e895ef) | Apr 19, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e2270ae1bb](https://bsd-hardware.info/?probe=e2270ae1bb) | Apr 18, 2025 |
| Dell          | Precision M4800             | [9cc1c2089d](https://bsd-hardware.info/?probe=9cc1c2089d) | Apr 14, 2025 |
| Dell          | Precision M4800             | [7dddf66c8c](https://bsd-hardware.info/?probe=7dddf66c8c) | Apr 14, 2025 |
| Dell          | G5 5505                     | [68c2a37c22](https://bsd-hardware.info/?probe=68c2a37c22) | Apr 10, 2025 |
| ASUSTek       | X555LB                      | [712d49a30c](https://bsd-hardware.info/?probe=712d49a30c) | Apr 10, 2025 |
| ASUSTek       | X555LB                      | [60f8c81294](https://bsd-hardware.info/?probe=60f8c81294) | Apr 10, 2025 |
| Lenovo        | ThinkPad W530 24384FG       | [14e1094401](https://bsd-hardware.info/?probe=14e1094401) | Apr 08, 2025 |
| Toshiba       | Satellite U500              | [d1831ac8a5](https://bsd-hardware.info/?probe=d1831ac8a5) | Apr 04, 2025 |
| Dell          | Latitude 3450               | [8ef9fa6a4d](https://bsd-hardware.info/?probe=8ef9fa6a4d) | Mar 25, 2025 |
| HP            | ProBook 6470b               | [c4b73a523c](https://bsd-hardware.info/?probe=c4b73a523c) | Mar 24, 2025 |
| Dell          | Latitude E6540              | [d36a68717a](https://bsd-hardware.info/?probe=d36a68717a) | Mar 24, 2025 |
| Dell          | Vostro 5471                 | [f8e21968bd](https://bsd-hardware.info/?probe=f8e21968bd) | Mar 22, 2025 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [b4c15f0f7b](https://bsd-hardware.info/?probe=b4c15f0f7b) | Mar 19, 2025 |
| Dell          | Latitude 3420               | [0fd9295c89](https://bsd-hardware.info/?probe=0fd9295c89) | Mar 17, 2025 |
| Dell          | Latitude E6430              | [b3cd44d807](https://bsd-hardware.info/?probe=b3cd44d807) | Mar 15, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9294266766](https://bsd-hardware.info/?probe=9294266766) | Mar 15, 2025 |
| Panasonic     | CFSZ6-2                     | [1b784b035f](https://bsd-hardware.info/?probe=1b784b035f) | Mar 15, 2025 |
| Fujitsu       | LIFEBOOK U745               | [51a0ad3f62](https://bsd-hardware.info/?probe=51a0ad3f62) | Mar 14, 2025 |
| Lenovo        | G500 20236                  | [79165cce66](https://bsd-hardware.info/?probe=79165cce66) | Mar 13, 2025 |
| HP            | ENVY Laptop 17-da0xxx       | [5c09a6b720](https://bsd-hardware.info/?probe=5c09a6b720) | Mar 13, 2025 |
| Acer          | Swift SF316-51              | [5089137bb4](https://bsd-hardware.info/?probe=5089137bb4) | Mar 12, 2025 |
| Lenovo        | ThinkPad E14 20RBS3Q000     | [ddb3503b7b](https://bsd-hardware.info/?probe=ddb3503b7b) | Mar 12, 2025 |
| Dell          | Inspiron One 2310           | [13c9c06011](https://bsd-hardware.info/?probe=13c9c06011) | Mar 11, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [35f4485666](https://bsd-hardware.info/?probe=35f4485666) | Mar 11, 2025 |
| Dell          | Latitude E6420              | [38f99c7eee](https://bsd-hardware.info/?probe=38f99c7eee) | Mar 10, 2025 |
| Apple         | MacBook5,1                  | [8c618c0e44](https://bsd-hardware.info/?probe=8c618c0e44) | Mar 09, 2025 |
| HONOR         | BRN-HXX                     | [b560f90081](https://bsd-hardware.info/?probe=b560f90081) | Feb 19, 2025 |
| Acer          | AOHAPPY2                    | [b8495fa045](https://bsd-hardware.info/?probe=b8495fa045) | Feb 15, 2025 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [8d5ce1eca6](https://bsd-hardware.info/?probe=8d5ce1eca6) | Feb 15, 2025 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [350016d15c](https://bsd-hardware.info/?probe=350016d15c) | Feb 06, 2025 |
| Apple         | MacBookPro11,1              | [fc93b80fe3](https://bsd-hardware.info/?probe=fc93b80fe3) | Jan 29, 2025 |
| Haier         | T6-C                        | [06b37e1a45](https://bsd-hardware.info/?probe=06b37e1a45) | Jan 26, 2025 |
| Dell          | G15 5535                    | [16231c1f0d](https://bsd-hardware.info/?probe=16231c1f0d) | Jan 24, 2025 |
| Fujitsu       | LIFEBOOK E549               | [2afbf7fe2f](https://bsd-hardware.info/?probe=2afbf7fe2f) | Jan 23, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [22637a1fba](https://bsd-hardware.info/?probe=22637a1fba) | Jan 20, 2025 |
| Lenovo        | IdeaPad S145-15API 81V7     | [4bd0423b13](https://bsd-hardware.info/?probe=4bd0423b13) | Jan 05, 2025 |
| Dell          | Latitude E5520              | [e8415a5758](https://bsd-hardware.info/?probe=e8415a5758) | Jan 05, 2025 |
| HP            | EliteBook 840 G3            | [5e09879203](https://bsd-hardware.info/?probe=5e09879203) | Jan 03, 2025 |
| Dell          | Latitude E7250              | [dbff7c2ebb](https://bsd-hardware.info/?probe=dbff7c2ebb) | Jan 02, 2025 |
| Dell          | Inspiron 3421               | [0cae3b71cd](https://bsd-hardware.info/?probe=0cae3b71cd) | Dec 31, 2024 |
| Lenovo        | V15-ADA 82C7                | [62c66a5499](https://bsd-hardware.info/?probe=62c66a5499) | Dec 29, 2024 |
| Lenovo        | V15-ADA 82C7                | [67ea149c61](https://bsd-hardware.info/?probe=67ea149c61) | Dec 29, 2024 |
| Radio Vict... | A24Win8                     | [f85030bb1a](https://bsd-hardware.info/?probe=f85030bb1a) | Dec 27, 2024 |
| Radio Vict... | A24Win8                     | [17813c478e](https://bsd-hardware.info/?probe=17813c478e) | Dec 27, 2024 |
| Dell          | Precision M2800             | [176ae44ed3](https://bsd-hardware.info/?probe=176ae44ed3) | Dec 25, 2024 |
| Dell          | Inspiron 3458               | [c90d1d5857](https://bsd-hardware.info/?probe=c90d1d5857) | Dec 24, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | [9fe06419eb](https://bsd-hardware.info/?probe=9fe06419eb) | Dec 21, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | [86efb87e9e](https://bsd-hardware.info/?probe=86efb87e9e) | Dec 21, 2024 |
| HP            | 2000                        | [0705a401f8](https://bsd-hardware.info/?probe=0705a401f8) | Dec 16, 2024 |
| HP            | ProBook 4430s               | [45102636ac](https://bsd-hardware.info/?probe=45102636ac) | Dec 16, 2024 |
| Apple         | MacBookPro11,1              | [0aea251037](https://bsd-hardware.info/?probe=0aea251037) | Dec 13, 2024 |
| Acer          | Aspire 5755G                | [474ddb6777](https://bsd-hardware.info/?probe=474ddb6777) | Dec 08, 2024 |
| ASUSTek       | N550JV                      | [43db70e6e9](https://bsd-hardware.info/?probe=43db70e6e9) | Dec 07, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [196fb6634a](https://bsd-hardware.info/?probe=196fb6634a) | Dec 03, 2024 |
| Sony          | VGN-FZ11MR                  | [0d1d0647c3](https://bsd-hardware.info/?probe=0d1d0647c3) | Dec 01, 2024 |
| HP            | ProBook 430 G2              | [9cfdbbc839](https://bsd-hardware.info/?probe=9cfdbbc839) | Nov 29, 2024 |
| Sony          | VGN-FZ11MR                  | [9d737dbace](https://bsd-hardware.info/?probe=9d737dbace) | Nov 28, 2024 |
| Acer          | Nitro AN515-46              | [d66960aa84](https://bsd-hardware.info/?probe=d66960aa84) | Nov 24, 2024 |
| Fujitsu       | LIFEBOOK T730               | [577dc596e5](https://bsd-hardware.info/?probe=577dc596e5) | Nov 23, 2024 |
| Fujitsu       | LIFEBOOK T730               | [b5cfe0c0b2](https://bsd-hardware.info/?probe=b5cfe0c0b2) | Nov 23, 2024 |
| HP            | 255 G7 Notebook PC          | [9422dbf997](https://bsd-hardware.info/?probe=9422dbf997) | Nov 22, 2024 |
| Dell          | Vostro 3400                 | [65071f6e52](https://bsd-hardware.info/?probe=65071f6e52) | Nov 18, 2024 |
| ASUSTek       | K54C                        | [4f0c073344](https://bsd-hardware.info/?probe=4f0c073344) | Nov 12, 2024 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [4bcf1051ee](https://bsd-hardware.info/?probe=4bcf1051ee) | Nov 09, 2024 |
| HP            | Laptop 14-cf2xxx            | [b5a01ca528](https://bsd-hardware.info/?probe=b5a01ca528) | Nov 05, 2024 |
| Apple         | MacBook7,1                  | [056bc64a0c](https://bsd-hardware.info/?probe=056bc64a0c) | Nov 03, 2024 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [fa70f945fe](https://bsd-hardware.info/?probe=fa70f945fe) | Nov 03, 2024 |
| ASUSTek       | GL752VW                     | [efc1d86951](https://bsd-hardware.info/?probe=efc1d86951) | Nov 02, 2024 |
| Positivo      | H14BT58                     | [b54614c603](https://bsd-hardware.info/?probe=b54614c603) | Oct 31, 2024 |
| Acer          | Aspire 5755G                | [fddb380732](https://bsd-hardware.info/?probe=fddb380732) | Oct 31, 2024 |
| Lenovo        | ThinkPad X280 20KES2VQ00    | [d864971168](https://bsd-hardware.info/?probe=d864971168) | Oct 30, 2024 |
| HP            | Pavilion Notebook           | [4609004e3e](https://bsd-hardware.info/?probe=4609004e3e) | Oct 30, 2024 |
| ASUSTek       | X453SA                      | [51933883d6](https://bsd-hardware.info/?probe=51933883d6) | Oct 29, 2024 |
| Apple         | MacBook5,2                  | [959da1d116](https://bsd-hardware.info/?probe=959da1d116) | Oct 29, 2024 |
| Lenovo        | ThinkPad E470 20H1002FLM    | [d11900e726](https://bsd-hardware.info/?probe=d11900e726) | Oct 25, 2024 |
| Lenovo        | ThinkPad X201T 3093A79      | [9f1d2db1a6](https://bsd-hardware.info/?probe=9f1d2db1a6) | Oct 25, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | [934ff561a5](https://bsd-hardware.info/?probe=934ff561a5) | Oct 20, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | [6c6e16db1a](https://bsd-hardware.info/?probe=6c6e16db1a) | Oct 19, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | [37cb237ce2](https://bsd-hardware.info/?probe=37cb237ce2) | Oct 07, 2024 |
| Medion        | S15449                      | [b7a0fc4f21](https://bsd-hardware.info/?probe=b7a0fc4f21) | Oct 06, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | [12b6d4abf3](https://bsd-hardware.info/?probe=12b6d4abf3) | Oct 06, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | [74e780b044](https://bsd-hardware.info/?probe=74e780b044) | Oct 05, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [370c96e120](https://bsd-hardware.info/?probe=370c96e120) | Oct 02, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [71dbda24c3](https://bsd-hardware.info/?probe=71dbda24c3) | Oct 02, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [4713dcbd2c](https://bsd-hardware.info/?probe=4713dcbd2c) | Oct 02, 2024 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [c1a712cb6a](https://bsd-hardware.info/?probe=c1a712cb6a) | Sep 30, 2024 |
| Sony          | VGN-FZ19VN                  | [a5e398c41f](https://bsd-hardware.info/?probe=a5e398c41f) | Sep 28, 2024 |
| TUXEDO        | Aura 15 Gen1                | [0f0cf20fe9](https://bsd-hardware.info/?probe=0f0cf20fe9) | Sep 28, 2024 |
| Acer          | Aspire 4820                 | [2ba56db0c4](https://bsd-hardware.info/?probe=2ba56db0c4) | Sep 26, 2024 |
| Apple         | MacBook6,1                  | [6b5e02a63b](https://bsd-hardware.info/?probe=6b5e02a63b) | Sep 22, 2024 |
| Dell          | Latitude E6440              | [cfabb27e7a](https://bsd-hardware.info/?probe=cfabb27e7a) | Sep 21, 2024 |
| Dell          | Latitude E6540              | [e8bdb7007b](https://bsd-hardware.info/?probe=e8bdb7007b) | Sep 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8657f5a0d9](https://bsd-hardware.info/?probe=8657f5a0d9) | Sep 19, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [f2a74cd513](https://bsd-hardware.info/?probe=f2a74cd513) | Sep 17, 2024 |
| ASUSTek       | X540SC                      | [6eb57b9354](https://bsd-hardware.info/?probe=6eb57b9354) | Sep 13, 2024 |
| Dell          | Latitude E7440              | [0e95a909ad](https://bsd-hardware.info/?probe=0e95a909ad) | Sep 11, 2024 |
| HP            | Mini 210-1000               | [5271409065](https://bsd-hardware.info/?probe=5271409065) | Sep 11, 2024 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [2fd4b148bb](https://bsd-hardware.info/?probe=2fd4b148bb) | Sep 06, 2024 |
| HP            | Stream Notebook             | [7d427180ae](https://bsd-hardware.info/?probe=7d427180ae) | Aug 30, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | [d5e4a58748](https://bsd-hardware.info/?probe=d5e4a58748) | Aug 27, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d74ebfd0d0](https://bsd-hardware.info/?probe=d74ebfd0d0) | Aug 19, 2024 |
| Intelbras     | S41ILx                      | [85e9cf50b4](https://bsd-hardware.info/?probe=85e9cf50b4) | Aug 16, 2024 |
| ASUSTek       | 1215N                       | [0970f34b42](https://bsd-hardware.info/?probe=0970f34b42) | Aug 15, 2024 |
| HP            | ProBook 640 G2              | [fa5e1f0cae](https://bsd-hardware.info/?probe=fa5e1f0cae) | Aug 11, 2024 |
| Lenovo        | ThinkPad X270 20HMA04EJP    | [d515224367](https://bsd-hardware.info/?probe=d515224367) | Aug 09, 2024 |
| Lenovo        | ThinkPad T520 4243FS9       | [664d48690e](https://bsd-hardware.info/?probe=664d48690e) | Aug 08, 2024 |
| Fujitsu       | CELSIUS H710                | [dc35b855e5](https://bsd-hardware.info/?probe=dc35b855e5) | Jul 31, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3RV0... | [271f4b1030](https://bsd-hardware.info/?probe=271f4b1030) | Jul 27, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3RV0... | [a5fe1bd04d](https://bsd-hardware.info/?probe=a5fe1bd04d) | Jul 27, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [2bad6a4269](https://bsd-hardware.info/?probe=2bad6a4269) | Jul 26, 2024 |
| Toshiba       | QOSMIO F60                  | [fadd162caa](https://bsd-hardware.info/?probe=fadd162caa) | Jul 25, 2024 |
| Dell          | Latitude 3410               | [c5b69d8cf7](https://bsd-hardware.info/?probe=c5b69d8cf7) | Jul 23, 2024 |
| HP            | Pavilion dv7                | [5178909b84](https://bsd-hardware.info/?probe=5178909b84) | Jul 21, 2024 |
| HP            | Pavilion g6                 | [19ddfa696d](https://bsd-hardware.info/?probe=19ddfa696d) | Jul 20, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [c043693b87](https://bsd-hardware.info/?probe=c043693b87) | Jul 17, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [b66947b74a](https://bsd-hardware.info/?probe=b66947b74a) | Jul 16, 2024 |
| Lenovo        | ThinkPad X200 7459WT6       | [fa49267388](https://bsd-hardware.info/?probe=fa49267388) | Jul 13, 2024 |
| HP            | Compaq Presario CQ71        | [45d3874955](https://bsd-hardware.info/?probe=45d3874955) | Jul 13, 2024 |
| HP            | EliteBook 820 G1            | [0de2223643](https://bsd-hardware.info/?probe=0de2223643) | Jul 11, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [0529ba7873](https://bsd-hardware.info/?probe=0529ba7873) | Jul 09, 2024 |
| Lenovo        | ThinkPad X230 2325SCM       | [8406cad5be](https://bsd-hardware.info/?probe=8406cad5be) | Jul 06, 2024 |
| Lenovo        | M30-70 20446                | [fd24cae390](https://bsd-hardware.info/?probe=fd24cae390) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [e9a1a61239](https://bsd-hardware.info/?probe=e9a1a61239) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [babc2efc9e](https://bsd-hardware.info/?probe=babc2efc9e) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [0251872176](https://bsd-hardware.info/?probe=0251872176) | Jun 26, 2024 |
| HP            | ZBook 17 G3                 | [6b15cd05af](https://bsd-hardware.info/?probe=6b15cd05af) | Jun 26, 2024 |
| HP            | Laptop 14-cf1xxx            | [a0118881e6](https://bsd-hardware.info/?probe=a0118881e6) | Jun 20, 2024 |
| HP            | Laptop 14-cf1xxx            | [70254105eb](https://bsd-hardware.info/?probe=70254105eb) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [fb23c3c64b](https://bsd-hardware.info/?probe=fb23c3c64b) | Jun 18, 2024 |
| HP            | Pavilion dv6500             | [49f31626da](https://bsd-hardware.info/?probe=49f31626da) | Jun 16, 2024 |
| Dell          | Latitude E6410              | [30f7b05dcf](https://bsd-hardware.info/?probe=30f7b05dcf) | Jun 15, 2024 |
| Framework     | Laptop                      | [f43baabeee](https://bsd-hardware.info/?probe=f43baabeee) | Jun 12, 2024 |
| Fujitsu       | CELSIUS H710                | [93308d8e8e](https://bsd-hardware.info/?probe=93308d8e8e) | Jun 11, 2024 |
| Notebook      | W740SU                      | [31be7db967](https://bsd-hardware.info/?probe=31be7db967) | Jun 09, 2024 |
| Fujitsu       | LIFEBOOK E751               | [c4e275f1a2](https://bsd-hardware.info/?probe=c4e275f1a2) | Jun 08, 2024 |
| ASUSTek       | X555LAB                     | [cc126b0787](https://bsd-hardware.info/?probe=cc126b0787) | Jun 06, 2024 |
| ASUSTek       | X555LAB                     | [20959ef447](https://bsd-hardware.info/?probe=20959ef447) | Jun 05, 2024 |
| ASUSTek       | X555UJ                      | [df9f681ce9](https://bsd-hardware.info/?probe=df9f681ce9) | Jun 05, 2024 |
| Toshiba       | Satellite C800D             | [3b26adb52f](https://bsd-hardware.info/?probe=3b26adb52f) | Jun 05, 2024 |
| Sony          | SVF1521G6EW                 | [b977d6f1e0](https://bsd-hardware.info/?probe=b977d6f1e0) | Jun 02, 2024 |
| Dell          | Latitude E7250              | [b5504e5573](https://bsd-hardware.info/?probe=b5504e5573) | Jun 02, 2024 |
| HP            | Laptop 14s-dy5xxx           | [76d2f8d955](https://bsd-hardware.info/?probe=76d2f8d955) | May 28, 2024 |
| ASUSTek       | N50Vc                       | [69d37366c1](https://bsd-hardware.info/?probe=69d37366c1) | May 27, 2024 |
| Toshiba       | Satellite A110              | [df367f56ee](https://bsd-hardware.info/?probe=df367f56ee) | May 26, 2024 |
| HP            | Compaq Presario CQ71        | [ddf13477d5](https://bsd-hardware.info/?probe=ddf13477d5) | May 24, 2024 |
| Thomson       | N15C                        | [45c095d0c8](https://bsd-hardware.info/?probe=45c095d0c8) | May 23, 2024 |
| HP            | EliteBook 840 G2            | [ac725cc2bd](https://bsd-hardware.info/?probe=ac725cc2bd) | May 22, 2024 |
| HP            | OMEN by Laptop              | [7148244e3e](https://bsd-hardware.info/?probe=7148244e3e) | May 21, 2024 |
| HP            | Compaq Presario CQ71        | [7646daa3c0](https://bsd-hardware.info/?probe=7646daa3c0) | May 19, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [98429d1dc9](https://bsd-hardware.info/?probe=98429d1dc9) | May 19, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | [dc41ec80ef](https://bsd-hardware.info/?probe=dc41ec80ef) | May 14, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | [9bc81955aa](https://bsd-hardware.info/?probe=9bc81955aa) | May 08, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | [651bd2de24](https://bsd-hardware.info/?probe=651bd2de24) | May 08, 2024 |
| Acer          | Aspire R3-131T              | [dec4102ec0](https://bsd-hardware.info/?probe=dec4102ec0) | May 07, 2024 |
| Lenovo        | ThinkPad L420 7827W27       | [5231c79a27](https://bsd-hardware.info/?probe=5231c79a27) | May 05, 2024 |
| Apple         | MacBook4,1                  | [5916d9274d](https://bsd-hardware.info/?probe=5916d9274d) | May 05, 2024 |
| Apple         | MacBookPro5,5               | [ffd31a143f](https://bsd-hardware.info/?probe=ffd31a143f) | May 04, 2024 |
| MSI           | GE75 Raider 10SFS           | [227924f274](https://bsd-hardware.info/?probe=227924f274) | May 03, 2024 |
| Lenovo        | Legion Y7000P 81HC          | [3dff76a9dd](https://bsd-hardware.info/?probe=3dff76a9dd) | Apr 27, 2024 |
| Apple         | MacBookAir4,1               | [a6e153110d](https://bsd-hardware.info/?probe=a6e153110d) | Apr 22, 2024 |
| Lenovo        | B51-30 80LK                 | [c1435ee19d](https://bsd-hardware.info/?probe=c1435ee19d) | Apr 21, 2024 |
| HP            | OMEN by Laptop              | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Apple         | MacBookPro8,1               | [6778d6844d](https://bsd-hardware.info/?probe=6778d6844d) | Apr 17, 2024 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [8e3f536127](https://bsd-hardware.info/?probe=8e3f536127) | Apr 16, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [0de254980a](https://bsd-hardware.info/?probe=0de254980a) | Apr 16, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| ASUSTek       | N76VZ                       | [c1af06bf99](https://bsd-hardware.info/?probe=c1af06bf99) | Apr 12, 2024 |
| Acer          | Aspire A314-35              | [6d4fa8616c](https://bsd-hardware.info/?probe=6d4fa8616c) | Apr 09, 2024 |
| Dell          | Latitude E5530 non-vPro     | [227f0ffb18](https://bsd-hardware.info/?probe=227f0ffb18) | Apr 09, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [21768f1b7a](https://bsd-hardware.info/?probe=21768f1b7a) | Apr 04, 2024 |
| Acer          | Aspire V5-431               | [9abe9b5007](https://bsd-hardware.info/?probe=9abe9b5007) | Apr 03, 2024 |
| Lenovo        | ThinkPad W530 2447GH2       | [0cb3f41765](https://bsd-hardware.info/?probe=0cb3f41765) | Apr 01, 2024 |
| Apple         | MacBookAir3,1               | [b6dc892e24](https://bsd-hardware.info/?probe=b6dc892e24) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | [4a80e4b570](https://bsd-hardware.info/?probe=4a80e4b570) | Mar 31, 2024 |
| HUAWEI        | BOHB-WAX9                   | [b46f6ead5d](https://bsd-hardware.info/?probe=b46f6ead5d) | Mar 28, 2024 |
| Lenovo        | N22 80S6                    | [7f8b876a83](https://bsd-hardware.info/?probe=7f8b876a83) | Mar 26, 2024 |
| Lenovo        | G510 20238                  | [faf771068a](https://bsd-hardware.info/?probe=faf771068a) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0fbac8264b](https://bsd-hardware.info/?probe=0fbac8264b) | Mar 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| ASUSTek       | X550CA                      | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| HP            | EliteBook 8470p             | [51841c9dfd](https://bsd-hardware.info/?probe=51841c9dfd) | Mar 17, 2024 |
| Apple         | MacBookPro11,1              | [58369a2ff3](https://bsd-hardware.info/?probe=58369a2ff3) | Mar 16, 2024 |
| Lenovo        | G580 20150                  | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| Lenovo        | ThinkPad X220 429147U       | [0644799933](https://bsd-hardware.info/?probe=0644799933) | Mar 15, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [fd60868096](https://bsd-hardware.info/?probe=fd60868096) | Mar 10, 2024 |
| Dell          | Latitude E6220              | [5a42aa442f](https://bsd-hardware.info/?probe=5a42aa442f) | Mar 09, 2024 |
| Maibenben     | MaiBook X series            | [2a58491971](https://bsd-hardware.info/?probe=2a58491971) | Mar 03, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [3653895b8e](https://bsd-hardware.info/?probe=3653895b8e) | Mar 03, 2024 |
| Acer          | Aspire A715-75G             | [415aa43c5c](https://bsd-hardware.info/?probe=415aa43c5c) | Mar 02, 2024 |
| ASUSTek       | X550EA                      | [42b10a3b6a](https://bsd-hardware.info/?probe=42b10a3b6a) | Mar 01, 2024 |
| Itautec       | Infoway                     | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9c88473675](https://bsd-hardware.info/?probe=9c88473675) | Feb 27, 2024 |
| ASUSTek       | X550EA                      | [a49aa7d3d8](https://bsd-hardware.info/?probe=a49aa7d3d8) | Feb 24, 2024 |
| Lenovo        | ThinkPad X220 4290KV8       | [9bc55d7f8a](https://bsd-hardware.info/?probe=9bc55d7f8a) | Feb 23, 2024 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | [5702ec8e8e](https://bsd-hardware.info/?probe=5702ec8e8e) | Feb 22, 2024 |
| Notebook      | N960Kx                      | [4e83c12f96](https://bsd-hardware.info/?probe=4e83c12f96) | Feb 12, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [47f57b0893](https://bsd-hardware.info/?probe=47f57b0893) | Feb 11, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [5315513827](https://bsd-hardware.info/?probe=5315513827) | Feb 11, 2024 |
| Lenovo        | ThinkPad T480 20L6SDA400    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| ASUSTek       | K52F                        | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| Panasonic     | CF-52PGNBX2M                | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| ASUSTek       | F8Vr                        | [2f3b6a6089](https://bsd-hardware.info/?probe=2f3b6a6089) | Feb 03, 2024 |
| ASUSTek       | K52F                        | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| Dell          | XPS 15 9530                 | [f9481e59b6](https://bsd-hardware.info/?probe=f9481e59b6) | Feb 01, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | [952fa413fe](https://bsd-hardware.info/?probe=952fa413fe) | Feb 01, 2024 |
| ASUSTek       | K50IJ                       | [b5cc2ab7ff](https://bsd-hardware.info/?probe=b5cc2ab7ff) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | [a952b43f14](https://bsd-hardware.info/?probe=a952b43f14) | Jan 31, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | [b66edf2033](https://bsd-hardware.info/?probe=b66edf2033) | Jan 31, 2024 |
| Fujitsu       | LIFEBOOK LH772              | [afe4fb6608](https://bsd-hardware.info/?probe=afe4fb6608) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK LH772              | [491823db1e](https://bsd-hardware.info/?probe=491823db1e) | Jan 30, 2024 |
| HP            | OMEN by Laptop 17-ck0xxx    | [8cad8e084d](https://bsd-hardware.info/?probe=8cad8e084d) | Jan 28, 2024 |
| Lenovo        | ThinkPad T460 20FMS1VA1D    | [03d11c45e9](https://bsd-hardware.info/?probe=03d11c45e9) | Jan 28, 2024 |
| Acer          | Nitro AN515-54              | [94f04895fe](https://bsd-hardware.info/?probe=94f04895fe) | Jan 27, 2024 |
| Dell          | Precision M4700             | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Acer          | Nitro AN515-54              | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Apple         | MacBookAir4,1               | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [2065609a0c](https://bsd-hardware.info/?probe=2065609a0c) | Jan 19, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [62abffe402](https://bsd-hardware.info/?probe=62abffe402) | Jan 19, 2024 |
| Dell          | Latitude 7480               | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| HP            | Mini 210-1000               | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| Star Labs     | StarBook                    | [1e903acb93](https://bsd-hardware.info/?probe=1e903acb93) | Jan 16, 2024 |
| HP            | Mini 210-1000               | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [20090cb5c6](https://bsd-hardware.info/?probe=20090cb5c6) | Jan 15, 2024 |
| Apple         | MacBookAir4,1               | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| Dell          | Inspiron 14-3452            | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [40b8a056f7](https://bsd-hardware.info/?probe=40b8a056f7) | Jan 07, 2024 |
| Dell          | XPS 15 9530                 | [13f09671ce](https://bsd-hardware.info/?probe=13f09671ce) | Jan 07, 2024 |
| ASUSTek       | X551MA                      | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| Lenovo        | ThinkPad X250 20CMS01M00    | [1f52525bb9](https://bsd-hardware.info/?probe=1f52525bb9) | Jan 04, 2024 |
| ASUSTek       | X555LB                      | [45a80466a3](https://bsd-hardware.info/?probe=45a80466a3) | Jan 04, 2024 |
| Samsung       | R510/P510                   | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| Dell          | Vostro V130                 | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Acer          | Aspire E5-574               | [8b71e16af3](https://bsd-hardware.info/?probe=8b71e16af3) | Dec 27, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| AMI           | Intel                       | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Lenovo        | ThinkPad X250 20CLS8Q601    | [2c52684baa](https://bsd-hardware.info/?probe=2c52684baa) | Dec 25, 2023 |
| eMachines     | eM350                       | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| Acer          | V5-131                      | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| Intel         | H81U                        | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Samsung       | N150P/N210P/N220P           | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| Dell          | Latitude E5540              | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| Toshiba       | Satellite C40-A             | [0c545b75e9](https://bsd-hardware.info/?probe=0c545b75e9) | Nov 21, 2023 |
| Toshiba       | Satellite C40-A             | [cecd389c82](https://bsd-hardware.info/?probe=cecd389c82) | Nov 21, 2023 |
| Dell          | XPS 13 9360                 | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | [fc54b10db3](https://bsd-hardware.info/?probe=fc54b10db3) | Nov 18, 2023 |
| Acer          | Aspire ES1-572              | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| Dell          | Precision 7720              | [65a0287ad6](https://bsd-hardware.info/?probe=65a0287ad6) | Nov 16, 2023 |
| Dell          | Inspiron 1525               | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| Dell          | Inspiron 3442               | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b85df96058](https://bsd-hardware.info/?probe=b85df96058) | Nov 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Gateway       | NV79                        | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Dell          | Inspiron 5570               | [1f6c70fd78](https://bsd-hardware.info/?probe=1f6c70fd78) | Nov 07, 2023 |
| HP            | Pavilion g6                 | [6e2c3d13a4](https://bsd-hardware.info/?probe=6e2c3d13a4) | Nov 07, 2023 |
| Dell          | Precision 7720              | [45614f0ff9](https://bsd-hardware.info/?probe=45614f0ff9) | Nov 06, 2023 |
| Dell          | Inspiron N4050              | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| Dell          | Precision 7720              | [ef59e0f80d](https://bsd-hardware.info/?probe=ef59e0f80d) | Nov 05, 2023 |
| Lenovo        | Z50-70 20354                | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| Dell          | Precision 7720              | [cc321f8dea](https://bsd-hardware.info/?probe=cc321f8dea) | Nov 01, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| HP            | Pavilion g6                 | [6aee98fb1a](https://bsd-hardware.info/?probe=6aee98fb1a) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Toshiba       | Unknown                     | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Acer          | Aspire 5336                 | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Dell          | Inspiron 5559               | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | Latitude 3440               | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | [0aa91c2a5c](https://bsd-hardware.info/?probe=0aa91c2a5c) | Oct 15, 2023 |
| Acer          | Aspire ES1-571              | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| Toshiba       | Satellite C55-A             | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Apple         | MacBook5,1                  | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Dell          | Latitude D830               | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| ASUSTek       | K73E                        | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| Apple         | MacBookPro9,1               | [9b9f826560](https://bsd-hardware.info/?probe=9b9f826560) | Oct 01, 2023 |
| ASUSTek       | K40IN                       | [f98d4be34d](https://bsd-hardware.info/?probe=f98d4be34d) | Sep 29, 2023 |
| Dell          | Latitude E6430              | [bec165c243](https://bsd-hardware.info/?probe=bec165c243) | Sep 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| OEGStone      | doceo 510                   | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| Acer          | Monserrat                   | [9c79dbac8b](https://bsd-hardware.info/?probe=9c79dbac8b) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | [d615a8daba](https://bsd-hardware.info/?probe=d615a8daba) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | [6f5db06303](https://bsd-hardware.info/?probe=6f5db06303) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| HP            | Pavilion g7                 | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| ASUSTek       | K40IN                       | [00a4f6e5a0](https://bsd-hardware.info/?probe=00a4f6e5a0) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| ASUSTek       | 1005PXD                     | [8dac93d19d](https://bsd-hardware.info/?probe=8dac93d19d) | Sep 03, 2023 |
| ASUSTek       | K40IN                       | [df0a3f55c2](https://bsd-hardware.info/?probe=df0a3f55c2) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| Apple         | MacBookPro7,1               | [d49b8413db](https://bsd-hardware.info/?probe=d49b8413db) | Sep 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9b322dc202](https://bsd-hardware.info/?probe=9b322dc202) | Sep 02, 2023 |
| MSI           | CX62 6QD                    | [4356e5b30f](https://bsd-hardware.info/?probe=4356e5b30f) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| HP            | 2000                        | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| Toshiba       | Satellite S55t-B            | [c2ed5fa6bd](https://bsd-hardware.info/?probe=c2ed5fa6bd) | Aug 30, 2023 |
| Dell          | Latitude E4310              | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| HP            | Pavilion dv3500             | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Fujitsu       | FMVA0803D                   | [36528b957c](https://bsd-hardware.info/?probe=36528b957c) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| Toshiba       | Satellite S55t-B            | [eb85f0b975](https://bsd-hardware.info/?probe=eb85f0b975) | Aug 27, 2023 |
| Fujitsu       | FMVA0803D                   | [8ce6118bf4](https://bsd-hardware.info/?probe=8ce6118bf4) | Aug 26, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Dell          | Latitude E6420              | [a085ba3865](https://bsd-hardware.info/?probe=a085ba3865) | Aug 25, 2023 |
| NVN-ED01      | Unknown                     | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [c32aad1b1f](https://bsd-hardware.info/?probe=c32aad1b1f) | Aug 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| Star Labs     | Lite                        | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| ASUSTek       | X553MA                      | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| Acer          | Aspire V3-371               | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9693a5fc69](https://bsd-hardware.info/?probe=9693a5fc69) | Aug 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| Compaq        | Presario CQ-17              | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| HP            | EliteBook 840 G5            | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| Dell          | Latitude 5480               | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [1b3ba2b86a](https://bsd-hardware.info/?probe=1b3ba2b86a) | Jul 25, 2023 |
| ASUSTek       | 1015PX                      | [b0745153e4](https://bsd-hardware.info/?probe=b0745153e4) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Panasonic     | CF-F9JYFNDR                 | [be7b261f26](https://bsd-hardware.info/?probe=be7b261f26) | Jul 21, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| ASUSTek       | X541UVK                     | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| Dell          | Latitude E6420              | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| HP            | Compaq Presario CQ61        | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| ASUSTek       | 1005PXD                     | [246032ee65](https://bsd-hardware.info/?probe=246032ee65) | Jul 02, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Dell          | Inspiron 5570               | [a6e959358f](https://bsd-hardware.info/?probe=a6e959358f) | Jun 25, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-bs1xx             | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Acer          | Aspire 5749                 | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| Apple         | MacBook7,1                  | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| ASUSTek       | 1015P                       | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| ASUSTek       | 1015BX                      | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| Lenovo        | S10-3                       | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Panasonic     | CF-NX1GDHYS                 | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Pavilion Notebook           | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Apple         | MacBookPro10,2              | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| Fujitsu       | Unknown                     | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [a2726e621b](https://bsd-hardware.info/?probe=a2726e621b) | May 25, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| ASUSTek       | K42Jc                       | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Google        | Sentry                      | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| Sony          | VPCEG15FB                   | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Apple         | MacBookPro10,1              | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| HP            | ZBook 15 G3                 | [4965fc4251](https://bsd-hardware.info/?probe=4965fc4251) | May 21, 2023 |
| Packard Be... | EasyNote LJ65               | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| Sony          | SVF14A15CBB                 | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| HP            | Laptop 14-bs0xx             | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Acer          | V5-131                      | [9d3ba324bc](https://bsd-hardware.info/?probe=9d3ba324bc) | May 06, 2023 |
| Lenovo        | Flex 2-15 20405             | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [f899593f61](https://bsd-hardware.info/?probe=f899593f61) | May 01, 2023 |
| Dell          | Latitude E5570              | [98e3f9821b](https://bsd-hardware.info/?probe=98e3f9821b) | Apr 29, 2023 |
| HP            | ProBook 640 G4              | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [7caed06fdb](https://bsd-hardware.info/?probe=7caed06fdb) | Apr 24, 2023 |
| Google        | Peppy                       | [d162160498](https://bsd-hardware.info/?probe=d162160498) | Apr 24, 2023 |
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
| ASUSTek       | X200MA                      | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| Google        | Wolf                        | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| ASUSTek       | X58C                        | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| Acer          | Aspire 5745DG               | [2b8bf9802e](https://bsd-hardware.info/?probe=2b8bf9802e) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| LG Electro... | COLUMBIA                    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| HP            | EliteBook Folio 9470m       | [ea2865cbf5](https://bsd-hardware.info/?probe=ea2865cbf5) | Mar 26, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| Dell          | Latitude 5500               | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [83ee1d297d](https://bsd-hardware.info/?probe=83ee1d297d) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| MECHREVO S... | S1 Series                   | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
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
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| HP            | Laptop 15-bs1xx             | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| Lenovo        | ThinkPad X230 23252G8       | [2ff46d6b7c](https://bsd-hardware.info/?probe=2ff46d6b7c) | Mar 10, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [aafc670aa7](https://bsd-hardware.info/?probe=aafc670aa7) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| ASUSTek       | 1201N                       | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| Lenovo        | G400s 20244                 | [215f16c5d9](https://bsd-hardware.info/?probe=215f16c5d9) | Mar 05, 2023 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [8037475831](https://bsd-hardware.info/?probe=8037475831) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Acer          | TravelMate TX50-G2          | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| HP            | G62                         | [18487b3ab2](https://bsd-hardware.info/?probe=18487b3ab2) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Notebook      | N2x0WU                      | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [115bd3bc38](https://bsd-hardware.info/?probe=115bd3bc38) | Feb 26, 2023 |
| Dell          | Inspiron 15 3515            | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Toshiba       | dynabook R63/P              | [c41c3adfa4](https://bsd-hardware.info/?probe=c41c3adfa4) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [b3e56e9656](https://bsd-hardware.info/?probe=b3e56e9656) | Feb 25, 2023 |
| Dell          | Latitude 5591               | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| HP            | EliteBook 840 G1            | [0480ce43f2](https://bsd-hardware.info/?probe=0480ce43f2) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Plaisio       | Turbo X                     | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| HP            | EliteBook 840 G1            | [77c17e4a2f](https://bsd-hardware.info/?probe=77c17e4a2f) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Acer          | Aspire E1-421               | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [92bca4d026](https://bsd-hardware.info/?probe=92bca4d026) | Feb 19, 2023 |
| Lenovo        | G400s 20244                 | [f2c258a0ae](https://bsd-hardware.info/?probe=f2c258a0ae) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Google        | Lulu                        | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
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
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [97da411601](https://bsd-hardware.info/?probe=97da411601) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [a8ec146fc6](https://bsd-hardware.info/?probe=a8ec146fc6) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| Monster       | ABRA A7 V11.2               | [3e58da5c30](https://bsd-hardware.info/?probe=3e58da5c30) | Feb 02, 2023 |
| Unknown       | Unknown                     | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3309453ed5](https://bsd-hardware.info/?probe=3309453ed5) | Feb 02, 2023 |
| HP            | Mini 210-1000               | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| Acer          | Aspire ES1-520              | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| Dell          | Precision 5540              | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Razer         | Blade Stealth               | [c0b9641604](https://bsd-hardware.info/?probe=c0b9641604) | Jan 29, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [aed5292edc](https://bsd-hardware.info/?probe=aed5292edc) | Jan 28, 2023 |
| Packard Be... | DOT S                       | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [6914f6aab5](https://bsd-hardware.info/?probe=6914f6aab5) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Acer          | ES1-131-C2BM                | [400ef90a79](https://bsd-hardware.info/?probe=400ef90a79) | Jan 28, 2023 |
| Dell          | Latitude 5400               | [a266199ace](https://bsd-hardware.info/?probe=a266199ace) | Jan 27, 2023 |
| Acer          | Aspire E3-112               | [513c7ff4be](https://bsd-hardware.info/?probe=513c7ff4be) | Jan 27, 2023 |
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
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [8ae819f673](https://bsd-hardware.info/?probe=8ae819f673) | Jan 21, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [3497ee2fcc](https://bsd-hardware.info/?probe=3497ee2fcc) | Jan 21, 2023 |
| Lenovo        | B40-70 80F30005BR           | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| HP            | Pavilion dv6                | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| HP            | Pavilion dv6                | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [ceb79702f2](https://bsd-hardware.info/?probe=ceb79702f2) | Jan 13, 2023 |
| Razer         | Blade Stealth               | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| HP            | 2000                        | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Sony          | VPCSB11FX                   | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| Dell          | Inspiron 15-3552            | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Lenovo        | G510 20238                  | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| HP            | Pavilion dv4                | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| Apple         | MacBook3,1                  | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| HP            | 2000                        | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| HP            | 245 G6                      | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| HASEE Comp... | N95XKP6                     | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Dell          | Inspiron 3442               | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Lenovo        | Legion Y7000P 81HC          | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| GPD           | P3 MAX                      | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Apple         | MacBook5,1                  | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| Dell          | Inspiron 5558               | [10bece0518](https://bsd-hardware.info/?probe=10bece0518) | Nov 27, 2022 |
| Acer          | Aspire 5738                 | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| ASUSTek       | K55VD                       | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [e32a104392](https://bsd-hardware.info/?probe=e32a104392) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4d92a3b73](https://bsd-hardware.info/?probe=a4d92a3b73) | Nov 23, 2022 |
| Dell          | Latitude D630               | [1c600cc283](https://bsd-hardware.info/?probe=1c600cc283) | Nov 18, 2022 |
| Acer          | Aspire 5251                 | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7650f7619d](https://bsd-hardware.info/?probe=7650f7619d) | Nov 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2294352c5a](https://bsd-hardware.info/?probe=2294352c5a) | Nov 08, 2022 |
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
| helloSystem 0.8.1 | 357       | 30.18%  |
| helloSystem 0.7.0 | 227       | 19.19%  |
| helloSystem 0.8.0 | 135       | 11.41%  |
| helloSystem 0.9.0 | 133       | 11.24%  |
| helloSystem 0.5.0 | 116       | 9.81%   |
| helloSystem 0.4.0 | 92        | 7.78%   |
| helloSystem 0.6.0 | 74        | 6.26%   |
| helloSystem 0.8.2 | 34        | 2.87%   |
| helloSystem 0.3.0 | 14        | 1.18%   |
| helloSystem       | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 1100      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 1100      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 1085      | 98.28%  |
| GNOME        | 6         | 0.54%   |
| KDE5         | 5         | 0.45%   |
| XFCE         | 2         | 0.18%   |
| Window Maker | 1         | 0.09%   |
| TWM          | 1         | 0.09%   |
| LXQt         | 1         | 0.09%   |
| JWM          | 1         | 0.09%   |
| IceWM        | 1         | 0.09%   |
| Cinnamon     | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 1100      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 1097      | 99.46%  |
| SDDM    | 3         | 0.27%   |
| GDM     | 2         | 0.18%   |
| LightDM | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 711       | 62.1%   |
| Unknown      | 125       | 10.92%  |
| fr_FR        | 52        | 4.54%   |
| en           | 51        | 4.45%   |
| ru_RU        | 36        | 3.14%   |
| de_DE        | 32        | 2.79%   |
| es_ES        | 28        | 2.45%   |
| it_IT        | 17        | 1.48%   |
| pt_BR        | 14        | 1.22%   |
| pl_PL        | 12        | 1.05%   |
| zh_CN        | 7         | 0.61%   |
| ru           | 6         | 0.52%   |
| pt           | 6         | 0.52%   |
| nl_NL        | 6         | 0.52%   |
| de           | 6         | 0.52%   |
| es           | 5         | 0.44%   |
| C            | 5         | 0.44%   |
| tr_TR        | 3         | 0.26%   |
| fi_FI        | 3         | 0.26%   |
| zh_TW        | 2         | 0.17%   |
| pt_PT        | 2         | 0.17%   |
| ko_KR        | 2         | 0.17%   |
| jp_JP        | 2         | 0.17%   |
| it           | 2         | 0.17%   |
| fr           | 2         | 0.17%   |
| uk_UA        | 1         | 0.09%   |
| sv           | 1         | 0.09%   |
| pl           | 1         | 0.09%   |
| nl           | 1         | 0.09%   |
| LANG="en_US" | 1         | 0.09%   |
| fi_DK        | 1         | 0.09%   |
| en_UK        | 1         | 0.09%   |
| en_GB        | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1045      | 94.48%  |
| BIOS | 61        | 5.52%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 688       | 61.26%  |
| Cd9660 | 434       | 38.65%  |
| Ufs    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 1095      | 99.55%  |
| MBR  | 5         | 0.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 323       | 29.36%  |
| Dell                    | 158       | 14.36%  |
| Hewlett-Packard         | 151       | 13.73%  |
| ASUSTek Computer        | 101       | 9.18%   |
| Apple                   | 71        | 6.45%   |
| Acer                    | 71        | 6.45%   |
| Toshiba                 | 35        | 3.18%   |
| Samsung Electronics     | 25        | 2.27%   |
| Fujitsu                 | 19        | 1.73%   |
| Sony                    | 15        | 1.36%   |
| MSI                     | 11        | 1%      |
| Packard Bell            | 8         | 0.73%   |
| LG Electronics          | 8         | 0.73%   |
| Panasonic               | 7         | 0.64%   |
| Google                  | 7         | 0.64%   |
| Notebook                | 6         | 0.55%   |
| eMachines               | 5         | 0.45%   |
| TUXEDO                  | 4         | 0.36%   |
| Timi                    | 4         | 0.36%   |
| Star Labs               | 3         | 0.27%   |
| Positivo                | 3         | 0.27%   |
| Medion                  | 3         | 0.27%   |
| Itautec                 | 3         | 0.27%   |
| HUAWEI                  | 3         | 0.27%   |
| HASEE Computer          | 3         | 0.27%   |
| Gateway                 | 3         | 0.27%   |
| Fujitsu Siemens         | 3         | 0.27%   |
| Alienware               | 3         | 0.27%   |
| Razer                   | 2         | 0.18%   |
| MECHREVO S1 Series      | 2         | 0.18%   |
| Intel                   | 2         | 0.18%   |
| Clevo                   | 2         | 0.18%   |
| Chuwi                   | 2         | 0.18%   |
| WYSE                    | 1         | 0.09%   |
| TWINHEAD                | 1         | 0.09%   |
| Thomson                 | 1         | 0.09%   |
| SLIMBOOK                | 1         | 0.09%   |
| Semp Toshiba            | 1         | 0.09%   |
| Radio Victoria Fueguina | 1         | 0.09%   |
| Plaisio                 | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Apple MacBookPro9,2            | 8         | 0.73%   |
| Apple MacBook4,1               | 8         | 0.73%   |
| Unknown                        | 8         | 0.73%   |
| Dell Inspiron 3442             | 6         | 0.55%   |
| HP Pavilion dv6                | 5         | 0.45%   |
| HP 2000                        | 5         | 0.45%   |
| Dell Latitude E6420            | 5         | 0.45%   |
| Apple MacBookAir5,1            | 5         | 0.45%   |
| Apple MacBook5,1               | 5         | 0.45%   |
| HP Pavilion Notebook           | 4         | 0.36%   |
| HP Pavilion g6                 | 4         | 0.36%   |
| HP EliteBook 840 G3            | 4         | 0.36%   |
| Dell Latitude E6540            | 4         | 0.36%   |
| Dell Latitude E5570            | 4         | 0.36%   |
| Apple MacBookPro5,5            | 4         | 0.36%   |
| Acer Aspire ES1-533            | 4         | 0.36%   |
| Lenovo Z50-70 20354            | 3         | 0.27%   |
| Lenovo IdeaPad S145-15IWL 81MV | 3         | 0.27%   |
| Lenovo IdeaPad 110S-11IBR 80WG | 3         | 0.27%   |
| Lenovo G500 20236              | 3         | 0.27%   |
| HP Notebook                    | 3         | 0.27%   |
| Dell Precision 7710            | 3         | 0.27%   |
| Dell Latitude E6410            | 3         | 0.27%   |
| Dell Latitude E4310            | 3         | 0.27%   |
| Dell Latitude D630             | 3         | 0.27%   |
| Dell Latitude 7280             | 3         | 0.27%   |
| Dell Inspiron 7520             | 3         | 0.27%   |
| Dell Inspiron 3521             | 3         | 0.27%   |
| Dell Inspiron 3421             | 3         | 0.27%   |
| Dell Inspiron 15-3567          | 3         | 0.27%   |
| Apple MacBookPro8,1            | 3         | 0.27%   |
| Apple MacBookPro11,1           | 3         | 0.27%   |
| Apple MacBookAir4,1            | 3         | 0.27%   |
| Apple MacBook7,1               | 3         | 0.27%   |
| Apple MacBook6,1               | 3         | 0.27%   |
| Apple MacBook5,2               | 3         | 0.27%   |
| TUXEDO Aura 15 Gen1            | 2         | 0.18%   |
| Toshiba Satellite U500         | 2         | 0.18%   |
| Toshiba PORTEGE R930           | 2         | 0.18%   |
| Timi TM1701                    | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 217       | 19.73%  |
| Dell Latitude         | 81        | 7.36%   |
| Acer Aspire           | 54        | 4.91%   |
| Dell Inspiron         | 46        | 4.18%   |
| Lenovo IdeaPad        | 45        | 4.09%   |
| HP Pavilion           | 37        | 3.36%   |
| HP EliteBook          | 24        | 2.18%   |
| Toshiba Satellite     | 21        | 1.91%   |
| HP Laptop             | 19        | 1.73%   |
| HP ProBook            | 17        | 1.55%   |
| ASUS VivoBook         | 15        | 1.36%   |
| Fujitsu LIFEBOOK      | 14        | 1.27%   |
| Dell Precision        | 12        | 1.09%   |
| Apple MacBookPro9     | 9         | 0.82%   |
| Lenovo Yoga           | 8         | 0.73%   |
| Apple MacBook5        | 8         | 0.73%   |
| Apple MacBook4        | 8         | 0.73%   |
| Unknown               | 8         | 0.73%   |
| Lenovo Legion         | 7         | 0.64%   |
| HP Compaq             | 7         | 0.64%   |
| Toshiba PORTEGE       | 6         | 0.55%   |
| Packard Bell EasyNote | 6         | 0.55%   |
| Dell XPS              | 6         | 0.55%   |
| Dell Vostro           | 6         | 0.55%   |
| Apple MacBookPro5     | 6         | 0.55%   |
| HP ZBook              | 5         | 0.45%   |
| HP OMEN               | 5         | 0.45%   |
| HP 2000               | 5         | 0.45%   |
| Apple MacBookPro11    | 5         | 0.45%   |
| Apple MacBookAir5     | 5         | 0.45%   |
| Acer TravelMate       | 5         | 0.45%   |
| HP 255                | 4         | 0.36%   |
| ASUS ASUS             | 4         | 0.36%   |
| Apple MacBookAir4     | 4         | 0.36%   |
| Acer Nitro            | 4         | 0.36%   |
| Toshiba dynabook      | 3         | 0.27%   |
| Lenovo Z50-70         | 3         | 0.27%   |
| Lenovo ThinkBook      | 3         | 0.27%   |
| Lenovo G500           | 3         | 0.27%   |
| Itautec Infoway       | 3         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 100       | 9.09%   |
| 2012    | 92        | 8.36%   |
| 2011    | 87        | 7.91%   |
| 2020    | 85        | 7.73%   |
| 2016    | 82        | 7.45%   |
| 2019    | 70        | 6.36%   |
| 2015    | 66        | 6%      |
| 2014    | 66        | 6%      |
| 2010    | 65        | 5.91%   |
| 2017    | 62        | 5.64%   |
| 2018    | 59        | 5.36%   |
| 2009    | 59        | 5.36%   |
| 2021    | 53        | 4.82%   |
| 2022    | 46        | 4.18%   |
| 2008    | 43        | 3.91%   |
| 2023    | 24        | 2.18%   |
| 2007    | 22        | 2%      |
| 2024    | 9         | 0.82%   |
| 2006    | 7         | 0.64%   |
| Unknown | 2         | 0.18%   |
| 2025    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1100      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1088      | 98.91%  |
| Yes  | 12        | 1.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 417       | 37.74%  |
| 4.01-8.0    | 350       | 31.67%  |
| 16.01-24.0  | 208       | 18.82%  |
| 2.01-3.0    | 59        | 5.34%   |
| 32.01-64.0  | 38        | 3.44%   |
| 3.01-4.0    | 21        | 1.9%    |
| 24.01-32.0  | 7         | 0.63%   |
| 64.01-256.0 | 5         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 690       | 62.44%  |
| 0.51-1.0  | 299       | 27.06%  |
| 1.01-2.0  | 76        | 6.88%   |
| 2.01-3.0  | 33        | 2.99%   |
| 3.01-4.0  | 3         | 0.27%   |
| 4.01-8.0  | 2         | 0.18%   |
| 8.01-16.0 | 2         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 842       | 74.78%  |
| 2      | 173       | 15.36%  |
| 0      | 94        | 8.35%   |
| 3      | 16        | 1.42%   |
| 4      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 675       | 61.2%   |
| Yes       | 428       | 38.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 951       | 86.45%  |
| No        | 149       | 13.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1080      | 98.18%  |
| No        | 20        | 1.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 790       | 71.43%  |
| No        | 316       | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 165       | 14.97%  |
| Germany     | 91        | 8.26%   |
| Brazil      | 81        | 7.35%   |
| Russia      | 71        | 6.44%   |
| Italy       | 48        | 4.36%   |
| Spain       | 43        | 3.9%    |
| Poland      | 41        | 3.72%   |
| China       | 37        | 3.36%   |
| UK          | 35        | 3.18%   |
| Indonesia   | 35        | 3.18%   |
| Netherlands | 34        | 3.09%   |
| France      | 27        | 2.45%   |
| Canada      | 24        | 2.18%   |
| India       | 23        | 2.09%   |
| Hungary     | 19        | 1.72%   |
| Romania     | 17        | 1.54%   |
| Mexico      | 17        | 1.54%   |
| Sweden      | 16        | 1.45%   |
| Ukraine     | 15        | 1.36%   |
| Turkey      | 15        | 1.36%   |
| Portugal    | 13        | 1.18%   |
| Australia   | 13        | 1.18%   |
| Czechia     | 10        | 0.91%   |
| Chile       | 9         | 0.82%   |
| Switzerland | 8         | 0.73%   |
| Greece      | 8         | 0.73%   |
| Finland     | 8         | 0.73%   |
| Bulgaria    | 8         | 0.73%   |
| Vietnam     | 7         | 0.64%   |
| Taiwan      | 7         | 0.64%   |
| Norway      | 7         | 0.64%   |
| Lithuania   | 7         | 0.64%   |
| Japan       | 7         | 0.64%   |
| Colombia    | 7         | 0.64%   |
| South Korea | 6         | 0.54%   |
| Slovakia    | 6         | 0.54%   |
| New Zealand | 6         | 0.54%   |
| Belgium     | 6         | 0.54%   |
| Argentina   | 6         | 0.54%   |
| Malaysia    | 4         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 19        | 1.64%   |
| St Petersburg     | 11        | 0.95%   |
| Budapest          | 10        | 0.87%   |
| Wroclaw           | 9         | 0.78%   |
| Sao Paulo         | 9         | 0.78%   |
| Jakarta           | 9         | 0.78%   |
| Berlin            | 9         | 0.78%   |
| Guangzhou         | 7         | 0.61%   |
| Valencia          | 6         | 0.52%   |
| Los Angeles       | 6         | 0.52%   |
| Lisbon            | 6         | 0.52%   |
| Zurich            | 5         | 0.43%   |
| Vilnius           | 5         | 0.43%   |
| Utrecht           | 5         | 0.43%   |
| Toronto           | 5         | 0.43%   |
| Surabaya          | 5         | 0.43%   |
| Santiago          | 5         | 0.43%   |
| New York          | 5         | 0.43%   |
| Munich            | 5         | 0.43%   |
| Milan             | 5         | 0.43%   |
| Krakow            | 5         | 0.43%   |
| Hanoi             | 5         | 0.43%   |
| Frankfurt am Main | 5         | 0.43%   |
| Curitiba          | 5         | 0.43%   |
| Chicago           | 5         | 0.43%   |
| Bucharest         | 5         | 0.43%   |
| Warsaw            | 4         | 0.35%   |
| Sanford           | 4         | 0.35%   |
| Rome              | 4         | 0.35%   |
| Rio de Janeiro    | 4         | 0.35%   |
| Manchester        | 4         | 0.35%   |
| Madrid            | 4         | 0.35%   |
| Leipzig           | 4         | 0.35%   |
| Istanbul          | 4         | 0.35%   |
| Hamburg           | 4         | 0.35%   |
| Bengaluru         | 4         | 0.35%   |
| Athens            | 4         | 0.35%   |
| Ankara            | 4         | 0.35%   |
| Yogyakarta        | 3         | 0.26%   |
| Vienna            | 3         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 178       | 212    | 14.61%  |
| WDC                 | 157       | 175    | 12.89%  |
| Seagate             | 128       | 154    | 10.51%  |
| Toshiba             | 102       | 115    | 8.37%   |
| Kingston            | 82        | 89     | 6.73%   |
| Crucial             | 64        | 75     | 5.25%   |
| SanDisk             | 63        | 66     | 5.17%   |
| Hitachi             | 53        | 58     | 4.35%   |
| Intel               | 36        | 43     | 2.96%   |
| HGST                | 31        | 38     | 2.55%   |
| A-DATA Technology   | 26        | 27     | 2.13%   |
| Apple               | 24        | 25     | 1.97%   |
| SK hynix            | 23        | 23     | 1.89%   |
| Micron Technology   | 23        | 23     | 1.89%   |
| Fujitsu             | 13        | 15     | 1.07%   |
| Transcend           | 12        | 13     | 0.99%   |
| SPCC                | 12        | 15     | 0.99%   |
| Patriot             | 11        | 14     | 0.9%    |
| Intenso             | 11        | 11     | 0.9%    |
| OCZ                 | 9         | 10     | 0.74%   |
| PNY                 | 8         | 8      | 0.66%   |
| KingSpec            | 8         | 9      | 0.66%   |
| China               | 8         | 8      | 0.66%   |
| GOODRAM             | 7         | 7      | 0.57%   |
| LITEON              | 6         | 6      | 0.49%   |
| Lexar               | 6         | 6      | 0.49%   |
| KIOXIA              | 6         | 6      | 0.49%   |
| Gigabyte Technology | 6         | 7      | 0.49%   |
| SSSTC               | 5         | 5      | 0.41%   |
| Corsair             | 5         | 5      | 0.41%   |
| Apacer              | 5         | 5      | 0.41%   |
| Team                | 4         | 5      | 0.33%   |
| Phison              | 4         | 4      | 0.33%   |
| LITEONIT            | 4         | 4      | 0.33%   |
| FORESEE             | 4         | 5      | 0.33%   |
| Dogfish             | 4         | 5      | 0.33%   |
| Silicon Motion      | 3         | 3      | 0.25%   |
| Plextor             | 3         | 4      | 0.25%   |
| Hewlett-Packard     | 3         | 4      | 0.25%   |
| Zheino              | 2         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 17        | 1.36%   |
| Toshiba MQ01ABD100 1TB              | 15        | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB      | 14        | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 12        | 0.96%   |
| Kingston SA400S37240G 240GB         | 12        | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB        | 11        | 0.88%   |
| Seagate ST9500325AS 500GB           | 10        | 0.8%    |
| Samsung SSD 860 EVO 500GB           | 10        | 0.8%    |
| Kingston SA400S37120G 120GB         | 10        | 0.8%    |
| Kingston SV300S37A120G 120GB        | 9         | 0.72%   |
| Crucial CT500MX500SSD1 500GB        | 9         | 0.72%   |
| Seagate ST9320325AS 320GB           | 7         | 0.56%   |
| Samsung SSD 860 EVO 250GB           | 7         | 0.56%   |
| Samsung SSD 850 EVO 250GB           | 7         | 0.56%   |
| Crucial CT480BX500SSD1 480GB        | 7         | 0.56%   |
| Crucial CT240BX500SSD1 240GB        | 7         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB        | 6         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 0.48%   |
| Samsung SSD 840 EVO 250GB           | 6         | 0.48%   |
| Micron 1100 SATA 256GB              | 6         | 0.48%   |
| Hitachi HTS545032B9A300 320GB       | 6         | 0.48%   |
| Hitachi HTS541612J9SA00 120GB       | 6         | 0.48%   |
| HGST HTS721010A9E630 1TB            | 6         | 0.48%   |
| HGST HTS545050A7E680 500GB          | 6         | 0.48%   |
| Toshiba MK3261GSYN 320GB            | 5         | 0.4%    |
| Seagate ST9500420AS 500GB           | 5         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB      | 5         | 0.4%    |
| Samsung SSD 860 EVO 1TB             | 5         | 0.4%    |
| Samsung MZVLW256HEHP-000L7 256GB    | 5         | 0.4%    |
| Patriot Burst 120GB                 | 5         | 0.4%    |
| Hitachi HTS545050B9A300 500GB       | 5         | 0.4%    |
| HGST HTS725050A7E630 500GB          | 5         | 0.4%    |
| HGST HTS541010A9E680 1TB            | 5         | 0.4%    |
| Crucial CT120BX500SSD1 120GB        | 5         | 0.4%    |
| Crucial CT1000MX500SSD1 1TB         | 5         | 0.4%    |
| WDC WD10SPZX-24Z10 1TB              | 4         | 0.32%   |
| SPCC Solid State Disk 256GB         | 4         | 0.32%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 4         | 0.32%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 128       | 154    | 29.49%  |
| WDC                 | 107       | 117    | 24.65%  |
| Toshiba             | 82        | 95     | 18.89%  |
| Hitachi             | 53        | 58     | 12.21%  |
| HGST                | 31        | 38     | 7.14%   |
| Samsung Electronics | 16        | 17     | 3.69%   |
| Fujitsu             | 12        | 13     | 2.76%   |
| Apple               | 3         | 3      | 0.69%   |
| Maxtor              | 1         | 1      | 0.23%   |
| CSD                 | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 112       | 127    | 18.24%  |
| Kingston            | 71        | 76     | 11.56%  |
| SanDisk             | 63        | 66     | 10.26%  |
| Crucial             | 58        | 67     | 9.45%   |
| WDC                 | 33        | 36     | 5.37%   |
| Intel               | 21        | 26     | 3.42%   |
| Apple               | 21        | 22     | 3.42%   |
| A-DATA Technology   | 19        | 20     | 3.09%   |
| Micron Technology   | 15        | 15     | 2.44%   |
| Transcend           | 11        | 12     | 1.79%   |
| SPCC                | 11        | 13     | 1.79%   |
| Patriot             | 11        | 14     | 1.79%   |
| Intenso             | 11        | 11     | 1.79%   |
| Toshiba             | 10        | 10     | 1.63%   |
| OCZ                 | 9         | 10     | 1.47%   |
| SK hynix            | 8         | 8      | 1.3%    |
| PNY                 | 8         | 8      | 1.3%    |
| KingSpec            | 8         | 9      | 1.3%    |
| China               | 8         | 8      | 1.3%    |
| GOODRAM             | 7         | 7      | 1.14%   |
| LITEON              | 6         | 6      | 0.98%   |
| Lexar               | 6         | 6      | 0.98%   |
| Corsair             | 5         | 5      | 0.81%   |
| Apacer              | 5         | 5      | 0.81%   |
| Team                | 4         | 5      | 0.65%   |
| LITEONIT            | 4         | 4      | 0.65%   |
| Gigabyte Technology | 4         | 4      | 0.65%   |
| Dogfish             | 4         | 5      | 0.65%   |
| Plextor             | 3         | 4      | 0.49%   |
| Hewlett-Packard     | 3         | 4      | 0.49%   |
| Zheino              | 2         | 2      | 0.33%   |
| V-GeN               | 2         | 2      | 0.33%   |
| SSSTC               | 2         | 2      | 0.33%   |
| Pioneer             | 2         | 2      | 0.33%   |
| Phison              | 2         | 2      | 0.33%   |
| OWC                 | 2         | 2      | 0.33%   |
| Netac               | 2         | 2      | 0.33%   |
| MyDigitalSSD        | 2         | 2      | 0.33%   |
| MidasForce          | 2         | 2      | 0.33%   |
| Leven               | 2         | 2      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 557       | 672    | 48.95%  |
| HDD  | 409       | 497    | 35.94%  |
| NVMe | 172       | 201    | 15.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 897       | 1169   | 83.91%  |
| NVMe | 172       | 201    | 16.09%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 755       | 946    | 79.73%  |
| 0.51-1.0   | 172       | 202    | 18.16%  |
| 1.01-2.0   | 16        | 17     | 1.69%   |
| 2.01-3.0   | 2         | 2      | 0.21%   |
| 3.01-4.0   | 1         | 1      | 0.11%   |
| 4.01-10.0  | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 558       | 48.69%  |
| 101-250        | 242       | 21.12%  |
| 251-500        | 161       | 14.05%  |
| 51-100         | 80        | 6.98%   |
| 501-1000       | 65        | 5.67%   |
| 21-50          | 34        | 2.97%   |
| Unknown        | 3         | 0.26%   |
| 1001-2000      | 2         | 0.17%   |
| More than 3000 | 1         | 0.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 1069      | 96.92%  |
| 21-50   | 14        | 1.27%   |
| 101-250 | 9         | 0.82%   |
| 251-500 | 4         | 0.36%   |
| 51-100  | 4         | 0.36%   |
| Unknown | 3         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 7         | 9      | 2.95%   |
| Toshiba MQ01ABD100 1TB              | 6         | 6      | 2.53%   |
| Toshiba MQ01ABF050 500GB            | 5         | 7      | 2.11%   |
| Seagate ST9320325AS 320GB           | 5         | 5      | 2.11%   |
| HGST HTS541010A9E680 1TB            | 5         | 6      | 2.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 7      | 1.69%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 1.69%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 1.69%   |
| Hitachi HTS541612J9SA00 120GB       | 4         | 4      | 1.69%   |
| HGST HTS725050A7E630 500GB          | 4         | 5      | 1.69%   |
| Toshiba MK3261GSYN 320GB            | 3         | 5      | 1.27%   |
| SK hynix SC210 mSATA 256GB          | 3         | 3      | 1.27%   |
| Seagate ST9500420AS 500GB           | 3         | 3      | 1.27%   |
| Seagate ST9160821AS 160GB           | 3         | 3      | 1.27%   |
| Seagate ST9160412AS 160GB           | 3         | 3      | 1.27%   |
| Seagate ST500LM000-1EJ162 500GB     | 3         | 3      | 1.27%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 4      | 1.27%   |
| Hitachi HTS545025B9SA02 250GB       | 3         | 5      | 1.27%   |
| Hitachi HTS542525K9A300 250GB       | 3         | 3      | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.84%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.84%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.84%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 0.84%   |
| Toshiba MQ01ABD050 500GB            | 2         | 2      | 0.84%   |
| Toshiba MQ01ABD032 320GB            | 2         | 2      | 0.84%   |
| Toshiba MK8034GSX 80GB              | 2         | 3      | 0.84%   |
| Toshiba MK3261GSY 320GB             | 2         | 2      | 0.84%   |
| Toshiba MK1646GSX 160GB             | 2         | 2      | 0.84%   |
| SSSTC CVB-8D128-HP 128GB            | 2         | 2      | 0.84%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.84%   |
| Seagate ST9160827AS 160GB           | 2         | 2      | 0.84%   |
| Seagate ST9120821AS 120GB           | 2         | 2      | 0.84%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 2      | 0.84%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2      | 0.84%   |
| SanDisk SSD PLUS 240GB              | 2         | 2      | 0.84%   |
| Samsung Electronics HM321HI 320GB   | 2         | 2      | 0.84%   |
| Samsung Electronics HM160HI 160GB   | 2         | 2      | 0.84%   |
| Kingston SV300S37A60G 64GB          | 2         | 2      | 0.84%   |
| Kingston SUV400S37120G 120GB        | 2         | 2      | 0.84%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 74     | 25.74%  |
| Toshiba             | 41        | 47     | 17.3%   |
| WDC                 | 35        | 38     | 14.77%  |
| Hitachi             | 32        | 35     | 13.5%   |
| HGST                | 15        | 18     | 6.33%   |
| Samsung Electronics | 10        | 12     | 4.22%   |
| Kingston            | 8         | 8      | 3.38%   |
| Crucial             | 6         | 9      | 2.53%   |
| SanDisk             | 5         | 5      | 2.11%   |
| SK hynix            | 4         | 4      | 1.69%   |
| Micron Technology   | 4         | 4      | 1.69%   |
| Fujitsu             | 3         | 3      | 1.27%   |
| SSSTC               | 2         | 2      | 0.84%   |
| LITEON              | 2         | 2      | 0.84%   |
| Corsair             | 2         | 2      | 0.84%   |
| Apple               | 2         | 2      | 0.84%   |
| OCZ                 | 1         | 1      | 0.42%   |
| Intel               | 1         | 1      | 0.42%   |
| Hewlett-Packard     | 1         | 1      | 0.42%   |
| China               | 1         | 1      | 0.42%   |
| AGI                 | 1         | 1      | 0.42%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 74     | 32.28%  |
| Toshiba             | 40        | 46     | 21.16%  |
| Hitachi             | 32        | 35     | 16.93%  |
| WDC                 | 31        | 34     | 16.4%   |
| HGST                | 15        | 18     | 7.94%   |
| Samsung Electronics | 6         | 6      | 3.17%   |
| Fujitsu             | 3         | 3      | 1.59%   |
| Apple               | 1         | 1      | 0.53%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 181       | 217    | 79.04%  |
| SSD  | 46        | 51     | 20.09%  |
| NVMe | 2         | 2      | 0.87%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 32GB                 | 1         | 1      | 20%     |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 20%     |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 20%     |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 20%     |
| CSD T65SX160N 4H0204656BY 160GB   | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HPE                 | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |
| CSD                 | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 838       | 1086   | 77.59%  |
| Malfunc  | 228       | 270    | 21.11%  |
| Detected | 9         | 9      | 0.83%   |
| Failed   | 5         | 5      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 895       | 73.78%  |
| AMD                                     | 84        | 6.92%   |
| Samsung Electronics                     | 71        | 5.85%   |
| SanDisk                                 | 34        | 2.8%    |
| Nvidia                                  | 25        | 2.06%   |
| SK hynix                                | 14        | 1.15%   |
| Kingston Technology Company             | 12        | 0.99%   |
| KIOXIA                                  | 11        | 0.91%   |
| Toshiba                                 | 9         | 0.74%   |
| Micron Technology                       | 9         | 0.74%   |
| Silicon Motion                          | 8         | 0.66%   |
| Micron/Crucial Technology               | 7         | 0.58%   |
| Realtek Semiconductor                   | 6         | 0.49%   |
| Phison Electronics                      | 6         | 0.49%   |
| Solid State Storage Technology          | 4         | 0.33%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.33%   |
| ADATA Technology                        | 3         | 0.25%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.16%   |
| Marvell Technology Group                | 2         | 0.16%   |
| JMicron Technology                      | 2         | 0.16%   |
| Biwin Storage Technology                | 2         | 0.16%   |
| Shenzhen Unionmemory Information System | 1         | 0.08%   |
| Lenovo                                  | 1         | 0.08%   |
| INNOGRIT                                | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 144       | 10.9%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 115       | 8.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 86        | 6.51%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 71        | 5.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 65        | 4.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 58        | 4.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 48        | 3.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 48        | 3.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 44        | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 41        | 3.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 35        | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 23        | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 23        | 1.74%   |
| Nvidia MCP79 AHCI Controller                                                     | 19        | 1.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 19        | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 19        | 1.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16        | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 16        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14        | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 0.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 13        | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 12        | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 11        | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 0.83%   |
| Intel SSD 660P Series                                                            | 10        | 0.76%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 9         | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 0.68%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 8         | 0.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 7         | 0.53%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 0.53%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 0.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 7         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 6         | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 0.45%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 6         | 0.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 909       | 71.41%  |
| NVMe | 201       | 15.79%  |
| IDE  | 100       | 7.86%   |
| RAID | 63        | 4.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 985       | 89.55%  |
| AMD    | 115       | 10.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel CPU Version                       | 23        | 2.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 21        | 1.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 20        | 1.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 20        | 1.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 19        | 1.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 17        | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 17        | 1.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 16        | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 15        | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 14        | 1.27%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 12        | 1.09%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 12        | 1.09%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 11        | 1%      |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 11        | 1%      |
| Intel Core i3-4005U CPU @ 1.70GHz       | 11        | 1%      |
| Intel Core i7-3520M CPU @ 2.90GHz       | 10        | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.91%   |
| Intel Core 2 Duo                        | 10        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 0.82%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 9         | 0.82%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 9         | 0.82%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 9         | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 0.82%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 8         | 0.73%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 8         | 0.73%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 8         | 0.73%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 8         | 0.73%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 8         | 0.73%   |
| Intel Genuine CPU                       | 7         | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 7         | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 7         | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 0.54%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 6         | 0.54%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 6         | 0.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 6         | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 6         | 0.54%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 6         | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 6         | 0.54%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 6         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 344       | 31.24%  |
| Intel Core i7           | 189       | 17.17%  |
| Intel Core i3           | 108       | 9.81%   |
| Intel Core 2 Duo        | 102       | 9.26%   |
| Intel Celeron           | 73        | 6.63%   |
| Other                   | 69        | 6.27%   |
| Intel Pentium           | 35        | 3.18%   |
| AMD Ryzen 7             | 25        | 2.27%   |
| AMD Ryzen 5             | 24        | 2.18%   |
| Intel Atom              | 21        | 1.91%   |
| Intel Pentium Dual-Core | 9         | 0.82%   |
| Intel Genuine           | 9         | 0.82%   |
| AMD E1                  | 9         | 0.82%   |
| AMD A6                  | 9         | 0.82%   |
| Intel Core 2            | 8         | 0.73%   |
| AMD Ryzen 3             | 7         | 0.64%   |
| Intel Xeon              | 5         | 0.45%   |
| AMD A10                 | 5         | 0.45%   |
| Intel Pentium Silver    | 4         | 0.36%   |
| AMD E                   | 4         | 0.36%   |
| AMD Athlon              | 4         | 0.36%   |
| Intel Pentium Dual      | 3         | 0.27%   |
| Intel Core m3           | 3         | 0.27%   |
| AMD E2                  | 3         | 0.27%   |
| AMD A8                  | 3         | 0.27%   |
| Intel Core M            | 2         | 0.18%   |
| AMD Ryzen 7 PRO         | 2         | 0.18%   |
| AMD Phenom II           | 2         | 0.18%   |
| AMD C-60                | 2         | 0.18%   |
| AMD A4                  | 2         | 0.18%   |
| Intel Pentium M         | 1         | 0.09%   |
| Intel Pentium Gold      | 1         | 0.09%   |
| Intel Core m7           | 1         | 0.09%   |
| Intel Core i9           | 1         | 0.09%   |
| Intel Core 2 Solo       | 1         | 0.09%   |
| Intel Core              | 1         | 0.09%   |
| Intel Celeron Dual-Core | 1         | 0.09%   |
| Intel Celeron D         | 1         | 0.09%   |
| AMD V120                | 1         | 0.09%   |
| AMD Turion 64 X2 Mobile | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 668       | 60.73%  |
| 4       | 221       | 20.09%  |
| Unknown | 107       | 9.73%   |
| 16      | 24        | 2.18%   |
| 8       | 24        | 2.18%   |
| 6       | 21        | 1.91%   |
| 12      | 15        | 1.36%   |
| 1       | 15        | 1.36%   |
| 20      | 2         | 0.18%   |
| 10      | 2         | 0.18%   |
| 11      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 1059      | 96.27%  |
| 2       | 38        | 3.45%   |
| Unknown | 3         | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 705       | 64.09%  |
| 1       | 283       | 25.73%  |
| Unknown | 112       | 10.18%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 143       | 12.99%  |
| IvyBridge     | 132       | 11.99%  |
| SandyBridge   | 116       | 10.54%  |
| Haswell       | 101       | 9.17%   |
| Penryn        | 99        | 8.99%   |
| Skylake       | 87        | 7.9%    |
| Westmere      | 63        | 5.72%   |
| Broadwell     | 56        | 5.09%   |
| Core          | 51        | 4.63%   |
| Silvermont    | 41        | 3.72%   |
| Unknown       | 35        | 3.18%   |
| Zen+          | 21        | 1.91%   |
| Bonnell       | 21        | 1.91%   |
| TigerLake     | 19        | 1.73%   |
| Zen 2         | 16        | 1.45%   |
| Zen 3         | 13        | 1.18%   |
| Excavator     | 13        | 1.18%   |
| Bobcat        | 13        | 1.18%   |
| Goldmont plus | 10        | 0.91%   |
| Goldmont      | 10        | 0.91%   |
| CometLake     | 9         | 0.82%   |
| Jaguar        | 7         | 0.64%   |
| Zen           | 5         | 0.45%   |
| Piledriver    | 5         | 0.45%   |
| K10           | 4         | 0.36%   |
| Nehalem       | 3         | 0.27%   |
| Puma          | 2         | 0.18%   |
| K8 Hammer     | 2         | 0.18%   |
| K10 Llano     | 2         | 0.18%   |
| IceLake       | 2         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 882       | 67.28%  |
| Nvidia                           | 246       | 18.76%  |
| AMD                              | 180       | 13.73%  |
| Silicon Integrated Systems [SiS] | 3         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 128       | 9.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 110       | 8.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 71        | 5.24%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 60        | 4.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 49        | 3.62%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 48        | 3.54%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 45        | 3.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 3.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 31        | 2.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 31        | 2.29%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 31        | 2.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 1.77%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 19        | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.25%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 17        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 1.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 1.18%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 16        | 1.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 15        | 1.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.11%   |
| Nvidia C79 [GeForce 9400M]                                                               | 14        | 1.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 0.74%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 8         | 0.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 0.59%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 0.59%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.52%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 7         | 0.52%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 7         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.44%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 6         | 0.44%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.44%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 6         | 0.44%   |
| AMD Lucienne                                                                             | 6         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 592       | 53.77%  |
| Intel + Nvidia         | 151       | 13.71%  |
| 1 x AMD                | 118       | 10.72%  |
| 2 x Intel              | 97        | 8.81%   |
| 1 x Nvidia             | 76        | 6.9%    |
| Intel + AMD            | 39        | 3.54%   |
| AMD + Nvidia           | 17        | 1.54%   |
| 2 x AMD                | 5         | 0.45%   |
| 1 x SiS                | 3         | 0.27%   |
| 2 x Nvidia             | 2         | 0.18%   |
| 2 x Intel + 1 x Nvidia | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 984       | 88.65%  |
| Unknown     | 74        | 6.67%   |
| Proprietary | 52        | 4.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 979       | 88.12%  |
| 0.01-0.5   | 78        | 7.02%   |
| 1.01-2.0   | 22        | 1.98%   |
| 0.51-1.0   | 22        | 1.98%   |
| 5.01-6.0   | 4         | 0.36%   |
| 3.01-4.0   | 4         | 0.36%   |
| 7.01-8.0   | 1         | 0.09%   |
| 2.01-3.0   | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 168       | 19.24%  |
| AU Optronics            | 168       | 19.24%  |
| Chimei Innolux          | 125       | 14.32%  |
| BOE                     | 97        | 11.11%  |
| Samsung Electronics     | 86        | 9.85%   |
| Lenovo                  | 48        | 5.5%    |
| Apple                   | 46        | 5.27%   |
| Chi Mei Optoelectronics | 26        | 2.98%   |
| InfoVision              | 14        | 1.6%    |
| Sharp                   | 11        | 1.26%   |
| LG Philips              | 7         | 0.8%    |
| AOC                     | 7         | 0.8%    |
| PANDA                   | 6         | 0.69%   |
| Goldstar                | 6         | 0.69%   |
| HannStar                | 5         | 0.57%   |
| Hewlett-Packard         | 4         | 0.46%   |
| Dell                    | 4         | 0.46%   |
| Ancor Communications    | 4         | 0.46%   |
| Philips                 | 3         | 0.34%   |
| Nvidia                  | 3         | 0.34%   |
| Acer                    | 3         | 0.34%   |
| Sony                    | 2         | 0.23%   |
| NCS                     | 2         | 0.23%   |
| IBM                     | 2         | 0.23%   |
| Fujitsu Siemens         | 2         | 0.23%   |
| CPT                     | 2         | 0.23%   |
| BenQ                    | 2         | 0.23%   |
| ViewSonic               | 1         | 0.11%   |
| Vestel Elektronik       | 1         | 0.11%   |
| Toshiba                 | 1         | 0.11%   |
| TMX                     | 1         | 0.11%   |
| Ruijiang                | 1         | 0.11%   |
| Quanta Display          | 1         | 0.11%   |
| MTD                     | 1         | 0.11%   |
| LPL                     | 1         | 0.11%   |
| Lenovo Group Limited    | 1         | 0.11%   |
| LED                     | 1         | 0.11%   |
| KTC                     | 1         | 0.11%   |
| InnoLux Display         | 1         | 0.11%   |
| HRN                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 11        | 1.25%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 8         | 0.91%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 7         | 0.8%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 6         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 380x210mm 17.1-inch    | 6         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 6         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 6         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 5         | 0.57%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 5         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 5         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch          | 5         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 5         | 0.57%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 5         | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch            | 5         | 0.57%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch            | 5         | 0.57%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 5         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 4         | 0.46%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.46%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 4         | 0.46%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 4         | 0.46%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch          | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 4         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 4         | 0.46%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                     | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch           | 4         | 0.46%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                   | 4         | 0.46%   |
| LG Display LCD Monitor LGD045C 1366x768 340x190mm 15.3-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch              | 3         | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 3         | 0.34%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 3         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 376       | 43.72%  |
| 1920x1080 (FHD)    | 269       | 31.28%  |
| 1280x800 (WXGA)    | 69        | 8.02%   |
| 1600x900 (HD+)     | 50        | 5.81%   |
| 1024x600           | 16        | 1.86%   |
| 1440x900 (WXGA+)   | 14        | 1.63%   |
| 3840x2160 (4K)     | 11        | 1.28%   |
| 2560x1440 (QHD)    | 9         | 1.05%   |
| 1280x1024 (SXGA)   | 7         | 0.81%   |
| 3200x1800 (QHD+)   | 6         | 0.7%    |
| 2560x1600          | 6         | 0.7%    |
| 1920x1200 (WUXGA)  | 6         | 0.7%    |
| 1680x1050 (WSXGA+) | 4         | 0.47%   |
| 1024x768 (XGA)     | 4         | 0.47%   |
| 2880x1800          | 2         | 0.23%   |
| 1920x540           | 2         | 0.23%   |
| 1400x1050          | 2         | 0.23%   |
| 3840x2400          | 1         | 0.12%   |
| 3200x2000          | 1         | 0.12%   |
| 2560x1080          | 1         | 0.12%   |
| 2256x1504          | 1         | 0.12%   |
| 2240x1400          | 1         | 0.12%   |
| 1920x515           | 1         | 0.12%   |
| 1600x1200          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 320       | 36.49%  |
| 13      | 273       | 31.13%  |
| 12      | 76        | 8.67%   |
| 17      | 50        | 5.7%    |
| 14      | 36        | 4.1%    |
| 11      | 30        | 3.42%   |
| 10      | 14        | 1.6%    |
| 27      | 11        | 1.25%   |
| 24      | 9         | 1.03%   |
| 23      | 9         | 1.03%   |
| 21      | 9         | 1.03%   |
| 19      | 8         | 0.91%   |
| 16      | 5         | 0.57%   |
| 9       | 4         | 0.46%   |
| Unknown | 4         | 0.46%   |
| 40      | 3         | 0.34%   |
| 42      | 2         | 0.23%   |
| 31      | 2         | 0.23%   |
| 22      | 2         | 0.23%   |
| 20      | 2         | 0.23%   |
| 18      | 2         | 0.23%   |
| 86      | 1         | 0.11%   |
| 64      | 1         | 0.11%   |
| 54      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 34      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 519       | 59.38%  |
| 201-300     | 233       | 26.66%  |
| 351-400     | 57        | 6.52%   |
| 501-600     | 27        | 3.09%   |
| 401-500     | 20        | 2.29%   |
| 601-700     | 4         | 0.46%   |
| Unknown     | 4         | 0.46%   |
| 801-900     | 3         | 0.34%   |
| 1001-1500   | 3         | 0.34%   |
| 901-1000    | 2         | 0.23%   |
| 701-800     | 1         | 0.11%   |
| 1501-2000   | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 704       | 83.71%  |
| 16/10   | 104       | 12.37%  |
| 3/2     | 12        | 1.43%   |
| 4/3     | 9         | 1.07%   |
| 5/4     | 6         | 0.71%   |
| Unknown | 4         | 0.48%   |
| 3.88    | 1         | 0.12%   |
| 21/9    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 260       | 29.65%  |
| 91-100         | 245       | 27.94%  |
| 101-110        | 79        | 9.01%   |
| 61-70          | 74        | 8.44%   |
| 71-80          | 43        | 4.9%    |
| 121-130        | 43        | 4.9%    |
| 51-60          | 29        | 3.31%   |
| 201-250        | 26        | 2.96%   |
| 41-50          | 18        | 2.05%   |
| 301-350        | 12        | 1.37%   |
| 151-200        | 11        | 1.25%   |
| 111-120        | 9         | 1.03%   |
| 131-140        | 5         | 0.57%   |
| 501-1000       | 5         | 0.57%   |
| More than 1000 | 4         | 0.46%   |
| 141-150        | 4         | 0.46%   |
| Unknown        | 4         | 0.46%   |
| 351-500        | 3         | 0.34%   |
| 251-300        | 2         | 0.23%   |
| 1-40           | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 358       | 41.24%  |
| 101-120       | 345       | 39.75%  |
| 51-100        | 105       | 12.1%   |
| 161-240       | 42        | 4.84%   |
| More than 240 | 12        | 1.38%   |
| Unknown       | 4         | 0.46%   |
| 1-50          | 2         | 0.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 928       | 83.6%   |
| 0     | 122       | 10.99%  |
| 2     | 60        | 5.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 610       | 34.8%   |
| Realtek Semiconductor                  | 479       | 27.32%  |
| Qualcomm Atheros                       | 266       | 15.17%  |
| Broadcom                               | 164       | 9.36%   |
| Marvell Technology Group               | 32        | 1.83%   |
| Nvidia                                 | 21        | 1.2%    |
| Xiaomi                                 | 17        | 0.97%   |
| Samsung Electronics                    | 17        | 0.97%   |
| Ralink                                 | 14        | 0.8%    |
| Sierra Wireless                        | 13        | 0.74%   |
| MediaTek                               | 12        | 0.68%   |
| Dell                                   | 12        | 0.68%   |
| JMicron Technology                     | 11        | 0.63%   |
| Ericsson Business Mobile Networks      | 11        | 0.63%   |
| TP-Link                                | 9         | 0.51%   |
| Ralink Technology                      | 9         | 0.51%   |
| Google                                 | 9         | 0.51%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.23%   |
| OPPO Electronics                       | 4         | 0.23%   |
| Huawei Technologies                    | 4         | 0.23%   |
| Hewlett-Packard                        | 4         | 0.23%   |
| Edimax Technology                      | 4         | 0.23%   |
| NetGear                                | 3         | 0.17%   |
| Motorola PCS                           | 3         | 0.17%   |
| D-Link System                          | 3         | 0.17%   |
| Qualcomm Technologies                  | 2         | 0.11%   |
| Qualcomm                               | 2         | 0.11%   |
| D-Link                                 | 2         | 0.11%   |
| ASUSTek Computer                       | 2         | 0.11%   |
| Toshiba                                | 1         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Qualcomm Atheros Communications        | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Mercucys                               | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| BUFFALO                                | 1         | 0.06%   |
| AboCom Systems                         | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 304       | 13.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 114       | 5.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 81        | 3.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 2.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 58        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 56        | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 53        | 2.41%   |
| Intel Wireless 8265 / 8275                                              | 50        | 2.28%   |
| Intel Wireless 7265                                                     | 50        | 2.28%   |
| Intel Wireless 7260                                                     | 50        | 2.28%   |
| Intel Wireless 8260                                                     | 49        | 2.23%   |
| Intel Ethernet Connection I219-LM                                       | 28        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 26        | 1.18%   |
| Intel 82577LM Gigabit Network Connection                                | 25        | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 1%      |
| Intel Wi-Fi 6 AX200                                                     | 21        | 0.96%   |
| Intel Wireless 3165                                                     | 20        | 0.91%   |
| Intel Ethernet Connection I218-LM                                       | 20        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                                   | 20        | 0.91%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 20        | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 0.87%   |
| Intel Ethernet Connection I217-LM                                       | 19        | 0.87%   |
| Intel Centrino Advanced-N 6200                                          | 19        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 0.82%   |
| Nvidia MCP79 Ethernet                                                   | 18        | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                                   | 18        | 0.82%   |
| Intel Centrino Advanced-N 6235                                          | 18        | 0.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 18        | 0.82%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 0.73%   |
| Intel WiFi Link 5100                                                    | 15        | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                | 15        | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 15        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.64%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 14        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 578       | 49.61%  |
| Qualcomm Atheros                | 239       | 20.52%  |
| Realtek Semiconductor           | 140       | 12.02%  |
| Broadcom                        | 131       | 11.24%  |
| Ralink                          | 14        | 1.2%    |
| MediaTek                        | 10        | 0.86%   |
| TP-Link                         | 9         | 0.77%   |
| Sierra Wireless                 | 9         | 0.77%   |
| Ralink Technology               | 9         | 0.77%   |
| Dell                            | 7         | 0.6%    |
| Edimax Technology               | 4         | 0.34%   |
| NetGear                         | 3         | 0.26%   |
| Qualcomm Technologies           | 2         | 0.17%   |
| D-Link System                   | 2         | 0.17%   |
| D-Link                          | 2         | 0.17%   |
| ASUSTek Computer                | 2         | 0.17%   |
| Qualcomm Atheros Communications | 1         | 0.09%   |
| Mercucys                        | 1         | 0.09%   |
| BUFFALO                         | 1         | 0.09%   |
| AboCom Systems                  | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 58        | 4.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 56        | 4.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 53        | 4.5%    |
| Intel Wireless 8265 / 8275                                              | 50        | 4.24%   |
| Intel Wireless 7265                                                     | 50        | 4.24%   |
| Intel Wireless 7260                                                     | 50        | 4.24%   |
| Intel Wireless 8260                                                     | 49        | 4.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 26        | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 1.87%   |
| Intel Wi-Fi 6 AX200                                                     | 21        | 1.78%   |
| Intel Wireless 3165                                                     | 20        | 1.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 20        | 1.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 1.61%   |
| Intel Centrino Advanced-N 6200                                          | 19        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.53%   |
| Intel Centrino Advanced-N 6235                                          | 18        | 1.53%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 18        | 1.53%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 1.36%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 1.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 1.36%   |
| Intel WiFi Link 5100                                                    | 15        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 15        | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 1.1%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 1.1%    |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.1%    |
| Broadcom BCM4321 802.11a/b/g/n                                          | 13        | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 12        | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 10        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 422       | 43.06%  |
| Intel                                  | 309       | 31.53%  |
| Qualcomm Atheros                       | 68        | 6.94%   |
| Broadcom                               | 57        | 5.82%   |
| Marvell Technology Group               | 32        | 3.27%   |
| Nvidia                                 | 21        | 2.14%   |
| Xiaomi                                 | 17        | 1.73%   |
| Samsung Electronics                    | 17        | 1.73%   |
| JMicron Technology                     | 11        | 1.12%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.41%   |
| OPPO Electronics                       | 4         | 0.41%   |
| Google                                 | 4         | 0.41%   |
| Motorola PCS                           | 3         | 0.31%   |
| Qualcomm                               | 2         | 0.2%    |
| MediaTek                               | 2         | 0.2%    |
| Huawei Technologies                    | 2         | 0.2%    |
| T & A Mobile Phones                    | 1         | 0.1%    |
| Spreadtrum Communications              | 1         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)          | 1         | 0.1%    |
| ICS Advent                             | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 304       | 31.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 114       | 11.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 81        | 8.27%   |
| Intel Ethernet Connection I219-LM                                      | 28        | 2.86%   |
| Intel 82577LM Gigabit Network Connection                               | 25        | 2.55%   |
| Intel Ethernet Connection I218-LM                                      | 20        | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 20        | 2.04%   |
| Intel Ethernet Connection I217-LM                                      | 19        | 1.94%   |
| Nvidia MCP79 Ethernet                                                  | 18        | 1.84%   |
| Intel Ethernet Connection (3) I218-LM                                  | 18        | 1.84%   |
| Intel 82567LM Gigabit Network Connection                               | 15        | 1.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 14        | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 13        | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 13        | 1.33%   |
| Intel 82566MM Gigabit Network Connection                               | 13        | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 12        | 1.22%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 10        | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.92%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 9         | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 8         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 6         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 6         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 6         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 6         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 5         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 0.51%   |
| Intel Ethernet Connection I219-V                                       | 5         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                                  | 5         | 0.51%   |
| Intel 82573L Gigabit Ethernet Controller                               | 5         | 0.51%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 5         | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 4         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.41%   |
| Intel Ethernet Connection (3) I218-V                                   | 4         | 0.41%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1082      | 52.19%  |
| Ethernet | 954       | 46.02%  |
| Unknown  | 25        | 1.21%   |
| Modem    | 12        | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 693       | 53.47%  |
| Ethernet | 593       | 45.76%  |
| Modem    | 5         | 0.39%   |
| Unknown  | 5         | 0.39%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 901       | 81.91%  |
| 1     | 189       | 17.18%  |
| 0     | 7         | 0.64%   |
| 3     | 3         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1045      | 94.14%  |
| Yes  | 65        | 5.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 367       | 46.05%  |
| Broadcom                        | 79        | 9.91%   |
| Apple                           | 68        | 8.53%   |
| Qualcomm Atheros Communications | 66        | 8.28%   |
| Realtek Semiconductor           | 59        | 7.4%    |
| IMC Networks                    | 34        | 4.27%   |
| Foxconn / Hon Hai               | 33        | 4.14%   |
| Lite-On Technology              | 21        | 2.63%   |
| Dell                            | 16        | 2.01%   |
| Hewlett-Packard                 | 14        | 1.76%   |
| Cambridge Silicon Radio         | 13        | 1.63%   |
| Ralink                          | 7         | 0.88%   |
| ASUSTek Computer                | 7         | 0.88%   |
| Alps Electric                   | 5         | 0.63%   |
| Toshiba                         | 2         | 0.25%   |
| Askey Computer                  | 2         | 0.25%   |
| TP-Link                         | 1         | 0.13%   |
| Realtek                         | 1         | 0.13%   |
| MediaTek                        | 1         | 0.13%   |
| Fujitsu                         | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 216       | 26.93%  |
| Intel AX201 Bluetooth                               | 38        | 4.74%   |
| Apple Bluetooth Host Controller                     | 33        | 4.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 3.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 2.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 2.74%   |
| Intel AX200 Bluetooth                               | 20        | 2.49%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 2.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 2.37%   |
| Realtek Bluetooth Adapter                           | 15        | 1.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 1.75%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1              | 13        | 1.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 1.62%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 12        | 1.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 12        | 1.5%    |
| Apple Broadcom Built-in Bluetooth                   | 12        | 1.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 11        | 1.37%   |
| Apple Built-in iSight (no firmware loaded)          | 10        | 1.25%   |
| Intel AX210 Bluetooth                               | 9         | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1%      |
| Realtek RTL8821A Bluetooth                          | 7         | 0.87%   |
| Realtek Bluetooth 4.2 Adapter                       | 7         | 0.87%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.87%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.87%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.87%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.75%   |
| Realtek Bluetooth 4.0 Adapter                       | 6         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.75%   |
| Intel AX211 Bluetooth                               | 6         | 0.75%   |
| IMC Networks Realtek Bluetooth Adapter              | 6         | 0.75%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 6         | 0.75%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 6         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 6         | 0.75%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth       | 5         | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.62%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module         | 5         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 955       | 79.32%  |
| AMD                                          | 136       | 11.3%   |
| Nvidia                                       | 86        | 7.14%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.33%   |
| Texas Instruments                            | 3         | 0.25%   |
| Realtek Semiconductor                        | 3         | 0.25%   |
| GN Netcom                                    | 3         | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.08%   |
| XMOS                                         | 1         | 0.08%   |
| SteelSeries ApS                              | 1         | 0.08%   |
| Phison Electronics                           | 1         | 0.08%   |
| Kingston Technology                          | 1         | 0.08%   |
| Hewlett-Packard                              | 1         | 0.08%   |
| Generalplus Technology                       | 1         | 0.08%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.08%   |
| Creative Technology                          | 1         | 0.08%   |
| Conexant Systems                             | 1         | 0.08%   |
| C-Media Electronics                          | 1         | 0.08%   |
| ASUSTek Computer                             | 1         | 0.08%   |
| Apogee Electronics                           | 1         | 0.08%   |
| Unknown                                      | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 155       | 10.57%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 144       | 9.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 93        | 6.34%   |
| Intel 8 Series HD Audio Controller                                                                | 72        | 4.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 69        | 4.71%   |
| AMD Ryzen HD Audio Controller                                                                     | 67        | 4.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 66        | 4.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 65        | 4.43%   |
| Intel Broadwell-U Audio Controller                                                                | 56        | 3.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 53        | 3.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 48        | 3.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 29        | 1.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 28        | 1.91%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 28        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 26        | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 24        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 1.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 20        | 1.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 16        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 13        | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 0.82%   |
| AMD Wrestler HDMI Audio                                                                           | 11        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.75%   |
| AMD High Definition Audio Controller                                                              | 11        | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 9         | 0.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 8         | 0.55%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 346       | 26.25%  |
| SK hynix                     | 258       | 19.58%  |
| Micron Technology            | 140       | 10.62%  |
| Kingston                     | 114       | 8.65%   |
| Unknown                      | 113       | 8.57%   |
| Elpida                       | 44        | 3.34%   |
| Crucial                      | 38        | 2.88%   |
| Ramaxel Technology           | 31        | 2.35%   |
| A-DATA Technology            | 28        | 2.12%   |
| Unknown                      | 28        | 2.12%   |
| Smart                        | 27        | 2.05%   |
| Nanya Technology             | 27        | 2.05%   |
| Corsair                      | 11        | 0.83%   |
| Transcend                    | 9         | 0.68%   |
| Teikon                       | 8         | 0.61%   |
| Unknown (ABCD)               | 7         | 0.53%   |
| G.Skill                      | 7         | 0.53%   |
| Apacer                       | 7         | 0.53%   |
| Smart Brazil                 | 6         | 0.46%   |
| High Bridge                  | 6         | 0.46%   |
| ASint Technology             | 6         | 0.46%   |
| Team                         | 5         | 0.38%   |
| Silicon Power                | 3         | 0.23%   |
| SHARETRONIC                  | 3         | 0.23%   |
| PNY                          | 3         | 0.23%   |
| 48spaces                     | 3         | 0.23%   |
| Sesame                       | 2         | 0.15%   |
| Multilaser                   | 2         | 0.15%   |
| Lenovo                       | 2         | 0.15%   |
| GSkill                       | 2         | 0.15%   |
| GOODRAM                      | 2         | 0.15%   |
| Avant                        | 2         | 0.15%   |
| V-GeN                        | 1         | 0.08%   |
| Unknown (8AFD)               | 1         | 0.08%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.08%   |
| Unknown (0x3D7F000000000000) | 1         | 0.08%   |
| Unknown (0x0809)             | 1         | 0.08%   |
| Unknown (0x0080)             | 1         | 0.08%   |
| Unknown (08B5)               | 1         | 0.08%   |
| Unifosa                      | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 28        | 2%      |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 27        | 1.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 1.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 1.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 1.29%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 1.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 1.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 13        | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s            | 13        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 11        | 0.79%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 11        | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 11        | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.79%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 11        | 0.79%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 10        | 0.71%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 10        | 0.71%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 10        | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 8         | 0.57%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 8         | 0.57%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 8         | 0.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 8         | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.5%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 7         | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 6         | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 6         | 0.43%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.43%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3                     | 6         | 0.43%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 6         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 5         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 5         | 0.36%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 5         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 592       | 54.56%  |
| DDR4    | 311       | 28.66%  |
| DDR2    | 104       | 9.59%   |
| Unknown | 19        | 1.75%   |
| LPDDR3  | 18        | 1.66%   |
| LPDDR4  | 14        | 1.29%   |
| DDR5    | 8         | 0.74%   |
| SDRAM   | 7         | 0.65%   |
| DDR     | 5         | 0.46%   |
| LPDDR5  | 4         | 0.37%   |
| DRAM    | 3         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1018      | 93.31%  |
| Row Of Chips | 38        | 3.48%   |
| Chip         | 16        | 1.47%   |
| DIMM         | 11        | 1.01%   |
| Unknown      | 8         | 0.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 464       | 38.06%  |
| 8192  | 334       | 27.4%   |
| 2048  | 274       | 22.48%  |
| 16384 | 91        | 7.47%   |
| 1024  | 45        | 3.69%   |
| 32768 | 11        | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 374       | 31.38%  |
| 1333    | 119       | 9.98%   |
| 3200    | 108       | 9.06%   |
| 2400    | 104       | 8.72%   |
| 2667    | 92        | 7.72%   |
| 667     | 78        | 6.54%   |
| 1334    | 70        | 5.87%   |
| 2133    | 58        | 4.87%   |
| 1067    | 54        | 4.53%   |
| Unknown | 31        | 2.6%    |
| 800     | 30        | 2.52%   |
| 1867    | 28        | 2.35%   |
| 1066    | 11        | 0.92%   |
| 4800    | 5         | 0.42%   |
| 975     | 5         | 0.42%   |
| 6400    | 4         | 0.34%   |
| 4267    | 4         | 0.34%   |
| 2048    | 4         | 0.34%   |
| 5600    | 3         | 0.25%   |
| 533     | 3         | 0.25%   |
| 333     | 2         | 0.17%   |
| 4266    | 1         | 0.08%   |
| 3733    | 1         | 0.08%   |
| 2800    | 1         | 0.08%   |
| 1866    | 1         | 0.08%   |
| 1639    | 1         | 0.08%   |

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
| Chicony Electronics                    | 228       | 27.98%  |
| Bison Electronics                      | 84        | 10.31%  |
| Realtek Semiconductor                  | 69        | 8.47%   |
| IMC Networks                           | 68        | 8.34%   |
| Microdia                               | 67        | 8.22%   |
| Sunplus Innovation Technology          | 46        | 5.64%   |
| Suyin                                  | 31        | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 25        | 3.07%   |
| Apple                                  | 24        | 2.94%   |
| Syntek                                 | 23        | 2.82%   |
| Quanta                                 | 23        | 2.82%   |
| Lite-On Technology                     | 23        | 2.82%   |
| Silicon Motion                         | 15        | 1.84%   |
| Alcor Micro                            | 15        | 1.84%   |
| Lenovo                                 | 12        | 1.47%   |
| Luxvisions Innotech Limited            | 10        | 1.23%   |
| ALi                                    | 9         | 1.1%    |
| Z-Star Microelectronics                | 8         | 0.98%   |
| Importek                               | 5         | 0.61%   |
| Ricoh                                  | 4         | 0.49%   |
| Jiangxi Shinetech Optical              | 4         | 0.49%   |
| Supreme Electronics                    | 3         | 0.37%   |
| Y Media                                | 2         | 0.25%   |
| Primax Electronics                     | 2         | 0.25%   |
| Logitech                               | 2         | 0.25%   |
| DigiTech                               | 2         | 0.25%   |
| USB Camera                             | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Tripath Technology                     | 1         | 0.12%   |
| OmniVision Technologies                | 1         | 0.12%   |
| Nanchang BYD Electronics               | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |
| HYGD-231214-A                          | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| Cubeternet                             | 1         | 0.12%   |
| Creative Technology                    | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 57        | 6.95%   |
| Bison Integrated Camera                   | 26        | 3.17%   |
| Microdia Integrated_Webcam_HD             | 23        | 2.8%    |
| Sunplus Integrated_Webcam_HD              | 18        | 2.2%    |
| Chicony Lenovo Integrated Camera (0.3MP)  | 16        | 1.95%   |
| Lite-On Integrated Camera                 | 15        | 1.83%   |
| Chicony HD Webcam                         | 14        | 1.71%   |
| Bison Lenovo EasyCamera                   | 14        | 1.71%   |
| Microdia Integrated Webcam                | 13        | 1.59%   |
| Realtek USB 2.0 PC Camera                 | 12        | 1.46%   |
| Realtek Integrated_Webcam_HD              | 12        | 1.46%   |
| IMC Networks Integrated Camera            | 12        | 1.46%   |
| Apple FaceTime HD Camera                  | 12        | 1.46%   |
| Realtek USB Camera                        | 11        | 1.34%   |
| Syntek Lenovo EasyCamera                  | 10        | 1.22%   |
| IMC Networks Realtek PC Camera            | 10        | 1.22%   |
| Chicony Lenovo EasyCamera                 | 10        | 1.22%   |
| Chicony FJ Camera                         | 10        | 1.22%   |
| IMC Networks EasyCamera                   | 9         | 1.1%    |
| Chicony HP HD Webcam [Fixed]              | 9         | 1.1%    |
| Bison ThinkPad Integrated Camera          | 9         | 1.1%    |
| Syntek EasyCamera                         | 7         | 0.85%   |
| Microdia Dell Laptop Integrated Webcam HD | 7         | 0.85%   |
| Chicony USB2.0 HD UVC WebCam              | 7         | 0.85%   |
| Chicony USB 2.0 Camera                    | 7         | 0.85%   |
| Bison HD Webcam                           | 7         | 0.85%   |
| Apple FaceTime HD Camera (Built-in)       | 7         | 0.85%   |
| Quanta HP TrueVision HD Camera            | 6         | 0.73%   |
| Microdia Laptop_Integrated_Webcam_HD      | 6         | 0.73%   |
| Lenovo Integrated Webcam                  | 6         | 0.73%   |
| IMC Networks UVC VGA Webcam               | 6         | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam             | 6         | 0.73%   |
| Chicony Realtek DMFT RGB                  | 6         | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 5         | 0.61%   |
| Lenovo Integrated Webcam [R5U877]         | 5         | 0.61%   |
| IMC Networks USB2.0 HD UVC WebCam         | 5         | 0.61%   |
| IMC Networks Integrated Webcam            | 5         | 0.61%   |
| Chicony VGA Webcam                        | 5         | 0.61%   |
| Chicony Integrated Camera [ThinkPad]      | 5         | 0.61%   |
| Chicony HP HD Camera                      | 5         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 83        | 42.56%  |
| AuthenTec                  | 30        | 15.38%  |
| Upek                       | 24        | 12.31%  |
| Synaptics                  | 15        | 7.69%   |
| STMicroelectronics         | 11        | 5.64%   |
| Elan Microelectronics      | 9         | 4.62%   |
| Broadcom                   | 9         | 4.62%   |
| Shenzhen Goodix Technology | 8         | 4.1%    |
| LighTuning Technology      | 4         | 2.05%   |
| FocalTech Systems          | 1         | 0.51%   |
| Fingerprint Cards          | 1         | 0.51%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 22        | 11.28%  |
| Validity Sensors VFS 5011 fingerprint sensor                                      | 19        | 9.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                        | 18        | 9.23%   |
| Validity Sensors Synaptics WBDI                                                   | 11        | 5.64%   |
| STMicroelectronics Fingerprint Reader                                             | 11        | 5.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 10        | 5.13%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor      | 9         | 4.62%   |
| Elan Fingerprint Sensor                                                           | 8         | 4.1%    |
| AuthenTec AES2810                                                                 | 6         | 3.08%   |
| AuthenTec AES1600                                                                 | 6         | 3.08%   |
| Validity Sensors Fingerprint scanner                                              | 5         | 2.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                                 | 5         | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                                                | 5         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                              | 5         | 2.56%   |
| AuthenTec AES1660                                                                 | 5         | 2.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 4         | 2.05%   |
| Validity Sensors VFS491                                                           | 4         | 2.05%   |
| Synaptics WBDI Fingerprint Reader USB 086                                         | 4         | 2.05%   |
| AuthenTec AES2660                                                                 | 4         | 2.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                        | 3         | 1.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 3         | 1.54%   |
| AuthenTec AES2550 Fingerprint Sensor                                              | 3         | 1.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                        | 2         | 1.03%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 2         | 1.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                         | 2         | 1.03%   |
| Upek TCS5B Fingerprint sensor                                                     | 2         | 1.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                                  | 2         | 1.03%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 2         | 1.03%   |
| Validity Sensors VFS301 Fingerprint Reader                                        | 1         | 0.51%   |
| Validity Sensors VFS Fingerprint sensor                                           | 1         | 0.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint        | 1         | 0.51%   |
| Synaptics WBDI                                                                    | 1         | 0.51%   |
| Synaptics UWP WBDI Device                                                         | 1         | 0.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                                  | 1         | 0.51%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                          | 1         | 0.51%   |
| Shenzhen Goodix  Fingerprint Device                                               | 1         | 0.51%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                         | 1         | 0.51%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 0.51%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 0.51%   |
| Elan WBF Fingerprint Sensor                                                       | 1         | 0.51%   |

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
| 1     | 396       | 35.29%  |
| 2     | 348       | 31.02%  |
| 0     | 171       | 15.24%  |
| 3     | 152       | 13.55%  |
| 4     | 44        | 3.92%   |
| 5     | 9         | 0.8%    |
| 6     | 2         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 772       | 46.56%  |
| Card reader              | 234       | 14.11%  |
| Net/wireless             | 223       | 13.45%  |
| Fingerprint reader       | 191       | 11.52%  |
| Bluetooth                | 162       | 9.77%   |
| Storage                  | 21        | 1.27%   |
| Sound                    | 17        | 1.03%   |
| Firewire controller      | 17        | 1.03%   |
| Network                  | 12        | 0.72%   |
| Net/ethernet             | 4         | 0.24%   |
| Dvb card                 | 3         | 0.18%   |
| Storage/raid             | 2         | 0.12%   |

