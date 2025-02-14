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

Total: 195

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook Pro AMD Gen... | [b880be6d5f](https://bsd-hardware.info/?probe=b880be6d5f) | Dec 30, 2024 |
| Apple         | MacBookPro8,1               | [dc3d4a1f8d](https://bsd-hardware.info/?probe=dc3d4a1f8d) | Nov 24, 2024 |
| Acer          | Nitro AN515-42              | [0cd9c4bf36](https://bsd-hardware.info/?probe=0cd9c4bf36) | Nov 11, 2024 |
| HP            | Mini 210-1000               | [2e6b2f7727](https://bsd-hardware.info/?probe=2e6b2f7727) | Nov 08, 2024 |
| HP            | EliteBook 840 G3            | [4e4e2da2fc](https://bsd-hardware.info/?probe=4e4e2da2fc) | Oct 14, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [52ca4ac8cd](https://bsd-hardware.info/?probe=52ca4ac8cd) | Oct 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [402e2d6b51](https://bsd-hardware.info/?probe=402e2d6b51) | Oct 05, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [9ea21fa783](https://bsd-hardware.info/?probe=9ea21fa783) | Sep 26, 2024 |
| MSI           | Prestige 15 A10SC           | [6cdde2a1ab](https://bsd-hardware.info/?probe=6cdde2a1ab) | Sep 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [14457d4dfe](https://bsd-hardware.info/?probe=14457d4dfe) | Sep 19, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c993d0a7ec](https://bsd-hardware.info/?probe=c993d0a7ec) | Sep 18, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [41254dde12](https://bsd-hardware.info/?probe=41254dde12) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [c5e1346269](https://bsd-hardware.info/?probe=c5e1346269) | Sep 14, 2024 |
| HP            | Pavilion dv6500             | [012d5b1541](https://bsd-hardware.info/?probe=012d5b1541) | Sep 10, 2024 |
| HP            | Pavilion dv6500             | [d5fb091f0e](https://bsd-hardware.info/?probe=d5fb091f0e) | Sep 09, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [5c1dfe489a](https://bsd-hardware.info/?probe=5c1dfe489a) | Sep 08, 2024 |
| Acer          | Aspire A514-52              | [69ff95eed9](https://bsd-hardware.info/?probe=69ff95eed9) | Aug 22, 2024 |
| HP            | Victus by Laptop 16-d1xx... | [66efc0232a](https://bsd-hardware.info/?probe=66efc0232a) | Jun 20, 2024 |
| HP            | Pavilion 15                 | [36a75dbcf3](https://bsd-hardware.info/?probe=36a75dbcf3) | Jun 18, 2024 |
| Acer          | TravelMate P653-MG          | [f00a8363c2](https://bsd-hardware.info/?probe=f00a8363c2) | Jun 05, 2024 |
| Dell          | Inspiron 15 3525            | [08918d8cb5](https://bsd-hardware.info/?probe=08918d8cb5) | May 31, 2024 |
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
| NomadBSD 1.3.2    | 34        | 21.66%  |
| NomadBSD 5806f915 | 32        | 20.38%  |
| NomadBSD 20221130 | 27        | 17.2%   |
| NomadBSD 1.4      | 18        | 11.46%  |
| NomadBSD 20240711 | 14        | 8.92%   |
| NomadBSD 20240126 | 7         | 4.46%   |
| NomadBSD 1.3.1    | 7         | 4.46%   |
| NomadBSD 20231013 | 6         | 3.82%   |
| NomadBSD 1.4-RC1  | 6         | 3.82%   |
| NomadBSD 20231121 | 5         | 3.18%   |
| NomadBSD 81e34fc3 | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| NomadBSD | 152       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 145       | 94.77%  |
| i386  | 8         | 5.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 111       | 73.03%  |
| XFCE    | 22        | 14.47%  |
| xinitrc | 8         | 5.26%   |
| GNOME   | 6         | 3.95%   |
| KDE5    | 5         | 3.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 152       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 93        | 61.18%  |
| SDDM | 59        | 38.82%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 51        | 33.12%  |
| Unknown | 24        | 15.58%  |
| en_GB   | 15        | 9.74%   |
| de_DE   | 14        | 9.09%   |
| ru_RU   | 8         | 5.19%   |
| fr_FR   | 7         | 4.55%   |
| es_ES   | 7         | 4.55%   |
| zh_TW   | 5         | 3.25%   |
| zh_CN   | 3         | 1.95%   |
| it_IT   | 3         | 1.95%   |
| fi_FI   | 3         | 1.95%   |
| pl_PL   | 2         | 1.3%    |
| hu_HU   | 2         | 1.3%    |
| en_AU   | 2         | 1.3%    |
| tr_TR   | 1         | 0.65%   |
| sv_SE   | 1         | 0.65%   |
| lt_LT   | 1         | 0.65%   |
| ko_KR   | 1         | 0.65%   |
| de_CH   | 1         | 0.65%   |
| cs_CZ   | 1         | 0.65%   |
| C       | 1         | 0.65%   |
| bg_BG   | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 147       | 96.08%  |
| BIOS | 6         | 3.92%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 119       | 77.78%  |
| Zfs  | 34        | 22.22%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 107       | 69.93%  |
| MBR  | 46        | 30.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 45        | 29.61%  |
| Hewlett-Packard     | 19        | 12.5%   |
| Dell                | 19        | 12.5%   |
| ASUSTek Computer    | 15        | 9.87%   |
| Acer                | 12        | 7.89%   |
| Apple               | 8         | 5.26%   |
| TUXEDO              | 5         | 3.29%   |
| Sony                | 4         | 2.63%   |
| Samsung Electronics | 3         | 1.97%   |
| Fujitsu             | 3         | 1.97%   |
| Notebook            | 2         | 1.32%   |
| MSI                 | 2         | 1.32%   |
| Google              | 2         | 1.32%   |
| Fujitsu Siemens     | 2         | 1.32%   |
| Toshiba             | 1         | 0.66%   |
| Pegatron            | 1         | 0.66%   |
| Panasonic           | 1         | 0.66%   |
| NEC Computers       | 1         | 0.66%   |
| IBM                 | 1         | 0.66%   |
| GEO                 | 1         | 0.66%   |
| eMachines           | 1         | 0.66%   |
| Clevo               | 1         | 0.66%   |
| Chuwi               | 1         | 0.66%   |
| Alienware           | 1         | 0.66%   |
| Unknown             | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                         | 2         | 1.32%   |
| Apple MacBookPro7,1                         | 2         | 1.32%   |
| Unknown                                     | 2         | 1.32%   |
| TUXEDO Pulse 15 Gen2                        | 1         | 0.66%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.66%   |
| TUXEDO InfinityBook S 15 Gen6               | 1         | 0.66%   |
| TUXEDO InfinityBook Pro AMD Gen9            | 1         | 0.66%   |
| Toshiba Satellite C660                      | 1         | 0.66%   |
| Sony VPCM13M1R                              | 1         | 0.66%   |
| Sony VJS122C11L                             | 1         | 0.66%   |
| Sony VJS121C11N                             | 1         | 0.66%   |
| Sony SVE1713S1RW                            | 1         | 0.66%   |
| Samsung N150/N210/N220                      | 1         | 0.66%   |
| Samsung N145P/N250P/N260P                   | 1         | 0.66%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV     | 1         | 0.66%   |
| Pegatron T12Ah                              | 1         | 0.66%   |
| Panasonic CF-C1BD06EFG                      | 1         | 0.66%   |
| Notebook W650DC,DD                          | 1         | 0.66%   |
| Notebook N650DU                             | 1         | 0.66%   |
| NEC Computers PC-GL186Y3AZ                  | 1         | 0.66%   |
| MSI Prestige 15 A10SC                       | 1         | 0.66%   |
| MSI MS-N033                                 | 1         | 0.66%   |
| Lenovo Yoga 710-11IKB 80V6                  | 1         | 0.66%   |
| Lenovo V580 20147                           | 1         | 0.66%   |
| Lenovo ThinkPad X280 20KESB4T00             | 1         | 0.66%   |
| Lenovo ThinkPad X270 20HN006CUS             | 1         | 0.66%   |
| Lenovo ThinkPad X260 20F60093US             | 1         | 0.66%   |
| Lenovo ThinkPad X230 2325IB1                | 1         | 0.66%   |
| Lenovo ThinkPad X230 23255NG                | 1         | 0.66%   |
| Lenovo ThinkPad X230 23205UG                | 1         | 0.66%   |
| Lenovo ThinkPad X201 Tablet 311396U         | 1         | 0.66%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT    | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU    | 1         | 0.66%   |
| Lenovo ThinkPad W541 20EGS04800             | 1         | 0.66%   |
| Lenovo ThinkPad W520 42844DG                | 1         | 0.66%   |
| Lenovo ThinkPad T530 24295VU                | 1         | 0.66%   |
| Lenovo ThinkPad T510 4384FF3                | 1         | 0.66%   |
| Lenovo ThinkPad T490s 20NX000DRT            | 1         | 0.66%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 33        | 21.71%  |
| Dell Latitude              | 10        | 6.58%   |
| Acer Aspire                | 9         | 5.92%   |
| Lenovo IdeaPad             | 6         | 3.95%   |
| HP Pavilion                | 5         | 3.29%   |
| Dell Inspiron              | 4         | 2.63%   |
| HP EliteBook               | 3         | 1.97%   |
| ASUS VivoBook              | 3         | 1.97%   |
| TUXEDO Pulse               | 2         | 1.32%   |
| TUXEDO InfinityBook        | 2         | 1.32%   |
| HP ProBook                 | 2         | 1.32%   |
| HP Laptop                  | 2         | 1.32%   |
| Fujitsu Siemens AMILO      | 2         | 1.32%   |
| Fujitsu LIFEBOOK           | 2         | 1.32%   |
| Dell XPS                   | 2         | 1.32%   |
| Apple MacBookPro8          | 2         | 1.32%   |
| Apple MacBookPro7          | 2         | 1.32%   |
| Unknown                    | 2         | 1.32%   |
| Toshiba Satellite          | 1         | 0.66%   |
| Sony VPCM13M1R             | 1         | 0.66%   |
| Sony VJS122C11L            | 1         | 0.66%   |
| Sony VJS121C11N            | 1         | 0.66%   |
| Sony SVE1713S1RW           | 1         | 0.66%   |
| Samsung N150               | 1         | 0.66%   |
| Samsung N145P              | 1         | 0.66%   |
| Samsung 300E5EV            | 1         | 0.66%   |
| Pegatron T12Ah             | 1         | 0.66%   |
| Panasonic CF-C1BD06EFG     | 1         | 0.66%   |
| Notebook W650DC            | 1         | 0.66%   |
| Notebook N650DU            | 1         | 0.66%   |
| NEC Computers PC-GL186Y3AZ | 1         | 0.66%   |
| MSI Prestige               | 1         | 0.66%   |
| MSI MS-N033                | 1         | 0.66%   |
| Lenovo Yoga                | 1         | 0.66%   |
| Lenovo V580                | 1         | 0.66%   |
| Lenovo Legion              | 1         | 0.66%   |
| Lenovo G570                | 1         | 0.66%   |
| Lenovo G50-70              | 1         | 0.66%   |
| Lenovo G50-45              | 1         | 0.66%   |
| IBM 2647NG8                | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 16        | 10.53%  |
| 2019 | 15        | 9.87%   |
| 2011 | 12        | 7.89%   |
| 2018 | 11        | 7.24%   |
| 2017 | 11        | 7.24%   |
| 2022 | 9         | 5.92%   |
| 2021 | 9         | 5.92%   |
| 2012 | 9         | 5.92%   |
| 2016 | 8         | 5.26%   |
| 2014 | 8         | 5.26%   |
| 2013 | 8         | 5.26%   |
| 2010 | 8         | 5.26%   |
| 2015 | 7         | 4.61%   |
| 2008 | 6         | 3.95%   |
| 2023 | 5         | 3.29%   |
| 2009 | 4         | 2.63%   |
| 2024 | 3         | 1.97%   |
| 2006 | 2         | 1.32%   |
| 2004 | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 152       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 149       | 98.03%  |
| Yes  | 3         | 1.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 59        | 38.56%  |
| 16.01-24.0  | 35        | 22.88%  |
| 4.01-8.0    | 29        | 18.95%  |
| 32.01-64.0  | 12        | 7.84%   |
| 2.01-3.0    | 8         | 5.23%   |
| 64.01-256.0 | 3         | 1.96%   |
| 0.51-1.0    | 3         | 1.96%   |
| 3.01-4.0    | 2         | 1.31%   |
| 24.01-32.0  | 2         | 1.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 75        | 48.08%  |
| 0.51-1.0  | 47        | 30.13%  |
| 1.01-2.0  | 22        | 14.1%   |
| 2.01-3.0  | 7         | 4.49%   |
| 4.01-8.0  | 3         | 1.92%   |
| 3.01-4.0  | 1         | 0.64%   |
| 8.01-16.0 | 1         | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 70.59%  |
| 0      | 22        | 14.38%  |
| 2      | 21        | 13.73%  |
| 3      | 2         | 1.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 66.01%  |
| Yes       | 52        | 33.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 84.97%  |
| No        | 23        | 15.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 99.34%  |
| No        | 1         | 0.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 75.66%  |
| No        | 37        | 24.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 20        | 13.16%  |
| Germany     | 19        | 12.5%   |
| France      | 17        | 11.18%  |
| UK          | 15        | 9.87%   |
| Russia      | 14        | 9.21%   |
| Taiwan      | 5         | 3.29%   |
| Spain       | 5         | 3.29%   |
| Italy       | 5         | 3.29%   |
| Finland     | 4         | 2.63%   |
| Argentina   | 4         | 2.63%   |
| Switzerland | 3         | 1.97%   |
| Norway      | 3         | 1.97%   |
| Mexico      | 3         | 1.97%   |
| Hungary     | 3         | 1.97%   |
| China       | 3         | 1.97%   |
| Australia   | 3         | 1.97%   |
| Turkey      | 2         | 1.32%   |
| Romania     | 2         | 1.32%   |
| Poland      | 2         | 1.32%   |
| Lithuania   | 2         | 1.32%   |
| Japan       | 2         | 1.32%   |
| Egypt       | 2         | 1.32%   |
| Colombia    | 2         | 1.32%   |
| Ukraine     | 1         | 0.66%   |
| Sweden      | 1         | 0.66%   |
| South Korea | 1         | 0.66%   |
| San Marino  | 1         | 0.66%   |
| Philippines | 1         | 0.66%   |
| Indonesia   | 1         | 0.66%   |
| Hong Kong   | 1         | 0.66%   |
| Denmark     | 1         | 0.66%   |
| Czechia     | 1         | 0.66%   |
| Canada      | 1         | 0.66%   |
| Bulgaria    | 1         | 0.66%   |
| Belarus     | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 10        | 6.49%   |
| Franconville                | 6         | 3.9%    |
| Whittier                    | 3         | 1.95%   |
| Tijuana                     | 3         | 1.95%   |
| Taichung                    | 3         | 1.95%   |
| Markt Indersdorf            | 3         | 1.95%   |
| Madrid                      | 3         | 1.95%   |
| Zwingenberg                 | 2         | 1.3%    |
| Vollen                      | 2         | 1.3%    |
| Vilnius                     | 2         | 1.3%    |
| Turku                       | 2         | 1.3%    |
| Taipei                      | 2         | 1.3%    |
| Setagaya-ku                 | 2         | 1.3%    |
| San Nicolás de los Arroyos | 2         | 1.3%    |
| Rome                        | 2         | 1.3%    |
| Nuremberg                   | 2         | 1.3%    |
| New Braunfels               | 2         | 1.3%    |
| Melun                       | 2         | 1.3%    |
| Los Angeles                 | 2         | 1.3%    |
| Istanbul                    | 2         | 1.3%    |
| Hodmezovasarhely            | 2         | 1.3%    |
| Greenwich                   | 2         | 1.3%    |
| Drobeta-Turnu Severin       | 2         | 1.3%    |
| Changzhou                   | 2         | 1.3%    |
| Zurich                      | 1         | 0.65%   |
| Woodland                    | 1         | 0.65%   |
| Wloszczowa                  | 1         | 0.65%   |
| Wissen                      | 1         | 0.65%   |
| Wilhelmshaven               | 1         | 0.65%   |
| West Bromwich               | 1         | 0.65%   |
| Warsaw                      | 1         | 0.65%   |
| Wakefield                   | 1         | 0.65%   |
| Vladimir                    | 1         | 0.65%   |
| Vertou                      | 1         | 0.65%   |
| Vantaa                      | 1         | 0.65%   |
| Vaasa                       | 1         | 0.65%   |
| Urcuit                      | 1         | 0.65%   |
| Ufa                         | 1         | 0.65%   |
| Trieste                     | 1         | 0.65%   |
| Tala                        | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 35     | 18.79%  |
| WDC                 | 20        | 22     | 13.42%  |
| Seagate             | 15        | 16     | 10.07%  |
| Toshiba             | 14        | 14     | 9.4%    |
| SanDisk             | 8         | 8      | 5.37%   |
| Transcend           | 6         | 6      | 4.03%   |
| Crucial             | 6         | 6      | 4.03%   |
| Micron Technology   | 5         | 5      | 3.36%   |
| Hitachi             | 5         | 6      | 3.36%   |
| Apple               | 5         | 6      | 3.36%   |
| SK hynix            | 4         | 5      | 2.68%   |
| Kingston            | 4         | 4      | 2.68%   |
| Intel               | 4         | 4      | 2.68%   |
| Gigabyte Technology | 3         | 3      | 2.01%   |
| Fujitsu             | 3         | 4      | 2.01%   |
| SPCC                | 2         | 2      | 1.34%   |
| OCZ                 | 2         | 2      | 1.34%   |
| Intenso             | 2         | 2      | 1.34%   |
| UMIS                | 1         | 1      | 0.67%   |
| SETHRISE            | 1         | 1      | 0.67%   |
| PNY                 | 1         | 1      | 0.67%   |
| Phison              | 1         | 1      | 0.67%   |
| LITEONIT            | 1         | 1      | 0.67%   |
| LITEON              | 1         | 1      | 0.67%   |
| KingDian            | 1         | 1      | 0.67%   |
| HGST                | 1         | 1      | 0.67%   |
| Dogfish             | 1         | 1      | 0.67%   |
| Corsair             | 1         | 1      | 0.67%   |
| ASUSTek Computer    | 1         | 2      | 0.67%   |
| AirDisk             | 1         | 1      | 0.67%   |
| A-DATA Technology   | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 1.95%   |
| SanDisk pSSD 16GB                    | 3         | 1.95%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.95%   |
| WDC WD2500BEVT-80A23T0 250GB         | 2         | 1.3%    |
| Toshiba MQ04ABF100 1TB               | 2         | 1.3%    |
| Toshiba MQ01ABF050 500GB             | 2         | 1.3%    |
| Seagate ST95005620AS 500GB           | 2         | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.3%    |
| SanDisk SSD U100 24GB                | 2         | 1.3%    |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.3%    |
| Samsung SSD 840 EVO 250GB            | 2         | 1.3%    |
| Kingston SA400S37240G 240GB          | 2         | 1.3%    |
| Apple SSD SM0512F 500GB              | 2         | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.65%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.65%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.65%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.65%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.65%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.65%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.65%   |
| WDC WD2500LPCX-24C6HT0 250GB         | 1         | 0.65%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10SMRW-11Y43S0 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.65%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.65%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB   | 1         | 0.65%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.65%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.65%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.65%   |
| UMIS RPJTJ256MED1OWX 256GB           | 1         | 0.65%   |
| Transcend TS512GSSD370S 512GB        | 1         | 0.65%   |
| Transcend TS512GSSD230S 512GB        | 1         | 0.65%   |
| Transcend TS240GSSD220S 240GB        | 1         | 0.65%   |
| Transcend TS128GSSD340K 128GB        | 1         | 0.65%   |
| Transcend TS128GSSD340 128GB         | 1         | 0.65%   |
| Transcend TS120GSSD220S 120GB        | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 15     | 30%     |
| Seagate | 15        | 16     | 30%     |
| Toshiba | 10        | 10     | 20%     |
| Hitachi | 5         | 6      | 10%     |
| Fujitsu | 3         | 4      | 6%      |
| HGST    | 1         | 1      | 2%      |
| Apple   | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 17     | 19.72%  |
| SanDisk             | 8         | 8      | 11.27%  |
| Transcend           | 6         | 6      | 8.45%   |
| Crucial             | 5         | 5      | 7.04%   |
| Micron Technology   | 4         | 4      | 5.63%   |
| Kingston            | 4         | 4      | 5.63%   |
| Apple               | 4         | 5      | 5.63%   |
| Toshiba             | 3         | 3      | 4.23%   |
| Intel               | 3         | 3      | 4.23%   |
| Gigabyte Technology | 3         | 3      | 4.23%   |
| WDC                 | 2         | 3      | 2.82%   |
| SPCC                | 2         | 2      | 2.82%   |
| OCZ                 | 2         | 2      | 2.82%   |
| Intenso             | 2         | 2      | 2.82%   |
| SETHRISE            | 1         | 1      | 1.41%   |
| PNY                 | 1         | 1      | 1.41%   |
| LITEONIT            | 1         | 1      | 1.41%   |
| LITEON              | 1         | 1      | 1.41%   |
| KingDian            | 1         | 1      | 1.41%   |
| Dogfish             | 1         | 1      | 1.41%   |
| Corsair             | 1         | 1      | 1.41%   |
| ASUSTek Computer    | 1         | 2      | 1.41%   |
| A-DATA Technology   | 1         | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 67        | 77     | 45.89%  |
| HDD  | 50        | 53     | 34.25%  |
| NVMe | 29        | 34     | 19.86%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 108       | 130    | 78.83%  |
| NVMe | 29        | 34     | 21.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 99     | 73.68%  |
| 0.51-1.0   | 26        | 27     | 22.81%  |
| 1.01-2.0   | 4         | 4      | 3.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 117       | 76.47%  |
| 101-250    | 14        | 9.15%   |
| 21-50      | 9         | 5.88%   |
| 51-100     | 5         | 3.27%   |
| 251-500    | 4         | 2.61%   |
| 501-1000   | 3         | 1.96%   |
| 1001-2000  | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 150       | 98.04%  |
| 21-50   | 2         | 1.31%   |
| 51-100  | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 4.35%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 4.35%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 4.35%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 4.35%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 4.35%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 4.35%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 4.35%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 4.35%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 4.35%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 4.35%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 4.35%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 4.35%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 4.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB       | 1         | 1      | 4.35%   |
| Intenso SSD Sata III 248GB                       | 1         | 1      | 4.35%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 4.35%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 2      | 4.35%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 4.35%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 4.35%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 21.74%  |
| Toshiba             | 4         | 4      | 17.39%  |
| Seagate             | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 4      | 13.04%  |
| Micron Technology   | 2         | 2      | 8.7%    |
| SanDisk             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Intenso             | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |
| Corsair             | 1         | 1      | 4.35%   |

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
| HDD  | 16        | 17     | 69.57%  |
| SSD  | 7         | 7      | 30.43%  |

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
| Works    | 113       | 137    | 81.88%  |
| Malfunc  | 23        | 24     | 16.67%  |
| Detected | 1         | 2      | 0.72%   |
| Failed   | 1         | 1      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 102       | 60%     |
| Samsung Electronics                     | 20        | 11.76%  |
| AMD                                     | 16        | 9.41%   |
| Sandisk                                 | 9         | 5.29%   |
| SK hynix                                | 4         | 2.35%   |
| Nvidia                                  | 4         | 2.35%   |
| Micron/Crucial Technology               | 2         | 1.18%   |
| Micron Technology                       | 2         | 1.18%   |
| MAXIO Technology (Hangzhou)             | 2         | 1.18%   |
| KIOXIA                                  | 2         | 1.18%   |
| VIA Technologies                        | 1         | 0.59%   |
| Toshiba                                 | 1         | 0.59%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.59%   |
| Shenzhen Unionmemory Information System | 1         | 0.59%   |
| Phison Electronics                      | 1         | 0.59%   |
| Kingston Technology Company             | 1         | 0.59%   |
| JMicron Technology                      | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 9.34%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 7.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 5.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 5.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 3.3%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.65%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 2         | 1.1%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 2         | 1.1%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 1.1%    |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 2         | 1.1%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 1.1%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 2         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.1%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.1%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.1%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.55%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.55%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.55%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 0.55%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.55%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.55%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 x2 NVMe SSD 256GB         | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 102       | 59.3%   |
| NVMe | 42        | 24.42%  |
| IDE  | 16        | 9.3%    |
| RAID | 12        | 6.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 129       | 84.31%  |
| AMD    | 24        | 15.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 3.27%   |
| Intel CPU Version                             | 3         | 1.96%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.96%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.96%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.96%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.31%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.31%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.31%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 1.31%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.31%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.31%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.31%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.31%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.31%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.31%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 1.31%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 1.31%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 1.31%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.31%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.31%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.65%   |
| Intel Pentium III                             | 1         | 0.65%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.65%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.65%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.65%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.65%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.65%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.65%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.65%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.65%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 45        | 29.41%  |
| Intel Core i7           | 37        | 24.18%  |
| Other                   | 14        | 9.15%   |
| AMD Ryzen 7             | 8         | 5.23%   |
| Intel Core i3           | 7         | 4.58%   |
| Intel Core 2 Duo        | 6         | 3.92%   |
| Intel Atom              | 6         | 3.92%   |
| Intel Celeron           | 4         | 2.61%   |
| AMD Ryzen 5             | 4         | 2.61%   |
| Intel Pentium           | 3         | 1.96%   |
| AMD A6                  | 3         | 1.96%   |
| Intel Celeron Dual-Core | 2         | 1.31%   |
| AMD Ryzen 7 PRO         | 2         | 1.31%   |
| AMD A8                  | 2         | 1.31%   |
| Intel Xeon              | 1         | 0.65%   |
| Intel Pentium III       | 1         | 0.65%   |
| Intel Genuine           | 1         | 0.65%   |
| Intel Core m5           | 1         | 0.65%   |
| Intel Core i9           | 1         | 0.65%   |
| Intel Core 2            | 1         | 0.65%   |
| Intel Celeron M         | 1         | 0.65%   |
| AMD Turion 64 X2 Mobile | 1         | 0.65%   |
| AMD E1                  | 1         | 0.65%   |
| AMD A10                 | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 71        | 46.41%  |
| 4       | 42        | 27.45%  |
| Unknown | 11        | 7.19%   |
| 8       | 7         | 4.58%   |
| 16      | 6         | 3.92%   |
| 6       | 6         | 3.92%   |
| 1       | 5         | 3.27%   |
| 12      | 4         | 2.61%   |
| 20      | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 149       | 98.03%  |
| 2       | 2         | 1.32%   |
| Unknown | 1         | 0.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 101       | 66.01%  |
| 1       | 39        | 25.49%  |
| Unknown | 13        | 8.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 18.95%  |
| Haswell       | 19        | 12.42%  |
| Skylake       | 14        | 9.15%   |
| IvyBridge     | 14        | 9.15%   |
| Unknown       | 11        | 7.19%   |
| Penryn        | 10        | 6.54%   |
| SandyBridge   | 8         | 5.23%   |
| Bonnell       | 7         | 4.58%   |
| CometLake     | 5         | 3.27%   |
| Zen+          | 4         | 2.61%   |
| Puma          | 4         | 2.61%   |
| TigerLake     | 3         | 1.96%   |
| Silvermont    | 3         | 1.96%   |
| Core          | 3         | 1.96%   |
| Broadwell     | 3         | 1.96%   |
| Zen 2         | 2         | 1.31%   |
| Westmere      | 2         | 1.31%   |
| P6            | 2         | 1.31%   |
| Zen 3         | 1         | 0.65%   |
| Zen           | 1         | 0.65%   |
| Steamroller   | 1         | 0.65%   |
| K8 Hammer     | 1         | 0.65%   |
| K10 Llano     | 1         | 0.65%   |
| K10           | 1         | 0.65%   |
| Jaguar        | 1         | 0.65%   |
| Goldmont plus | 1         | 0.65%   |
| Goldmont      | 1         | 0.65%   |
| Excavator     | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 113       | 64.2%   |
| Nvidia           | 31        | 17.61%  |
| AMD              | 30        | 17.05%  |
| VIA Technologies | 1         | 0.57%   |
| S3 Graphics      | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 7.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 6.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 6.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.87%   |
| Intel HD Graphics 620                                                                    | 6         | 3.31%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.76%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 2.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.21%   |
| AMD Lucienne                                                                             | 4         | 2.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.66%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.66%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.66%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 1.1%    |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 1.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.1%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.1%    |
| Intel Comet Lake UHD Graphics                                                            | 2         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.1%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 1.1%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.55%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.55%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.55%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.55%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.55%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.55%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.55%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.55%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.55%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.55%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.55%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 81        | 52.94%  |
| 1 x AMD         | 25        | 16.34%  |
| Intel + Nvidia  | 18        | 11.76%  |
| 2 x Intel       | 11        | 7.19%   |
| 1 x Nvidia      | 11        | 7.19%   |
| Intel + AMD     | 2         | 1.31%   |
| AMD + Nvidia    | 2         | 1.31%   |
| 2 x AMD         | 1         | 0.65%   |
| 1 x VIA         | 1         | 0.65%   |
| 1 x S3 Graphics | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 133       | 87.5%   |
| Unknown     | 15        | 9.87%   |
| Proprietary | 4         | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 89.54%  |
| 0.01-0.5   | 7         | 4.58%   |
| 0.51-1.0   | 5         | 3.27%   |
| 1.01-2.0   | 4         | 2.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 18.85%  |
| LG Display              | 18        | 14.75%  |
| BOE                     | 18        | 14.75%  |
| Samsung Electronics     | 16        | 13.11%  |
| Chimei Innolux          | 13        | 10.66%  |
| Apple                   | 6         | 4.92%   |
| Sharp                   | 5         | 4.1%    |
| HannStar                | 4         | 3.28%   |
| Chi Mei Optoelectronics | 4         | 3.28%   |
| Lenovo                  | 3         | 2.46%   |
| Panasonic               | 2         | 1.64%   |
| LG Philips              | 1         | 0.82%   |
| Hewlett-Packard         | 1         | 0.82%   |
| Goldstar                | 1         | 0.82%   |
| Dell                    | 1         | 0.82%   |
| CSW                     | 1         | 0.82%   |
| CSO                     | 1         | 0.82%   |
| CPT                     | 1         | 0.82%   |
| BenQ                    | 1         | 0.82%   |
| AOC                     | 1         | 0.82%   |
| Acer                    | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 3         | 2.44%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 2         | 1.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 1.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 1.63%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 1.63%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.63%   |
| Apple LCD Monitor APP9CCB 1280x800 290x180mm 13.4-inch                   | 2         | 1.63%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.81%   |
| Sharp LCD Monitor SHP14C2 1920x1080 260x140mm 11.6-inch                  | 1         | 0.81%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.81%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.81%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 0.81%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3152 1024x600 220x130mm 10.1-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 340x190mm 15.3-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 700x390mm 31.5-inch    | 1         | 0.81%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.81%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD0612 1920x1080 340x190mm 15.3-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD05BE 1920x1080 380x210mm 17.1-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 46        | 38.33%  |
| 1366x768 (WXGA)   | 40        | 33.33%  |
| 1280x800 (WXGA)   | 6         | 5%      |
| 1024x600          | 6         | 5%      |
| 3840x2160 (4K)    | 5         | 4.17%   |
| 1600x900 (HD+)    | 5         | 4.17%   |
| 1440x900 (WXGA+)  | 4         | 3.33%   |
| 2880x1800         | 3         | 2.5%    |
| 3200x1800 (QHD+)  | 1         | 0.83%   |
| 2560x1440 (QHD)   | 1         | 0.83%   |
| 2160x1350         | 1         | 0.83%   |
| 1920x1200 (WUXGA) | 1         | 0.83%   |
| 1280x1024 (SXGA)  | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 50        | 40.65%  |
| 13     | 29        | 23.58%  |
| 12     | 13        | 10.57%  |
| 17     | 10        | 8.13%   |
| 10     | 6         | 4.88%   |
| 11     | 4         | 3.25%   |
| 24     | 3         | 2.44%   |
| 27     | 2         | 1.63%   |
| 23     | 2         | 1.63%   |
| 14     | 2         | 1.63%   |
| 31     | 1         | 0.81%   |
| 18     | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 55.28%  |
| 201-300     | 37        | 30.08%  |
| 351-400     | 9         | 7.32%   |
| 501-600     | 6         | 4.88%   |
| 601-700     | 2         | 1.63%   |
| 401-500     | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 99        | 86.09%  |
| 16/10 | 13        | 11.3%   |
| 3/2   | 2         | 1.74%   |
| 5/4   | 1         | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 39        | 31.71%  |
| 81-90          | 24        | 19.51%  |
| 61-70          | 12        | 9.76%   |
| 101-110        | 10        | 8.13%   |
| 71-80          | 8         | 6.5%    |
| 121-130        | 8         | 6.5%    |
| 41-50          | 6         | 4.88%   |
| 201-250        | 5         | 4.07%   |
| 51-60          | 4         | 3.25%   |
| 301-350        | 2         | 1.63%   |
| 141-150        | 2         | 1.63%   |
| 351-500        | 1         | 0.81%   |
| 131-140        | 1         | 0.81%   |
| 111-120        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 43        | 34.96%  |
| 101-120       | 42        | 34.15%  |
| 161-240       | 15        | 12.2%   |
| 51-100        | 15        | 12.2%   |
| More than 240 | 8         | 6.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 121       | 78.57%  |
| 0     | 27        | 17.53%  |
| 2     | 5         | 3.25%   |
| 3     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 86        | 35.68%  |
| Realtek Semiconductor                  | 64        | 26.56%  |
| Qualcomm Atheros                       | 36        | 14.94%  |
| Broadcom                               | 19        | 7.88%   |
| Samsung Electronics                    | 5         | 2.07%   |
| TP-Link                                | 3         | 1.24%   |
| Ralink                                 | 3         | 1.24%   |
| Marvell Technology Group               | 3         | 1.24%   |
| Sierra Wireless                        | 2         | 0.83%   |
| Ralink Technology                      | 2         | 0.83%   |
| MediaTek                               | 2         | 0.83%   |
| Ericsson Business Mobile Networks      | 2         | 0.83%   |
| VIA Technologies                       | 1         | 0.41%   |
| U-Blox                                 | 1         | 0.41%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.41%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.41%   |
| Qualcomm Technologies                  | 1         | 0.41%   |
| Qualcomm                               | 1         | 0.41%   |
| Nvidia                                 | 1         | 0.41%   |
| NetGear                                | 1         | 0.41%   |
| JMicron Technology                     | 1         | 0.41%   |
| Fibocom                                | 1         | 0.41%   |
| Dell                                   | 1         | 0.41%   |
| D-Link                                 | 1         | 0.41%   |
| Atheros                                | 1         | 0.41%   |
| Apple                                  | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 41        | 13.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 5.47%   |
| Intel Wireless 7260                                                    | 10        | 3.22%   |
| Intel Wireless 8260                                                    | 9         | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 2.25%   |
| Intel Wireless 8265 / 8275                                             | 7         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 1.93%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.61%   |
| Intel Wireless 3165                                                    | 5         | 1.61%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.61%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.61%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.29%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.29%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.96%   |
| Intel WiFi Link 5100                                                   | 3         | 0.96%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.96%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 0.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3         | 0.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.64%   |
| Intel Wireless 7265                                                    | 2         | 0.64%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.64%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 2         | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 49.39%  |
| Qualcomm Atheros      | 31        | 18.9%   |
| Realtek Semiconductor | 24        | 14.63%  |
| Broadcom              | 13        | 7.93%   |
| TP-Link               | 3         | 1.83%   |
| Ralink                | 3         | 1.83%   |
| Ralink Technology     | 2         | 1.22%   |
| MediaTek              | 2         | 1.22%   |
| Sierra Wireless       | 1         | 0.61%   |
| Qualcomm Technologies | 1         | 0.61%   |
| NetGear               | 1         | 0.61%   |
| D-Link                | 1         | 0.61%   |
| Atheros               | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 10        | 5.95%   |
| Intel Wireless 8260                                            | 9         | 5.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 4.17%   |
| Intel Wireless 8265 / 8275                                     | 7         | 4.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 2.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.98%   |
| Intel Wireless 3165                                            | 5         | 2.98%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 2.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.79%   |
| Intel WiFi Link 5100                                           | 3         | 1.79%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.79%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.79%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 1.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.19%   |
| Intel Wireless 7265                                            | 2         | 1.19%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 1.19%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.19%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.19%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.19%   |
| TP-Link Wireless USB Adapter                                   | 1         | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.6%    |
| Sierra Wireless EM7455                                         | 1         | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller             | 1         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 58        | 42.65%  |
| Intel                                  | 44        | 32.35%  |
| Broadcom                               | 11        | 8.09%   |
| Qualcomm Atheros                       | 8         | 5.88%   |
| Samsung Electronics                    | 5         | 3.68%   |
| Marvell Technology Group               | 3         | 2.21%   |
| VIA Technologies                       | 1         | 0.74%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.74%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.74%   |
| Qualcomm                               | 1         | 0.74%   |
| Nvidia                                 | 1         | 0.74%   |
| JMicron Technology                     | 1         | 0.74%   |
| Apple                                  | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 41        | 29.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 12.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 5.84%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 4.38%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 3.65%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 3.65%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 2.92%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 2.92%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 2.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.46%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.46%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.46%   |
| Intel Ethernet Connection (11) I219-V                                  | 2         | 1.46%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 1.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.73%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.73%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.73%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.73%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.73%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.73%   |
| Qualcomm ALCATEL RNDIS Interface                                       | 1         | 0.73%   |
| Nvidia MCP65 Ethernet                                                  | 1         | 0.73%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.73%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.73%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.73%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.73%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller             | 1         | 0.73%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 0.73%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                      | 1         | 0.73%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 152       | 52.6%   |
| Ethernet | 131       | 45.33%  |
| Unknown  | 5         | 1.73%   |
| Modem    | 1         | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 51.02%  |
| WiFi     | 94        | 47.96%  |
| Unknown  | 2         | 1.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 126       | 82.35%  |
| 1     | 26        | 16.99%  |
| 3     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 136       | 88.89%  |
| Yes  | 17        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 47.01%  |
| Realtek Semiconductor           | 11        | 9.4%    |
| Lite-On Technology              | 9         | 7.69%   |
| Broadcom                        | 9         | 7.69%   |
| Qualcomm Atheros Communications | 7         | 5.98%   |
| Apple                           | 7         | 5.98%   |
| IMC Networks                    | 5         | 4.27%   |
| Foxconn / Hon Hai               | 4         | 3.42%   |
| ASUSTek Computer                | 4         | 3.42%   |
| USI                             | 1         | 0.85%   |
| Hewlett-Packard                 | 1         | 0.85%   |
| Dell                            | 1         | 0.85%   |
| Chicony Electronics             | 1         | 0.85%   |
| Cambridge Silicon Radio         | 1         | 0.85%   |
| Alps Electric                   | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 27        | 23.08%  |
| Intel AX201 Bluetooth                                       | 9         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 5.98%   |
| Intel AX200 Bluetooth                                       | 5         | 4.27%   |
| Apple Bluetooth Host Controller                             | 5         | 4.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.42%   |
| Lite-On Bluetooth USB Module                                | 3         | 2.56%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.71%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.71%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 1.71%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 1.71%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.71%   |
| Intel AX211 Bluetooth                                       | 2         | 1.71%   |
| Intel AX210 Bluetooth                                       | 2         | 1.71%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.71%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.71%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.71%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 1.71%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.71%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.85%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.85%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.85%   |
| Realtek Bluetooth Adapter                                   | 1         | 0.85%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.85%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.85%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.85%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.85%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.85%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.85%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.85%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.85%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.85%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 124       | 72.51%  |
| AMD                              | 27        | 15.79%  |
| Nvidia                           | 12        | 7.02%   |
| VIA Technologies                 | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Realtek Semiconductor            | 1         | 0.58%   |
| Lenovo                           | 1         | 0.58%   |
| Focusrite-Novation               | 1         | 0.58%   |
| C-Media Electronics              | 1         | 0.58%   |
| Blue Microphones                 | 1         | 0.58%   |
| ASUSTek Computer                 | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 11.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 6.98%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 14        | 6.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 5.58%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 3.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 3.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 3.26%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.4%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.93%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 0.93%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.47%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.47%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 34.05%  |
| SK hynix            | 40        | 21.62%  |
| Micron Technology   | 25        | 13.51%  |
| Unknown             | 12        | 6.49%   |
| Kingston            | 10        | 5.41%   |
| Crucial             | 6         | 3.24%   |
| Unknown             | 6         | 3.24%   |
| Elpida              | 4         | 2.16%   |
| A-DATA Technology   | 4         | 2.16%   |
| Transcend           | 2         | 1.08%   |
| Ramaxel Technology  | 2         | 1.08%   |
| Nanya Technology    | 2         | 1.08%   |
| Corsair             | 2         | 1.08%   |
| 48spaces            | 2         | 1.08%   |
| Unknown (ABCD)      | 1         | 0.54%   |
| Unknown (09D5)      | 1         | 0.54%   |
| Qimonda             | 1         | 0.54%   |
| Magnum Tech         | 1         | 0.54%   |
| G.Skill             | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 7         | 3.54%   |
| Unknown                                                                   | 6         | 3.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 2.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 2.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.52%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.52%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 1.01%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 2         | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 1.01%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.01%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 1.01%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 1.01%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s          | 2         | 1.01%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 1.01%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 1.01%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.01%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.01%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.01%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.01%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 2         | 1.01%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.01%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 2         | 1.01%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.01%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.01%   |
| 48spaces RAM 012345678901234567890123456789012345 1GB SODIMM DDR2 800MT/s | 2         | 1.01%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                 | 1         | 0.51%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                                 | 1         | 0.51%   |
| Unknown RAM Module 512MB SODIMM SDRAM                                     | 1         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 61        | 40.13%  |
| DDR4    | 53        | 34.87%  |
| DDR2    | 13        | 8.55%   |
| LPDDR3  | 9         | 5.92%   |
| SDRAM   | 4         | 2.63%   |
| LPDDR5  | 3         | 1.97%   |
| DDR5    | 3         | 1.97%   |
| LPDDR4  | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| RAM     | 1         | 0.66%   |
| DRAM    | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 139       | 90.85%  |
| Row Of Chips | 7         | 4.58%   |
| Chip         | 4         | 2.61%   |
| Unknown      | 2         | 1.31%   |
| DIMM         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 58        | 32.95%  |
| 4096  | 58        | 32.95%  |
| 2048  | 29        | 16.48%  |
| 16384 | 20        | 11.36%  |
| 1024  | 5         | 2.84%   |
| 32768 | 4         | 2.27%   |
| 512   | 1         | 0.57%   |
| 128   | 1         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 43        | 26.38%  |
| 2667    | 20        | 12.27%  |
| 3200    | 16        | 9.82%   |
| 2133    | 15        | 9.2%    |
| 2400    | 14        | 8.59%   |
| 1334    | 9         | 5.52%   |
| 1333    | 8         | 4.91%   |
| 667     | 8         | 4.91%   |
| 1867    | 6         | 3.68%   |
| Unknown | 5         | 3.07%   |
| 1067    | 4         | 2.45%   |
| 800     | 4         | 2.45%   |
| 6400    | 3         | 1.84%   |
| 5600    | 2         | 1.23%   |
| 4800    | 1         | 0.61%   |
| 4267    | 1         | 0.61%   |
| 1639    | 1         | 0.61%   |
| 975     | 1         | 0.61%   |
| 533     | 1         | 0.61%   |
| 400     | 1         | 0.61%   |

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
| Chicony Electronics                    | 32        | 26.45%  |
| Bison Electronics                      | 16        | 13.22%  |
| Realtek Semiconductor                  | 11        | 9.09%   |
| Sunplus Innovation Technology          | 10        | 8.26%   |
| Suyin                                  | 9         | 7.44%   |
| IMC Networks                           | 9         | 7.44%   |
| Microdia                               | 7         | 5.79%   |
| Quanta                                 | 4         | 3.31%   |
| Lite-On Technology                     | 4         | 3.31%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.31%   |
| Silicon Motion                         | 3         | 2.48%   |
| Logitech                               | 2         | 1.65%   |
| Apple                                  | 2         | 1.65%   |
| Z-Star Microelectronics                | 1         | 0.83%   |
| Syntek                                 | 1         | 0.83%   |
| Supreme Electronics                    | 1         | 0.83%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.83%   |
| Luxvisions Innotech Limited            | 1         | 0.83%   |
| Intel                                  | 1         | 0.83%   |
| Genesys Logic                          | 1         | 0.83%   |
| Alcor Micro                            | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 11        | 9.09%   |
| Bison Integrated Camera                                     | 7         | 5.79%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 3.31%   |
| Chicony HD WebCam                                           | 4         | 3.31%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.48%   |
| Microdia Integrated_Webcam_HD                               | 3         | 2.48%   |
| Microdia Integrated Webcam                                  | 3         | 2.48%   |
| Suyin Acer Crystal Eye webcam                               | 2         | 1.65%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 1.65%   |
| Realtek Lenovo EasyCamera                                   | 2         | 1.65%   |
| Quanta Front Camera                                         | 2         | 1.65%   |
| Logitech HD Pro Webcam C920                                 | 2         | 1.65%   |
| Lite-On Integrated Camera                                   | 2         | 1.65%   |
| IMC Networks Realtek PC Camera                              | 2         | 1.65%   |
| IMC Networks Integrated Camera                              | 2         | 1.65%   |
| IMC Networks EasyCamera                                     | 2         | 1.65%   |
| Chicony FJ Camera                                           | 2         | 1.65%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 1.65%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.65%   |
| Bison SunplusIT Integrated Camera                           | 2         | 1.65%   |
| Bison EasyCamera                                            | 2         | 1.65%   |
| Apple FaceTime HD Camera                                    | 2         | 1.65%   |
| Z-Star Webcam                                               | 1         | 0.83%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.83%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.83%   |
| Suyin Laptop_Integrated_Webcam_3M                           | 1         | 0.83%   |
| Suyin HP Webcam-50                                          | 1         | 0.83%   |
| Suyin HD WebCam                                             | 1         | 0.83%   |
| Suyin HD Video WebCam                                       | 1         | 0.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.83%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.83%   |
| Supreme Integrated Camera                                   | 1         | 0.83%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.83%   |
| Sunplus Integrated Webcam                                   | 1         | 0.83%   |
| Sunplus Hy HD Camera                                        | 1         | 0.83%   |
| Sunplus HD WebCam                                           | 1         | 0.83%   |
| Sunplus Asus Webcam                                         | 1         | 0.83%   |
| Sunplus 2-USB 2.0 Camera                                    | 1         | 0.83%   |
| Silicon Motion WebCam SCX Series                            | 1         | 0.83%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 40%     |
| Synaptics                  | 9         | 25.71%  |
| Upek                       | 4         | 11.43%  |
| LighTuning Technology      | 3         | 8.57%   |
| Shenzhen Goodix Technology | 2         | 5.71%   |
| Elan Microelectronics      | 1         | 2.86%   |
| Broadcom                   | 1         | 2.86%   |
| AuthenTec                  | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 4         | 11.43%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 11.43%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 8.57%   |
| Validity Sensors Synaptics WBDI                                              | 3         | 8.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 5.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 5.71%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 2.86%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 1         | 2.86%   |
| LighTuning Fingerprint Reader                                                | 1         | 2.86%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2.86%   |
| Elan Fingerprint Sensor                                                      | 1         | 2.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.86%   |
| AuthenTec AES1600                                                            | 1         | 2.86%   |
| Unknown                                                                      | 1         | 2.86%   |

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
| 1     | 45        | 28.85%  |
| 2     | 44        | 28.21%  |
| 3     | 25        | 16.03%  |
| 0     | 21        | 13.46%  |
| 4     | 16        | 10.26%  |
| 5     | 3         | 1.92%   |
| 7     | 1         | 0.64%   |
| 6     | 1         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 103       | 38.29%  |
| Net/wireless             | 48        | 17.84%  |
| Bluetooth                | 39        | 14.5%   |
| Fingerprint reader       | 34        | 12.64%  |
| Card reader              | 26        | 9.67%   |
| Firewire controller      | 13        | 4.83%   |
| Network                  | 2         | 0.74%   |
| Net/ethernet             | 2         | 0.74%   |
| Storage/raid             | 1         | 0.37%   |
| Sound                    | 1         | 0.37%   |

