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

Total: 419

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T460 20FMA00F00    | [69e4dd0799](https://bsd-hardware.info/?probe=69e4dd0799) | Dec 27, 2025 |
| Apple         | MacBookPro9,2               | [a4a70bd026](https://bsd-hardware.info/?probe=a4a70bd026) | Dec 26, 2025 |
| Dell          | Latitude E6530              | [a59fc2c1a3](https://bsd-hardware.info/?probe=a59fc2c1a3) | Dec 26, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [382db82098](https://bsd-hardware.info/?probe=382db82098) | Dec 18, 2025 |
| HP            | ProBook 430 G2              | [db1c1eb244](https://bsd-hardware.info/?probe=db1c1eb244) | Dec 16, 2025 |
| Apple         | MacBook7,1                  | [0ef8b03b05](https://bsd-hardware.info/?probe=0ef8b03b05) | Nov 29, 2025 |
| Alienware     | 17 R3                       | [7d28abe778](https://bsd-hardware.info/?probe=7d28abe778) | Nov 22, 2025 |
| Dell          | Precision M4600             | [a6449e24ba](https://bsd-hardware.info/?probe=a6449e24ba) | Nov 20, 2025 |
| Acer          | Aspire ES1-512              | [3bf0ca53c1](https://bsd-hardware.info/?probe=3bf0ca53c1) | Nov 18, 2025 |
| Dell          | Precision 7510              | [e304ad6b53](https://bsd-hardware.info/?probe=e304ad6b53) | Nov 10, 2025 |
| ASUSTek       | K53SC                       | [924b22d35b](https://bsd-hardware.info/?probe=924b22d35b) | Nov 09, 2025 |
| eMachines     | E527                        | [81e8246163](https://bsd-hardware.info/?probe=81e8246163) | Nov 02, 2025 |
| Lenovo        | Unknown                     | [96d1f6a4ad](https://bsd-hardware.info/?probe=96d1f6a4ad) | Oct 31, 2025 |
| Lenovo        | ThinkPad X220 4291ZFR       | [c7e13a8f2d](https://bsd-hardware.info/?probe=c7e13a8f2d) | Oct 31, 2025 |
| ASUSTek       | K52JB                       | [831c17b144](https://bsd-hardware.info/?probe=831c17b144) | Oct 28, 2025 |
| Apple         | MacBookAir4,1               | [682e6afdb7](https://bsd-hardware.info/?probe=682e6afdb7) | Oct 21, 2025 |
| eMachines     | eM350                       | [d170a6f699](https://bsd-hardware.info/?probe=d170a6f699) | Oct 17, 2025 |
| Acer          | Aspire E1-570               | [c862bcedb5](https://bsd-hardware.info/?probe=c862bcedb5) | Oct 11, 2025 |
| BenQ          | Joybook Lite U105i          | [ab622b4793](https://bsd-hardware.info/?probe=ab622b4793) | Oct 05, 2025 |
| Dell          | Latitude E6400              | [45c2c1f321](https://bsd-hardware.info/?probe=45c2c1f321) | Sep 30, 2025 |
| HP            | EliteBook 850 G7 Noteboo... | [e111a98c7e](https://bsd-hardware.info/?probe=e111a98c7e) | Sep 24, 2025 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [92e349dd86](https://bsd-hardware.info/?probe=92e349dd86) | Sep 20, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [b4dfb3fe25](https://bsd-hardware.info/?probe=b4dfb3fe25) | Sep 04, 2025 |
| LG Electro... | 14Z960-GP5IL                | [75c2349878](https://bsd-hardware.info/?probe=75c2349878) | Sep 01, 2025 |
| Acer          | Aspire E5-574               | [83363756fe](https://bsd-hardware.info/?probe=83363756fe) | Aug 31, 2025 |
| HASEE Comp... | N960Kx                      | [be67a81c28](https://bsd-hardware.info/?probe=be67a81c28) | Aug 29, 2025 |
| Apple         | MacBookAir5,1               | [052f8e7d66](https://bsd-hardware.info/?probe=052f8e7d66) | Aug 27, 2025 |
| Lenovo        | ThinkPad T60 200757U        | [3927aea578](https://bsd-hardware.info/?probe=3927aea578) | Aug 13, 2025 |
| Lenovo        | ThinkPad T60 200757U        | [1d212095eb](https://bsd-hardware.info/?probe=1d212095eb) | Aug 13, 2025 |
| Lenovo        | ThinkPad L420 782746U       | [45d26a88f2](https://bsd-hardware.info/?probe=45d26a88f2) | Aug 05, 2025 |
| Dell          | Inspiron 5559               | [04e7a6f515](https://bsd-hardware.info/?probe=04e7a6f515) | Jul 28, 2025 |
| Lenovo        | B470e HuronRiver Platfor... | [a4e9b01ed3](https://bsd-hardware.info/?probe=a4e9b01ed3) | Jul 21, 2025 |
| Lenovo        | ThinkPad T430 2349CTO       | [2c62e80103](https://bsd-hardware.info/?probe=2c62e80103) | Jul 13, 2025 |
| Acer          | Aspire A315-23              | [c99285530d](https://bsd-hardware.info/?probe=c99285530d) | Jul 08, 2025 |
| Acer          | Aspire A315-23              | [2a25ab1af4](https://bsd-hardware.info/?probe=2a25ab1af4) | Jul 08, 2025 |
| Lenovo        | ThinkPad E15 20RD005HUS     | [27bc961fcd](https://bsd-hardware.info/?probe=27bc961fcd) | Jul 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9e4e99a77d](https://bsd-hardware.info/?probe=9e4e99a77d) | Jun 26, 2025 |
| Apple         | MacBook4,1                  | [22fdd3b950](https://bsd-hardware.info/?probe=22fdd3b950) | Jun 20, 2025 |
| Dell          | Inspiron 1520               | [6fbe37c316](https://bsd-hardware.info/?probe=6fbe37c316) | Jun 19, 2025 |
| Dell          | Latitude E5540              | [1673f60df4](https://bsd-hardware.info/?probe=1673f60df4) | Jun 16, 2025 |
| HP            | ProBook 440 G3              | [e98046a043](https://bsd-hardware.info/?probe=e98046a043) | May 31, 2025 |
| LG Electro... | Z360-G.BG71P1               | [ee691a990c](https://bsd-hardware.info/?probe=ee691a990c) | May 08, 2025 |
| Multilaser    | UB22X                       | [fdc94fecc9](https://bsd-hardware.info/?probe=fdc94fecc9) | May 05, 2025 |
| Lenovo        | ThinkPad X240 20AMS7M800    | [e39734e519](https://bsd-hardware.info/?probe=e39734e519) | May 01, 2025 |
| Positivo      | S14BW01                     | [4eb5ebcf6d](https://bsd-hardware.info/?probe=4eb5ebcf6d) | Apr 22, 2025 |
| Dell          | Precision M4800             | [9cc1c2089d](https://bsd-hardware.info/?probe=9cc1c2089d) | Apr 14, 2025 |
| Dell          | Precision M4800             | [7dddf66c8c](https://bsd-hardware.info/?probe=7dddf66c8c) | Apr 14, 2025 |
| ASUSTek       | X555LB                      | [712d49a30c](https://bsd-hardware.info/?probe=712d49a30c) | Apr 10, 2025 |
| ASUSTek       | X555LB                      | [60f8c81294](https://bsd-hardware.info/?probe=60f8c81294) | Apr 10, 2025 |
| Toshiba       | Satellite U500              | [d1831ac8a5](https://bsd-hardware.info/?probe=d1831ac8a5) | Apr 04, 2025 |
| Dell          | Latitude E6540              | [d36a68717a](https://bsd-hardware.info/?probe=d36a68717a) | Mar 24, 2025 |
| Dell          | Vostro 5471                 | [f8e21968bd](https://bsd-hardware.info/?probe=f8e21968bd) | Mar 22, 2025 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [b4c15f0f7b](https://bsd-hardware.info/?probe=b4c15f0f7b) | Mar 19, 2025 |
| Dell          | Latitude 3420               | [0fd9295c89](https://bsd-hardware.info/?probe=0fd9295c89) | Mar 17, 2025 |
| Dell          | Latitude E6430              | [b3cd44d807](https://bsd-hardware.info/?probe=b3cd44d807) | Mar 15, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9294266766](https://bsd-hardware.info/?probe=9294266766) | Mar 15, 2025 |
| Fujitsu       | LIFEBOOK U745               | [51a0ad3f62](https://bsd-hardware.info/?probe=51a0ad3f62) | Mar 14, 2025 |
| HP            | ENVY Laptop 17-da0xxx       | [5c09a6b720](https://bsd-hardware.info/?probe=5c09a6b720) | Mar 13, 2025 |
| Dell          | Latitude E6420              | [38f99c7eee](https://bsd-hardware.info/?probe=38f99c7eee) | Mar 10, 2025 |
| HONOR         | BRN-HXX                     | [b560f90081](https://bsd-hardware.info/?probe=b560f90081) | Feb 19, 2025 |
| Acer          | AOHAPPY2                    | [b8495fa045](https://bsd-hardware.info/?probe=b8495fa045) | Feb 15, 2025 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [8d5ce1eca6](https://bsd-hardware.info/?probe=8d5ce1eca6) | Feb 15, 2025 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [350016d15c](https://bsd-hardware.info/?probe=350016d15c) | Feb 06, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [22637a1fba](https://bsd-hardware.info/?probe=22637a1fba) | Jan 20, 2025 |
| Lenovo        | IdeaPad S145-15API 81V7     | [4bd0423b13](https://bsd-hardware.info/?probe=4bd0423b13) | Jan 05, 2025 |
| HP            | EliteBook 840 G3            | [5e09879203](https://bsd-hardware.info/?probe=5e09879203) | Jan 03, 2025 |
| Dell          | Latitude E7250              | [dbff7c2ebb](https://bsd-hardware.info/?probe=dbff7c2ebb) | Jan 02, 2025 |
| Lenovo        | V15-ADA 82C7                | [62c66a5499](https://bsd-hardware.info/?probe=62c66a5499) | Dec 29, 2024 |
| Lenovo        | V15-ADA 82C7                | [67ea149c61](https://bsd-hardware.info/?probe=67ea149c61) | Dec 29, 2024 |
| Dell          | Inspiron 3458               | [c90d1d5857](https://bsd-hardware.info/?probe=c90d1d5857) | Dec 24, 2024 |
| HP            | 2000                        | [0705a401f8](https://bsd-hardware.info/?probe=0705a401f8) | Dec 16, 2024 |
| HP            | ProBook 4430s               | [45102636ac](https://bsd-hardware.info/?probe=45102636ac) | Dec 16, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [196fb6634a](https://bsd-hardware.info/?probe=196fb6634a) | Dec 03, 2024 |
| Fujitsu       | LIFEBOOK T730               | [577dc596e5](https://bsd-hardware.info/?probe=577dc596e5) | Nov 23, 2024 |
| Fujitsu       | LIFEBOOK T730               | [b5cfe0c0b2](https://bsd-hardware.info/?probe=b5cfe0c0b2) | Nov 23, 2024 |
| Dell          | Vostro 3400                 | [65071f6e52](https://bsd-hardware.info/?probe=65071f6e52) | Nov 18, 2024 |
| ASUSTek       | K54C                        | [4f0c073344](https://bsd-hardware.info/?probe=4f0c073344) | Nov 12, 2024 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [4bcf1051ee](https://bsd-hardware.info/?probe=4bcf1051ee) | Nov 09, 2024 |
| ASUSTek       | GL752VW                     | [efc1d86951](https://bsd-hardware.info/?probe=efc1d86951) | Nov 02, 2024 |
| Lenovo        | ThinkPad X280 20KES2VQ00    | [d864971168](https://bsd-hardware.info/?probe=d864971168) | Oct 30, 2024 |
| HP            | Pavilion Notebook           | [4609004e3e](https://bsd-hardware.info/?probe=4609004e3e) | Oct 30, 2024 |
| ASUSTek       | X453SA                      | [51933883d6](https://bsd-hardware.info/?probe=51933883d6) | Oct 29, 2024 |
| Lenovo        | ThinkPad E470 20H1002FLM    | [d11900e726](https://bsd-hardware.info/?probe=d11900e726) | Oct 25, 2024 |
| Lenovo        | ThinkPad X201T 3093A79      | [9f1d2db1a6](https://bsd-hardware.info/?probe=9f1d2db1a6) | Oct 25, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | [934ff561a5](https://bsd-hardware.info/?probe=934ff561a5) | Oct 20, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | [6c6e16db1a](https://bsd-hardware.info/?probe=6c6e16db1a) | Oct 19, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | [37cb237ce2](https://bsd-hardware.info/?probe=37cb237ce2) | Oct 07, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [370c96e120](https://bsd-hardware.info/?probe=370c96e120) | Oct 02, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [71dbda24c3](https://bsd-hardware.info/?probe=71dbda24c3) | Oct 02, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [4713dcbd2c](https://bsd-hardware.info/?probe=4713dcbd2c) | Oct 02, 2024 |
| Sony          | VGN-FZ19VN                  | [a5e398c41f](https://bsd-hardware.info/?probe=a5e398c41f) | Sep 28, 2024 |
| Acer          | Aspire 4820                 | [2ba56db0c4](https://bsd-hardware.info/?probe=2ba56db0c4) | Sep 26, 2024 |
| Apple         | MacBook6,1                  | [6b5e02a63b](https://bsd-hardware.info/?probe=6b5e02a63b) | Sep 22, 2024 |
| Dell          | Latitude E6440              | [cfabb27e7a](https://bsd-hardware.info/?probe=cfabb27e7a) | Sep 21, 2024 |
| Dell          | Latitude E6540              | [e8bdb7007b](https://bsd-hardware.info/?probe=e8bdb7007b) | Sep 19, 2024 |
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
| Dell          | Latitude 3410               | [c5b69d8cf7](https://bsd-hardware.info/?probe=c5b69d8cf7) | Jul 23, 2024 |
| HP            | Pavilion g6                 | [19ddfa696d](https://bsd-hardware.info/?probe=19ddfa696d) | Jul 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [b66947b74a](https://bsd-hardware.info/?probe=b66947b74a) | Jul 16, 2024 |
| Lenovo        | ThinkPad X200 7459WT6       | [fa49267388](https://bsd-hardware.info/?probe=fa49267388) | Jul 13, 2024 |
| HP            | EliteBook 820 G1            | [0de2223643](https://bsd-hardware.info/?probe=0de2223643) | Jul 11, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [0529ba7873](https://bsd-hardware.info/?probe=0529ba7873) | Jul 09, 2024 |
| Lenovo        | ThinkPad X230 2325SCM       | [8406cad5be](https://bsd-hardware.info/?probe=8406cad5be) | Jul 06, 2024 |
| Lenovo        | M30-70 20446                | [fd24cae390](https://bsd-hardware.info/?probe=fd24cae390) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [e9a1a61239](https://bsd-hardware.info/?probe=e9a1a61239) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [babc2efc9e](https://bsd-hardware.info/?probe=babc2efc9e) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [0251872176](https://bsd-hardware.info/?probe=0251872176) | Jun 26, 2024 |
| HP            | Pavilion dv6500             | [49f31626da](https://bsd-hardware.info/?probe=49f31626da) | Jun 16, 2024 |
| Dell          | Latitude E6410              | [30f7b05dcf](https://bsd-hardware.info/?probe=30f7b05dcf) | Jun 15, 2024 |
| Framework     | Laptop                      | [f43baabeee](https://bsd-hardware.info/?probe=f43baabeee) | Jun 12, 2024 |
| Fujitsu       | CELSIUS H710                | [93308d8e8e](https://bsd-hardware.info/?probe=93308d8e8e) | Jun 11, 2024 |
| Notebook      | W740SU                      | [31be7db967](https://bsd-hardware.info/?probe=31be7db967) | Jun 09, 2024 |
| Fujitsu       | LIFEBOOK E751               | [c4e275f1a2](https://bsd-hardware.info/?probe=c4e275f1a2) | Jun 08, 2024 |
| ASUSTek       | X555LAB                     | [20959ef447](https://bsd-hardware.info/?probe=20959ef447) | Jun 05, 2024 |
| ASUSTek       | X555UJ                      | [df9f681ce9](https://bsd-hardware.info/?probe=df9f681ce9) | Jun 05, 2024 |
| Toshiba       | Satellite C800D             | [3b26adb52f](https://bsd-hardware.info/?probe=3b26adb52f) | Jun 05, 2024 |
| Sony          | SVF1521G6EW                 | [b977d6f1e0](https://bsd-hardware.info/?probe=b977d6f1e0) | Jun 02, 2024 |
| HP            | Laptop 14s-dy5xxx           | [76d2f8d955](https://bsd-hardware.info/?probe=76d2f8d955) | May 28, 2024 |
| ASUSTek       | N50Vc                       | [69d37366c1](https://bsd-hardware.info/?probe=69d37366c1) | May 27, 2024 |
| HP            | Compaq Presario CQ71        | [ddf13477d5](https://bsd-hardware.info/?probe=ddf13477d5) | May 24, 2024 |
| Thomson       | N15C                        | [45c095d0c8](https://bsd-hardware.info/?probe=45c095d0c8) | May 23, 2024 |
| HP            | OMEN by Laptop              | [7148244e3e](https://bsd-hardware.info/?probe=7148244e3e) | May 21, 2024 |
| HP            | Compaq Presario CQ71        | [7646daa3c0](https://bsd-hardware.info/?probe=7646daa3c0) | May 19, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | [9bc81955aa](https://bsd-hardware.info/?probe=9bc81955aa) | May 08, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | [651bd2de24](https://bsd-hardware.info/?probe=651bd2de24) | May 08, 2024 |
| Acer          | Aspire R3-131T              | [dec4102ec0](https://bsd-hardware.info/?probe=dec4102ec0) | May 07, 2024 |
| Lenovo        | ThinkPad L420 7827W27       | [5231c79a27](https://bsd-hardware.info/?probe=5231c79a27) | May 05, 2024 |
| Apple         | MacBook4,1                  | [5916d9274d](https://bsd-hardware.info/?probe=5916d9274d) | May 05, 2024 |
| Lenovo        | B51-30 80LK                 | [c1435ee19d](https://bsd-hardware.info/?probe=c1435ee19d) | Apr 21, 2024 |
| HP            | OMEN by Laptop              | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [0de254980a](https://bsd-hardware.info/?probe=0de254980a) | Apr 16, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| ASUSTek       | N76VZ                       | [c1af06bf99](https://bsd-hardware.info/?probe=c1af06bf99) | Apr 12, 2024 |
| Dell          | Latitude E5530 non-vPro     | [227f0ffb18](https://bsd-hardware.info/?probe=227f0ffb18) | Apr 09, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [21768f1b7a](https://bsd-hardware.info/?probe=21768f1b7a) | Apr 04, 2024 |
| Lenovo        | ThinkPad W530 2447GH2       | [0cb3f41765](https://bsd-hardware.info/?probe=0cb3f41765) | Apr 01, 2024 |
| Lenovo        | G510 20238                  | [faf771068a](https://bsd-hardware.info/?probe=faf771068a) | Mar 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| ASUSTek       | X550CA                      | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| Lenovo        | G580 20150                  | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| Dell          | Latitude E6220              | [5a42aa442f](https://bsd-hardware.info/?probe=5a42aa442f) | Mar 09, 2024 |
| Maibenben     | MaiBook X series            | [2a58491971](https://bsd-hardware.info/?probe=2a58491971) | Mar 03, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [3653895b8e](https://bsd-hardware.info/?probe=3653895b8e) | Mar 03, 2024 |
| Acer          | Aspire A715-75G             | [415aa43c5c](https://bsd-hardware.info/?probe=415aa43c5c) | Mar 02, 2024 |
| Itautec       | Infoway                     | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Lenovo        | ThinkPad X220 4290KV8       | [9bc55d7f8a](https://bsd-hardware.info/?probe=9bc55d7f8a) | Feb 23, 2024 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | [5702ec8e8e](https://bsd-hardware.info/?probe=5702ec8e8e) | Feb 22, 2024 |
| Lenovo        | ThinkPad T480 20L6SDA400    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| ASUSTek       | K52F                        | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| Panasonic     | CF-52PGNBX2M                | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| ASUSTek       | K52F                        | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| Lenovo        | ThinkPad T460 20FMS1VA1D    | [03d11c45e9](https://bsd-hardware.info/?probe=03d11c45e9) | Jan 28, 2024 |
| Dell          | Precision M4700             | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Acer          | Nitro AN515-54              | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Apple         | MacBookAir4,1               | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | Latitude 7480               | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| HP            | Mini 210-1000               | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| HP            | Mini 210-1000               | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| Apple         | MacBookAir4,1               | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| Dell          | Inspiron 14-3452            | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| ASUSTek       | X551MA                      | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| Lenovo        | ThinkPad X250 20CMS01M00    | [1f52525bb9](https://bsd-hardware.info/?probe=1f52525bb9) | Jan 04, 2024 |
| Samsung       | R510/P510                   | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| Dell          | Vostro V130                 | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| eMachines     | eM350                       | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| Acer          | V5-131                      | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| Intel         | H81U                        | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Samsung       | N150P/N210P/N220P           | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b85df96058](https://bsd-hardware.info/?probe=b85df96058) | Nov 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Gateway       | NV79                        | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Lenovo        | Z50-70 20354                | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Toshiba       | Unknown                     | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Acer          | Aspire 5336                 | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Apple         | MacBook5,2                  | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | Latitude 3440               | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire ES1-571              | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| Apple         | MacBook5,1                  | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| ASUSTek       | K73E                        | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| OEGStone      | doceo 510                   | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| HP            | OMEN by Laptop              | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| HP            | Pavilion g7                 | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| HP            | 2000                        | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| HP            | Pavilion dv3500             | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| NVN-ED01      | Unknown                     | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| ASUSTek       | X553MA                      | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Acer          | Aspire V3-371               | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
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
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| ASUSTek       | X541UVK                     | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| HP            | Compaq Presario CQ61        | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Acer          | Aspire 5749                 | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
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
| amd64 | 357       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 355       | 99.44%  |
| JWM          | 1         | 0.28%   |
| GNOME        | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 357       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 357       | 99.72%  |
| SDDM | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 171       | 47.5%   |
| fr_FR   | 43        | 11.94%  |
| ru_RU   | 28        | 7.78%   |
| de_DE   | 22        | 6.11%   |
| Unknown | 19        | 5.28%   |
| es_ES   | 18        | 5%      |
| pl_PL   | 12        | 3.33%   |
| it_IT   | 12        | 3.33%   |
| pt_BR   | 11        | 3.06%   |
| nl_NL   | 5         | 1.39%   |
| zh_CN   | 4         | 1.11%   |
| fi_FI   | 3         | 0.83%   |
| pt_PT   | 2         | 0.56%   |
| ko_KR   | 2         | 0.56%   |
| zh_TW   | 1         | 0.28%   |
| tr_TR   | 1         | 0.28%   |
| pt      | 1         | 0.28%   |
| jp_JP   | 1         | 0.28%   |
| fi_DK   | 1         | 0.28%   |
| en_GB   | 1         | 0.28%   |
| en      | 1         | 0.28%   |
| C       | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 355       | 99.44%  |
| BIOS | 2         | 0.56%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 179       | 50.14%  |
| Cd9660 | 178       | 49.86%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 355       | 99.44%  |
| MBR  | 2         | 0.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 115       | 32.21%  |
| Hewlett-Packard     | 51        | 14.29%  |
| Dell                | 47        | 13.17%  |
| ASUSTek Computer    | 31        | 8.68%   |
| Acer                | 20        | 5.6%    |
| Apple               | 17        | 4.76%   |
| Toshiba             | 11        | 3.08%   |
| Samsung Electronics | 11        | 3.08%   |
| Fujitsu             | 9         | 2.52%   |
| Sony                | 4         | 1.12%   |
| LG Electronics      | 3         | 0.84%   |
| Google              | 3         | 0.84%   |
| eMachines           | 3         | 0.84%   |
| Panasonic           | 2         | 0.56%   |
| Packard Bell        | 2         | 0.56%   |
| Intel               | 2         | 0.56%   |
| TUXEDO              | 1         | 0.28%   |
| Timi                | 1         | 0.28%   |
| Thomson             | 1         | 0.28%   |
| Positivo            | 1         | 0.28%   |
| Plaisio             | 1         | 0.28%   |
| OEGStone            | 1         | 0.28%   |
| NVN-ED01            | 1         | 0.28%   |
| Notebook            | 1         | 0.28%   |
| Multilaser          | 1         | 0.28%   |
| MSI                 | 1         | 0.28%   |
| Medion              | 1         | 0.28%   |
| Maibenben           | 1         | 0.28%   |
| Itautec             | 1         | 0.28%   |
| Irbis               | 1         | 0.28%   |
| Intelbras           | 1         | 0.28%   |
| IGEL Technology     | 1         | 0.28%   |
| HUAWEI              | 1         | 0.28%   |
| HONOR               | 1         | 0.28%   |
| HASEE Computer      | 1         | 0.28%   |
| Gateway             | 1         | 0.28%   |
| Framework           | 1         | 0.28%   |
| Dynabook Europe     | 1         | 0.28%   |
| DNS                 | 1         | 0.28%   |
| Compaq              | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 5         | 1.4%    |
| Apple MacBookPro9,2             | 3         | 0.84%   |
| Apple MacBook4,1                | 3         | 0.84%   |
| Lenovo IdeaPad S145-15IWL 81MV  | 2         | 0.56%   |
| HP Pavilion Notebook            | 2         | 0.56%   |
| HP Pavilion g6                  | 2         | 0.56%   |
| HP Laptop 14-bs0xx              | 2         | 0.56%   |
| HP EliteBook 840 G3             | 2         | 0.56%   |
| HP 255 15.6 inch G9 Notebook PC | 2         | 0.56%   |
| HP 2000                         | 2         | 0.56%   |
| eMachines eM350                 | 2         | 0.56%   |
| Dell Latitude E6540             | 2         | 0.56%   |
| Apple MacBookAir4,1             | 2         | 0.56%   |
| Apple MacBook5,1                | 2         | 0.56%   |
| TUXEDO Aura 15 Gen1             | 1         | 0.28%   |
| Toshiba Satellite U500          | 1         | 0.28%   |
| Toshiba Satellite P300          | 1         | 0.28%   |
| Toshiba Satellite L675D         | 1         | 0.28%   |
| Toshiba Satellite L50-B         | 1         | 0.28%   |
| Toshiba Satellite L40           | 1         | 0.28%   |
| Toshiba Satellite C845          | 1         | 0.28%   |
| Toshiba Satellite C800D         | 1         | 0.28%   |
| Toshiba Satellite A200          | 1         | 0.28%   |
| Toshiba QOSMIO X775             | 1         | 0.28%   |
| Toshiba PORTEGE R700            | 1         | 0.28%   |
| Timi TM1701                     | 1         | 0.28%   |
| Thomson N15C                    | 1         | 0.28%   |
| Sony VPCEG15FB                  | 1         | 0.28%   |
| Sony VGN-FZ19VN                 | 1         | 0.28%   |
| Sony SVF1521G6EW                | 1         | 0.28%   |
| Sony SVF14A15CBB                | 1         | 0.28%   |
| Samsung RC530/RC730             | 1         | 0.28%   |
| Samsung R530/R730/R540          | 1         | 0.28%   |
| Samsung R520/R522/R620          | 1         | 0.28%   |
| Samsung R510/P510               | 1         | 0.28%   |
| Samsung R468/R418               | 1         | 0.28%   |
| Samsung N150P/N210P/N220P       | 1         | 0.28%   |
| Samsung 370E4K                  | 1         | 0.28%   |
| Samsung 340XAA/350XAA/550XAA    | 1         | 0.28%   |
| Samsung 305E4A/305E5A/305E7A    | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 75        | 21.01%  |
| Dell Latitude     | 28        | 7.84%   |
| Lenovo IdeaPad    | 19        | 5.32%   |
| HP Pavilion       | 14        | 3.92%   |
| Acer Aspire       | 14        | 3.92%   |
| Dell Inspiron     | 11        | 3.08%   |
| Toshiba Satellite | 8         | 2.24%   |
| HP Laptop         | 8         | 2.24%   |
| HP EliteBook      | 7         | 1.96%   |
| Fujitsu LIFEBOOK  | 6         | 1.68%   |
| ASUS VivoBook     | 6         | 1.68%   |
| HP Compaq         | 5         | 1.4%    |
| Unknown           | 5         | 1.4%    |
| HP ProBook        | 4         | 1.12%   |
| Dell Precision    | 4         | 1.12%   |
| Lenovo Yoga       | 3         | 0.84%   |
| Dell Vostro       | 3         | 0.84%   |
| Apple MacBookPro9 | 3         | 0.84%   |
| Apple MacBook5    | 3         | 0.84%   |
| Apple MacBook4    | 3         | 0.84%   |
| Lenovo Legion     | 2         | 0.56%   |
| HP Stream         | 2         | 0.56%   |
| HP 255            | 2         | 0.56%   |
| HP 2000           | 2         | 0.56%   |
| Fujitsu CELSIUS   | 2         | 0.56%   |
| eMachines eM350   | 2         | 0.56%   |
| Apple MacBookAir4 | 2         | 0.56%   |
| Acer TravelMate   | 2         | 0.56%   |
| TUXEDO Aura       | 1         | 0.28%   |
| Toshiba QOSMIO    | 1         | 0.28%   |
| Toshiba PORTEGE   | 1         | 0.28%   |
| Timi TM1701       | 1         | 0.28%   |
| Thomson N15C      | 1         | 0.28%   |
| Sony VPCEG15FB    | 1         | 0.28%   |
| Sony VGN-FZ19VN   | 1         | 0.28%   |
| Sony SVF1521G6EW  | 1         | 0.28%   |
| Sony SVF14A15CBB  | 1         | 0.28%   |
| Samsung RC530     | 1         | 0.28%   |
| Samsung R530      | 1         | 0.28%   |
| Samsung R520      | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 37        | 10.36%  |
| 2012 | 31        | 8.68%   |
| 2013 | 29        | 8.12%   |
| 2020 | 24        | 6.72%   |
| 2016 | 24        | 6.72%   |
| 2019 | 23        | 6.44%   |
| 2010 | 23        | 6.44%   |
| 2009 | 21        | 5.88%   |
| 2022 | 20        | 5.6%    |
| 2017 | 19        | 5.32%   |
| 2015 | 19        | 5.32%   |
| 2021 | 18        | 5.04%   |
| 2014 | 16        | 4.48%   |
| 2018 | 15        | 4.2%    |
| 2008 | 13        | 3.64%   |
| 2023 | 11        | 3.08%   |
| 2007 | 7         | 1.96%   |
| 2024 | 4         | 1.12%   |
| 2006 | 3         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 357       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 352       | 98.6%   |
| Yes  | 5         | 1.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 129       | 36.03%  |
| 4.01-8.0    | 102       | 28.49%  |
| 16.01-24.0  | 73        | 20.39%  |
| 2.01-3.0    | 29        | 8.1%    |
| 32.01-64.0  | 12        | 3.35%   |
| 3.01-4.0    | 11        | 3.07%   |
| 64.01-256.0 | 2         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 224       | 62.75%  |
| 0.51-1.0 | 96        | 26.89%  |
| 1.01-2.0 | 27        | 7.56%   |
| 2.01-3.0 | 8         | 2.24%   |
| 4.01-8.0 | 1         | 0.28%   |
| 3.01-4.0 | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 270       | 75.21%  |
| 2      | 55        | 15.32%  |
| 0      | 27        | 7.52%   |
| 3      | 7         | 1.95%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 229       | 64.15%  |
| Yes       | 128       | 35.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 313       | 87.68%  |
| No        | 44        | 12.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 347       | 97.2%   |
| No        | 10        | 2.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 73.11%  |
| No        | 96        | 26.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 55        | 15.41%  |
| Russia              | 28        | 7.84%   |
| Germany             | 27        | 7.56%   |
| Poland              | 24        | 6.72%   |
| Brazil              | 24        | 6.72%   |
| Italy               | 16        | 4.48%   |
| Indonesia           | 13        | 3.64%   |
| UK                  | 12        | 3.36%   |
| Spain               | 12        | 3.36%   |
| India               | 10        | 2.8%    |
| France              | 9         | 2.52%   |
| Canada              | 8         | 2.24%   |
| Turkey              | 7         | 1.96%   |
| Netherlands         | 7         | 1.96%   |
| China               | 7         | 1.96%   |
| Romania             | 6         | 1.68%   |
| Portugal            | 6         | 1.68%   |
| Mexico              | 6         | 1.68%   |
| Hungary             | 6         | 1.68%   |
| Finland             | 5         | 1.4%    |
| Australia           | 5         | 1.4%    |
| South Korea         | 3         | 0.84%   |
| Lithuania           | 3         | 0.84%   |
| Czechia             | 3         | 0.84%   |
| Chile               | 3         | 0.84%   |
| Bulgaria            | 3         | 0.84%   |
| Vietnam             | 2         | 0.56%   |
| Ukraine             | 2         | 0.56%   |
| Switzerland         | 2         | 0.56%   |
| New Zealand         | 2         | 0.56%   |
| Moldova             | 2         | 0.56%   |
| Israel              | 2         | 0.56%   |
| Greece              | 2         | 0.56%   |
| Denmark             | 2         | 0.56%   |
| Cyprus              | 2         | 0.56%   |
| Colombia            | 2         | 0.56%   |
| Bangladesh          | 2         | 0.56%   |
| Venezuela           | 1         | 0.28%   |
| Uzbekistan          | 1         | 0.28%   |
| Trinidad and Tobago | 1         | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| St Petersburg | 6         | 1.65%   |
| Sao Paulo     | 6         | 1.65%   |
| Berlin        | 5         | 1.38%   |
| Wroclaw       | 4         | 1.1%    |
| Moscow        | 3         | 0.83%   |
| Milan         | 3         | 0.83%   |
| Lisbon        | 3         | 0.83%   |
| Kochi         | 3         | 0.83%   |
| Jakarta       | 3         | 0.83%   |
| Irkutsk       | 3         | 0.83%   |
| Budapest      | 3         | 0.83%   |
| Yogyakarta    | 2         | 0.55%   |
| Warsaw        | 2         | 0.55%   |
| Vilnius       | 2         | 0.55%   |
| Valencia      | 2         | 0.55%   |
| Tolyatti      | 2         | 0.55%   |
| Sydney        | 2         | 0.55%   |
| Shenzhen      | 2         | 0.55%   |
| Santiago      | 2         | 0.55%   |
| Sanford       | 2         | 0.55%   |
| Peterborough  | 2         | 0.55%   |
| Montreal      | 2         | 0.55%   |
| Los Angeles   | 2         | 0.55%   |
| Leipzig       | 2         | 0.55%   |
| Krakow        | 2         | 0.55%   |
| Jaipur        | 2         | 0.55%   |
| Istanbul      | 2         | 0.55%   |
| Hamburg       | 2         | 0.55%   |
| Depok         | 2         | 0.55%   |
| Chicago       | 2         | 0.55%   |
| Brisbane      | 2         | 0.55%   |
| Ankara        | 2         | 0.55%   |
| Zurich        | 1         | 0.28%   |
| Zele          | 1         | 0.28%   |
| Zarautz       | 1         | 0.28%   |
| Yuseong-gu    | 1         | 0.28%   |
| Yeosu         | 1         | 0.28%   |
| Yekaterinburg | 1         | 0.28%   |
| Xalapa        | 1         | 0.28%   |
| Woodbridge    | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 67     | 14.97%  |
| WDC                 | 42        | 43     | 10.66%  |
| Seagate             | 33        | 36     | 8.38%   |
| Toshiba             | 32        | 34     | 8.12%   |
| Kingston            | 25        | 25     | 6.35%   |
| SanDisk             | 20        | 20     | 5.08%   |
| Hitachi             | 19        | 19     | 4.82%   |
| Crucial             | 19        | 22     | 4.82%   |
| SK hynix            | 13        | 13     | 3.3%    |
| HGST                | 12        | 15     | 3.05%   |
| Intel               | 10        | 11     | 2.54%   |
| A-DATA Technology   | 10        | 10     | 2.54%   |
| Micron Technology   | 8         | 8      | 2.03%   |
| China               | 6         | 6      | 1.52%   |
| Transcend           | 5         | 5      | 1.27%   |
| Patriot             | 5         | 5      | 1.27%   |
| GOODRAM             | 5         | 5      | 1.27%   |
| Apple               | 5         | 5      | 1.27%   |
| SPCC                | 4         | 5      | 1.02%   |
| Gigabyte Technology | 4         | 4      | 1.02%   |
| Fujitsu             | 4         | 5      | 1.02%   |
| Dogfish             | 4         | 4      | 1.02%   |
| KIOXIA              | 3         | 3      | 0.76%   |
| KingSpec            | 3         | 3      | 0.76%   |
| Intenso             | 3         | 3      | 0.76%   |
| Team                | 2         | 2      | 0.51%   |
| PNY                 | 2         | 2      | 0.51%   |
| Phison              | 2         | 2      | 0.51%   |
| OCZ                 | 2         | 2      | 0.51%   |
| Lexar               | 2         | 2      | 0.51%   |
| BHT                 | 2         | 2      | 0.51%   |
| Apacer              | 2         | 2      | 0.51%   |
| YMTC                | 1         | 1      | 0.25%   |
| Verbatim            | 1         | 1      | 0.25%   |
| Vaseky              | 1         | 1      | 0.25%   |
| V-GeN               | 1         | 1      | 0.25%   |
| UMIS                | 1         | 1      | 0.25%   |
| SSSTC               | 1         | 1      | 0.25%   |
| Silicon Motion      | 1         | 1      | 0.25%   |
| Silicon             | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB       | 5         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 1.25%   |
| Samsung SSD 860 EVO 500GB          | 5         | 1.25%   |
| Toshiba MQ01ABF050 500GB           | 4         | 1%      |
| Seagate ST9500325AS 500GB          | 4         | 1%      |
| Kingston SA400S37240G 240GB        | 4         | 1%      |
| HGST HTS721010A9E630 1TB           | 4         | 1%      |
| Crucial CT480BX500SSD1 480GB       | 4         | 1%      |
| Toshiba MQ01ABD100 1TB             | 3         | 0.75%   |
| Samsung SSD 980 500GB              | 3         | 0.75%   |
| Kingston SV300S37A60G 64GB         | 3         | 0.75%   |
| HGST HTS725050A7E630 500GB         | 3         | 0.75%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 0.75%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.5%    |
| WDC WD3200BPVT-22ZEST0 320GB       | 2         | 0.5%    |
| WDC WD2500BEVT-22ZCT0 250GB        | 2         | 0.5%    |
| WDC PC SN530 NVMe 256GB            | 2         | 0.5%    |
| Transcend TS120GSSD220S 120GB      | 2         | 0.5%    |
| Toshiba MQ01ACF050 500GB           | 2         | 0.5%    |
| Toshiba MK3261GSY 320GB            | 2         | 0.5%    |
| SPCC Solid State Disk 256GB        | 2         | 0.5%    |
| SPCC Solid State Disk 128GB        | 2         | 0.5%    |
| SK hynix SC210 mSATA 256GB         | 2         | 0.5%    |
| SK hynix HFM512GDHTNG-8310A 512GB  | 2         | 0.5%    |
| Seagate ST9250410AS 250GB          | 2         | 0.5%    |
| Seagate ST9160827AS 160GB          | 2         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.5%    |
| Seagate ST500LM000-1EJ162 500GB    | 2         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.5%    |
| SanDisk SSD PLUS 120GB             | 2         | 0.5%    |
| Samsung SSD 850 EVO 250GB          | 2         | 0.5%    |
| Samsung MZVLB256HAHQ-000H1 256GB   | 2         | 0.5%    |
| Samsung MZALQ512HBLU-00BL2 512GB   | 2         | 0.5%    |
| Samsung HM321HI 320GB              | 2         | 0.5%    |
| Samsung HM160HI 160GB              | 2         | 0.5%    |
| Micron 1100 SATA 256GB             | 2         | 0.5%    |
| KIOXIA KBG40ZNV512G 512GB          | 2         | 0.5%    |
| Kingston SV300S37A240G 240GB       | 2         | 0.5%    |
| Kingston SV300S37A120G 120GB       | 2         | 0.5%    |
| Kingston SA400S37960G 960GB        | 2         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 36     | 25.19%  |
| Toshiba             | 29        | 31     | 22.14%  |
| WDC                 | 25        | 25     | 19.08%  |
| Hitachi             | 19        | 19     | 14.5%   |
| HGST                | 12        | 15     | 9.16%   |
| Samsung Electronics | 7         | 8      | 5.34%   |
| Fujitsu             | 4         | 5      | 3.05%   |
| Maxtor              | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 31     | 14.72%  |
| Kingston            | 24        | 24     | 12.18%  |
| SanDisk             | 20        | 20     | 10.15%  |
| Crucial             | 17        | 20     | 8.63%   |
| WDC                 | 8         | 9      | 4.06%   |
| A-DATA Technology   | 8         | 8      | 4.06%   |
| Micron Technology   | 6         | 6      | 3.05%   |
| Intel               | 6         | 6      | 3.05%   |
| China               | 6         | 6      | 3.05%   |
| Patriot             | 5         | 5      | 2.54%   |
| GOODRAM             | 5         | 5      | 2.54%   |
| Transcend           | 4         | 4      | 2.03%   |
| SPCC                | 4         | 5      | 2.03%   |
| Dogfish             | 4         | 4      | 2.03%   |
| Apple               | 4         | 4      | 2.03%   |
| SK hynix            | 3         | 3      | 1.52%   |
| KingSpec            | 3         | 3      | 1.52%   |
| Intenso             | 3         | 3      | 1.52%   |
| Gigabyte Technology | 3         | 3      | 1.52%   |
| Toshiba             | 2         | 2      | 1.02%   |
| Team                | 2         | 2      | 1.02%   |
| PNY                 | 2         | 2      | 1.02%   |
| OCZ                 | 2         | 2      | 1.02%   |
| Lexar               | 2         | 2      | 1.02%   |
| BHT                 | 2         | 2      | 1.02%   |
| Apacer              | 2         | 2      | 1.02%   |
| YMTC                | 1         | 1      | 0.51%   |
| Verbatim            | 1         | 1      | 0.51%   |
| Vaseky              | 1         | 1      | 0.51%   |
| V-GeN               | 1         | 1      | 0.51%   |
| SSSTC               | 1         | 1      | 0.51%   |
| Silicon             | 1         | 1      | 0.51%   |
| SemsoTai            | 1         | 1      | 0.51%   |
| Plextor             | 1         | 1      | 0.51%   |
| Netac               | 1         | 1      | 0.51%   |
| MSI                 | 1         | 1      | 0.51%   |
| MidasForce          | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| LITEON              | 1         | 1      | 0.51%   |
| Kingmax             | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 181       | 204    | 48.92%  |
| HDD  | 126       | 141    | 34.05%  |
| NVMe | 63        | 72     | 17.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 284       | 345    | 81.84%  |
| NVMe | 63        | 72     | 18.16%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 248       | 286    | 82.94%  |
| 0.51-1.0   | 46        | 54     | 15.38%  |
| 2.01-3.0   | 2         | 2      | 0.67%   |
| 1.01-2.0   | 2         | 2      | 0.67%   |
| 3.01-4.0   | 1         | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 167       | 46.52%  |
| 101-250        | 67        | 18.66%  |
| 251-500        | 50        | 13.93%  |
| 51-100         | 49        | 13.65%  |
| 501-1000       | 13        | 3.62%   |
| 21-50          | 11        | 3.06%   |
| More than 3000 | 1         | 0.28%   |
| Unknown        | 1         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 353       | 98.88%  |
| 101-250 | 2         | 0.56%   |
| 21-50   | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 4         | 4      | 5.26%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 2      | 2.63%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 2      | 2.63%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 2.63%   |
| Toshiba MK3261GSY 320GB              | 2         | 2      | 2.63%   |
| SK hynix SC210 mSATA 256GB           | 2         | 2      | 2.63%   |
| Seagate ST9160827AS 160GB            | 2         | 2      | 2.63%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 2      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2      | 2.63%   |
| Kingston SV300S37A60G 64GB           | 2         | 2      | 2.63%   |
| Hitachi HTS542525K9A300 250GB        | 2         | 2      | 2.63%   |
| HGST HTS725050A7E630 500GB           | 2         | 2      | 2.63%   |
| HGST HTS541010A9E680 1TB             | 2         | 3      | 2.63%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 1         | 1      | 1.32%   |
| WDC WD30PURZ-85AKKY0 3TB             | 1         | 1      | 1.32%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 1      | 1.32%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 1      | 1.32%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD032 320GB             | 1         | 1      | 1.32%   |
| Toshiba MK5065GSX 500GB              | 1         | 1      | 1.32%   |
| Toshiba MK5059GSXP 500GB             | 1         | 1      | 1.32%   |
| Toshiba MK1655GSX 160GB              | 1         | 1      | 1.32%   |
| Toshiba MK1646GSX 160GB              | 1         | 1      | 1.32%   |
| Toshiba MK1229GSG 120GB              | 1         | 1      | 1.32%   |
| SSSTC CVB-8D128-HP 128GB             | 1         | 1      | 1.32%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.32%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 1.32%   |
| Seagate ST9250410AS 250GB            | 1         | 1      | 1.32%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 1.32%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 1      | 1.32%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 1      | 1.32%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB   | 1         | 1      | 1.32%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 1.32%   |
| Seagate ST320LT012-9WS14C 320GB      | 1         | 2      | 1.32%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1         | 1      | 1.32%   |
| Samsung Electronics HM321HI 320GB    | 1         | 1      | 1.32%   |
| Samsung Electronics HM160HI 160GB    | 1         | 1      | 1.32%   |
| OCZ AGILITY3 120GB                   | 1         | 1      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 20     | 25%     |
| Toshiba             | 12        | 12     | 15.79%  |
| Hitachi             | 12        | 12     | 15.79%  |
| WDC                 | 9         | 9      | 11.84%  |
| HGST                | 6         | 7      | 7.89%   |
| Crucial             | 4         | 5      | 5.26%   |
| SK hynix            | 3         | 3      | 3.95%   |
| Kingston            | 3         | 3      | 3.95%   |
| Samsung Electronics | 2         | 2      | 2.63%   |
| Micron Technology   | 2         | 2      | 2.63%   |
| SSSTC               | 1         | 1      | 1.32%   |
| OCZ                 | 1         | 1      | 1.32%   |
| Intel               | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 20     | 32.76%  |
| Toshiba             | 12        | 12     | 20.69%  |
| Hitachi             | 12        | 12     | 20.69%  |
| WDC                 | 7         | 7      | 12.07%  |
| HGST                | 6         | 7      | 10.34%  |
| Samsung Electronics | 2         | 2      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 60     | 75.68%  |
| SSD  | 17        | 18     | 22.97%  |
| NVMe | 1         | 1      | 1.35%   |

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
| Works   | 274       | 337    | 78.51%  |
| Malfunc | 74        | 79     | 21.2%   |
| Failed  | 1         | 1      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 290       | 74.94%  |
| AMD                                     | 24        | 6.2%    |
| Samsung Electronics                     | 23        | 5.94%   |
| SanDisk                                 | 13        | 3.36%   |
| SK hynix                                | 9         | 2.33%   |
| Nvidia                                  | 8         | 2.07%   |
| Silicon Motion                          | 4         | 1.03%   |
| Phison Electronics                      | 3         | 0.78%   |
| KIOXIA                                  | 3         | 0.78%   |
| Micron Technology                       | 2         | 0.52%   |
| Toshiba                                 | 1         | 0.26%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.26%   |
| Shenzhen Unionmemory Information System | 1         | 0.26%   |
| Realtek Semiconductor                   | 1         | 0.26%   |
| Micron/Crucial Technology               | 1         | 0.26%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.26%   |
| Kingston Technology Company             | 1         | 0.26%   |
| ADATA Technology                        | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 42        | 10.07%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 35        | 8.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 30        | 7.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 23        | 5.52%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 21        | 5.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 18        | 4.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 16        | 3.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 14        | 3.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 12        | 2.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 12        | 2.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 11        | 2.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 10        | 2.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 10        | 2.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 9         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 9         | 2.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 8         | 1.92%   |
| Nvidia MCP79 AHCI Controller                                                           | 6         | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 5         | 1.2%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 4         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 4         | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 4         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 0.96%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 0.72%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 3         | 0.72%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 3         | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 3         | 0.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 3         | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.72%   |
| SK hynix BC511 NVMe SSD                                                                | 2         | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.48%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                           | 2         | 0.48%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                  | 2         | 0.48%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                  | 2         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 286       | 71.14%  |
| NVMe | 62        | 15.42%  |
| IDE  | 30        | 7.46%   |
| RAID | 24        | 5.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 321       | 89.92%  |
| AMD    | 36        | 10.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 10        | 2.8%    |
| Intel CPU Version                           | 7         | 1.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 1.96%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 6         | 1.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 1.68%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 6         | 1.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 1.4%    |
| Intel Core i5-2540M CPU @ 2.60GHz           | 5         | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 1.4%    |
| Intel Core i5-7300U CPU @ 2.60GHz           | 4         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 4         | 1.12%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 4         | 1.12%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 1.12%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 1.12%   |
| Intel Atom CPU N450 @ 1.66GHz               | 4         | 1.12%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 3         | 0.84%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 3         | 0.84%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 0.84%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 0.84%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GH            | 3         | 0.84%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 0.84%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.84%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 0.84%   |
| Intel Core 2 Duo                            | 3         | 0.84%   |
| Intel Core 2 CPU                            | 3         | 0.84%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 0.84%   |
| Intel Atom CPU N570 @ 1.66GHz               | 3         | 0.84%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 3         | 0.84%   |
| AMD Ryzen 5 5600H with Radeon Graphics      | 3         | 0.84%   |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz        | 2         | 0.56%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 0.56%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 0.56%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 103       | 28.85%  |
| Intel Core i7           | 62        | 17.37%  |
| Intel Celeron           | 33        | 9.24%   |
| Intel Core 2 Duo        | 32        | 8.96%   |
| Intel Core i3           | 27        | 7.56%   |
| Other                   | 24        | 6.72%   |
| Intel Pentium           | 12        | 3.36%   |
| Intel Atom              | 10        | 2.8%    |
| AMD Ryzen 7             | 8         | 2.24%   |
| AMD Ryzen 5             | 8         | 2.24%   |
| Intel Pentium Dual-Core | 4         | 1.12%   |
| Intel Genuine           | 4         | 1.12%   |
| AMD Athlon              | 4         | 1.12%   |
| Intel Core 2            | 3         | 0.84%   |
| Intel Xeon              | 2         | 0.56%   |
| Intel Pentium Dual      | 2         | 0.56%   |
| AMD Ryzen 3             | 2         | 0.56%   |
| AMD E1                  | 2         | 0.56%   |
| AMD E                   | 2         | 0.56%   |
| AMD A6                  | 2         | 0.56%   |
| Intel Pentium Silver    | 1         | 0.28%   |
| Intel Pentium Gold      | 1         | 0.28%   |
| Intel Core              | 1         | 0.28%   |
| Intel Celeron Dual-Core | 1         | 0.28%   |
| Intel Celeron D         | 1         | 0.28%   |
| AMD Ryzen Embedded      | 1         | 0.28%   |
| AMD Phenom II           | 1         | 0.28%   |
| AMD E2                  | 1         | 0.28%   |
| AMD A8                  | 1         | 0.28%   |
| AMD A4                  | 1         | 0.28%   |
| AMD A10                 | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 213       | 59.66%  |
| 4       | 74        | 20.73%  |
| Unknown | 37        | 10.36%  |
| 1       | 8         | 2.24%   |
| 12      | 7         | 1.96%   |
| 8       | 7         | 1.96%   |
| 16      | 6         | 1.68%   |
| 6       | 4         | 1.12%   |
| 11      | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 346       | 96.92%  |
| 2       | 10        | 2.8%    |
| Unknown | 1         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 221       | 61.9%   |
| 1       | 96        | 26.89%  |
| Unknown | 40        | 11.2%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 43        | 12.04%  |
| SandyBridge   | 39        | 10.92%  |
| IvyBridge     | 39        | 10.92%  |
| Penryn        | 31        | 8.68%   |
| Haswell       | 29        | 8.12%   |
| Skylake       | 26        | 7.28%   |
| Westmere      | 21        | 5.88%   |
| Core          | 20        | 5.6%    |
| Silvermont    | 19        | 5.32%   |
| Broadwell     | 15        | 4.2%    |
| Bonnell       | 12        | 3.36%   |
| Unknown       | 11        | 3.08%   |
| TigerLake     | 10        | 2.8%    |
| Zen+          | 7         | 1.96%   |
| Zen 3         | 7         | 1.96%   |
| Goldmont plus | 6         | 1.68%   |
| Bobcat        | 5         | 1.4%    |
| Zen 2         | 4         | 1.12%   |
| Excavator     | 3         | 0.84%   |
| Zen           | 2         | 0.56%   |
| Piledriver    | 2         | 0.56%   |
| Goldmont      | 2         | 0.56%   |
| Nehalem       | 1         | 0.28%   |
| K10 Llano     | 1         | 0.28%   |
| K10           | 1         | 0.28%   |
| CometLake     | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 293       | 69.43%  |
| Nvidia                           | 74        | 17.54%  |
| AMD                              | 54        | 12.8%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 8.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 8.47%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 19        | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 4.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 4.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 3.89%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 15        | 3.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 3.2%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 13        | 2.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 2.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 2.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 11        | 2.52%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 10        | 2.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.92%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 0.92%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.69%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 3         | 0.69%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 3         | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.69%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.69%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 3         | 0.69%   |
| AMD Lucienne                                                                             | 3         | 0.69%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.46%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.46%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.46%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.46%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 2         | 0.46%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.46%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.46%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 2         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 192       | 53.78%  |
| Intel + Nvidia         | 49        | 13.73%  |
| 2 x Intel              | 40        | 11.2%   |
| 1 x AMD                | 39        | 10.92%  |
| 1 x Nvidia             | 19        | 5.32%   |
| Intel + AMD            | 10        | 2.8%    |
| AMD + Nvidia           | 4         | 1.12%   |
| 2 x Nvidia             | 1         | 0.28%   |
| 2 x Intel + 1 x Nvidia | 1         | 0.28%   |
| 2 x AMD                | 1         | 0.28%   |
| 1 x SiS                | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 324       | 90.76%  |
| Unknown     | 17        | 4.76%   |
| Proprietary | 16        | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 324       | 90.76%  |
| 0.01-0.5   | 19        | 5.32%   |
| 0.51-1.0   | 7         | 1.96%   |
| 1.01-2.0   | 6         | 1.68%   |
| 7.01-8.0   | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 52        | 22.51%  |
| LG Display              | 45        | 19.48%  |
| Chimei Innolux          | 31        | 13.42%  |
| Samsung Electronics     | 24        | 10.39%  |
| BOE                     | 24        | 10.39%  |
| Lenovo                  | 11        | 4.76%   |
| Apple                   | 9         | 3.9%    |
| Chi Mei Optoelectronics | 7         | 3.03%   |
| InfoVision              | 5         | 2.16%   |
| Sharp                   | 2         | 0.87%   |
| LG Philips              | 2         | 0.87%   |
| Goldstar                | 2         | 0.87%   |
| AOC                     | 2         | 0.87%   |
| Acer                    | 2         | 0.87%   |
| Quanta Display          | 1         | 0.43%   |
| PANDA                   | 1         | 0.43%   |
| Nvidia                  | 1         | 0.43%   |
| MTD                     | 1         | 0.43%   |
| InnoLux Display         | 1         | 0.43%   |
| IBM                     | 1         | 0.43%   |
| HRN                     | 1         | 0.43%   |
| HKC                     | 1         | 0.43%   |
| Hewlett-Packard         | 1         | 0.43%   |
| HannStar                | 1         | 0.43%   |
| Daewoo                  | 1         | 0.43%   |
| CPT                     | 1         | 0.43%   |
| Unknown                 | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 7         | 3.03%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 3         | 1.3%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 3         | 1.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 3         | 1.3%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 380x210mm 17.1-inch    | 2         | 0.87%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 2         | 0.87%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 2         | 0.87%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch                 | 2         | 0.87%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 310x170mm 13.9-inch          | 2         | 0.87%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 2         | 0.87%   |
| BOE LCD Monitor BOE06B3 1366x768 310x170mm 13.9-inch                     | 2         | 0.87%   |
| BOE LCD Monitor BOE0696 1366x768 310x170mm 13.9-inch                     | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 340x190mm 15.3-inch            | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO723C 1366x768 310x170mm 13.9-inch            | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch            | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 310x170mm 13.9-inch            | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch            | 2         | 0.87%   |
| Apple Color LCD APP9CF2 1366x768 260x140mm 11.6-inch                     | 2         | 0.87%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.43%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch      | 1         | 0.43%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch      | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 340x190mm 15.3-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 310x170mm 13.9-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch    | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC3452 1366x768 340x190mm 15.3-inch     | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 103       | 45.18%  |
| 1920x1080 (FHD)  | 78        | 34.21%  |
| 1280x800 (WXGA)  | 16        | 7.02%   |
| 1600x900 (HD+)   | 12        | 5.26%   |
| 1024x600         | 7         | 3.07%   |
| 2560x1600        | 2         | 0.88%   |
| 1400x1050        | 2         | 0.88%   |
| 3840x2160 (4K)   | 1         | 0.44%   |
| 3200x1800 (QHD+) | 1         | 0.44%   |
| 2560x1440 (QHD)  | 1         | 0.44%   |
| 2256x1504        | 1         | 0.44%   |
| 2240x1400        | 1         | 0.44%   |
| 1600x1200        | 1         | 0.44%   |
| 1280x1024 (SXGA) | 1         | 0.44%   |
| 1024x768 (XGA)   | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 81        | 35.06%  |
| 13      | 71        | 30.74%  |
| 12      | 20        | 8.66%   |
| 17      | 16        | 6.93%   |
| 14      | 11        | 4.76%   |
| 11      | 10        | 4.33%   |
| 21      | 5         | 2.16%   |
| 10      | 4         | 1.73%   |
| 27      | 3         | 1.3%    |
| 9       | 3         | 1.3%    |
| 16      | 2         | 0.87%   |
| 42      | 1         | 0.43%   |
| 31      | 1         | 0.43%   |
| 23      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 136       | 58.87%  |
| 201-300     | 64        | 27.71%  |
| 351-400     | 18        | 7.79%   |
| 401-500     | 6         | 2.6%    |
| 501-600     | 4         | 1.73%   |
| 601-700     | 1         | 0.43%   |
| 901-1000    | 1         | 0.43%   |
| Unknown     | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 197       | 87.56%  |
| 16/10   | 21        | 9.33%   |
| 4/3     | 4         | 1.78%   |
| 3/2     | 2         | 0.89%   |
| Unknown | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 67        | 29%     |
| 91-100         | 67        | 29%     |
| 61-70          | 20        | 8.66%   |
| 101-110        | 17        | 7.36%   |
| 121-130        | 15        | 6.49%   |
| 71-80          | 11        | 4.76%   |
| 51-60          | 10        | 4.33%   |
| 41-50          | 7         | 3.03%   |
| 201-250        | 5         | 2.16%   |
| 301-350        | 3         | 1.3%    |
| 111-120        | 3         | 1.3%    |
| 151-200        | 2         | 0.87%   |
| 351-500        | 1         | 0.43%   |
| 131-140        | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |
| Unknown        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 106       | 45.89%  |
| 101-120       | 93        | 40.26%  |
| 51-100        | 22        | 9.52%   |
| 161-240       | 7         | 3.03%   |
| More than 240 | 2         | 0.87%   |
| Unknown       | 1         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 318       | 89.08%  |
| 0     | 27        | 7.56%   |
| 2     | 12        | 3.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 193       | 33.51%  |
| Realtek Semiconductor             | 159       | 27.6%   |
| Qualcomm Atheros                  | 92        | 15.97%  |
| Broadcom                          | 45        | 7.81%   |
| Marvell Technology Group          | 11        | 1.91%   |
| Xiaomi                            | 10        | 1.74%   |
| Samsung Electronics               | 7         | 1.22%   |
| Nvidia                            | 7         | 1.22%   |
| Sierra Wireless                   | 6         | 1.04%   |
| MediaTek                          | 6         | 1.04%   |
| JMicron Technology                | 5         | 0.87%   |
| Ericsson Business Mobile Networks | 5         | 0.87%   |
| TP-Link                           | 3         | 0.52%   |
| Ralink Technology                 | 3         | 0.52%   |
| Ralink                            | 3         | 0.52%   |
| OPPO Electronics                  | 3         | 0.52%   |
| Dell                              | 3         | 0.52%   |
| Qualcomm                          | 2         | 0.35%   |
| ASUSTek Computer                  | 2         | 0.35%   |
| T & A Mobile Phones               | 1         | 0.17%   |
| Spreadtrum Communications         | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.17%   |
| Qualcomm Technologies             | 1         | 0.17%   |
| Motorola PCS                      | 1         | 0.17%   |
| ICS Advent                        | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Google                            | 1         | 0.17%   |
| Edimax Technology                 | 1         | 0.17%   |
| D-Link                            | 1         | 0.17%   |
| BUFFALO                           | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 91        | 12.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 40        | 5.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 31        | 4.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 3.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 3.08%   |
| Intel Wireless 8260                                                     | 16        | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 14        | 1.96%   |
| Intel Wireless 7265                                                     | 13        | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 1.82%   |
| Intel Wireless 7260                                                     | 12        | 1.68%   |
| Intel Ethernet Connection I219-LM                                       | 11        | 1.54%   |
| Intel Wireless 3165                                                     | 10        | 1.4%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.12%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 7         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 7         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                                | 7         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.84%   |
| Nvidia MCP79 Ethernet                                                   | 6         | 0.84%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                   | 6         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.84%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.84%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 5         | 0.7%    |
| Intel Wireless 3160                                                     | 5         | 0.7%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.7%    |
| Intel Ethernet Connection I218-LM                                       | 5         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 178       | 47.85%  |
| Qualcomm Atheros      | 79        | 21.24%  |
| Realtek Semiconductor | 52        | 13.98%  |
| Broadcom              | 38        | 10.22%  |
| MediaTek              | 4         | 1.08%   |
| TP-Link               | 3         | 0.81%   |
| Sierra Wireless       | 3         | 0.81%   |
| Ralink Technology     | 3         | 0.81%   |
| Ralink                | 3         | 0.81%   |
| Dell                  | 3         | 0.81%   |
| ASUSTek Computer      | 2         | 0.54%   |
| Qualcomm Technologies | 1         | 0.27%   |
| Edimax Technology     | 1         | 0.27%   |
| D-Link                | 1         | 0.27%   |
| BUFFALO               | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 6.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 5.87%   |
| Intel Wireless 8260                                                     | 16        | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 3.73%   |
| Intel Wireless 8265 / 8275                                              | 14        | 3.73%   |
| Intel Wireless 7265                                                     | 13        | 3.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 3.47%   |
| Intel Wireless 7260                                                     | 12        | 3.2%    |
| Intel Wireless 3165                                                     | 10        | 2.67%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.6%    |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.6%    |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.6%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.33%   |
| Intel Wireless 3160                                                     | 5         | 1.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.33%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 5         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.07%   |
| Intel WiFi Link 5100                                                    | 4         | 1.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.07%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.07%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.07%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.8%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 3         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 132       | 40.37%  |
| Intel                            | 106       | 32.42%  |
| Qualcomm Atheros                 | 25        | 7.65%   |
| Broadcom                         | 12        | 3.67%   |
| Marvell Technology Group         | 11        | 3.36%   |
| Xiaomi                           | 10        | 3.06%   |
| Samsung Electronics              | 7         | 2.14%   |
| Nvidia                           | 7         | 2.14%   |
| JMicron Technology               | 5         | 1.53%   |
| OPPO Electronics                 | 3         | 0.92%   |
| Qualcomm                         | 2         | 0.61%   |
| MediaTek                         | 2         | 0.61%   |
| T & A Mobile Phones              | 1         | 0.31%   |
| Spreadtrum Communications        | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Motorola PCS                     | 1         | 0.31%   |
| ICS Advent                       | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 91        | 27.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 12.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 31        | 9.48%   |
| Intel Ethernet Connection I219-LM                                      | 11        | 3.36%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 2.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 2.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 2.14%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 2.14%   |
| Intel 82577LM Gigabit Network Connection                               | 7         | 2.14%   |
| Intel 82567LM Gigabit Network Connection                               | 7         | 2.14%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 1.83%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 1.83%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 1.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 5         | 1.53%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 1.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 4         | 1.22%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.92%   |
| Intel 82573L Gigabit Ethernet Controller                               | 3         | 0.92%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.61%   |
| OPPO OPPO Find X3 Neo 5G RNDIS Control RNDIS Ethernet Data             | 2         | 0.61%   |
| MediaTek USB Ethernet-RNDIS                                            | 2         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.61%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.61%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                            | 1         | 0.31%   |
| Spreadtrum Android USB Ethernet RNDIS Gadget                           | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.31%   |
| Qualcomm FP3                                                           | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 348       | 51.56%  |
| Ethernet | 314       | 46.52%  |
| Unknown  | 10        | 1.48%   |
| Modem    | 3         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 177       | 56.73%  |
| Ethernet | 135       | 43.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 289       | 80.95%  |
| 1     | 62        | 17.37%  |
| 0     | 5         | 1.4%    |
| 3     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 336       | 93.85%  |
| Yes  | 22        | 6.15%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 117       | 44.66%  |
| Broadcom                        | 28        | 10.69%  |
| Realtek Semiconductor           | 23        | 8.78%   |
| Qualcomm Atheros Communications | 23        | 8.78%   |
| Apple                           | 16        | 6.11%   |
| Foxconn / Hon Hai               | 14        | 5.34%   |
| IMC Networks                    | 11        | 4.2%    |
| Dell                            | 6         | 2.29%   |
| Lite-On Technology              | 5         | 1.91%   |
| Hewlett-Packard                 | 5         | 1.91%   |
| ASUSTek Computer                | 4         | 1.53%   |
| Cambridge Silicon Radio         | 3         | 1.15%   |
| Toshiba                         | 2         | 0.76%   |
| Askey Computer                  | 2         | 0.76%   |
| TP-Link                         | 1         | 0.38%   |
| MediaTek                        | 1         | 0.38%   |
| Alps Electric                   | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 73        | 27.76%  |
| Intel AX201 Bluetooth                                    | 14        | 5.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 10        | 3.8%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 9         | 3.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 9         | 3.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8         | 3.04%   |
| Realtek Bluetooth Adapter                                | 7         | 2.66%   |
| Intel AX200 Bluetooth                                    | 6         | 2.28%   |
| Apple Bluetooth Host Controller                          | 6         | 2.28%   |
| Realtek Bluetooth 4.2 Adapter                            | 5         | 1.9%    |
| Broadcom BCM2045B (BDC-2.1)                              | 5         | 1.9%    |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 4         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                         | 4         | 1.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 4         | 1.52%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 4         | 1.52%   |
| Apple Built-in iSight (no firmware loaded)               | 4         | 1.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 4         | 1.52%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 3         | 1.14%   |
| Dell DW375 Bluetooth Module                              | 3         | 1.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 3         | 1.14%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 3         | 1.14%   |
| ASUS BT-270 Bluetooth Adapter                            | 3         | 1.14%   |
| Apple Broadcom Built-in Bluetooth                        | 3         | 1.14%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip          | 2         | 0.76%   |
| Realtek Wireless Bluetooth Adapter                       | 2         | 0.76%   |
| Realtek RTL8821A Bluetooth                               | 2         | 0.76%   |
| Realtek Bluetooth 4.0 Adapter                            | 2         | 0.76%   |
| Realtek Bluetooth 4.0 + High Speed Chip                  | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 2         | 0.76%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 2         | 0.76%   |
| IMC Networks Bluetooth module                            | 2         | 0.76%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 2         | 0.76%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter             | 2         | 0.76%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 2         | 0.76%   |
| Foxconn / Hon Hai Bluetooth USB Module                   | 2         | 0.76%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 2         | 0.76%   |
| Askey BlueSoleil Generic Bluetooth Device                | 2         | 0.76%   |
| TP-Link Bluetooth 5.0 USB Adapter                        | 1         | 0.38%   |
| Realtek RTL8723B Bluetooth                               | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 313       | 80.46%  |
| AMD                               | 43        | 11.05%  |
| Nvidia                            | 23        | 5.91%   |
| Realtek Semiconductor             | 2         | 0.51%   |
| Texas Instruments                 | 1         | 0.26%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.26%   |
| Phison Electronics                | 1         | 0.26%   |
| Hewlett-Packard                   | 1         | 0.26%   |
| Generalplus Technology            | 1         | 0.26%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.26%   |
| Conexant Systems                  | 1         | 0.26%   |
| Apogee Electronics                | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 44        | 9.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 44        | 9.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 35        | 7.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 25        | 5.4%    |
| AMD Ryzen HD Audio Controller                                                                     | 24        | 5.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 4.75%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 3.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 3.67%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 3.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 3.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 3.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 3.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 3.02%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 12        | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.94%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.51%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.65%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.65%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 118       | 28.37%  |
| SK hynix            | 76        | 18.27%  |
| Micron Technology   | 45        | 10.82%  |
| Unknown             | 38        | 9.13%   |
| Kingston            | 26        | 6.25%   |
| Crucial             | 14        | 3.37%   |
| Unknown             | 14        | 3.37%   |
| Elpida              | 12        | 2.88%   |
| Nanya Technology    | 10        | 2.4%    |
| Ramaxel Technology  | 8         | 1.92%   |
| A-DATA Technology   | 8         | 1.92%   |
| Corsair             | 6         | 1.44%   |
| Unknown (ABCD)      | 5         | 1.2%    |
| Smart               | 5         | 1.2%    |
| Transcend           | 4         | 0.96%   |
| SHARETRONIC         | 3         | 0.72%   |
| ASint Technology    | 3         | 0.72%   |
| Team                | 2         | 0.48%   |
| Multilaser          | 2         | 0.48%   |
| Teikon              | 1         | 0.24%   |
| Swissbit            | 1         | 0.24%   |
| Smart Brazil        | 1         | 0.24%   |
| Silicon Power       | 1         | 0.24%   |
| SemsoTai            | 1         | 0.24%   |
| Qimonda             | 1         | 0.24%   |
| PUSKILL             | 1         | 0.24%   |
| Patriot             | 1         | 0.24%   |
| Neo Forza           | 1         | 0.24%   |
| Lenovo              | 1         | 0.24%   |
| Kllisre             | 1         | 0.24%   |
| High Bridge         | 1         | 0.24%   |
| GOODRAM             | 1         | 0.24%   |
| G.Skill             | 1         | 0.24%   |
| Avant               | 1         | 0.24%   |
| Apacer              | 1         | 0.24%   |
| 48spaces            | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 14        | 3.19%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 8         | 1.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.59%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 1.37%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 6         | 1.37%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 5         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 5         | 1.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 1.14%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.91%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.91%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.91%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 0.91%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 4         | 0.91%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.91%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 3         | 0.68%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.68%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.68%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.68%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.68%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 2         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 2         | 0.46%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 2         | 0.46%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 2         | 0.46%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 186       | 53.3%   |
| DDR4    | 100       | 28.65%  |
| DDR2    | 38        | 10.89%  |
| Unknown | 10        | 2.87%   |
| LPDDR4  | 6         | 1.72%   |
| SDRAM   | 3         | 0.86%   |
| LPDDR3  | 3         | 0.86%   |
| LPDDR5  | 1         | 0.29%   |
| DDR5    | 1         | 0.29%   |
| DDR     | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 330       | 94.29%  |
| Row Of Chips | 10        | 2.86%   |
| Chip         | 4         | 1.14%   |
| Unknown      | 4         | 1.14%   |
| DIMM         | 2         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 131       | 33.76%  |
| 8192  | 120       | 30.93%  |
| 2048  | 88        | 22.68%  |
| 16384 | 23        | 5.93%   |
| 1024  | 22        | 5.67%   |
| 32768 | 4         | 1.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 121       | 32.53%  |
| 3200    | 39        | 10.48%  |
| 2400    | 39        | 10.48%  |
| 667     | 29        | 7.8%    |
| 1333    | 27        | 7.26%   |
| 2667    | 25        | 6.72%   |
| 1334    | 21        | 5.65%   |
| 1067    | 18        | 4.84%   |
| 2133    | 12        | 3.23%   |
| 800     | 12        | 3.23%   |
| Unknown | 12        | 3.23%   |
| 1867    | 5         | 1.34%   |
| 1066    | 5         | 1.34%   |
| 2048    | 2         | 0.54%   |
| 6400    | 1         | 0.27%   |
| 5600    | 1         | 0.27%   |
| 3733    | 1         | 0.27%   |
| 975     | 1         | 0.27%   |
| 533     | 1         | 0.27%   |

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
| Chicony Electronics                    | 71        | 27%     |
| Bison Electronics                      | 31        | 11.79%  |
| Microdia                               | 20        | 7.6%    |
| IMC Networks                           | 17        | 6.46%   |
| Sunplus Innovation Technology          | 16        | 6.08%   |
| Realtek Semiconductor                  | 15        | 5.7%    |
| Syntek                                 | 10        | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.8%    |
| Suyin                                  | 8         | 3.04%   |
| Silicon Motion                         | 8         | 3.04%   |
| Quanta                                 | 8         | 3.04%   |
| Lite-On Technology                     | 7         | 2.66%   |
| Apple                                  | 7         | 2.66%   |
| Alcor Micro                            | 6         | 2.28%   |
| ALi                                    | 5         | 1.9%    |
| Lenovo                                 | 4         | 1.52%   |
| Z-Star Microelectronics                | 3         | 1.14%   |
| Luxvisions Innotech Limited            | 3         | 1.14%   |
| Jiangxi Shinetech Optical              | 3         | 1.14%   |
| Y Media                                | 2         | 0.76%   |
| Supreme Electronics                    | 2         | 0.76%   |
| Ricoh                                  | 1         | 0.38%   |
| OmniVision Technologies                | 1         | 0.38%   |
| Intel                                  | 1         | 0.38%   |
| Importek                               | 1         | 0.38%   |
| DigiTech                               | 1         | 0.38%   |
| Cubeternet                             | 1         | 0.38%   |
| Unknown                                | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 22        | 8.33%   |
| Microdia Integrated_Webcam_HD                               | 10        | 3.79%   |
| Bison Integrated Camera                                     | 9         | 3.41%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 8         | 3.03%   |
| Sunplus Integrated_Webcam_HD                                | 6         | 2.27%   |
| Bison ThinkPad Integrated Camera                            | 5         | 1.89%   |
| Bison Lenovo EasyCamera                                     | 5         | 1.89%   |
| Syntek Lenovo EasyCamera                                    | 4         | 1.52%   |
| Realtek Integrated_Webcam_HD                                | 4         | 1.52%   |
| Microdia Integrated Webcam                                  | 4         | 1.52%   |
| Lite-On Integrated Camera                                   | 4         | 1.52%   |
| IMC Networks Integrated Webcam                              | 4         | 1.52%   |
| IMC Networks EasyCamera                                     | 4         | 1.52%   |
| Chicony Lenovo EasyCamera                                   | 4         | 1.52%   |
| Chicony FJ Camera                                           | 4         | 1.52%   |
| ALi WebCam                                                  | 4         | 1.52%   |
| Syntek Integrated Camera                                    | 3         | 1.14%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.14%   |
| Realtek USB Camera                                          | 3         | 1.14%   |
| Lenovo Integrated Webcam                                    | 3         | 1.14%   |
| IMC Networks UVC VGA Webcam                                 | 3         | 1.14%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.14%   |
| Chicony USB 2.0 Camera                                      | 3         | 1.14%   |
| Chicony HP HD Camera                                        | 3         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 3         | 1.14%   |
| Apple FaceTime HD Camera                                    | 3         | 1.14%   |
| Y Media USB Camera                                          | 2         | 0.76%   |
| Syntek EasyCamera                                           | 2         | 0.76%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.76%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 0.76%   |
| Sunplus HP HD Webcam [Fixed]                                | 2         | 0.76%   |
| Silicon Motion LG HD WebCam                                 | 2         | 0.76%   |
| Realtek USB2.0 VGA UVC WebCam                               | 2         | 0.76%   |
| Quanta HP TrueVision HD Camera                              | 2         | 0.76%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 0.76%   |
| Lite-On HP Universal Camera                                 | 2         | 0.76%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 0.76%   |
| IMC Networks Integrated Camera                              | 2         | 0.76%   |
| Chicony VGA Webcam                                          | 2         | 0.76%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 40.35%  |
| AuthenTec                  | 9         | 15.79%  |
| Upek                       | 8         | 14.04%  |
| Elan Microelectronics      | 5         | 8.77%   |
| Shenzhen Goodix Technology | 3         | 5.26%   |
| Broadcom                   | 3         | 5.26%   |
| Synaptics                  | 2         | 3.51%   |
| STMicroelectronics         | 1         | 1.75%   |
| LighTuning Technology      | 1         | 1.75%   |
| FocalTech Systems          | 1         | 1.75%   |
| Fingerprint Cards          | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 8         | 14.04%  |
| Validity Sensors VFS 5011 fingerprint sensor                                      | 7         | 12.28%  |
| Validity Sensors VFS495 Fingerprint Reader                                        | 5         | 8.77%   |
| Validity Sensors Synaptics WBDI                                                   | 4         | 7.02%   |
| Elan Fingerprint Sensor                                                           | 4         | 7.02%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 3         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor      | 3         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 2         | 3.51%   |
| AuthenTec AES2810                                                                 | 2         | 3.51%   |
| AuthenTec AES2660                                                                 | 2         | 3.51%   |
| AuthenTec AES2550 Fingerprint Sensor                                              | 2         | 3.51%   |
| AuthenTec AES2501 Fingerprint Sensor                                              | 2         | 3.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 1         | 1.75%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 1         | 1.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                         | 1         | 1.75%   |
| Validity Sensors Fingerprint scanner                                              | 1         | 1.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                                  | 1         | 1.75%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                          | 1         | 1.75%   |
| STMicroelectronics Fingerprint Reader                                             | 1         | 1.75%   |
| Shenzhen Goodix  Fingerprint Device                                               | 1         | 1.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 1         | 1.75%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 1.75%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 1.75%   |
| Elan WBF Fingerprint Sensor                                                       | 1         | 1.75%   |
| AuthenTec AES1660                                                                 | 1         | 1.75%   |

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
| 1     | 154       | 43.02%  |
| 2     | 98        | 27.37%  |
| 0     | 58        | 16.2%   |
| 3     | 44        | 12.29%  |
| 4     | 4         | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 242       | 52.38%  |
| Net/wireless             | 72        | 15.58%  |
| Fingerprint reader       | 57        | 12.34%  |
| Card reader              | 44        | 9.52%   |
| Bluetooth                | 28        | 6.06%   |
| Storage                  | 9         | 1.95%   |
| Sound                    | 6         | 1.3%    |
| Network                  | 3         | 0.65%   |
| Net/ethernet             | 1         | 0.22%   |

