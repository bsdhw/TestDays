NomadBSD - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for NomadBSD.

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

Total: 163

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| TUXEDO        | Pulse 15 Gen1               | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | [aa85ff898d](https://bsd-hardware.info/?probe=aa85ff898d) | Oct 26, 2023 |
| Acer          | Aspire E5-575G              | [f38d89e6c0](https://bsd-hardware.info/?probe=f38d89e6c0) | Oct 15, 2023 |
| ASUSTek       | K45VM                       | [054a6c3902](https://bsd-hardware.info/?probe=054a6c3902) | Oct 11, 2023 |
| ASUSTek       | 1005PXD                     | [1b05e8cf1b](https://bsd-hardware.info/?probe=1b05e8cf1b) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [e732d89b06](https://bsd-hardware.info/?probe=e732d89b06) | Sep 29, 2023 |
| Apple         | MacBookPro7,1               | [714516a696](https://bsd-hardware.info/?probe=714516a696) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | [cac0950717](https://bsd-hardware.info/?probe=cac0950717) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | [3c69dd7003](https://bsd-hardware.info/?probe=3c69dd7003) | Sep 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Dell          | XPS 13 7390                 | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| eMachines     | G640                        | [c05619033c](https://bsd-hardware.info/?probe=c05619033c) | Sep 14, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Unknown       | Unknown                     | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| Dell          | XPS 13 9360                 | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | EliteBook 750 G1            | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell          | Latitude 7300               | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer          | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel         | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Acer          | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| Lenovo        | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple         | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [995a8a5e6f](https://bsd-hardware.info/?probe=995a8a5e6f) | Jul 16, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| HP            | 255 G8 Notebook PC          | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| Dell          | Latitude 5290               | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HP            | ProBook 450 G2              | [c4f7b8a774](https://bsd-hardware.info/?probe=c4f7b8a774) | Apr 22, 2022 |
| Dell          | Studio 1555                 | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| Dell          | Latitude D630               | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| HP            | Laptop 15-db0xxx            | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| HP            | Pavilion Notebook           | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| ASUSTek       | 1000                        | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| HP            | ZBook Studio G3             | [767b44a6ae](https://bsd-hardware.info/?probe=767b44a6ae) | Oct 30, 2021 |
| ASUSTek       | X202E                       | [54259ac9a1](https://bsd-hardware.info/?probe=54259ac9a1) | Oct 29, 2021 |
| Sony          | VJS121C11N                  | [d86c621ef0](https://bsd-hardware.info/?probe=d86c621ef0) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| ASUSTek       | X540YA                      | [c5751c736c](https://bsd-hardware.info/?probe=c5751c736c) | Sep 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [d8f8901ae7](https://bsd-hardware.info/?probe=d8f8901ae7) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| HP            | Pavilion g6                 | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| HP            | 2000                        | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [39ef89f214](https://bsd-hardware.info/?probe=39ef89f214) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [4e7ace8a39](https://bsd-hardware.info/?probe=4e7ace8a39) | Aug 04, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Dell          | Inspiron 15-5568            | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| Apple         | MacBookAir6,1               | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| Acer          | Aspire E5-551               | [c9ab1cb207](https://bsd-hardware.info/?probe=c9ab1cb207) | Apr 29, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [e9155d12c7](https://bsd-hardware.info/?probe=e9155d12c7) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Apple         | MacBookPro8,1               | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| HP            | ProBook 640 G1              | [6bc6c5b2bf](https://bsd-hardware.info/?probe=6bc6c5b2bf) | Mar 31, 2021 |
| TUXEDO        | Unknown                     | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Toshiba       | Satellite C660              | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| MSI           | MS-N033                     | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Toshiba       | Satellite C660              | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| Notebook      | N650DU                      | [90d705dd1e](https://bsd-hardware.info/?probe=90d705dd1e) | Mar 14, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | [733c5edb74](https://bsd-hardware.info/?probe=733c5edb74) | Mar 08, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | [56844725d1](https://bsd-hardware.info/?probe=56844725d1) | Mar 08, 2021 |
| HP            | Laptop 15-da0xxx            | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [be2ad24d1b](https://bsd-hardware.info/?probe=be2ad24d1b) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0e06b5f17f](https://bsd-hardware.info/?probe=0e06b5f17f) | Mar 06, 2021 |
| Dell          | Latitude 5280               | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E754               | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eb7d8c3502](https://bsd-hardware.info/?probe=eb7d8c3502) | Mar 02, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| GEO           | GeoBook3                    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| Clevo         | W55xEU                      | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Pegatron      | T12Ah                       | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Clevo         | W55xEU                      | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Alienware     | M18xR1                      | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| Dell          | Latitude 3410               | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| Dell          | Latitude E4300              | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Pegatron      | T12Ah                       | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Dell          | Latitude 5400               | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ba45e27f88](https://bsd-hardware.info/?probe=ba45e27f88) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| NEC Comput... | PC-GL186Y3AZ                | [b9f8e78467](https://bsd-hardware.info/?probe=b9f8e78467) | Jan 05, 2021 |
| Dell          | Latitude 5280               | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [df9318dcea](https://bsd-hardware.info/?probe=df9318dcea) | Dec 27, 2020 |
| Dell          | Inspiron 5758               | [51ed7b02c2](https://bsd-hardware.info/?probe=51ed7b02c2) | Dec 21, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Apple         | MacBookPro11,3              | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| IBM           | 2647NG8                     | [a0f38de52f](https://bsd-hardware.info/?probe=a0f38de52f) | Nov 22, 2020 |
| HP            | ProBook 640 G1              | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Acer          | Aspire E5-432               | [39fb05c049](https://bsd-hardware.info/?probe=39fb05c049) | Nov 01, 2020 |
| Acer          | Aspire V3-575G              | [1ff0e90d9d](https://bsd-hardware.info/?probe=1ff0e90d9d) | Oct 24, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Apple         | MacBookAir7,2               | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Dell          | Precision 7530              | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Dell          | Vostro 3750                 | [587a9276bb](https://bsd-hardware.info/?probe=587a9276bb) | Sep 06, 2020 |
| Panasonic     | CF-C1BD06EFG                | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| Dell          | Inspiron 5567               | [5ef34cd40f](https://bsd-hardware.info/?probe=5ef34cd40f) | Aug 20, 2020 |
| Acer          | Aspire 5735                 | [6ca9384f34](https://bsd-hardware.info/?probe=6ca9384f34) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| HP            | ProBook 640 G1              | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| Dell          | Latitude 5480               | [907e0da9a4](https://bsd-hardware.info/?probe=907e0da9a4) | Aug 08, 2020 |
| HP            | EliteBook 820 G1            | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Google        | Lulu                        | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Unknown       | Unknown                     | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [b726c4536b](https://bsd-hardware.info/?probe=b726c4536b) | Jul 04, 2020 |
| Dell          | Latitude E7240              | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| NomadBSD 1.3.2    | 34        | 26.36%  |
| NomadBSD 5806f915 | 32        | 24.81%  |
| NomadBSD 20221130 | 27        | 20.93%  |
| NomadBSD 1.4      | 18        | 13.95%  |
| NomadBSD 1.3.1    | 7         | 5.43%   |
| NomadBSD 1.4-RC1  | 6         | 4.65%   |
| NomadBSD 20231013 | 4         | 3.1%    |
| NomadBSD 81e34fc3 | 1         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| NomadBSD | 125       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 118       | 93.65%  |
| i386  | 8         | 6.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 107       | 85.6%   |
| xinitrc | 7         | 5.6%    |
| GNOME   | 6         | 4.8%    |
| KDE5    | 4         | 3.2%    |
| XFCE    | 1         | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 125       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 93        | 74.4%   |
| SDDM | 32        | 25.6%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 41        | 32.54%  |
| Unknown | 20        | 15.87%  |
| de_DE   | 13        | 10.32%  |
| en_GB   | 12        | 9.52%   |
| ru_RU   | 7         | 5.56%   |
| fr_FR   | 6         | 4.76%   |
| zh_TW   | 5         | 3.97%   |
| zh_CN   | 3         | 2.38%   |
| it_IT   | 3         | 2.38%   |
| fi_FI   | 3         | 2.38%   |
| pl_PL   | 2         | 1.59%   |
| hu_HU   | 2         | 1.59%   |
| es_ES   | 2         | 1.59%   |
| tr_TR   | 1         | 0.79%   |
| sv_SE   | 1         | 0.79%   |
| lt_LT   | 1         | 0.79%   |
| ko_KR   | 1         | 0.79%   |
| en_AU   | 1         | 0.79%   |
| cs_CZ   | 1         | 0.79%   |
| bg_BG   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 120       | 95.24%  |
| BIOS | 6         | 4.76%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 102       | 81.6%   |
| Zfs  | 23        | 18.4%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 84        | 66.67%  |
| MBR  | 42        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 35        | 28%     |
| Dell                | 17        | 13.6%   |
| Hewlett-Packard     | 14        | 11.2%   |
| ASUSTek Computer    | 13        | 10.4%   |
| Acer                | 9         | 7.2%    |
| Apple               | 6         | 4.8%    |
| TUXEDO              | 4         | 3.2%    |
| Sony                | 3         | 2.4%    |
| Samsung Electronics | 3         | 2.4%    |
| Fujitsu             | 3         | 2.4%    |
| Notebook            | 2         | 1.6%    |
| Google              | 2         | 1.6%    |
| Fujitsu Siemens     | 2         | 1.6%    |
| Toshiba             | 1         | 0.8%    |
| Pegatron            | 1         | 0.8%    |
| Panasonic           | 1         | 0.8%    |
| NEC Computers       | 1         | 0.8%    |
| MSI                 | 1         | 0.8%    |
| IBM                 | 1         | 0.8%    |
| GEO                 | 1         | 0.8%    |
| eMachines           | 1         | 0.8%    |
| Clevo               | 1         | 0.8%    |
| Chuwi               | 1         | 0.8%    |
| Alienware           | 1         | 0.8%    |
| Unknown             | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 1.6%    |
| TUXEDO Pulse 15 Gen2                     | 1         | 0.8%    |
| TUXEDO Pulse 15 Gen1                     | 1         | 0.8%    |
| TUXEDO InfinityBook S 15 Gen6            | 1         | 0.8%    |
| Toshiba Satellite C660                   | 1         | 0.8%    |
| Sony VPCM13M1R                           | 1         | 0.8%    |
| Sony VJS121C11N                          | 1         | 0.8%    |
| Sony SVE1713S1RW                         | 1         | 0.8%    |
| Samsung N150/N210/N220                   | 1         | 0.8%    |
| Samsung N145P/N250P/N260P                | 1         | 0.8%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.8%    |
| Pegatron T12Ah                           | 1         | 0.8%    |
| Panasonic CF-C1BD06EFG                   | 1         | 0.8%    |
| Notebook W650DC,DD                       | 1         | 0.8%    |
| Notebook N650DU                          | 1         | 0.8%    |
| NEC Computers PC-GL186Y3AZ               | 1         | 0.8%    |
| MSI MS-N033                              | 1         | 0.8%    |
| Lenovo Yoga 710-11IKB 80V6               | 1         | 0.8%    |
| Lenovo V580 20147                        | 1         | 0.8%    |
| Lenovo ThinkPad X280 20KESB4T00          | 1         | 0.8%    |
| Lenovo ThinkPad X270 20HN006CUS          | 1         | 0.8%    |
| Lenovo ThinkPad X230 2325IB1             | 1         | 0.8%    |
| Lenovo ThinkPad X230 23255NG             | 1         | 0.8%    |
| Lenovo ThinkPad X230 23205UG             | 1         | 0.8%    |
| Lenovo ThinkPad X201 Tablet 311396U      | 1         | 0.8%    |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT | 1         | 0.8%    |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU | 1         | 0.8%    |
| Lenovo ThinkPad W541 20EGS04800          | 1         | 0.8%    |
| Lenovo ThinkPad W520 42844DG             | 1         | 0.8%    |
| Lenovo ThinkPad T530 24295VU             | 1         | 0.8%    |
| Lenovo ThinkPad T510 4384FF3             | 1         | 0.8%    |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 0.8%    |
| Lenovo ThinkPad T490 20RYS06R00          | 1         | 0.8%    |
| Lenovo ThinkPad T480 20L50000GE          | 1         | 0.8%    |
| Lenovo ThinkPad T470s W10DG 20JS001FGE   | 1         | 0.8%    |
| Lenovo ThinkPad T470 20HES0EV0A          | 1         | 0.8%    |
| Lenovo ThinkPad T460 20FMS78014          | 1         | 0.8%    |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 0.8%    |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 0.8%    |
| Lenovo ThinkPad T440p 20AWS0VK00         | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 27        | 21.6%   |
| Dell Latitude              | 9         | 7.2%    |
| Acer Aspire                | 8         | 6.4%    |
| HP Pavilion                | 3         | 2.4%    |
| Dell Inspiron              | 3         | 2.4%    |
| TUXEDO Pulse               | 2         | 1.6%    |
| Lenovo IdeaPad             | 2         | 1.6%    |
| HP ProBook                 | 2         | 1.6%    |
| HP Laptop                  | 2         | 1.6%    |
| HP EliteBook               | 2         | 1.6%    |
| Fujitsu Siemens AMILO      | 2         | 1.6%    |
| Fujitsu LIFEBOOK           | 2         | 1.6%    |
| Dell XPS                   | 2         | 1.6%    |
| Unknown                    | 2         | 1.6%    |
| TUXEDO InfinityBook        | 1         | 0.8%    |
| Toshiba Satellite          | 1         | 0.8%    |
| Sony VPCM13M1R             | 1         | 0.8%    |
| Sony VJS121C11N            | 1         | 0.8%    |
| Sony SVE1713S1RW           | 1         | 0.8%    |
| Samsung N150               | 1         | 0.8%    |
| Samsung N145P              | 1         | 0.8%    |
| Samsung 300E5EV            | 1         | 0.8%    |
| Pegatron T12Ah             | 1         | 0.8%    |
| Panasonic CF-C1BD06EFG     | 1         | 0.8%    |
| Notebook W650DC            | 1         | 0.8%    |
| Notebook N650DU            | 1         | 0.8%    |
| NEC Computers PC-GL186Y3AZ | 1         | 0.8%    |
| MSI MS-N033                | 1         | 0.8%    |
| Lenovo Yoga                | 1         | 0.8%    |
| Lenovo V580                | 1         | 0.8%    |
| Lenovo Legion              | 1         | 0.8%    |
| Lenovo G570                | 1         | 0.8%    |
| Lenovo G50-70              | 1         | 0.8%    |
| Lenovo G50-45              | 1         | 0.8%    |
| IBM 2647NG8                | 1         | 0.8%    |
| HP ZBook                   | 1         | 0.8%    |
| HP OMEN                    | 1         | 0.8%    |
| HP Notebook                | 1         | 0.8%    |
| HP 255                     | 1         | 0.8%    |
| HP 2000                    | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 17        | 13.6%   |
| 2020 | 12        | 9.6%    |
| 2017 | 10        | 8%      |
| 2012 | 10        | 8%      |
| 2014 | 8         | 6.4%    |
| 2011 | 8         | 6.4%    |
| 2021 | 7         | 5.6%    |
| 2018 | 7         | 5.6%    |
| 2015 | 7         | 5.6%    |
| 2010 | 7         | 5.6%    |
| 2013 | 6         | 4.8%    |
| 2008 | 6         | 4.8%    |
| 2022 | 5         | 4%      |
| 2016 | 5         | 4%      |
| 2009 | 4         | 3.2%    |
| 2023 | 3         | 2.4%    |
| 2006 | 2         | 1.6%    |
| 2004 | 1         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 125       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 122       | 97.6%   |
| Yes  | 3         | 2.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 53        | 42.06%  |
| 4.01-8.0    | 26        | 20.63%  |
| 16.01-24.0  | 25        | 19.84%  |
| 32.01-64.0  | 6         | 4.76%   |
| 2.01-3.0    | 6         | 4.76%   |
| 64.01-256.0 | 3         | 2.38%   |
| 0.51-1.0    | 3         | 2.38%   |
| 3.01-4.0    | 2         | 1.59%   |
| 24.01-32.0  | 2         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 68        | 53.13%  |
| 0.51-1.0  | 38        | 29.69%  |
| 1.01-2.0  | 12        | 9.38%   |
| 2.01-3.0  | 5         | 3.91%   |
| 4.01-8.0  | 3         | 2.34%   |
| 3.01-4.0  | 1         | 0.78%   |
| 8.01-16.0 | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 95        | 76%     |
| 2      | 19        | 15.2%   |
| 0      | 9         | 7.2%    |
| 3      | 2         | 1.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 63.49%  |
| Yes       | 46        | 36.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 86.51%  |
| No        | 17        | 13.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 99.2%   |
| No        | 1         | 0.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 72%     |
| No        | 35        | 28%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 17        | 13.6%   |
| USA         | 16        | 12.8%   |
| France      | 15        | 12%     |
| Russia      | 14        | 11.2%   |
| UK          | 12        | 9.6%    |
| Taiwan      | 5         | 4%      |
| Italy       | 5         | 4%      |
| Norway      | 3         | 2.4%    |
| Mexico      | 3         | 2.4%    |
| Finland     | 3         | 2.4%    |
| China       | 3         | 2.4%    |
| Turkey      | 2         | 1.6%    |
| Spain       | 2         | 1.6%    |
| Romania     | 2         | 1.6%    |
| Poland      | 2         | 1.6%    |
| Japan       | 2         | 1.6%    |
| Hungary     | 2         | 1.6%    |
| Colombia    | 2         | 1.6%    |
| Australia   | 2         | 1.6%    |
| Ukraine     | 1         | 0.8%    |
| Sweden      | 1         | 0.8%    |
| South Korea | 1         | 0.8%    |
| San Marino  | 1         | 0.8%    |
| Philippines | 1         | 0.8%    |
| Lithuania   | 1         | 0.8%    |
| Hong Kong   | 1         | 0.8%    |
| Egypt       | 1         | 0.8%    |
| Denmark     | 1         | 0.8%    |
| Czechia     | 1         | 0.8%    |
| Bulgaria    | 1         | 0.8%    |
| Belarus     | 1         | 0.8%    |
| Argentina   | 1         | 0.8%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Moscow                | 10        | 7.87%   |
| Franconville          | 6         | 4.72%   |
| Whittier              | 3         | 2.36%   |
| Tijuana               | 3         | 2.36%   |
| Taichung              | 3         | 2.36%   |
| Markt Indersdorf      | 3         | 2.36%   |
| Zwingenberg           | 2         | 1.57%   |
| Vollen                | 2         | 1.57%   |
| Turku                 | 2         | 1.57%   |
| Taipei                | 2         | 1.57%   |
| Setagaya-ku           | 2         | 1.57%   |
| Rome                  | 2         | 1.57%   |
| New Braunfels         | 2         | 1.57%   |
| Melun                 | 2         | 1.57%   |
| Los Angeles           | 2         | 1.57%   |
| Istanbul              | 2         | 1.57%   |
| Hodmezovasarhely      | 2         | 1.57%   |
| Greenwich             | 2         | 1.57%   |
| Drobeta-Turnu Severin | 2         | 1.57%   |
| Changzhou             | 2         | 1.57%   |
| Woodland              | 1         | 0.79%   |
| Wloszczowa            | 1         | 0.79%   |
| Wissen                | 1         | 0.79%   |
| Wilhelmshaven         | 1         | 0.79%   |
| West Bromwich         | 1         | 0.79%   |
| Warsaw                | 1         | 0.79%   |
| Wakefield             | 1         | 0.79%   |
| Vladimir              | 1         | 0.79%   |
| Vilnius               | 1         | 0.79%   |
| Vertou                | 1         | 0.79%   |
| Vaasa                 | 1         | 0.79%   |
| Urcuit                | 1         | 0.79%   |
| Ufa                   | 1         | 0.79%   |
| Trieste               | 1         | 0.79%   |
| Swindon               | 1         | 0.79%   |
| Suwon                 | 1         | 0.79%   |
| St Petersburg         | 1         | 0.79%   |
| Southampton           | 1         | 0.79%   |
| Sofia                 | 1         | 0.79%   |
| Södertälje          | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 31     | 18.8%   |
| WDC                 | 20        | 22     | 15.04%  |
| Toshiba             | 13        | 13     | 9.77%   |
| Seagate             | 13        | 14     | 9.77%   |
| SanDisk             | 8         | 8      | 6.02%   |
| Transcend           | 5         | 5      | 3.76%   |
| Crucial             | 5         | 5      | 3.76%   |
| Apple               | 5         | 6      | 3.76%   |
| SK hynix            | 4         | 5      | 3.01%   |
| Intel               | 4         | 4      | 3.01%   |
| Hitachi             | 4         | 5      | 3.01%   |
| Micron Technology   | 3         | 3      | 2.26%   |
| Kingston            | 3         | 3      | 2.26%   |
| SPCC                | 2         | 2      | 1.5%    |
| OCZ                 | 2         | 2      | 1.5%    |
| Gigabyte Technology | 2         | 2      | 1.5%    |
| Fujitsu             | 2         | 3      | 1.5%    |
| UMIS                | 1         | 1      | 0.75%   |
| PNY                 | 1         | 1      | 0.75%   |
| Phison              | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| LITEON              | 1         | 1      | 0.75%   |
| KingDian            | 1         | 1      | 0.75%   |
| Intenso             | 1         | 1      | 0.75%   |
| HGST                | 1         | 1      | 0.75%   |
| Dogfish             | 1         | 1      | 0.75%   |
| Corsair             | 1         | 1      | 0.75%   |
| ASUSTek Computer    | 1         | 2      | 0.75%   |
| AirDisk             | 1         | 1      | 0.75%   |
| A-DATA Technology   | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 2.19%   |
| SanDisk pSSD 256GB                   | 3         | 2.19%   |
| WDC WD2500BEVT-80A23T0 250GB         | 2         | 1.46%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.46%   |
| Seagate ST95005620AS 500GB           | 2         | 1.46%   |
| SanDisk SSD U100 24GB                | 2         | 1.46%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.46%   |
| Kingston SA400S37240G 240GB          | 2         | 1.46%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.46%   |
| Apple SSD SM0512F 500GB              | 2         | 1.46%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.73%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.73%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.73%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.73%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.73%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.73%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.73%   |
| WDC WD2500LPCX-24C6HT0 250GB         | 1         | 0.73%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.73%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.73%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.73%   |
| WDC WD10SMRW-11Y43S0 1TB             | 1         | 0.73%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.73%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.73%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.73%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.73%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB   | 1         | 0.73%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.73%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.73%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.73%   |
| UMIS RPJTJ256MED1OWX 256GB           | 1         | 0.73%   |
| Transcend TS512GSSD370S 512GB        | 1         | 0.73%   |
| Transcend TS512GSSD230S 512GB        | 1         | 0.73%   |
| Transcend TS128GSSD340K 128GB        | 1         | 0.73%   |
| Transcend TS128GSSD340 128GB         | 1         | 0.73%   |
| Transcend TS120GSSD220S 120GB        | 1         | 0.73%   |
| Toshiba TR200 240GB                  | 1         | 0.73%   |
| Toshiba THNSNC128GBSJ                | 1         | 0.73%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.73%   |
| Toshiba MK7575GSX 752GB              | 1         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 15     | 33.33%  |
| Seagate | 13        | 14     | 28.89%  |
| Toshiba | 9         | 9      | 20%     |
| Hitachi | 4         | 5      | 8.89%   |
| Fujitsu | 2         | 3      | 4.44%   |
| HGST    | 1         | 1      | 2.22%   |
| Apple   | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 15     | 20.97%  |
| SanDisk             | 8         | 8      | 12.9%   |
| Transcend           | 5         | 5      | 8.06%   |
| Crucial             | 4         | 4      | 6.45%   |
| Apple               | 4         | 5      | 6.45%   |
| Toshiba             | 3         | 3      | 4.84%   |
| Kingston            | 3         | 3      | 4.84%   |
| Intel               | 3         | 3      | 4.84%   |
| WDC                 | 2         | 3      | 3.23%   |
| SPCC                | 2         | 2      | 3.23%   |
| OCZ                 | 2         | 2      | 3.23%   |
| Micron Technology   | 2         | 2      | 3.23%   |
| Gigabyte Technology | 2         | 2      | 3.23%   |
| PNY                 | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| KingDian            | 1         | 1      | 1.61%   |
| Intenso             | 1         | 1      | 1.61%   |
| Dogfish             | 1         | 1      | 1.61%   |
| Corsair             | 1         | 1      | 1.61%   |
| ASUSTek Computer    | 1         | 2      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 58        | 67     | 44.62%  |
| HDD  | 45        | 48     | 34.62%  |
| NVMe | 27        | 32     | 20.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 115    | 78.05%  |
| NVMe | 27        | 32     | 21.95%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 87     | 73.27%  |
| 0.51-1.0   | 24        | 25     | 23.76%  |
| 1.01-2.0   | 3         | 3      | 2.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 101       | 80.8%   |
| 101-250    | 8         | 6.4%    |
| 21-50      | 7         | 5.6%    |
| 251-500    | 4         | 3.2%    |
| 51-100     | 3         | 2.4%    |
| 501-1000   | 2         | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 123       | 97.62%  |
| 21-50   | 2         | 1.59%   |
| 51-100  | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 4.76%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 4.76%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 4.76%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 4.76%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 4.76%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 4.76%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 4.76%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 4.76%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 4.76%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 4.76%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 4.76%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 4.76%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 4.76%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 2      | 4.76%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 4.76%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 4.76%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 23.81%  |
| Toshiba             | 4         | 4      | 19.05%  |
| Seagate             | 3         | 3      | 14.29%  |
| Hitachi             | 3         | 4      | 14.29%  |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Corsair             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 31.25%  |
| Toshiba | 4         | 4      | 25%     |
| Seagate | 3         | 3      | 18.75%  |
| Hitachi | 3         | 4      | 18.75%  |
| HGST    | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 17     | 76.19%  |
| SSD  | 5         | 5      | 23.81%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model              | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 100       | 122    | 81.3%   |
| Malfunc  | 21        | 22     | 17.07%  |
| Detected | 1         | 2      | 0.81%   |
| Failed   | 1         | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 90        | 64.29%  |
| Samsung Electronics                     | 16        | 11.43%  |
| AMD                                     | 14        | 10%     |
| Sandisk                                 | 5         | 3.57%   |
| SK hynix                                | 4         | 2.86%   |
| Nvidia                                  | 2         | 1.43%   |
| VIA Technologies                        | 1         | 0.71%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.71%   |
| Shenzhen Unionmemory Information System | 1         | 0.71%   |
| Phison Electronics                      | 1         | 0.71%   |
| Micron/Crucial Technology               | 1         | 0.71%   |
| Micron Technology                       | 1         | 0.71%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.71%   |
| KIOXIA                                  | 1         | 0.71%   |
| JMicron Technology                      | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 9.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 8%      |
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 8%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 6%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 6%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 5.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 2%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 2%      |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 1.33%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 2         | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.33%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.33%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.33%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.67%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.67%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 0.67%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.67%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.67%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 x2 NVMe SSD 256GB         | 1         | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1         | 0.67%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 0.67%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 1         | 0.67%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.67%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 90        | 63.38%  |
| NVMe | 28        | 19.72%  |
| IDE  | 15        | 10.56%  |
| RAID | 9         | 6.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 109       | 86.51%  |
| AMD    | 17        | 13.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 3.17%   |
| Intel CPU Version                             | 3         | 2.38%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 2.38%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 2.38%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 2.38%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.59%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.59%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 1.59%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.59%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.59%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.79%   |
| Intel Pentium III                             | 1         | 0.79%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.79%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.79%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.79%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.79%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.79%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.79%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.79%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.79%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.79%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 0.79%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz            | 1         | 0.79%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.79%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.79%   |
| Intel Core i7-4610M CPU @ 3.00GHz             | 1         | 0.79%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 31.75%  |
| Intel Core i7           | 30        | 23.81%  |
| Other                   | 10        | 7.94%   |
| Intel Core i3           | 7         | 5.56%   |
| Intel Core 2 Duo        | 5         | 3.97%   |
| Intel Atom              | 5         | 3.97%   |
| AMD Ryzen 7             | 5         | 3.97%   |
| Intel Pentium           | 3         | 2.38%   |
| AMD A6                  | 3         | 2.38%   |
| Intel Celeron Dual-Core | 2         | 1.59%   |
| Intel Celeron           | 2         | 1.59%   |
| AMD Ryzen 5             | 2         | 1.59%   |
| AMD A8                  | 2         | 1.59%   |
| Intel Xeon              | 1         | 0.79%   |
| Intel Pentium III       | 1         | 0.79%   |
| Intel Genuine           | 1         | 0.79%   |
| Intel Core m5           | 1         | 0.79%   |
| Intel Core i9           | 1         | 0.79%   |
| Intel Core 2            | 1         | 0.79%   |
| Intel Celeron M         | 1         | 0.79%   |
| AMD Ryzen 7 PRO         | 1         | 0.79%   |
| AMD E1                  | 1         | 0.79%   |
| AMD A10                 | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 63        | 50%     |
| 4       | 37        | 29.37%  |
| Unknown | 10        | 7.94%   |
| 8       | 4         | 3.17%   |
| 1       | 4         | 3.17%   |
| 16      | 3         | 2.38%   |
| 12      | 3         | 2.38%   |
| 6       | 2         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 123       | 98.4%   |
| 2       | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 83        | 65.87%  |
| 1       | 31        | 24.6%   |
| Unknown | 12        | 9.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 20.63%  |
| Haswell       | 18        | 14.29%  |
| IvyBridge     | 13        | 10.32%  |
| Skylake       | 12        | 9.52%   |
| Penryn        | 9         | 7.14%   |
| SandyBridge   | 7         | 5.56%   |
| Bonnell       | 6         | 4.76%   |
| Unknown       | 5         | 3.97%   |
| Zen+          | 4         | 3.17%   |
| Puma          | 4         | 3.17%   |
| Core          | 3         | 2.38%   |
| Broadwell     | 3         | 2.38%   |
| Westmere      | 2         | 1.59%   |
| TigerLake     | 2         | 1.59%   |
| Silvermont    | 2         | 1.59%   |
| P6            | 2         | 1.59%   |
| Zen 2         | 1         | 0.79%   |
| Steamroller   | 1         | 0.79%   |
| K10 Llano     | 1         | 0.79%   |
| K10           | 1         | 0.79%   |
| Jaguar        | 1         | 0.79%   |
| Goldmont plus | 1         | 0.79%   |
| Excavator     | 1         | 0.79%   |
| CometLake     | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 94        | 66.2%   |
| AMD              | 24        | 16.9%   |
| Nvidia           | 22        | 15.49%  |
| VIA Technologies | 1         | 0.7%    |
| S3 Graphics      | 1         | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 8.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 7.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 6.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.42%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.42%   |
| Intel HD Graphics 620                                                                    | 5         | 3.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 2.05%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 1.37%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.37%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.37%   |
| AMD Lucienne                                                                             | 2         | 1.37%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.68%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.68%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.68%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.68%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.68%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.68%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.68%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.68%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.68%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.68%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.68%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.68%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.68%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 0.68%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.68%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 69        | 54.76%  |
| 1 x AMD         | 21        | 16.67%  |
| Intel + Nvidia  | 12        | 9.52%   |
| 2 x Intel       | 10        | 7.94%   |
| 1 x Nvidia      | 9         | 7.14%   |
| Intel + AMD     | 2         | 1.59%   |
| 1 x VIA         | 1         | 0.79%   |
| 1 x S3 Graphics | 1         | 0.79%   |
| AMD + Nvidia    | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 106       | 84.8%   |
| Unknown     | 15        | 12%     |
| Proprietary | 4         | 3.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 89.68%  |
| 0.01-0.5   | 6         | 4.76%   |
| 0.51-1.0   | 4         | 3.17%   |
| 1.01-2.0   | 3         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 17.89%  |
| LG Display              | 16        | 16.84%  |
| BOE                     | 14        | 14.74%  |
| Samsung Electronics     | 11        | 11.58%  |
| Chimei Innolux          | 9         | 9.47%   |
| Sharp                   | 4         | 4.21%   |
| HannStar                | 4         | 4.21%   |
| Chi Mei Optoelectronics | 4         | 4.21%   |
| Apple                   | 4         | 4.21%   |
| Lenovo                  | 3         | 3.16%   |
| Panasonic               | 2         | 2.11%   |
| LG Philips              | 1         | 1.05%   |
| Hewlett-Packard         | 1         | 1.05%   |
| Goldstar                | 1         | 1.05%   |
| CPT                     | 1         | 1.05%   |
| BenQ                    | 1         | 1.05%   |
| AOC                     | 1         | 1.05%   |
| Acer                    | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 3         | 3.13%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 2         | 2.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 2.08%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 2.08%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 1.04%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 1.04%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.04%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 1.04%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 1.04%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD0612 1920x1080 340x190mm 15.3-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch              | 1         | 1.04%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 37        | 38.95%  |
| 1920x1080 (FHD)  | 30        | 31.58%  |
| 1600x900 (HD+)   | 5         | 5.26%   |
| 1024x600         | 5         | 5.26%   |
| 1280x800 (WXGA)  | 4         | 4.21%   |
| 3840x2160 (4K)   | 3         | 3.16%   |
| 1440x900 (WXGA+) | 3         | 3.16%   |
| 2880x1800        | 2         | 2.11%   |
| 2880x1620        | 2         | 2.11%   |
| 3200x1800 (QHD+) | 1         | 1.05%   |
| 2560x1440 (QHD)  | 1         | 1.05%   |
| 2160x1350        | 1         | 1.05%   |
| 1280x1024 (SXGA) | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 39        | 40.63%  |
| 13     | 24        | 25%     |
| 12     | 11        | 11.46%  |
| 17     | 7         | 7.29%   |
| 10     | 5         | 5.21%   |
| 24     | 3         | 3.13%   |
| 11     | 3         | 3.13%   |
| 27     | 2         | 2.08%   |
| 18     | 1         | 1.04%   |
| 14     | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 56.25%  |
| 201-300     | 30        | 31.25%  |
| 351-400     | 6         | 6.25%   |
| 501-600     | 4         | 4.17%   |
| 601-700     | 1         | 1.04%   |
| 401-500     | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 79        | 87.78%  |
| 16/10 | 9         | 10%     |
| 5/4   | 1         | 1.11%   |
| 3/2   | 1         | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 30        | 31.25%  |
| 81-90          | 18        | 18.75%  |
| 61-70          | 10        | 10.42%  |
| 101-110        | 9         | 9.38%   |
| 71-80          | 8         | 8.33%   |
| 41-50          | 5         | 5.21%   |
| 121-130        | 5         | 5.21%   |
| 51-60          | 3         | 3.13%   |
| 201-250        | 3         | 3.13%   |
| 301-350        | 2         | 2.08%   |
| 141-150        | 2         | 2.08%   |
| 131-140        | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 37        | 38.95%  |
| 121-160       | 30        | 31.58%  |
| 161-240       | 13        | 13.68%  |
| 51-100        | 11        | 11.58%  |
| More than 240 | 4         | 4.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 100       | 78.74%  |
| 0     | 23        | 18.11%  |
| 2     | 3         | 2.36%   |
| 3     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 74        | 37.37%  |
| Realtek Semiconductor             | 49        | 24.75%  |
| Qualcomm Atheros                  | 32        | 16.16%  |
| Broadcom                          | 14        | 7.07%   |
| Samsung Electronics               | 4         | 2.02%   |
| Ralink                            | 3         | 1.52%   |
| Marvell Technology Group          | 3         | 1.52%   |
| TP-Link                           | 2         | 1.01%   |
| Sierra Wireless                   | 2         | 1.01%   |
| Ralink Technology                 | 2         | 1.01%   |
| Ericsson Business Mobile Networks | 2         | 1.01%   |
| VIA Technologies                  | 1         | 0.51%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.51%   |
| Qualcomm Technologies             | 1         | 0.51%   |
| Qualcomm                          | 1         | 0.51%   |
| NetGear                           | 1         | 0.51%   |
| JMicron Technology                | 1         | 0.51%   |
| Fibocom                           | 1         | 0.51%   |
| Dell                              | 1         | 0.51%   |
| D-Link                            | 1         | 0.51%   |
| Atheros                           | 1         | 0.51%   |
| Apple                             | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 33        | 12.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 13        | 5.02%   |
| Intel Wireless 7260                                                         | 10        | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 8         | 3.09%   |
| Intel Wireless 8265 / 8275                                                  | 7         | 2.7%    |
| Intel Wireless 8260                                                         | 7         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                                       | 6         | 2.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 5         | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 5         | 1.93%   |
| Intel Wireless 3165                                                         | 5         | 1.93%   |
| Intel Ethernet Connection I217-LM                                           | 5         | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 5         | 1.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 4         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 4         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                         | 4         | 1.54%   |
| Intel Ethernet Connection I218-LM                                           | 4         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 4         | 1.54%   |
| Samsung Galaxy series, misc. (tethering mode)                               | 3         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 3         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 3         | 1.16%   |
| Intel WiFi Link 5100                                                        | 3         | 1.16%   |
| Intel Ethernet Connection I219-LM                                           | 3         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 3         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                              | 3         | 1.16%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                           | 3         | 1.16%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 3         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 2         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 2         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 2         | 0.77%   |
| Intel Wireless 7265                                                         | 2         | 0.77%   |
| Intel Wi-Fi 6 AX201                                                         | 2         | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 2         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                                        | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                        | 2         | 0.77%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 0.77%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 69        | 50.74%  |
| Qualcomm Atheros      | 27        | 19.85%  |
| Realtek Semiconductor | 18        | 13.24%  |
| Broadcom              | 10        | 7.35%   |
| Ralink                | 3         | 2.21%   |
| TP-Link               | 2         | 1.47%   |
| Ralink Technology     | 2         | 1.47%   |
| Sierra Wireless       | 1         | 0.74%   |
| Qualcomm Technologies | 1         | 0.74%   |
| NetGear               | 1         | 0.74%   |
| D-Link                | 1         | 0.74%   |
| Atheros               | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 10        | 7.19%   |
| Intel Wireless 8265 / 8275                                     | 7         | 5.04%   |
| Intel Wireless 8260                                            | 7         | 5.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 3.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.6%    |
| Intel Wireless 3165                                            | 5         | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 3.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 2.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.88%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 2.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.16%   |
| Intel WiFi Link 5100                                           | 3         | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.16%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.16%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 2.16%   |
| Intel Wireless 7265                                            | 2         | 1.44%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.44%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.44%   |
| TP-Link Wireless USB Adapter                                   | 1         | 0.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.72%   |
| Sierra Wireless EM7455                                         | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.72%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller             | 1         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.72%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 0.72%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 0.72%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1         | 0.72%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 46        | 40.35%  |
| Intel                            | 40        | 35.09%  |
| Qualcomm Atheros                 | 8         | 7.02%   |
| Broadcom                         | 8         | 7.02%   |
| Samsung Electronics              | 4         | 3.51%   |
| Marvell Technology Group         | 3         | 2.63%   |
| VIA Technologies                 | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| Qualcomm                         | 1         | 0.88%   |
| JMicron Technology               | 1         | 0.88%   |
| Apple                            | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 28.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 11.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 6.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 5.22%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 4.35%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 3.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 2.61%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.61%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 2.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.74%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.74%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.74%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.74%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.87%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.87%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.87%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.87%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.87%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.87%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.87%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.87%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.87%   |
| Intel Ethernet Connection (23) I219-V                             | 1         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.87%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 0.87%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.87%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.87%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 125       | 52.08%  |
| Ethernet | 110       | 45.83%  |
| Unknown  | 5         | 2.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 88        | 50.57%  |
| WiFi     | 84        | 48.28%  |
| Unknown  | 2         | 1.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 107       | 84.92%  |
| 1     | 19        | 15.08%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 112       | 88.89%  |
| Yes  | 14        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 46.74%  |
| Broadcom                        | 9         | 9.78%   |
| Realtek Semiconductor           | 8         | 8.7%    |
| Qualcomm Atheros Communications | 6         | 6.52%   |
| Lite-On Technology              | 6         | 6.52%   |
| Apple                           | 5         | 5.43%   |
| IMC Networks                    | 4         | 4.35%   |
| ASUSTek Computer                | 4         | 4.35%   |
| Foxconn / Hon Hai               | 2         | 2.17%   |
| USI                             | 1         | 1.09%   |
| Hewlett-Packard                 | 1         | 1.09%   |
| Dell                            | 1         | 1.09%   |
| Cambridge Silicon Radio         | 1         | 1.09%   |
| Alps Electric                   | 1         | 1.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 27.17%  |
| Intel AX201 Bluetooth                                       | 6         | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 5.43%   |
| Intel AX200 Bluetooth                                       | 4         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 4.35%   |
| Apple Bluetooth Host Controller                             | 3         | 3.26%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 2.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.17%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.17%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.17%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 2.17%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 2.17%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 1.09%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.09%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.09%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.09%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 1.09%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.09%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 1.09%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.09%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.09%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.09%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.09%   |
| Lite-On Bluetooth USB Module                                | 1         | 1.09%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.09%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.09%   |
| Intel AX211 Bluetooth                                       | 1         | 1.09%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.09%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 1.09%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.09%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.09%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.09%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.09%   |
| Broadcom Bluetooth 4.0                                      | 1         | 1.09%   |
| Broadcom Bluetooth 2.1 Device                               | 1         | 1.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 105       | 76.09%  |
| AMD                              | 21        | 15.22%  |
| Nvidia                           | 8         | 5.8%    |
| VIA Technologies                 | 1         | 0.72%   |
| Silicon Integrated Systems [SiS] | 1         | 0.72%   |
| Realtek Semiconductor            | 1         | 0.72%   |
| Blue Microphones                 | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 12.57%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 8%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 6.29%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 4.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 4%      |
| AMD FCH Azalia Controller                                                                         | 7         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.71%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.14%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.14%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.57%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.57%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.57%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.57%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.57%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.57%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 0.57%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 32.45%  |
| SK hynix            | 36        | 23.84%  |
| Micron Technology   | 16        | 10.6%   |
| Unknown             | 11        | 7.28%   |
| Kingston            | 9         | 5.96%   |
| Unknown             | 5         | 3.31%   |
| Elpida              | 4         | 2.65%   |
| Crucial             | 4         | 2.65%   |
| A-DATA Technology   | 4         | 2.65%   |
| Transcend           | 2         | 1.32%   |
| Ramaxel Technology  | 2         | 1.32%   |
| Nanya Technology    | 2         | 1.32%   |
| 48spaces            | 2         | 1.32%   |
| Unknown (ABCD)      | 1         | 0.66%   |
| Unknown (09D5)      | 1         | 0.66%   |
| Magnum Tech         | 1         | 0.66%   |
| G.Skill             | 1         | 0.66%   |
| Corsair             | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 7         | 4.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 3.05%   |
| Unknown                                                                   | 5         | 3.05%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 2.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.83%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.83%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 1.22%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.22%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 1.22%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 1.22%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 1.22%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM 1600MT/s                          | 2         | 1.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.22%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.22%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.22%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.22%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 2         | 1.22%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 1.22%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                 | 1         | 0.61%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                                 | 1         | 0.61%   |
| Unknown RAM Module 512MB SODIMM SDRAM                                     | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                                | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.61%   |
| Unknown RAM Module 128MB SODIMM SDRAM                                     | 1         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 1         | 0.61%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s                       | 1         | 0.61%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                            | 1         | 0.61%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 667MT/s                         | 1         | 0.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                              | 1         | 0.61%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 0.61%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s                     | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 56        | 44.44%  |
| DDR4    | 39        | 30.95%  |
| DDR2    | 11        | 8.73%   |
| LPDDR3  | 7         | 5.56%   |
| SDRAM   | 4         | 3.17%   |
| LPDDR5  | 2         | 1.59%   |
| LPDDR4  | 2         | 1.59%   |
| Unknown | 2         | 1.59%   |
| RAM     | 1         | 0.79%   |
| DRAM    | 1         | 0.79%   |
| DDR5    | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 116       | 91.34%  |
| Row Of Chips | 5         | 3.94%   |
| Chip         | 3         | 2.36%   |
| Unknown      | 2         | 1.57%   |
| DIMM         | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 54        | 37.24%  |
| 8192  | 44        | 30.34%  |
| 2048  | 26        | 17.93%  |
| 16384 | 13        | 8.97%   |
| 1024  | 4         | 2.76%   |
| 32768 | 2         | 1.38%   |
| 512   | 1         | 0.69%   |
| 128   | 1         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 40        | 29.41%  |
| 2667    | 17        | 12.5%   |
| 2400    | 14        | 10.29%  |
| 2133    | 10        | 7.35%   |
| 1334    | 9         | 6.62%   |
| 667     | 9         | 6.62%   |
| 3200    | 7         | 5.15%   |
| 1333    | 6         | 4.41%   |
| 1867    | 5         | 3.68%   |
| Unknown | 5         | 3.68%   |
| 1067    | 3         | 2.21%   |
| 6400    | 2         | 1.47%   |
| 800     | 2         | 1.47%   |
| 5600    | 1         | 0.74%   |
| 4267    | 1         | 0.74%   |
| 1866    | 1         | 0.74%   |
| 1639    | 1         | 0.74%   |
| 975     | 1         | 0.74%   |
| 533     | 1         | 0.74%   |
| 400     | 1         | 0.74%   |

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
| Chicony Electronics                    | 28        | 28.28%  |
| Bison Electronics                      | 14        | 14.14%  |
| Realtek Semiconductor                  | 10        | 10.1%   |
| Suyin                                  | 8         | 8.08%   |
| Sunplus Innovation Technology          | 8         | 8.08%   |
| IMC Networks                           | 7         | 7.07%   |
| Microdia                               | 6         | 6.06%   |
| Silicon Motion                         | 3         | 3.03%   |
| Lite-On Technology                     | 3         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.03%   |
| Quanta                                 | 2         | 2.02%   |
| Z-Star Microelectronics                | 1         | 1.01%   |
| Luxvisions Innotech Limited            | 1         | 1.01%   |
| Logitech                               | 1         | 1.01%   |
| Intel                                  | 1         | 1.01%   |
| Genesys Logic                          | 1         | 1.01%   |
| Apple                                  | 1         | 1.01%   |
| Alcor Micro                            | 1         | 1.01%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 9.09%   |
| Bison Integrated Camera                                     | 6         | 6.06%   |
| Chicony HD WebCam                                           | 4         | 4.04%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 3.03%   |
| Realtek Integrated_Webcam_HD                                | 3         | 3.03%   |
| Microdia Integrated Webcam                                  | 3         | 3.03%   |
| Suyin Acer Crystal Eye webcam                               | 2         | 2.02%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 2.02%   |
| Realtek Lenovo EasyCamera                                   | 2         | 2.02%   |
| Microdia Integrated_Webcam_HD                               | 2         | 2.02%   |
| IMC Networks EasyCamera                                     | 2         | 2.02%   |
| Chicony FJ Camera                                           | 2         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 2.02%   |
| Bison ThinkPad Integrated Camera                            | 2         | 2.02%   |
| Bison SunplusIT Integrated Camera                           | 2         | 2.02%   |
| Z-Star Webcam                                               | 1         | 1.01%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 1.01%   |
| Suyin Laptop_Integrated_Webcam_3M                           | 1         | 1.01%   |
| Suyin HD WebCam                                             | 1         | 1.01%   |
| Suyin HD Video WebCam                                       | 1         | 1.01%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.01%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.01%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.01%   |
| Sunplus Integrated Webcam                                   | 1         | 1.01%   |
| Sunplus Hy HD Camera                                        | 1         | 1.01%   |
| Sunplus hama C-600 Pro Webcam                               | 1         | 1.01%   |
| Sunplus Asus Webcam                                         | 1         | 1.01%   |
| Silicon Motion WebCam SCX Series                            | 1         | 1.01%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 1.01%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 1.01%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 1.01%   |
| Realtek USB Camera                                          | 1         | 1.01%   |
| Realtek HD Webcam - Realtek                                 | 1         | 1.01%   |
| Quanta Realtek DMFT RGB                                     | 1         | 1.01%   |
| Quanta Front camera                                         | 1         | 1.01%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.01%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.01%   |
| Logitech HD Pro Webcam C920                                 | 1         | 1.01%   |
| Lite-On Realtek PC Camera                                   | 1         | 1.01%   |
| Lite-On Integrated Camera                                   | 1         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 46.43%  |
| Synaptics                  | 5         | 17.86%  |
| Upek                       | 4         | 14.29%  |
| LighTuning Technology      | 2         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 3.57%   |
| Elan Microelectronics      | 1         | 3.57%   |
| Broadcom                   | 1         | 3.57%   |
| AuthenTec                  | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 10.71%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 10.71%  |
| Validity Sensors Synaptics WBDI                                              | 3         | 10.71%  |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 7.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 3.57%   |
| LighTuning Fingerprint Reader                                                | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.57%   |
| Elan Fingerprint Sensor                                                      | 1         | 3.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.57%   |
| AuthenTec AES1600                                                            | 1         | 3.57%   |
| Unknown                                                                      | 1         | 3.57%   |

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
| 1     | 40        | 31.25%  |
| 2     | 36        | 28.13%  |
| 3     | 19        | 14.84%  |
| 0     | 18        | 14.06%  |
| 4     | 11        | 8.59%   |
| 5     | 2         | 1.56%   |
| 7     | 1         | 0.78%   |
| 6     | 1         | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 85        | 39.53%  |
| Net/wireless             | 39        | 18.14%  |
| Bluetooth                | 29        | 13.49%  |
| Fingerprint reader       | 27        | 12.56%  |
| Card reader              | 20        | 9.3%    |
| Firewire controller      | 10        | 4.65%   |
| Network                  | 2         | 0.93%   |
| Storage/raid             | 1         | 0.47%   |
| Sound                    | 1         | 0.47%   |
| Net/ethernet             | 1         | 0.47%   |

