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

Total: 213

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5ce21a2637](https://bsd-hardware.info/?probe=5ce21a2637) | Oct 06, 2025 |
| Acer          | Aspire E5-575G              | [f0511fe814](https://bsd-hardware.info/?probe=f0511fe814) | Sep 14, 2025 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [0b3f5f2e3b](https://bsd-hardware.info/?probe=0b3f5f2e3b) | Sep 01, 2025 |
| ASUSTek       | BU403UA                     | [e654f9bd9f](https://bsd-hardware.info/?probe=e654f9bd9f) | Aug 19, 2025 |
| ASUSTek       | BU403UA                     | [dde40f3528](https://bsd-hardware.info/?probe=dde40f3528) | Aug 17, 2025 |
| Dell          | XPS 9320                    | [6fce7f517f](https://bsd-hardware.info/?probe=6fce7f517f) | Jul 18, 2025 |
| Lenovo        | ThinkPad T430 2347H76       | [74c977c0d0](https://bsd-hardware.info/?probe=74c977c0d0) | Jul 06, 2025 |
| Dell          | Latitude 5510               | [1aa765fb61](https://bsd-hardware.info/?probe=1aa765fb61) | Jul 04, 2025 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [153e453fda](https://bsd-hardware.info/?probe=153e453fda) | Mar 22, 2025 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [98729678c4](https://bsd-hardware.info/?probe=98729678c4) | Mar 22, 2025 |
| Dell          | Latitude 7430               | [891c106bce](https://bsd-hardware.info/?probe=891c106bce) | Mar 10, 2025 |
| ASUSTek       | X550JK                      | [fad19d4674](https://bsd-hardware.info/?probe=fad19d4674) | Mar 07, 2025 |
| Dell          | Inspiron N5010              | [8f006ed1f6](https://bsd-hardware.info/?probe=8f006ed1f6) | Feb 09, 2025 |
| Apple         | MacBook4,1                  | [f28a86fa7b](https://bsd-hardware.info/?probe=f28a86fa7b) | Feb 08, 2025 |
| Lenovo        | ThinkPad T470s 20HGS10F0... | [88bd5e9c42](https://bsd-hardware.info/?probe=88bd5e9c42) | Jan 21, 2025 |
| Apple         | MacBookPro9,2               | [6440069298](https://bsd-hardware.info/?probe=6440069298) | Jan 18, 2025 |
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
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [dab0ca2417](https://bsd-hardware.info/?probe=dab0ca2417) | Jun 01, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [96cc0c27b0](https://bsd-hardware.info/?probe=96cc0c27b0) | May 25, 2021 |
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
| NomadBSD 1.3.2    | 34        | 19.77%  |
| NomadBSD 5806f915 | 33        | 19.19%  |
| NomadBSD 20240711 | 28        | 16.28%  |
| NomadBSD 20221130 | 27        | 15.7%   |
| NomadBSD 1.4      | 18        | 10.47%  |
| NomadBSD 20240126 | 7         | 4.07%   |
| NomadBSD 1.3.1    | 7         | 4.07%   |
| NomadBSD 20231013 | 6         | 3.49%   |
| NomadBSD 1.4-RC1  | 6         | 3.49%   |
| NomadBSD 20231121 | 5         | 2.91%   |
| NomadBSD 81e34fc3 | 1         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| NomadBSD | 167       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 160       | 95.24%  |
| i386  | 8         | 4.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 112       | 67.07%  |
| XFCE    | 36        | 21.56%  |
| xinitrc | 8         | 4.79%   |
| GNOME   | 6         | 3.59%   |
| KDE5    | 5         | 2.99%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 167       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 94        | 56.29%  |
| SDDM | 73        | 43.71%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 55        | 32.35%  |
| Unknown | 24        | 14.12%  |
| en_GB   | 17        | 10%     |
| de_DE   | 15        | 8.82%   |
| ru_RU   | 9         | 5.29%   |
| fr_FR   | 7         | 4.12%   |
| es_ES   | 7         | 4.12%   |
| zh_TW   | 5         | 2.94%   |
| zh_CN   | 4         | 2.35%   |
| fi_FI   | 4         | 2.35%   |
| it_IT   | 3         | 1.76%   |
| de_CH   | 3         | 1.76%   |
| tr_TR   | 2         | 1.18%   |
| pl_PL   | 2         | 1.18%   |
| hu_HU   | 2         | 1.18%   |
| en_AU   | 2         | 1.18%   |
| C       | 2         | 1.18%   |
| sv_SE   | 1         | 0.59%   |
| lt_LT   | 1         | 0.59%   |
| ko_KR   | 1         | 0.59%   |
| en_CA   | 1         | 0.59%   |
| de_AT   | 1         | 0.59%   |
| cs_CZ   | 1         | 0.59%   |
| bg_BG   | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 162       | 96.43%  |
| BIOS | 6         | 3.57%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 129       | 76.79%  |
| Zfs  | 39        | 23.21%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 120       | 71.43%  |
| MBR  | 48        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 29.34%  |
| Dell                | 23        | 13.77%  |
| Hewlett-Packard     | 19        | 11.38%  |
| ASUSTek Computer    | 19        | 11.38%  |
| Acer                | 13        | 7.78%   |
| Apple               | 10        | 5.99%   |
| TUXEDO              | 5         | 2.99%   |
| Sony                | 4         | 2.4%    |
| Samsung Electronics | 3         | 1.8%    |
| Fujitsu             | 3         | 1.8%    |
| Notebook            | 2         | 1.2%    |
| MSI                 | 2         | 1.2%    |
| Google              | 2         | 1.2%    |
| Fujitsu Siemens     | 2         | 1.2%    |
| Toshiba             | 1         | 0.6%    |
| Pegatron            | 1         | 0.6%    |
| Panasonic           | 1         | 0.6%    |
| NEC Computers       | 1         | 0.6%    |
| IBM                 | 1         | 0.6%    |
| GEO                 | 1         | 0.6%    |
| eMachines           | 1         | 0.6%    |
| Clevo               | 1         | 0.6%    |
| Chuwi               | 1         | 0.6%    |
| Alienware           | 1         | 0.6%    |
| Unknown             | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                         | 2         | 1.2%    |
| Apple MacBookPro7,1                         | 2         | 1.2%    |
| Acer Aspire E5-575G                         | 2         | 1.2%    |
| Unknown                                     | 2         | 1.2%    |
| TUXEDO Pulse 15 Gen2                        | 1         | 0.6%    |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.6%    |
| TUXEDO InfinityBook S 15 Gen6               | 1         | 0.6%    |
| TUXEDO InfinityBook Pro AMD Gen9            | 1         | 0.6%    |
| Toshiba Satellite C660                      | 1         | 0.6%    |
| Sony VPCM13M1R                              | 1         | 0.6%    |
| Sony VJS122C11L                             | 1         | 0.6%    |
| Sony VJS121C11N                             | 1         | 0.6%    |
| Sony SVE1713S1RW                            | 1         | 0.6%    |
| Samsung N150/N210/N220                      | 1         | 0.6%    |
| Samsung N145P/N250P/N260P                   | 1         | 0.6%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV     | 1         | 0.6%    |
| Pegatron T12Ah                              | 1         | 0.6%    |
| Panasonic CF-C1BD06EFG                      | 1         | 0.6%    |
| Notebook W650DC,DD                          | 1         | 0.6%    |
| Notebook N650DU                             | 1         | 0.6%    |
| NEC Computers PC-GL186Y3AZ                  | 1         | 0.6%    |
| MSI Prestige 15 A10SC                       | 1         | 0.6%    |
| MSI MS-N033                                 | 1         | 0.6%    |
| Lenovo Yoga 710-11IKB 80V6                  | 1         | 0.6%    |
| Lenovo V580 20147                           | 1         | 0.6%    |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK        | 1         | 0.6%    |
| Lenovo ThinkPad X280 20KESB4T00             | 1         | 0.6%    |
| Lenovo ThinkPad X270 20HN006CUS             | 1         | 0.6%    |
| Lenovo ThinkPad X260 20F60093US             | 1         | 0.6%    |
| Lenovo ThinkPad X230 2325IB1                | 1         | 0.6%    |
| Lenovo ThinkPad X230 23255NG                | 1         | 0.6%    |
| Lenovo ThinkPad X230 23205UG                | 1         | 0.6%    |
| Lenovo ThinkPad X201 Tablet 311396U         | 1         | 0.6%    |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT    | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU    | 1         | 0.6%    |
| Lenovo ThinkPad W541 20EGS04800             | 1         | 0.6%    |
| Lenovo ThinkPad W520 42844DG                | 1         | 0.6%    |
| Lenovo ThinkPad T530 24295VU                | 1         | 0.6%    |
| Lenovo ThinkPad T510 4384FF3                | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 37        | 22.16%  |
| Dell Latitude              | 12        | 7.19%   |
| Acer Aspire                | 10        | 5.99%   |
| Lenovo IdeaPad             | 6         | 3.59%   |
| HP Pavilion                | 5         | 2.99%   |
| Dell Inspiron              | 5         | 2.99%   |
| HP EliteBook               | 3         | 1.8%    |
| Dell XPS                   | 3         | 1.8%    |
| ASUS VivoBook              | 3         | 1.8%    |
| TUXEDO Pulse               | 2         | 1.2%    |
| TUXEDO InfinityBook        | 2         | 1.2%    |
| HP ProBook                 | 2         | 1.2%    |
| HP Laptop                  | 2         | 1.2%    |
| Fujitsu Siemens AMILO      | 2         | 1.2%    |
| Fujitsu LIFEBOOK           | 2         | 1.2%    |
| Apple MacBookPro8          | 2         | 1.2%    |
| Apple MacBookPro7          | 2         | 1.2%    |
| Unknown                    | 2         | 1.2%    |
| Toshiba Satellite          | 1         | 0.6%    |
| Sony VPCM13M1R             | 1         | 0.6%    |
| Sony VJS122C11L            | 1         | 0.6%    |
| Sony VJS121C11N            | 1         | 0.6%    |
| Sony SVE1713S1RW           | 1         | 0.6%    |
| Samsung N150               | 1         | 0.6%    |
| Samsung N145P              | 1         | 0.6%    |
| Samsung 300E5EV            | 1         | 0.6%    |
| Pegatron T12Ah             | 1         | 0.6%    |
| Panasonic CF-C1BD06EFG     | 1         | 0.6%    |
| Notebook W650DC            | 1         | 0.6%    |
| Notebook N650DU            | 1         | 0.6%    |
| NEC Computers PC-GL186Y3AZ | 1         | 0.6%    |
| MSI Prestige               | 1         | 0.6%    |
| MSI MS-N033                | 1         | 0.6%    |
| Lenovo Yoga                | 1         | 0.6%    |
| Lenovo V580                | 1         | 0.6%    |
| Lenovo Legion              | 1         | 0.6%    |
| Lenovo G570                | 1         | 0.6%    |
| Lenovo G50-70              | 1         | 0.6%    |
| Lenovo G50-45              | 1         | 0.6%    |
| IBM 2647NG8                | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 17        | 10.18%  |
| 2019 | 16        | 9.58%   |
| 2017 | 13        | 7.78%   |
| 2011 | 12        | 7.19%   |
| 2021 | 11        | 6.59%   |
| 2018 | 11        | 6.59%   |
| 2022 | 10        | 5.99%   |
| 2014 | 10        | 5.99%   |
| 2012 | 10        | 5.99%   |
| 2010 | 9         | 5.39%   |
| 2016 | 8         | 4.79%   |
| 2013 | 8         | 4.79%   |
| 2015 | 7         | 4.19%   |
| 2008 | 7         | 4.19%   |
| 2023 | 6         | 3.59%   |
| 2024 | 5         | 2.99%   |
| 2009 | 4         | 2.4%    |
| 2006 | 2         | 1.2%    |
| 2004 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 167       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 98.2%   |
| Yes  | 3         | 1.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 63        | 37.5%   |
| 16.01-24.0  | 41        | 24.4%   |
| 4.01-8.0    | 31        | 18.45%  |
| 32.01-64.0  | 14        | 8.33%   |
| 2.01-3.0    | 9         | 5.36%   |
| 64.01-256.0 | 3         | 1.79%   |
| 0.51-1.0    | 3         | 1.79%   |
| 3.01-4.0    | 2         | 1.19%   |
| 24.01-32.0  | 2         | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 80        | 46.78%  |
| 0.51-1.0  | 53        | 30.99%  |
| 1.01-2.0  | 26        | 15.2%   |
| 2.01-3.0  | 7         | 4.09%   |
| 4.01-8.0  | 3         | 1.75%   |
| 3.01-4.0  | 1         | 0.58%   |
| 8.01-16.0 | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 67.46%  |
| 0      | 29        | 17.16%  |
| 2      | 24        | 14.2%   |
| 3      | 2         | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 66.07%  |
| Yes       | 57        | 33.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 84.52%  |
| No        | 26        | 15.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 99.4%   |
| No        | 1         | 0.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 76.65%  |
| No        | 39        | 23.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 22        | 13.17%  |
| Germany      | 21        | 12.57%  |
| France       | 17        | 10.18%  |
| UK           | 16        | 9.58%   |
| Russia       | 15        | 8.98%   |
| Taiwan       | 5         | 2.99%   |
| Switzerland  | 5         | 2.99%   |
| Spain        | 5         | 2.99%   |
| Italy        | 5         | 2.99%   |
| Finland      | 5         | 2.99%   |
| Argentina    | 4         | 2.4%    |
| Turkey       | 3         | 1.8%    |
| Norway       | 3         | 1.8%    |
| Mexico       | 3         | 1.8%    |
| Hungary      | 3         | 1.8%    |
| China        | 3         | 1.8%    |
| Australia    | 3         | 1.8%    |
| Romania      | 2         | 1.2%    |
| Poland       | 2         | 1.2%    |
| Lithuania    | 2         | 1.2%    |
| Japan        | 2         | 1.2%    |
| Egypt        | 2         | 1.2%    |
| Colombia     | 2         | 1.2%    |
| Canada       | 2         | 1.2%    |
| Bulgaria     | 2         | 1.2%    |
| Ukraine      | 1         | 0.6%    |
| Sweden       | 1         | 0.6%    |
| South Korea  | 1         | 0.6%    |
| Slovenia     | 1         | 0.6%    |
| Saudi Arabia | 1         | 0.6%    |
| San Marino   | 1         | 0.6%    |
| Philippines  | 1         | 0.6%    |
| Indonesia    | 1         | 0.6%    |
| Hong Kong    | 1         | 0.6%    |
| Denmark      | 1         | 0.6%    |
| Czechia      | 1         | 0.6%    |
| Belarus      | 1         | 0.6%    |
| Austria      | 1         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 10        | 5.92%   |
| Franconville                | 6         | 3.55%   |
| Zurich                      | 3         | 1.78%   |
| Whittier                    | 3         | 1.78%   |
| Tijuana                     | 3         | 1.78%   |
| Taichung                    | 3         | 1.78%   |
| Markt Indersdorf            | 3         | 1.78%   |
| Madrid                      | 3         | 1.78%   |
| Istanbul                    | 3         | 1.78%   |
| Zwingenberg                 | 2         | 1.18%   |
| Vollen                      | 2         | 1.18%   |
| Vilnius                     | 2         | 1.18%   |
| Turku                       | 2         | 1.18%   |
| Taipei                      | 2         | 1.18%   |
| Setagaya-ku                 | 2         | 1.18%   |
| San Nicolás de los Arroyos | 2         | 1.18%   |
| Rome                        | 2         | 1.18%   |
| Portland                    | 2         | 1.18%   |
| Nuremberg                   | 2         | 1.18%   |
| New Braunfels               | 2         | 1.18%   |
| Munich                      | 2         | 1.18%   |
| Melun                       | 2         | 1.18%   |
| Los Angeles                 | 2         | 1.18%   |
| Hodmezovasarhely            | 2         | 1.18%   |
| Greenwich                   | 2         | 1.18%   |
| Drobeta-Turnu Severin       | 2         | 1.18%   |
| Changzhou                   | 2         | 1.18%   |
| Woodland                    | 1         | 0.59%   |
| Wloszczowa                  | 1         | 0.59%   |
| Wissen                      | 1         | 0.59%   |
| Wilhelmshaven               | 1         | 0.59%   |
| West Bromwich               | 1         | 0.59%   |
| Warsaw                      | 1         | 0.59%   |
| Wakefield                   | 1         | 0.59%   |
| Vladimir                    | 1         | 0.59%   |
| Vertou                      | 1         | 0.59%   |
| Vantaa                      | 1         | 0.59%   |
| Vaasa                       | 1         | 0.59%   |
| Urcuit                      | 1         | 0.59%   |
| Ufa                         | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 35     | 17.5%   |
| WDC                 | 21        | 23     | 13.13%  |
| Seagate             | 18        | 19     | 11.25%  |
| Toshiba             | 15        | 16     | 9.38%   |
| SanDisk             | 8         | 8      | 5%      |
| Transcend           | 6         | 6      | 3.75%   |
| Micron Technology   | 6         | 6      | 3.75%   |
| Kingston            | 6         | 6      | 3.75%   |
| Hitachi             | 6         | 7      | 3.75%   |
| Crucial             | 6         | 6      | 3.75%   |
| Apple               | 6         | 7      | 3.75%   |
| SK hynix            | 4         | 5      | 2.5%    |
| Intel               | 4         | 4      | 2.5%    |
| Gigabyte Technology | 3         | 3      | 1.88%   |
| Fujitsu             | 3         | 4      | 1.88%   |
| SPCC                | 2         | 2      | 1.25%   |
| OCZ                 | 2         | 2      | 1.25%   |
| LITEONIT            | 2         | 2      | 1.25%   |
| Intenso             | 2         | 2      | 1.25%   |
| UMIS                | 1         | 1      | 0.63%   |
| SETHRISE            | 1         | 1      | 0.63%   |
| PNY                 | 1         | 1      | 0.63%   |
| Phison              | 1         | 1      | 0.63%   |
| LITEON              | 1         | 1      | 0.63%   |
| KingDian            | 1         | 1      | 0.63%   |
| HGST                | 1         | 1      | 0.63%   |
| Dogfish             | 1         | 1      | 0.63%   |
| Corsair             | 1         | 1      | 0.63%   |
| ASUSTek Computer    | 1         | 2      | 0.63%   |
| AirDisk             | 1         | 1      | 0.63%   |
| A-DATA Technology   | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 1.82%   |
| SanDisk pSSD 32GB                    | 3         | 1.82%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.82%   |
| WDC WD2500BEVT-80A23T0 250GB         | 2         | 1.21%   |
| Toshiba MQ04ABF100 1TB               | 2         | 1.21%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.21%   |
| Seagate ST95005620AS 500GB           | 2         | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.21%   |
| SanDisk SSD U100 24GB                | 2         | 1.21%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.21%   |
| Samsung SSD 840 EVO 250GB            | 2         | 1.21%   |
| Kingston SA400S37240G 240GB          | 2         | 1.21%   |
| Apple SSD SM0512F 500GB              | 2         | 1.21%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.61%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.61%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.61%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.61%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.61%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 1         | 0.61%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.61%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.61%   |
| WDC WD2500LPCX-24C6HT0 250GB         | 1         | 0.61%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.61%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.61%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.61%   |
| WDC WD10SMRW-11Y43S0 1TB             | 1         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.61%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.61%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.61%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB   | 1         | 0.61%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.61%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.61%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.61%   |
| UMIS RPJTJ256MED1OWX 256GB           | 1         | 0.61%   |
| Transcend TS512GSSD370S 512GB        | 1         | 0.61%   |
| Transcend TS512GSSD230S 512GB        | 1         | 0.61%   |
| Transcend TS240GSSD220S 240GB        | 1         | 0.61%   |
| Transcend TS128GSSD340K 128GB        | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 19     | 32.14%  |
| WDC     | 16        | 16     | 28.57%  |
| Toshiba | 10        | 10     | 17.86%  |
| Hitachi | 6         | 7      | 10.71%  |
| Fujitsu | 3         | 4      | 5.36%   |
| Apple   | 2         | 2      | 3.57%   |
| HGST    | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 17     | 18.67%  |
| SanDisk             | 8         | 8      | 10.67%  |
| Transcend           | 6         | 6      | 8%      |
| Kingston            | 6         | 6      | 8%      |
| Micron Technology   | 5         | 5      | 6.67%   |
| Crucial             | 5         | 5      | 6.67%   |
| Apple               | 4         | 5      | 5.33%   |
| Toshiba             | 3         | 3      | 4%      |
| Intel               | 3         | 3      | 4%      |
| Gigabyte Technology | 3         | 3      | 4%      |
| WDC                 | 2         | 3      | 2.67%   |
| SPCC                | 2         | 2      | 2.67%   |
| OCZ                 | 2         | 2      | 2.67%   |
| LITEONIT            | 2         | 2      | 2.67%   |
| Intenso             | 2         | 2      | 2.67%   |
| SETHRISE            | 1         | 1      | 1.33%   |
| PNY                 | 1         | 1      | 1.33%   |
| LITEON              | 1         | 1      | 1.33%   |
| KingDian            | 1         | 1      | 1.33%   |
| Dogfish             | 1         | 1      | 1.33%   |
| Corsair             | 1         | 1      | 1.33%   |
| ASUSTek Computer    | 1         | 2      | 1.33%   |
| A-DATA Technology   | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 70        | 81     | 44.87%  |
| HDD  | 56        | 59     | 35.9%   |
| NVMe | 30        | 36     | 19.23%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 116       | 140    | 79.45%  |
| NVMe | 30        | 36     | 20.55%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 106    | 72.95%  |
| 0.51-1.0   | 28        | 29     | 22.95%  |
| 1.01-2.0   | 5         | 5      | 4.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 126       | 75%     |
| 101-250    | 15        | 8.93%   |
| 21-50      | 11        | 6.55%   |
| 251-500    | 6         | 3.57%   |
| 51-100     | 6         | 3.57%   |
| 501-1000   | 3         | 1.79%   |
| 1001-2000  | 1         | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 165       | 98.21%  |
| 21-50   | 2         | 1.19%   |
| 51-100  | 1         | 0.6%    |

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
| SanDisk pSSD 32GB | 1         | 1      | 100%    |

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
| Works    | 120       | 148    | 82.19%  |
| Malfunc  | 23        | 24     | 15.75%  |
| Detected | 2         | 3      | 1.37%   |
| Failed   | 1         | 1      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 110       | 58.82%  |
| Samsung Electronics                     | 21        | 11.23%  |
| AMD                                     | 17        | 9.09%   |
| SanDisk                                 | 11        | 5.88%   |
| SK hynix                                | 5         | 2.67%   |
| Nvidia                                  | 4         | 2.14%   |
| Micron/Crucial Technology               | 3         | 1.6%    |
| KIOXIA                                  | 3         | 1.6%    |
| Toshiba                                 | 2         | 1.07%   |
| Micron Technology                       | 2         | 1.07%   |
| MAXIO Technology (Hangzhou)             | 2         | 1.07%   |
| VIA Technologies                        | 1         | 0.53%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.53%   |
| Shenzhen Unionmemory Information System | 1         | 0.53%   |
| Phison Electronics                      | 1         | 0.53%   |
| Lenovo                                  | 1         | 0.53%   |
| Kingston Technology Company             | 1         | 0.53%   |
| JMicron Technology                      | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 9.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 7.46%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 7.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 4.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 4.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 3.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.49%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.99%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 3         | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.49%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 2         | 1%      |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 1%      |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 2         | 1%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 1%      |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 1%      |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 1%      |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 2         | 1%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 1%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1%      |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1%      |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1%      |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1%      |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.5%    |
| VIA VT8237A Integrated SATA RAID Controller                                      | 1         | 0.5%    |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.5%    |
| Toshiba XG5 NVMe SSD Controller                                                  | 1         | 0.5%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 0.5%    |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.5%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 111       | 58.42%  |
| NVMe | 50        | 26.32%  |
| IDE  | 17        | 8.95%   |
| RAID | 12        | 6.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 142       | 84.52%  |
| AMD    | 26        | 15.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 2.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 2.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 2.38%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 2.38%   |
| Intel CPU Version                             | 3         | 1.79%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.79%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.79%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.79%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 1.79%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.19%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.19%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.19%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.19%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.19%   |
| Intel Core i5-10310U CPU @ 1.70GHz            | 2         | 1.19%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.19%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 2         | 1.19%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 1.19%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 1.19%   |
| Intel 13th Gen Core i7-1355U                  | 2         | 1.19%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.19%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.19%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.19%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.6%    |
| Intel Pentium III                             | 1         | 0.6%    |
| Intel Pentium CPU P6200 @ 2.13GH              | 1         | 0.6%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.6%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.6%    |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.6%    |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.6%    |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 51        | 30.36%  |
| Intel Core i7           | 39        | 23.21%  |
| Other                   | 17        | 10.12%  |
| AMD Ryzen 7             | 10        | 5.95%   |
| Intel Core i3           | 7         | 4.17%   |
| Intel Core 2 Duo        | 7         | 4.17%   |
| Intel Atom              | 6         | 3.57%   |
| Intel Pentium           | 4         | 2.38%   |
| Intel Celeron           | 4         | 2.38%   |
| AMD Ryzen 5             | 4         | 2.38%   |
| AMD A6                  | 3         | 1.79%   |
| Intel Celeron Dual-Core | 2         | 1.19%   |
| AMD Ryzen 7 PRO         | 2         | 1.19%   |
| AMD A8                  | 2         | 1.19%   |
| Intel Xeon              | 1         | 0.6%    |
| Intel Pentium III       | 1         | 0.6%    |
| Intel Genuine           | 1         | 0.6%    |
| Intel Core m5           | 1         | 0.6%    |
| Intel Core i9           | 1         | 0.6%    |
| Intel Core 2            | 1         | 0.6%    |
| Intel Celeron M         | 1         | 0.6%    |
| AMD Turion 64 X2 Mobile | 1         | 0.6%    |
| AMD E1                  | 1         | 0.6%    |
| AMD A10                 | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 77        | 45.83%  |
| 4       | 45        | 26.79%  |
| Unknown | 12        | 7.14%   |
| 8       | 10        | 5.95%   |
| 6       | 8         | 4.76%   |
| 16      | 6         | 3.57%   |
| 1       | 5         | 2.98%   |
| 12      | 4         | 2.38%   |
| 20      | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 163       | 97.6%   |
| 2       | 3         | 1.8%    |
| Unknown | 1         | 0.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 114       | 67.86%  |
| 1       | 40        | 23.81%  |
| Unknown | 14        | 8.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 33        | 19.64%  |
| Haswell       | 20        | 11.9%   |
| IvyBridge     | 16        | 9.52%   |
| Skylake       | 15        | 8.93%   |
| Unknown       | 15        | 8.93%   |
| Penryn        | 11        | 6.55%   |
| SandyBridge   | 8         | 4.76%   |
| Bonnell       | 7         | 4.17%   |
| CometLake     | 5         | 2.98%   |
| Zen+          | 4         | 2.38%   |
| Puma          | 4         | 2.38%   |
| Zen 2         | 3         | 1.79%   |
| Westmere      | 3         | 1.79%   |
| TigerLake     | 3         | 1.79%   |
| Silvermont    | 3         | 1.79%   |
| Core          | 3         | 1.79%   |
| Broadwell     | 3         | 1.79%   |
| P6            | 2         | 1.19%   |
| Zen 3         | 1         | 0.6%    |
| Zen           | 1         | 0.6%    |
| Steamroller   | 1         | 0.6%    |
| K8 Hammer     | 1         | 0.6%    |
| K10 Llano     | 1         | 0.6%    |
| K10           | 1         | 0.6%    |
| Jaguar        | 1         | 0.6%    |
| Goldmont plus | 1         | 0.6%    |
| Goldmont      | 1         | 0.6%    |
| Excavator     | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 126       | 64.95%  |
| Nvidia           | 34        | 17.53%  |
| AMD              | 32        | 16.49%  |
| VIA Technologies | 1         | 0.52%   |
| S3 Graphics      | 1         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 8%      |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 12        | 6%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 6%      |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 8         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.5%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 6         | 3%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 3%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 2.5%    |
| AMD Lucienne                                                                             | 5         | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.5%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 1.5%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1%      |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 1%      |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1%      |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 1%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1%      |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1%      |
| Intel Comet Lake UHD Graphics                                                            | 2         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1%      |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 2         | 1%      |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.5%    |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.5%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.5%    |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.5%    |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.5%    |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.5%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 91        | 54.17%  |
| 1 x AMD         | 26        | 15.48%  |
| Intel + Nvidia  | 20        | 11.9%   |
| 2 x Intel       | 12        | 7.14%   |
| 1 x Nvidia      | 11        | 6.55%   |
| AMD + Nvidia    | 3         | 1.79%   |
| Intel + AMD     | 2         | 1.19%   |
| 2 x AMD         | 1         | 0.6%    |
| 1 x VIA         | 1         | 0.6%    |
| 1 x S3 Graphics | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 148       | 88.62%  |
| Unknown     | 15        | 8.98%   |
| Proprietary | 4         | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 89.88%  |
| 0.01-0.5   | 8         | 4.76%   |
| 0.51-1.0   | 5         | 2.98%   |
| 1.01-2.0   | 4         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 18.71%  |
| LG Display              | 22        | 15.83%  |
| BOE                     | 18        | 12.95%  |
| Samsung Electronics     | 17        | 12.23%  |
| Chimei Innolux          | 16        | 11.51%  |
| Apple                   | 8         | 5.76%   |
| Sharp                   | 6         | 4.32%   |
| HannStar                | 4         | 2.88%   |
| Chi Mei Optoelectronics | 4         | 2.88%   |
| Lenovo                  | 3         | 2.16%   |
| Panasonic               | 2         | 1.44%   |
| Goldstar                | 2         | 1.44%   |
| Sony                    | 1         | 0.72%   |
| PANDA                   | 1         | 0.72%   |
| LG Philips              | 1         | 0.72%   |
| Hewlett-Packard         | 1         | 0.72%   |
| Dell                    | 1         | 0.72%   |
| CSW                     | 1         | 0.72%   |
| CSO                     | 1         | 0.72%   |
| CPT                     | 1         | 0.72%   |
| BenQ                    | 1         | 0.72%   |
| AOC                     | 1         | 0.72%   |
| Acer                    | 1         | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 4         | 2.86%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 3         | 2.14%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch              | 2         | 1.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 340x190mm 15.3-inch         | 2         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 1.43%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 1.43%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.43%   |
| Apple LCD Monitor APP9CCB 1280x800 290x180mm 13.4-inch                   | 2         | 1.43%   |
| Sony TV  *00 SNYF903 3840x2160 1080x610mm 48.8-inch                      | 1         | 0.71%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.71%   |
| Sharp LCD Monitor SHP1548 1920x1200 290x180mm 13.4-inch                  | 1         | 0.71%   |
| Sharp LCD Monitor SHP14C2 1920x1080 260x140mm 11.6-inch                  | 1         | 0.71%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.71%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.71%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 0.71%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3152 1024x600 220x130mm 10.1-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch    | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 700x390mm 31.5-inch    | 1         | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.71%   |
| PANDA LCD Monitor NCP004D 1920x1080 340x190mm 15.3-inch                  | 1         | 0.71%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.71%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.71%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch              | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 54        | 39.71%  |
| 1366x768 (WXGA)   | 43        | 31.62%  |
| 1280x800 (WXGA)   | 8         | 5.88%   |
| 3840x2160 (4K)    | 6         | 4.41%   |
| 1024x600          | 6         | 4.41%   |
| 1600x900 (HD+)    | 5         | 3.68%   |
| 1440x900 (WXGA+)  | 4         | 2.94%   |
| 2880x1800         | 3         | 2.21%   |
| 1920x1200 (WUXGA) | 3         | 2.21%   |
| 3200x1800 (QHD+)  | 1         | 0.74%   |
| 2560x1440 (QHD)   | 1         | 0.74%   |
| 2160x1350         | 1         | 0.74%   |
| 1280x1024 (SXGA)  | 1         | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 55        | 39.29%  |
| 13     | 38        | 27.14%  |
| 12     | 13        | 9.29%   |
| 17     | 10        | 7.14%   |
| 10     | 6         | 4.29%   |
| 24     | 4         | 2.86%   |
| 11     | 4         | 2.86%   |
| 14     | 3         | 2.14%   |
| 27     | 2         | 1.43%   |
| 23     | 2         | 1.43%   |
| 48     | 1         | 0.71%   |
| 31     | 1         | 0.71%   |
| 18     | 1         | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 55%     |
| 201-300     | 43        | 30.71%  |
| 351-400     | 9         | 6.43%   |
| 501-600     | 7         | 5%      |
| 601-700     | 2         | 1.43%   |
| 401-500     | 1         | 0.71%   |
| 1001-1500   | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 110       | 84.62%  |
| 16/10 | 17        | 13.08%  |
| 3/2   | 2         | 1.54%   |
| 5/4   | 1         | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 42        | 30%     |
| 81-90          | 32        | 22.86%  |
| 61-70          | 12        | 8.57%   |
| 101-110        | 12        | 8.57%   |
| 71-80          | 10        | 7.14%   |
| 121-130        | 8         | 5.71%   |
| 41-50          | 6         | 4.29%   |
| 201-250        | 6         | 4.29%   |
| 51-60          | 4         | 2.86%   |
| 301-350        | 2         | 1.43%   |
| 141-150        | 2         | 1.43%   |
| More than 1000 | 1         | 0.71%   |
| 351-500        | 1         | 0.71%   |
| 131-140        | 1         | 0.71%   |
| 111-120        | 1         | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 49        | 35.25%  |
| 101-120       | 45        | 32.37%  |
| 161-240       | 19        | 13.67%  |
| 51-100        | 18        | 12.95%  |
| More than 240 | 8         | 5.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 134       | 79.29%  |
| 0     | 27        | 15.98%  |
| 2     | 7         | 4.14%   |
| 3     | 1         | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 95        | 36.12%  |
| Realtek Semiconductor                  | 68        | 25.86%  |
| Qualcomm Atheros                       | 38        | 14.45%  |
| Broadcom                               | 21        | 7.98%   |
| Samsung Electronics                    | 5         | 1.9%    |
| TP-Link                                | 4         | 1.52%   |
| Ralink                                 | 4         | 1.52%   |
| Marvell Technology Group               | 4         | 1.52%   |
| Sierra Wireless                        | 3         | 1.14%   |
| Ralink Technology                      | 2         | 0.76%   |
| MediaTek                               | 2         | 0.76%   |
| Fibocom                                | 2         | 0.76%   |
| Ericsson Business Mobile Networks      | 2         | 0.76%   |
| VIA Technologies                       | 1         | 0.38%   |
| U-Blox                                 | 1         | 0.38%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.38%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.38%   |
| Qualcomm Technologies                  | 1         | 0.38%   |
| Qualcomm                               | 1         | 0.38%   |
| Nvidia                                 | 1         | 0.38%   |
| NetGear                                | 1         | 0.38%   |
| JMicron Technology                     | 1         | 0.38%   |
| Dell                                   | 1         | 0.38%   |
| D-Link                                 | 1         | 0.38%   |
| Atheros                                | 1         | 0.38%   |
| Apple                                  | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 12.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 5.29%   |
| Intel Wireless 8265 / 8275                                             | 10        | 2.94%   |
| Intel Wireless 7260                                                    | 10        | 2.94%   |
| Intel Wireless 8260                                                    | 9         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 2.65%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 2.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.47%   |
| Intel Wireless 3165                                                    | 5         | 1.47%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.47%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.47%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.47%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.18%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.88%   |
| Intel WiFi Link 5100                                                   | 3         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.88%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 0.88%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 0.88%   |
| TP-Link Wireless USB Adapter                                           | 2         | 0.59%   |
| Sierra Wireless EM7455                                                 | 2         | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 89        | 49.44%  |
| Qualcomm Atheros      | 33        | 18.33%  |
| Realtek Semiconductor | 25        | 13.89%  |
| Broadcom              | 15        | 8.33%   |
| TP-Link               | 4         | 2.22%   |
| Ralink                | 4         | 2.22%   |
| Sierra Wireless       | 2         | 1.11%   |
| Ralink Technology     | 2         | 1.11%   |
| MediaTek              | 2         | 1.11%   |
| Qualcomm Technologies | 1         | 0.56%   |
| NetGear               | 1         | 0.56%   |
| D-Link                | 1         | 0.56%   |
| Atheros               | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 10        | 5.43%   |
| Intel Wireless 7260                                                  | 10        | 5.43%   |
| Intel Wireless 8260                                                  | 9         | 4.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 7         | 3.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 3.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 6         | 3.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 3.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 6         | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5         | 2.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 2.72%   |
| Intel Wireless 3165                                                  | 5         | 2.72%   |
| Intel Wi-Fi 6 AX200                                                  | 5         | 2.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 5         | 2.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 5         | 2.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 3         | 1.63%   |
| Intel WiFi Link 5100                                                 | 3         | 1.63%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 1.63%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.63%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 3         | 1.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 1.63%   |
| TP-Link Wireless USB Adapter                                         | 2         | 1.09%   |
| Sierra Wireless EM7455                                               | 2         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.09%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.09%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 2         | 1.09%   |
| Intel Wireless 7265                                                  | 2         | 1.09%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.09%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.09%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 2         | 1.09%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.54%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                   | 1         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 62        | 41.89%  |
| Intel                                  | 50        | 33.78%  |
| Broadcom                               | 12        | 8.11%   |
| Qualcomm Atheros                       | 8         | 5.41%   |
| Samsung Electronics                    | 5         | 3.38%   |
| Marvell Technology Group               | 4         | 2.7%    |
| VIA Technologies                       | 1         | 0.68%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.68%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.68%   |
| Qualcomm                               | 1         | 0.68%   |
| Nvidia                                 | 1         | 0.68%   |
| JMicron Technology                     | 1         | 0.68%   |
| Apple                                  | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 29.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 12.08%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 6.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 5.37%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 3.36%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 3.36%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 2.68%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 2.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 2.01%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 2.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.34%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.34%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.34%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.34%   |
| Intel Ethernet Connection (23) I219-V                                  | 2         | 1.34%   |
| Intel Ethernet Connection (11) I219-V                                  | 2         | 1.34%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.34%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 1.34%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.67%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.67%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.67%   |
| Qualcomm ALCATEL RNDIS Interface                                       | 1         | 0.67%   |
| Nvidia MCP65 Ethernet                                                  | 1         | 0.67%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.67%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.67%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.67%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller             | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 167       | 52.68%  |
| Ethernet | 143       | 45.11%  |
| Unknown  | 6         | 1.89%   |
| Modem    | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 107       | 50.47%  |
| WiFi     | 102       | 48.11%  |
| Unknown  | 3         | 1.42%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 137       | 81.55%  |
| 1     | 30        | 17.86%  |
| 3     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 150       | 89.29%  |
| Yes  | 18        | 10.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 47.69%  |
| Realtek Semiconductor           | 11        | 8.46%   |
| Lite-On Technology              | 11        | 8.46%   |
| Broadcom                        | 9         | 6.92%   |
| Apple                           | 9         | 6.92%   |
| Qualcomm Atheros Communications | 7         | 5.38%   |
| IMC Networks                    | 6         | 4.62%   |
| Foxconn / Hon Hai               | 4         | 3.08%   |
| ASUSTek Computer                | 4         | 3.08%   |
| USI                             | 1         | 0.77%   |
| Ralink                          | 1         | 0.77%   |
| Hewlett-Packard                 | 1         | 0.77%   |
| Dell                            | 1         | 0.77%   |
| Chicony Electronics             | 1         | 0.77%   |
| Cambridge Silicon Radio         | 1         | 0.77%   |
| Alps Electric                   | 1         | 0.77%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 30        | 23.08%  |
| Intel AX201 Bluetooth                                       | 11        | 8.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 5.38%   |
| Intel AX200 Bluetooth                                       | 5         | 3.85%   |
| Apple Bluetooth Host Controller                             | 5         | 3.85%   |
| Intel AX211 Bluetooth                                       | 4         | 3.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.31%   |
| Lite-On Bluetooth USB Module                                | 3         | 2.31%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 2.31%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.54%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.54%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 1.54%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.54%   |
| Lite-On Realtek Bluetooth Adapter                           | 2         | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.54%   |
| Intel AX210 Bluetooth                                       | 2         | 1.54%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.54%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.54%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.54%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 1.54%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.77%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.77%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.77%   |
| Realtek Bluetooth Adapter                                   | 1         | 0.77%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.77%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.77%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.77%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.77%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.77%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.77%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.77%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.77%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.77%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.77%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 137       | 72.87%  |
| AMD                              | 29        | 15.43%  |
| Nvidia                           | 13        | 6.91%   |
| VIA Technologies                 | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Realtek Semiconductor            | 1         | 0.53%   |
| Lenovo                           | 1         | 0.53%   |
| Focusrite-Novation               | 1         | 0.53%   |
| Corsair                          | 1         | 0.53%   |
| C-Media Electronics              | 1         | 0.53%   |
| Blue Microphones                 | 1         | 0.53%   |
| ASUSTek Computer                 | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 12.34%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 7.23%   |
| AMD Ryzen HD Audio Controller                                                                     | 16        | 6.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 5.11%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.83%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 9         | 3.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 3.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.98%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 2.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.28%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.85%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.85%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.85%   |
| AMD Radeon High Definition Audio Controller                                                       | 2         | 0.85%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.43%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.43%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.43%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 70        | 33.98%  |
| SK hynix            | 44        | 21.36%  |
| Micron Technology   | 28        | 13.59%  |
| Unknown             | 12        | 5.83%   |
| Kingston            | 11        | 5.34%   |
| Unknown             | 8         | 3.88%   |
| Crucial             | 7         | 3.4%    |
| Elpida              | 4         | 1.94%   |
| A-DATA Technology   | 4         | 1.94%   |
| Transcend           | 3         | 1.46%   |
| Ramaxel Technology  | 2         | 0.97%   |
| Nanya Technology    | 2         | 0.97%   |
| G.Skill             | 2         | 0.97%   |
| Corsair             | 2         | 0.97%   |
| 48spaces            | 2         | 0.97%   |
| Unknown (ABCD)      | 1         | 0.49%   |
| Unknown (09D5)      | 1         | 0.49%   |
| Qimonda             | 1         | 0.49%   |
| Magnum Tech         | 1         | 0.49%   |
| Aeneon              | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 8         | 3.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 7         | 3.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 2.28%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 1.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 4         | 1.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 4         | 1.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s                     | 3         | 1.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s                     | 3         | 1.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.37%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 3         | 1.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 3         | 1.37%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 0.91%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 2         | 0.91%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.91%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.91%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 0.91%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.91%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s                    | 2         | 0.91%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s          | 2         | 0.91%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 0.91%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.91%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.91%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.91%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2133MT/s                     | 2         | 0.91%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.91%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.91%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 2         | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.91%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 2         | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.91%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 800MT/s | 2         | 0.91%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                 | 1         | 0.46%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                                 | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 65        | 38.92%  |
| DDR4    | 61        | 36.53%  |
| DDR2    | 14        | 8.38%   |
| LPDDR3  | 9         | 5.39%   |
| SDRAM   | 4         | 2.4%    |
| LPDDR5  | 4         | 2.4%    |
| LPDDR4  | 3         | 1.8%    |
| DDR5    | 3         | 1.8%    |
| Unknown | 2         | 1.2%    |
| RAM     | 1         | 0.6%    |
| DRAM    | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 152       | 90.48%  |
| Row Of Chips | 9         | 5.36%   |
| Chip         | 4         | 2.38%   |
| Unknown      | 2         | 1.19%   |
| DIMM         | 1         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 63        | 32.98%  |
| 4096  | 63        | 32.98%  |
| 2048  | 31        | 16.23%  |
| 16384 | 22        | 11.52%  |
| 1024  | 6         | 3.14%   |
| 32768 | 4         | 2.09%   |
| 512   | 1         | 0.52%   |
| 128   | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 46        | 25.7%   |
| 3200    | 26        | 14.53%  |
| 2133    | 17        | 9.5%    |
| 2400    | 16        | 8.94%   |
| 2667    | 15        | 8.38%   |
| 1334    | 9         | 5.03%   |
| 1333    | 9         | 5.03%   |
| 667     | 9         | 5.03%   |
| 1867    | 6         | 3.35%   |
| Unknown | 5         | 2.79%   |
| 6400    | 4         | 2.23%   |
| 1067    | 4         | 2.23%   |
| 800     | 4         | 2.23%   |
| 5600    | 2         | 1.12%   |
| 4800    | 1         | 0.56%   |
| 4267    | 1         | 0.56%   |
| 4266    | 1         | 0.56%   |
| 1639    | 1         | 0.56%   |
| 975     | 1         | 0.56%   |
| 533     | 1         | 0.56%   |
| 400     | 1         | 0.56%   |

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
| Chicony Electronics                    | 37        | 27.61%  |
| Bison Electronics                      | 17        | 12.69%  |
| Realtek Semiconductor                  | 14        | 10.45%  |
| IMC Networks                           | 11        | 8.21%   |
| Sunplus Innovation Technology          | 10        | 7.46%   |
| Suyin                                  | 9         | 6.72%   |
| Microdia                               | 8         | 5.97%   |
| Quanta                                 | 4         | 2.99%   |
| Lite-On Technology                     | 4         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.99%   |
| Silicon Motion                         | 3         | 2.24%   |
| Apple                                  | 3         | 2.24%   |
| Logitech                               | 2         | 1.49%   |
| Z-Star Microelectronics                | 1         | 0.75%   |
| Syntek                                 | 1         | 0.75%   |
| Supreme Electronics                    | 1         | 0.75%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.75%   |
| Luxvisions Innotech Limited            | 1         | 0.75%   |
| Intel                                  | 1         | 0.75%   |
| Genesys Logic                          | 1         | 0.75%   |
| Alcor Micro                            | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 13        | 9.7%    |
| Bison Integrated Camera                                     | 8         | 5.97%   |
| Chicony HD WebCam                                           | 5         | 3.73%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 2.99%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.99%   |
| IMC Networks Realtek PC Camera                              | 4         | 2.99%   |
| Microdia Integrated_Webcam_HD                               | 3         | 2.24%   |
| Microdia Integrated Webcam                                  | 3         | 2.24%   |
| Apple FaceTime HD Camera                                    | 3         | 2.24%   |
| Suyin Acer Crystal Eye webcam                               | 2         | 1.49%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 1.49%   |
| Realtek Lenovo EasyCamera                                   | 2         | 1.49%   |
| Quanta Front Camera                                         | 2         | 1.49%   |
| Logitech HD Pro Webcam C920                                 | 2         | 1.49%   |
| Lite-On Integrated Camera                                   | 2         | 1.49%   |
| IMC Networks Integrated Camera                              | 2         | 1.49%   |
| IMC Networks EasyCamera                                     | 2         | 1.49%   |
| Chicony FJ Camera                                           | 2         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 1.49%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.49%   |
| Bison SunplusIT Integrated Camera                           | 2         | 1.49%   |
| Bison EasyCamera                                            | 2         | 1.49%   |
| Z-Star Webcam                                               | 1         | 0.75%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.75%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.75%   |
| Suyin Laptop_Integrated_Webcam_3M                           | 1         | 0.75%   |
| Suyin HP Webcam-50                                          | 1         | 0.75%   |
| Suyin HD WebCam                                             | 1         | 0.75%   |
| Suyin HD Video WebCam                                       | 1         | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.75%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.75%   |
| Supreme Integrated Camera                                   | 1         | 0.75%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.75%   |
| Sunplus Integrated Webcam                                   | 1         | 0.75%   |
| Sunplus Hy HD Camera                                        | 1         | 0.75%   |
| Sunplus HD WebCam                                           | 1         | 0.75%   |
| Sunplus Asus Webcam                                         | 1         | 0.75%   |
| Sunplus 2-USB 2.0 Camera                                    | 1         | 0.75%   |
| Silicon Motion WebCam SCX Series                            | 1         | 0.75%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 43.59%  |
| Synaptics                  | 9         | 23.08%  |
| Upek                       | 4         | 10.26%  |
| Shenzhen Goodix Technology | 3         | 7.69%   |
| LighTuning Technology      | 3         | 7.69%   |
| Elan Microelectronics      | 1         | 2.56%   |
| Broadcom                   | 1         | 2.56%   |
| AuthenTec                  | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                              | 5         | 12.82%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 12.82%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 4         | 10.26%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 10.26%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 5.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 5.13%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 2.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 2.56%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 2.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 1         | 2.56%   |
| LighTuning Fingerprint Reader                                                | 1         | 2.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2.56%   |
| Elan Fingerprint Sensor                                                      | 1         | 2.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.56%   |
| AuthenTec AES1600                                                            | 1         | 2.56%   |
| Unknown                                                                      | 1         | 2.56%   |

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
| 2     | 50        | 29.24%  |
| 1     | 47        | 27.49%  |
| 3     | 28        | 16.37%  |
| 0     | 22        | 12.87%  |
| 4     | 18        | 10.53%  |
| 5     | 4         | 2.34%   |
| 7     | 1         | 0.58%   |
| 6     | 1         | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 115       | 38.33%  |
| Net/wireless             | 52        | 17.33%  |
| Bluetooth                | 46        | 15.33%  |
| Fingerprint reader       | 38        | 12.67%  |
| Card reader              | 27        | 9%      |
| Firewire controller      | 15        | 5%      |
| Network                  | 3         | 1%      |
| Net/ethernet             | 2         | 0.67%   |
| Storage/raid             | 1         | 0.33%   |
| Sound                    | 1         | 0.33%   |

