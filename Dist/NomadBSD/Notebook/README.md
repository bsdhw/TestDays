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

Total: 174

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [5f31e6dc7e](https://bsd-hardware.info/?probe=5f31e6dc7e) | May 04, 2024 |
| Apple         | MacBookAir6,2               | [fc810b38b1](https://bsd-hardware.info/?probe=fc810b38b1) | Apr 16, 2024 |
| Lenovo        | ThinkPad X260 20F60093US    | [3b7eee9621](https://bsd-hardware.info/?probe=3b7eee9621) | Apr 04, 2024 |
| Dell          | Latitude 7220 Rugged Ext... | [d882577127](https://bsd-hardware.info/?probe=d882577127) | Mar 07, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dab1edae0c](https://bsd-hardware.info/?probe=dab1edae0c) | Jan 08, 2024 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [9ed586661c](https://bsd-hardware.info/?probe=9ed586661c) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [77d8cc2e7c](https://bsd-hardware.info/?probe=77d8cc2e7c) | Jan 02, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [02bf1d2cd4](https://bsd-hardware.info/?probe=02bf1d2cd4) | Dec 19, 2023 |
| Sony          | VJS122C11L                  | [7d100c8e2c](https://bsd-hardware.info/?probe=7d100c8e2c) | Dec 06, 2023 |
| Apple         | MacBookPro7,1               | [97267cbee9](https://bsd-hardware.info/?probe=97267cbee9) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
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
| NomadBSD 1.3.2    | 34        | 24.46%  |
| NomadBSD 5806f915 | 32        | 23.02%  |
| NomadBSD 20221130 | 27        | 19.42%  |
| NomadBSD 1.4      | 18        | 12.95%  |
| NomadBSD 1.3.1    | 7         | 5.04%   |
| NomadBSD 20231013 | 6         | 4.32%   |
| NomadBSD 1.4-RC1  | 6         | 4.32%   |
| NomadBSD 20231121 | 5         | 3.6%    |
| NomadBSD 20240126 | 3         | 2.16%   |
| NomadBSD 81e34fc3 | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| NomadBSD | 134       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 127       | 94.07%  |
| i386  | 8         | 5.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 111       | 82.84%  |
| xinitrc | 8         | 5.97%   |
| GNOME   | 6         | 4.48%   |
| KDE5    | 5         | 3.73%   |
| XFCE    | 4         | 2.99%   |

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
| SLiM | 93        | 69.4%   |
| SDDM | 41        | 30.6%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 47        | 34.56%  |
| Unknown | 22        | 16.18%  |
| de_DE   | 13        | 9.56%   |
| en_GB   | 12        | 8.82%   |
| ru_RU   | 7         | 5.15%   |
| fr_FR   | 7         | 5.15%   |
| zh_TW   | 5         | 3.68%   |
| zh_CN   | 3         | 2.21%   |
| it_IT   | 3         | 2.21%   |
| fi_FI   | 3         | 2.21%   |
| pl_PL   | 2         | 1.47%   |
| hu_HU   | 2         | 1.47%   |
| es_ES   | 2         | 1.47%   |
| en_AU   | 2         | 1.47%   |
| tr_TR   | 1         | 0.74%   |
| sv_SE   | 1         | 0.74%   |
| lt_LT   | 1         | 0.74%   |
| ko_KR   | 1         | 0.74%   |
| cs_CZ   | 1         | 0.74%   |
| bg_BG   | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 129       | 95.56%  |
| BIOS | 6         | 4.44%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 110       | 81.48%  |
| Zfs  | 25        | 18.52%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 92        | 68.15%  |
| MBR  | 43        | 31.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 29.85%  |
| Dell                | 18        | 13.43%  |
| Hewlett-Packard     | 14        | 10.45%  |
| ASUSTek Computer    | 14        | 10.45%  |
| Acer                | 9         | 6.72%   |
| Apple               | 7         | 5.22%   |
| TUXEDO              | 4         | 2.99%   |
| Sony                | 4         | 2.99%   |
| Samsung Electronics | 3         | 2.24%   |
| Fujitsu             | 3         | 2.24%   |
| Notebook            | 2         | 1.49%   |
| Google              | 2         | 1.49%   |
| Fujitsu Siemens     | 2         | 1.49%   |
| Toshiba             | 1         | 0.75%   |
| Pegatron            | 1         | 0.75%   |
| Panasonic           | 1         | 0.75%   |
| NEC Computers       | 1         | 0.75%   |
| MSI                 | 1         | 0.75%   |
| IBM                 | 1         | 0.75%   |
| GEO                 | 1         | 0.75%   |
| eMachines           | 1         | 0.75%   |
| Clevo               | 1         | 0.75%   |
| Chuwi               | 1         | 0.75%   |
| Alienware           | 1         | 0.75%   |
| Unknown             | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Apple MacBookPro7,1                         | 2         | 1.49%   |
| Unknown                                     | 2         | 1.49%   |
| TUXEDO Pulse 15 Gen2                        | 1         | 0.75%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.75%   |
| TUXEDO InfinityBook S 15 Gen6               | 1         | 0.75%   |
| Toshiba Satellite C660                      | 1         | 0.75%   |
| Sony VPCM13M1R                              | 1         | 0.75%   |
| Sony VJS122C11L                             | 1         | 0.75%   |
| Sony VJS121C11N                             | 1         | 0.75%   |
| Sony SVE1713S1RW                            | 1         | 0.75%   |
| Samsung N150/N210/N220                      | 1         | 0.75%   |
| Samsung N145P/N250P/N260P                   | 1         | 0.75%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV     | 1         | 0.75%   |
| Pegatron T12Ah                              | 1         | 0.75%   |
| Panasonic CF-C1BD06EFG                      | 1         | 0.75%   |
| Notebook W650DC,DD                          | 1         | 0.75%   |
| Notebook N650DU                             | 1         | 0.75%   |
| NEC Computers PC-GL186Y3AZ                  | 1         | 0.75%   |
| MSI MS-N033                                 | 1         | 0.75%   |
| Lenovo Yoga 710-11IKB 80V6                  | 1         | 0.75%   |
| Lenovo V580 20147                           | 1         | 0.75%   |
| Lenovo ThinkPad X280 20KESB4T00             | 1         | 0.75%   |
| Lenovo ThinkPad X270 20HN006CUS             | 1         | 0.75%   |
| Lenovo ThinkPad X260 20F60093US             | 1         | 0.75%   |
| Lenovo ThinkPad X230 2325IB1                | 1         | 0.75%   |
| Lenovo ThinkPad X230 23255NG                | 1         | 0.75%   |
| Lenovo ThinkPad X230 23205UG                | 1         | 0.75%   |
| Lenovo ThinkPad X201 Tablet 311396U         | 1         | 0.75%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT    | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU    | 1         | 0.75%   |
| Lenovo ThinkPad W541 20EGS04800             | 1         | 0.75%   |
| Lenovo ThinkPad W520 42844DG                | 1         | 0.75%   |
| Lenovo ThinkPad T530 24295VU                | 1         | 0.75%   |
| Lenovo ThinkPad T510 4384FF3                | 1         | 0.75%   |
| Lenovo ThinkPad T490s 20NX000DRT            | 1         | 0.75%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.75%   |
| Lenovo ThinkPad T480 20L50000GE             | 1         | 0.75%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE      | 1         | 0.75%   |
| Lenovo ThinkPad T470 20HES0EV0A             | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 31        | 23.13%  |
| Dell Latitude              | 10        | 7.46%   |
| Acer Aspire                | 8         | 5.97%   |
| Lenovo IdeaPad             | 3         | 2.24%   |
| HP Pavilion                | 3         | 2.24%   |
| Dell Inspiron              | 3         | 2.24%   |
| TUXEDO Pulse               | 2         | 1.49%   |
| HP ProBook                 | 2         | 1.49%   |
| HP Laptop                  | 2         | 1.49%   |
| HP EliteBook               | 2         | 1.49%   |
| Fujitsu Siemens AMILO      | 2         | 1.49%   |
| Fujitsu LIFEBOOK           | 2         | 1.49%   |
| Dell XPS                   | 2         | 1.49%   |
| ASUS VivoBook              | 2         | 1.49%   |
| Apple MacBookPro7          | 2         | 1.49%   |
| Unknown                    | 2         | 1.49%   |
| TUXEDO InfinityBook        | 1         | 0.75%   |
| Toshiba Satellite          | 1         | 0.75%   |
| Sony VPCM13M1R             | 1         | 0.75%   |
| Sony VJS122C11L            | 1         | 0.75%   |
| Sony VJS121C11N            | 1         | 0.75%   |
| Sony SVE1713S1RW           | 1         | 0.75%   |
| Samsung N150               | 1         | 0.75%   |
| Samsung N145P              | 1         | 0.75%   |
| Samsung 300E5EV            | 1         | 0.75%   |
| Pegatron T12Ah             | 1         | 0.75%   |
| Panasonic CF-C1BD06EFG     | 1         | 0.75%   |
| Notebook W650DC            | 1         | 0.75%   |
| Notebook N650DU            | 1         | 0.75%   |
| NEC Computers PC-GL186Y3AZ | 1         | 0.75%   |
| MSI MS-N033                | 1         | 0.75%   |
| Lenovo Yoga                | 1         | 0.75%   |
| Lenovo V580                | 1         | 0.75%   |
| Lenovo Legion              | 1         | 0.75%   |
| Lenovo G570                | 1         | 0.75%   |
| Lenovo G50-70              | 1         | 0.75%   |
| Lenovo G50-45              | 1         | 0.75%   |
| IBM 2647NG8                | 1         | 0.75%   |
| HP ZBook                   | 1         | 0.75%   |
| HP OMEN                    | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 14        | 10.45%  |
| 2020 | 13        | 9.7%    |
| 2018 | 10        | 7.46%   |
| 2017 | 10        | 7.46%   |
| 2012 | 10        | 7.46%   |
| 2011 | 10        | 7.46%   |
| 2022 | 9         | 6.72%   |
| 2021 | 8         | 5.97%   |
| 2014 | 8         | 5.97%   |
| 2015 | 7         | 5.22%   |
| 2010 | 7         | 5.22%   |
| 2016 | 6         | 4.48%   |
| 2013 | 6         | 4.48%   |
| 2008 | 6         | 4.48%   |
| 2009 | 4         | 2.99%   |
| 2023 | 3         | 2.24%   |
| 2006 | 2         | 1.49%   |
| 2004 | 1         | 0.75%   |

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
| No   | 131       | 97.76%  |
| Yes  | 3         | 2.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 56        | 41.48%  |
| 16.01-24.0  | 28        | 20.74%  |
| 4.01-8.0    | 27        | 20%     |
| 32.01-64.0  | 8         | 5.93%   |
| 2.01-3.0    | 6         | 4.44%   |
| 64.01-256.0 | 3         | 2.22%   |
| 0.51-1.0    | 3         | 2.22%   |
| 3.01-4.0    | 2         | 1.48%   |
| 24.01-32.0  | 2         | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 69        | 50%     |
| 0.51-1.0  | 43        | 31.16%  |
| 1.01-2.0  | 16        | 11.59%  |
| 2.01-3.0  | 5         | 3.62%   |
| 4.01-8.0  | 3         | 2.17%   |
| 3.01-4.0  | 1         | 0.72%   |
| 8.01-16.0 | 1         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 74.81%  |
| 2      | 19        | 14.07%  |
| 0      | 13        | 9.63%   |
| 3      | 2         | 1.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 65.19%  |
| Yes       | 47        | 34.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 85.19%  |
| No        | 20        | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 99.25%  |
| No        | 1         | 0.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 73.88%  |
| No        | 35        | 26.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 18        | 13.43%  |
| Germany     | 17        | 12.69%  |
| France      | 16        | 11.94%  |
| Russia      | 14        | 10.45%  |
| UK          | 12        | 8.96%   |
| Taiwan      | 5         | 3.73%   |
| Italy       | 5         | 3.73%   |
| Finland     | 4         | 2.99%   |
| Norway      | 3         | 2.24%   |
| Mexico      | 3         | 2.24%   |
| Hungary     | 3         | 2.24%   |
| China       | 3         | 2.24%   |
| Australia   | 3         | 2.24%   |
| Turkey      | 2         | 1.49%   |
| Spain       | 2         | 1.49%   |
| Romania     | 2         | 1.49%   |
| Poland      | 2         | 1.49%   |
| Japan       | 2         | 1.49%   |
| Colombia    | 2         | 1.49%   |
| Ukraine     | 1         | 0.75%   |
| Switzerland | 1         | 0.75%   |
| Sweden      | 1         | 0.75%   |
| South Korea | 1         | 0.75%   |
| San Marino  | 1         | 0.75%   |
| Philippines | 1         | 0.75%   |
| Lithuania   | 1         | 0.75%   |
| Indonesia   | 1         | 0.75%   |
| Hong Kong   | 1         | 0.75%   |
| Egypt       | 1         | 0.75%   |
| Denmark     | 1         | 0.75%   |
| Czechia     | 1         | 0.75%   |
| Canada      | 1         | 0.75%   |
| Bulgaria    | 1         | 0.75%   |
| Belarus     | 1         | 0.75%   |
| Argentina   | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Moscow                | 10        | 7.35%   |
| Franconville          | 6         | 4.41%   |
| Whittier              | 3         | 2.21%   |
| Tijuana               | 3         | 2.21%   |
| Taichung              | 3         | 2.21%   |
| Markt Indersdorf      | 3         | 2.21%   |
| Zwingenberg           | 2         | 1.47%   |
| Vollen                | 2         | 1.47%   |
| Turku                 | 2         | 1.47%   |
| Taipei                | 2         | 1.47%   |
| Setagaya-ku           | 2         | 1.47%   |
| Rome                  | 2         | 1.47%   |
| New Braunfels         | 2         | 1.47%   |
| Melun                 | 2         | 1.47%   |
| Los Angeles           | 2         | 1.47%   |
| Istanbul              | 2         | 1.47%   |
| Hodmezovasarhely      | 2         | 1.47%   |
| Greenwich             | 2         | 1.47%   |
| Drobeta-Turnu Severin | 2         | 1.47%   |
| Changzhou             | 2         | 1.47%   |
| Woodland              | 1         | 0.74%   |
| Wloszczowa            | 1         | 0.74%   |
| Wissen                | 1         | 0.74%   |
| Wilhelmshaven         | 1         | 0.74%   |
| West Bromwich         | 1         | 0.74%   |
| Warsaw                | 1         | 0.74%   |
| Wakefield             | 1         | 0.74%   |
| Vladimir              | 1         | 0.74%   |
| Vilnius               | 1         | 0.74%   |
| Vertou                | 1         | 0.74%   |
| Vantaa                | 1         | 0.74%   |
| Vaasa                 | 1         | 0.74%   |
| Urcuit                | 1         | 0.74%   |
| Ufa                   | 1         | 0.74%   |
| Trieste               | 1         | 0.74%   |
| Sydney                | 1         | 0.74%   |
| Swindon               | 1         | 0.74%   |
| Suwon                 | 1         | 0.74%   |
| St Petersburg         | 1         | 0.74%   |
| Southampton           | 1         | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 33     | 19.57%  |
| WDC                 | 20        | 22     | 14.49%  |
| Toshiba             | 13        | 13     | 9.42%   |
| Seagate             | 13        | 14     | 9.42%   |
| SanDisk             | 8         | 8      | 5.8%    |
| Transcend           | 6         | 6      | 4.35%   |
| Hitachi             | 5         | 6      | 3.62%   |
| Crucial             | 5         | 5      | 3.62%   |
| Apple               | 5         | 6      | 3.62%   |
| SK hynix            | 4         | 5      | 2.9%    |
| Kingston            | 4         | 4      | 2.9%    |
| Intel               | 4         | 4      | 2.9%    |
| Micron Technology   | 3         | 3      | 2.17%   |
| SPCC                | 2         | 2      | 1.45%   |
| OCZ                 | 2         | 2      | 1.45%   |
| Gigabyte Technology | 2         | 2      | 1.45%   |
| Fujitsu             | 2         | 3      | 1.45%   |
| UMIS                | 1         | 1      | 0.72%   |
| PNY                 | 1         | 1      | 0.72%   |
| Phison              | 1         | 1      | 0.72%   |
| LITEONIT            | 1         | 1      | 0.72%   |
| LITEON              | 1         | 1      | 0.72%   |
| KingDian            | 1         | 1      | 0.72%   |
| Intenso             | 1         | 1      | 0.72%   |
| HGST                | 1         | 1      | 0.72%   |
| Dogfish             | 1         | 1      | 0.72%   |
| Corsair             | 1         | 1      | 0.72%   |
| ASUSTek Computer    | 1         | 2      | 0.72%   |
| AirDisk             | 1         | 1      | 0.72%   |
| A-DATA Technology   | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 2.11%   |
| SanDisk pSSD 16GB                    | 3         | 2.11%   |
| WDC WD2500BEVT-80A23T0 250GB         | 2         | 1.41%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.41%   |
| Seagate ST95005620AS 500GB           | 2         | 1.41%   |
| SanDisk SSD U100 24GB                | 2         | 1.41%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.41%   |
| Kingston SA400S37240G 240GB          | 2         | 1.41%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.41%   |
| Apple SSD SM0512F 500GB              | 2         | 1.41%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.7%    |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.7%    |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.7%    |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.7%    |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.7%    |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.7%    |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.7%    |
| WDC WD2500LPCX-24C6HT0 250GB         | 1         | 0.7%    |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.7%    |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.7%    |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.7%    |
| WDC WD10SMRW-11Y43S0 1TB             | 1         | 0.7%    |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.7%    |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.7%    |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.7%    |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB   | 1         | 0.7%    |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.7%    |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.7%    |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.7%    |
| UMIS RPJTJ256MED1OWX 256GB           | 1         | 0.7%    |
| Transcend TS512GSSD370S 512GB        | 1         | 0.7%    |
| Transcend TS512GSSD230S 512GB        | 1         | 0.7%    |
| Transcend TS240GSSD220S 240GB        | 1         | 0.7%    |
| Transcend TS128GSSD340K 128GB        | 1         | 0.7%    |
| Transcend TS128GSSD340 128GB         | 1         | 0.7%    |
| Transcend TS120GSSD220S 120GB        | 1         | 0.7%    |
| Toshiba TR200 240GB                  | 1         | 0.7%    |
| Toshiba THNSNC128GBSJ                | 1         | 0.7%    |
| Toshiba MQ04ABF100 1TB               | 1         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 15     | 32.61%  |
| Seagate | 13        | 14     | 28.26%  |
| Toshiba | 9         | 9      | 19.57%  |
| Hitachi | 5         | 6      | 10.87%  |
| Fujitsu | 2         | 3      | 4.35%   |
| HGST    | 1         | 1      | 2.17%   |
| Apple   | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 15     | 20.31%  |
| SanDisk             | 8         | 8      | 12.5%   |
| Transcend           | 6         | 6      | 9.38%   |
| Kingston            | 4         | 4      | 6.25%   |
| Crucial             | 4         | 4      | 6.25%   |
| Apple               | 4         | 5      | 6.25%   |
| Toshiba             | 3         | 3      | 4.69%   |
| Intel               | 3         | 3      | 4.69%   |
| WDC                 | 2         | 3      | 3.13%   |
| SPCC                | 2         | 2      | 3.13%   |
| OCZ                 | 2         | 2      | 3.13%   |
| Micron Technology   | 2         | 2      | 3.13%   |
| Gigabyte Technology | 2         | 2      | 3.13%   |
| PNY                 | 1         | 1      | 1.56%   |
| LITEONIT            | 1         | 1      | 1.56%   |
| LITEON              | 1         | 1      | 1.56%   |
| KingDian            | 1         | 1      | 1.56%   |
| Intenso             | 1         | 1      | 1.56%   |
| Dogfish             | 1         | 1      | 1.56%   |
| Corsair             | 1         | 1      | 1.56%   |
| ASUSTek Computer    | 1         | 2      | 1.56%   |
| A-DATA Technology   | 1         | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 60        | 69     | 44.44%  |
| HDD  | 46        | 49     | 34.07%  |
| NVMe | 29        | 34     | 21.48%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 118    | 77.34%  |
| NVMe | 29        | 34     | 22.66%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 90     | 74.04%  |
| 0.51-1.0   | 24        | 25     | 23.08%  |
| 1.01-2.0   | 3         | 3      | 2.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 108       | 80%     |
| 101-250    | 9         | 6.67%   |
| 21-50      | 8         | 5.93%   |
| 251-500    | 4         | 2.96%   |
| 51-100     | 3         | 2.22%   |
| 501-1000   | 2         | 1.48%   |
| 1001-2000  | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 132       | 97.78%  |
| 21-50   | 2         | 1.48%   |
| 51-100  | 1         | 0.74%   |

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


| Model             | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 16GB | 1         | 1      | 100%    |

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
| Works    | 105       | 127    | 82.03%  |
| Malfunc  | 21        | 22     | 16.41%  |
| Detected | 1         | 2      | 0.78%   |
| Failed   | 1         | 1      | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 93        | 62.42%  |
| Samsung Electronics                     | 18        | 12.08%  |
| AMD                                     | 14        | 9.4%    |
| SanDisk                                 | 5         | 3.36%   |
| SK hynix                                | 4         | 2.68%   |
| Nvidia                                  | 3         | 2.01%   |
| KIOXIA                                  | 2         | 1.34%   |
| VIA Technologies                        | 1         | 0.67%   |
| Toshiba                                 | 1         | 0.67%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.67%   |
| Shenzhen Unionmemory Information System | 1         | 0.67%   |
| Phison Electronics                      | 1         | 0.67%   |
| Micron/Crucial Technology               | 1         | 0.67%   |
| Micron Technology                       | 1         | 0.67%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.67%   |
| Kingston Technology Company             | 1         | 0.67%   |
| JMicron Technology                      | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 10%     |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 7.5%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 7.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 6.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 5.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 5%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.88%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 1.25%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 2         | 1.25%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 1.25%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.25%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.25%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.25%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.63%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.63%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.63%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 0.63%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.63%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.63%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 x2 NVMe SSD 256GB         | 1         | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1         | 0.63%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.63%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 0.63%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 93        | 61.18%  |
| NVMe | 34        | 22.37%  |
| IDE  | 15        | 9.87%   |
| RAID | 10        | 6.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 86.67%  |
| AMD    | 18        | 13.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 3.7%    |
| Intel CPU Version                             | 3         | 2.22%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 2.22%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 2.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 2.22%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 2.22%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.48%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.48%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.48%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.48%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.48%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 1.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.48%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.48%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.48%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.74%   |
| Intel Pentium III                             | 1         | 0.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.74%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.74%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.74%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.74%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.74%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.74%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.74%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.74%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.74%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 0.74%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz            | 1         | 0.74%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.74%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 31.85%  |
| Intel Core i7           | 32        | 23.7%   |
| Other                   | 12        | 8.89%   |
| Intel Core i3           | 7         | 5.19%   |
| Intel Core 2 Duo        | 6         | 4.44%   |
| AMD Ryzen 7             | 6         | 4.44%   |
| Intel Atom              | 5         | 3.7%    |
| Intel Pentium           | 3         | 2.22%   |
| AMD A6                  | 3         | 2.22%   |
| Intel Celeron Dual-Core | 2         | 1.48%   |
| Intel Celeron           | 2         | 1.48%   |
| AMD Ryzen 5             | 2         | 1.48%   |
| AMD A8                  | 2         | 1.48%   |
| Intel Xeon              | 1         | 0.74%   |
| Intel Pentium III       | 1         | 0.74%   |
| Intel Genuine           | 1         | 0.74%   |
| Intel Core m5           | 1         | 0.74%   |
| Intel Core i9           | 1         | 0.74%   |
| Intel Core 2            | 1         | 0.74%   |
| Intel Celeron M         | 1         | 0.74%   |
| AMD Ryzen 7 PRO         | 1         | 0.74%   |
| AMD E1                  | 1         | 0.74%   |
| AMD A10                 | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 65        | 48.15%  |
| 4       | 39        | 28.89%  |
| Unknown | 11        | 8.15%   |
| 8       | 5         | 3.7%    |
| 16      | 4         | 2.96%   |
| 6       | 4         | 2.96%   |
| 1       | 4         | 2.96%   |
| 12      | 3         | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 131       | 97.76%  |
| 2       | 2         | 1.49%   |
| Unknown | 1         | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 90        | 66.67%  |
| 1       | 32        | 23.7%   |
| Unknown | 13        | 9.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 20.74%  |
| Haswell       | 18        | 13.33%  |
| Skylake       | 13        | 9.63%   |
| IvyBridge     | 13        | 9.63%   |
| Penryn        | 10        | 7.41%   |
| SandyBridge   | 7         | 5.19%   |
| Unknown       | 7         | 5.19%   |
| Bonnell       | 6         | 4.44%   |
| Zen+          | 4         | 2.96%   |
| Puma          | 4         | 2.96%   |
| TigerLake     | 3         | 2.22%   |
| Core          | 3         | 2.22%   |
| CometLake     | 3         | 2.22%   |
| Broadwell     | 3         | 2.22%   |
| Westmere      | 2         | 1.48%   |
| Silvermont    | 2         | 1.48%   |
| P6            | 2         | 1.48%   |
| Zen 2         | 1         | 0.74%   |
| Steamroller   | 1         | 0.74%   |
| K10 Llano     | 1         | 0.74%   |
| K10           | 1         | 0.74%   |
| Jaguar        | 1         | 0.74%   |
| Goldmont plus | 1         | 0.74%   |
| Excavator     | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 101       | 66.01%  |
| Nvidia           | 25        | 16.34%  |
| AMD              | 25        | 16.34%  |
| VIA Technologies | 1         | 0.65%   |
| S3 Graphics      | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 8.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 7.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 6.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 3.82%   |
| Intel HD Graphics 620                                                                    | 6         | 3.82%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.55%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.91%   |
| AMD Lucienne                                                                             | 3         | 1.91%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 1.27%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 1.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.27%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.27%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.64%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.64%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.64%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.64%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.64%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.64%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.64%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.64%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.64%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.64%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.64%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.64%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.64%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.64%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 74        | 54.81%  |
| 1 x AMD         | 22        | 16.3%   |
| Intel + Nvidia  | 14        | 10.37%  |
| 2 x Intel       | 10        | 7.41%   |
| 1 x Nvidia      | 10        | 7.41%   |
| Intel + AMD     | 2         | 1.48%   |
| 1 x VIA         | 1         | 0.74%   |
| 1 x S3 Graphics | 1         | 0.74%   |
| AMD + Nvidia    | 1         | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 115       | 85.82%  |
| Unknown     | 15        | 11.19%  |
| Proprietary | 4         | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 89.63%  |
| 0.01-0.5   | 6         | 4.44%   |
| 0.51-1.0   | 5         | 3.7%    |
| 1.01-2.0   | 3         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 18.1%   |
| LG Display              | 16        | 15.24%  |
| BOE                     | 15        | 14.29%  |
| Samsung Electronics     | 12        | 11.43%  |
| Chimei Innolux          | 11        | 10.48%  |
| Sharp                   | 5         | 4.76%   |
| Apple                   | 5         | 4.76%   |
| HannStar                | 4         | 3.81%   |
| Chi Mei Optoelectronics | 4         | 3.81%   |
| Lenovo                  | 3         | 2.86%   |
| Panasonic               | 2         | 1.9%    |
| LG Philips              | 1         | 0.95%   |
| Hewlett-Packard         | 1         | 0.95%   |
| Goldstar                | 1         | 0.95%   |
| Dell                    | 1         | 0.95%   |
| CSO                     | 1         | 0.95%   |
| CPT                     | 1         | 0.95%   |
| BenQ                    | 1         | 0.95%   |
| AOC                     | 1         | 0.95%   |
| Acer                    | 1         | 0.95%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 3         | 2.83%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 2         | 1.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 1.89%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 1.89%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.89%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.94%   |
| Sharp LCD Monitor SHP14C2 1920x1080 260x140mm 11.6-inch                  | 1         | 0.94%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.94%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.94%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 0.94%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch     | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.94%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.94%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.94%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.94%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch              | 1         | 0.94%   |
| LG Display LCD Monitor LGD0612 1920x1080 340x190mm 15.3-inch             | 1         | 0.94%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 0.94%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 1         | 0.94%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 0.94%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch             | 1         | 0.94%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 0.94%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 0.94%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch              | 1         | 0.94%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 0.94%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch              | 1         | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 37        | 35.58%  |
| 1366x768 (WXGA)   | 37        | 35.58%  |
| 3840x2160 (4K)    | 5         | 4.81%   |
| 1600x900 (HD+)    | 5         | 4.81%   |
| 1024x600          | 5         | 4.81%   |
| 1440x900 (WXGA+)  | 4         | 3.85%   |
| 1280x800 (WXGA)   | 4         | 3.85%   |
| 2880x1800         | 2         | 1.92%   |
| 3200x1800 (QHD+)  | 1         | 0.96%   |
| 2560x1440 (QHD)   | 1         | 0.96%   |
| 2160x1350         | 1         | 0.96%   |
| 1920x1200 (WUXGA) | 1         | 0.96%   |
| 1280x1024 (SXGA)  | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 41        | 38.68%  |
| 13     | 25        | 23.58%  |
| 12     | 13        | 12.26%  |
| 17     | 9         | 8.49%   |
| 10     | 5         | 4.72%   |
| 11     | 4         | 3.77%   |
| 24     | 3         | 2.83%   |
| 27     | 2         | 1.89%   |
| 23     | 2         | 1.89%   |
| 18     | 1         | 0.94%   |
| 14     | 1         | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 52.83%  |
| 201-300     | 34        | 32.08%  |
| 351-400     | 8         | 7.55%   |
| 501-600     | 6         | 5.66%   |
| 601-700     | 1         | 0.94%   |
| 401-500     | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 86        | 86.87%  |
| 16/10 | 10        | 10.1%   |
| 3/2   | 2         | 2.02%   |
| 5/4   | 1         | 1.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 31        | 29.25%  |
| 81-90          | 19        | 17.92%  |
| 61-70          | 12        | 11.32%  |
| 101-110        | 9         | 8.49%   |
| 71-80          | 8         | 7.55%   |
| 121-130        | 7         | 6.6%    |
| 41-50          | 5         | 4.72%   |
| 201-250        | 5         | 4.72%   |
| 51-60          | 4         | 3.77%   |
| 301-350        | 2         | 1.89%   |
| 141-150        | 2         | 1.89%   |
| 131-140        | 1         | 0.94%   |
| 111-120        | 1         | 0.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 37        | 34.91%  |
| 121-160       | 34        | 32.08%  |
| 161-240       | 15        | 14.15%  |
| 51-100        | 13        | 12.26%  |
| More than 240 | 7         | 6.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 106       | 77.94%  |
| 0     | 25        | 18.38%  |
| 2     | 4         | 2.94%   |
| 3     | 1         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 37.09%  |
| Realtek Semiconductor             | 53        | 24.88%  |
| Qualcomm Atheros                  | 34        | 15.96%  |
| Broadcom                          | 15        | 7.04%   |
| Samsung Electronics               | 4         | 1.88%   |
| TP-Link                           | 3         | 1.41%   |
| Ralink                            | 3         | 1.41%   |
| Marvell Technology Group          | 3         | 1.41%   |
| Sierra Wireless                   | 2         | 0.94%   |
| Ralink Technology                 | 2         | 0.94%   |
| Ericsson Business Mobile Networks | 2         | 0.94%   |
| VIA Technologies                  | 1         | 0.47%   |
| U-Blox                            | 1         | 0.47%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.47%   |
| Qualcomm Technologies             | 1         | 0.47%   |
| Qualcomm                          | 1         | 0.47%   |
| NetGear                           | 1         | 0.47%   |
| MediaTek                          | 1         | 0.47%   |
| JMicron Technology                | 1         | 0.47%   |
| Fibocom                           | 1         | 0.47%   |
| Dell                              | 1         | 0.47%   |
| D-Link                            | 1         | 0.47%   |
| Atheros                           | 1         | 0.47%   |
| Apple                             | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36        | 13.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 4.71%   |
| Intel Wireless 7260                                                    | 10        | 3.62%   |
| Intel Wireless 8260                                                    | 8         | 2.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.9%    |
| Intel Wireless 8265 / 8275                                             | 7         | 2.54%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.81%   |
| Intel Wireless 3165                                                    | 5         | 1.81%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 1.45%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 1.45%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 1.09%   |
| Intel WiFi Link 5100                                                   | 3         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 1.09%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 1.09%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 1.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3         | 1.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.72%   |
| Intel Wireless 7265                                                    | 2         | 0.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 2         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.72%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 50.68%  |
| Qualcomm Atheros      | 29        | 19.86%  |
| Realtek Semiconductor | 19        | 13.01%  |
| Broadcom              | 10        | 6.85%   |
| TP-Link               | 3         | 2.05%   |
| Ralink                | 3         | 2.05%   |
| Ralink Technology     | 2         | 1.37%   |
| Sierra Wireless       | 1         | 0.68%   |
| Qualcomm Technologies | 1         | 0.68%   |
| NetGear               | 1         | 0.68%   |
| MediaTek              | 1         | 0.68%   |
| D-Link                | 1         | 0.68%   |
| Atheros               | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 10        | 6.71%   |
| Intel Wireless 8260                                            | 8         | 5.37%   |
| Intel Wireless 8265 / 8275                                     | 7         | 4.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 3.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 3.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 3.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.36%   |
| Intel Wireless 3165                                            | 5         | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 3.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 3.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.68%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.01%   |
| Intel WiFi Link 5100                                           | 3         | 2.01%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.01%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.01%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 2.01%   |
| Intel Wireless 7265                                            | 2         | 1.34%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.34%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.34%   |
| TP-Link Wireless USB Adapter                                   | 1         | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.67%   |
| Sierra Wireless EM7455                                         | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.67%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller             | 1         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.67%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 0.67%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 0.67%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 49        | 40.83%  |
| Intel                            | 42        | 35%     |
| Broadcom                         | 9         | 7.5%    |
| Qualcomm Atheros                 | 8         | 6.67%   |
| Samsung Electronics              | 4         | 3.33%   |
| Marvell Technology Group         | 3         | 2.5%    |
| VIA Technologies                 | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Qualcomm                         | 1         | 0.83%   |
| JMicron Technology               | 1         | 0.83%   |
| Apple                            | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36        | 29.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 10.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 6.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 4.96%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 4.13%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 3.31%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 3.31%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 2.48%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 2.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.65%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.65%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.65%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.65%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 1.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.83%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.83%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.83%   |
| Qualcomm ALCATEL RNDIS Interface                                       | 1         | 0.83%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.83%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.83%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.83%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.83%   |
| Intel Ethernet Connection (11) I219-V                                  | 1         | 0.83%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller             | 1         | 0.83%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.83%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.83%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 134       | 52.34%  |
| Ethernet | 116       | 45.31%  |
| Unknown  | 5         | 1.95%   |
| Modem    | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 91        | 50.56%  |
| WiFi     | 87        | 48.33%  |
| Unknown  | 2         | 1.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 112       | 82.96%  |
| 1     | 23        | 17.04%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 118       | 87.41%  |
| Yes  | 17        | 12.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 47.52%  |
| Broadcom                        | 9         | 8.91%   |
| Realtek Semiconductor           | 8         | 7.92%   |
| Qualcomm Atheros Communications | 7         | 6.93%   |
| Lite-On Technology              | 6         | 5.94%   |
| Apple                           | 6         | 5.94%   |
| IMC Networks                    | 4         | 3.96%   |
| Foxconn / Hon Hai               | 4         | 3.96%   |
| ASUSTek Computer                | 4         | 3.96%   |
| USI                             | 1         | 0.99%   |
| Hewlett-Packard                 | 1         | 0.99%   |
| Dell                            | 1         | 0.99%   |
| Cambridge Silicon Radio         | 1         | 0.99%   |
| Alps Electric                   | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 26        | 25.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 6.93%   |
| Intel AX201 Bluetooth                                       | 7         | 6.93%   |
| Intel AX200 Bluetooth                                       | 4         | 3.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.96%   |
| Apple Bluetooth Host Controller                             | 4         | 3.96%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.98%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 1.98%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.98%   |
| Intel AX211 Bluetooth                                       | 2         | 1.98%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.98%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.98%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.98%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 1.98%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.98%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.99%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.99%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.99%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.99%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.99%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.99%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.99%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.99%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.99%   |
| Lite-On Bluetooth USB Module                                | 1         | 0.99%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.99%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.99%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.99%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.99%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.99%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.99%   |
| Broadcom Bluetooth 4.0                                      | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 112       | 74.67%  |
| AMD                              | 22        | 14.67%  |
| Nvidia                           | 9         | 6%      |
| VIA Technologies                 | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.67%   |
| Realtek Semiconductor            | 1         | 0.67%   |
| Lenovo                           | 1         | 0.67%   |
| C-Media Electronics              | 1         | 0.67%   |
| Blue Microphones                 | 1         | 0.67%   |
| ASUSTek Computer                 | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 12.77%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 7.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 5.85%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 5.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 3.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.72%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.6%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.6%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.06%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.06%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.53%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.53%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.53%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Gen 2 USB Audio                                                | 1         | 0.53%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 33.13%  |
| SK hynix            | 39        | 23.93%  |
| Micron Technology   | 18        | 11.04%  |
| Unknown             | 11        | 6.75%   |
| Kingston            | 9         | 5.52%   |
| Unknown             | 6         | 3.68%   |
| Elpida              | 4         | 2.45%   |
| Crucial             | 4         | 2.45%   |
| A-DATA Technology   | 4         | 2.45%   |
| Transcend           | 2         | 1.23%   |
| Ramaxel Technology  | 2         | 1.23%   |
| Nanya Technology    | 2         | 1.23%   |
| Corsair             | 2         | 1.23%   |
| 48spaces            | 2         | 1.23%   |
| Unknown (ABCD)      | 1         | 0.61%   |
| Unknown (09D5)      | 1         | 0.61%   |
| Magnum Tech         | 1         | 0.61%   |
| G.Skill             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 7         | 3.98%   |
| Unknown                                                                   | 6         | 3.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 2.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 2.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.7%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 2         | 1.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 1.14%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.14%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 1.14%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 1.14%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s          | 2         | 1.14%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 1.14%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 1.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.14%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 2         | 1.14%   |
| 48spaces RAM 012345678901234567890123456789012345 1GB SODIMM DDR2 800MT/s | 2         | 1.14%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                 | 1         | 0.57%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 512MB SODIMM SDRAM                                     | 1         | 0.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                                | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.57%   |
| Unknown RAM Module 128MB SODIMM SDRAM                                     | 1         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 1         | 0.57%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s                       | 1         | 0.57%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                            | 1         | 0.57%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 667MT/s                         | 1         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                              | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 57        | 42.22%  |
| DDR4    | 44        | 32.59%  |
| DDR2    | 11        | 8.15%   |
| LPDDR3  | 9         | 6.67%   |
| SDRAM   | 4         | 2.96%   |
| LPDDR5  | 3         | 2.22%   |
| LPDDR4  | 2         | 1.48%   |
| Unknown | 2         | 1.48%   |
| RAM     | 1         | 0.74%   |
| DRAM    | 1         | 0.74%   |
| DDR5    | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 122       | 89.71%  |
| Row Of Chips | 7         | 5.15%   |
| Chip         | 4         | 2.94%   |
| Unknown      | 2         | 1.47%   |
| DIMM         | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 57        | 36.54%  |
| 8192  | 50        | 32.05%  |
| 2048  | 27        | 17.31%  |
| 16384 | 13        | 8.33%   |
| 1024  | 4         | 2.56%   |
| 32768 | 3         | 1.92%   |
| 512   | 1         | 0.64%   |
| 128   | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 40        | 27.59%  |
| 2667    | 17        | 11.72%  |
| 2400    | 14        | 9.66%   |
| 2133    | 14        | 9.66%   |
| 3200    | 10        | 6.9%    |
| 1334    | 9         | 6.21%   |
| 1333    | 7         | 4.83%   |
| 1867    | 6         | 4.14%   |
| 667     | 6         | 4.14%   |
| Unknown | 5         | 3.45%   |
| 1067    | 4         | 2.76%   |
| 800     | 4         | 2.76%   |
| 6400    | 3         | 2.07%   |
| 5600    | 1         | 0.69%   |
| 4267    | 1         | 0.69%   |
| 1639    | 1         | 0.69%   |
| 975     | 1         | 0.69%   |
| 533     | 1         | 0.69%   |
| 400     | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Brother HL-L2340D series | 1         | 100%    |

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
| Chicony Electronics                    | 30        | 28.04%  |
| Bison Electronics                      | 15        | 14.02%  |
| Realtek Semiconductor                  | 11        | 10.28%  |
| Sunplus Innovation Technology          | 9         | 8.41%   |
| Suyin                                  | 8         | 7.48%   |
| IMC Networks                           | 8         | 7.48%   |
| Microdia                               | 6         | 5.61%   |
| Lite-On Technology                     | 4         | 3.74%   |
| Silicon Motion                         | 3         | 2.8%    |
| Quanta                                 | 3         | 2.8%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.8%    |
| Z-Star Microelectronics                | 1         | 0.93%   |
| Luxvisions Innotech Limited            | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| Intel                                  | 1         | 0.93%   |
| Genesys Logic                          | 1         | 0.93%   |
| Apple                                  | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 10        | 9.35%   |
| Bison Integrated Camera                                     | 7         | 6.54%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 3.74%   |
| Chicony HD WebCam                                           | 4         | 3.74%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.8%    |
| Microdia Integrated Webcam                                  | 3         | 2.8%    |
| Suyin Acer Crystal Eye webcam                               | 2         | 1.87%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 1.87%   |
| Realtek Lenovo EasyCamera                                   | 2         | 1.87%   |
| Quanta Front Camera                                         | 2         | 1.87%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.87%   |
| Lite-On Integrated Camera                                   | 2         | 1.87%   |
| IMC Networks Realtek PC Camera                              | 2         | 1.87%   |
| IMC Networks EasyCamera                                     | 2         | 1.87%   |
| Chicony FJ Camera                                           | 2         | 1.87%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 1.87%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.87%   |
| Bison SunplusIT Integrated Camera                           | 2         | 1.87%   |
| Z-Star Webcam                                               | 1         | 0.93%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.93%   |
| Suyin Laptop_Integrated_Webcam_3M                           | 1         | 0.93%   |
| Suyin HD WebCam                                             | 1         | 0.93%   |
| Suyin HD Video WebCam                                       | 1         | 0.93%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.93%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.93%   |
| Sunplus Integrated_Webcam_5M                                | 1         | 0.93%   |
| Sunplus Integrated Webcam                                   | 1         | 0.93%   |
| Sunplus Hy HD Camera                                        | 1         | 0.93%   |
| Sunplus Asus Webcam                                         | 1         | 0.93%   |
| Silicon Motion WebCam SCX Series                            | 1         | 0.93%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 0.93%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 0.93%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 0.93%   |
| Realtek USB Camera                                          | 1         | 0.93%   |
| Realtek PC Camera                                           | 1         | 0.93%   |
| Realtek HD Webcam - Realtek                                 | 1         | 0.93%   |
| Quanta Realtek DMFT RGB                                     | 1         | 0.93%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 0.93%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 45.16%  |
| Synaptics                  | 6         | 19.35%  |
| Upek                       | 4         | 12.9%   |
| Shenzhen Goodix Technology | 2         | 6.45%   |
| LighTuning Technology      | 2         | 6.45%   |
| Elan Microelectronics      | 1         | 3.23%   |
| Broadcom                   | 1         | 3.23%   |
| AuthenTec                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 4         | 12.9%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 12.9%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 9.68%   |
| Validity Sensors Synaptics WBDI                                              | 3         | 9.68%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 9.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 6.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 6.45%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 3.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.23%   |
| LighTuning Fingerprint Reader                                                | 1         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.23%   |
| Elan Fingerprint Sensor                                                      | 1         | 3.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.23%   |
| AuthenTec AES1600                                                            | 1         | 3.23%   |
| Unknown                                                                      | 1         | 3.23%   |

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
| 1     | 41        | 29.71%  |
| 2     | 38        | 27.54%  |
| 3     | 23        | 16.67%  |
| 0     | 19        | 13.77%  |
| 4     | 13        | 9.42%   |
| 5     | 2         | 1.45%   |
| 7     | 1         | 0.72%   |
| 6     | 1         | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 92        | 39.15%  |
| Net/wireless             | 42        | 17.87%  |
| Bluetooth                | 33        | 14.04%  |
| Fingerprint reader       | 30        | 12.77%  |
| Card reader              | 22        | 9.36%   |
| Firewire controller      | 11        | 4.68%   |
| Network                  | 2         | 0.85%   |
| Storage/raid             | 1         | 0.43%   |
| Sound                    | 1         | 0.43%   |
| Net/ethernet             | 1         | 0.43%   |

