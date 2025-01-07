NomadBSD - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for NomadBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NomadBSD/Desktop/README.md) and [notebooks](/Dist/NomadBSD/Notebook/README.md).

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

Total: 290

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 14 7440 2-in-1     | Convertible | [1dca2d5f7d](https://bsd-hardware.info/?probe=1dca2d5f7d) | Jan 01, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [b880be6d5f](https://bsd-hardware.info/?probe=b880be6d5f) | Dec 30, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [dc3d4a1f8d](https://bsd-hardware.info/?probe=dc3d4a1f8d) | Nov 24, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [0cd9c4bf36](https://bsd-hardware.info/?probe=0cd9c4bf36) | Nov 11, 2024 |
| HP            | Mini 210-1000               | Notebook    | [2e6b2f7727](https://bsd-hardware.info/?probe=2e6b2f7727) | Nov 08, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [4e4e2da2fc](https://bsd-hardware.info/?probe=4e4e2da2fc) | Oct 14, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [52ca4ac8cd](https://bsd-hardware.info/?probe=52ca4ac8cd) | Oct 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [402e2d6b51](https://bsd-hardware.info/?probe=402e2d6b51) | Oct 05, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [9ea21fa783](https://bsd-hardware.info/?probe=9ea21fa783) | Sep 26, 2024 |
| MSI           | Prestige 15 A10SC           | Notebook    | [6cdde2a1ab](https://bsd-hardware.info/?probe=6cdde2a1ab) | Sep 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [14457d4dfe](https://bsd-hardware.info/?probe=14457d4dfe) | Sep 19, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [c993d0a7ec](https://bsd-hardware.info/?probe=c993d0a7ec) | Sep 18, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [41254dde12](https://bsd-hardware.info/?probe=41254dde12) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [c5e1346269](https://bsd-hardware.info/?probe=c5e1346269) | Sep 14, 2024 |
| HP            | Pavilion dv6500             | Notebook    | [012d5b1541](https://bsd-hardware.info/?probe=012d5b1541) | Sep 10, 2024 |
| HP            | Pavilion dv6500             | Notebook    | [d5fb091f0e](https://bsd-hardware.info/?probe=d5fb091f0e) | Sep 09, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [5c1dfe489a](https://bsd-hardware.info/?probe=5c1dfe489a) | Sep 08, 2024 |
| Acer          | Aspire A514-52              | Notebook    | [69ff95eed9](https://bsd-hardware.info/?probe=69ff95eed9) | Aug 22, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [24dc7d5ecf](https://bsd-hardware.info/?probe=24dc7d5ecf) | Aug 07, 2024 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [66efc0232a](https://bsd-hardware.info/?probe=66efc0232a) | Jun 20, 2024 |
| HP            | Pavilion 15                 | Notebook    | [36a75dbcf3](https://bsd-hardware.info/?probe=36a75dbcf3) | Jun 18, 2024 |
| Acer          | TravelMate P653-MG          | Notebook    | [f00a8363c2](https://bsd-hardware.info/?probe=f00a8363c2) | Jun 05, 2024 |
| Dell          | Inspiron 15 3525            | Notebook    | [08918d8cb5](https://bsd-hardware.info/?probe=08918d8cb5) | May 31, 2024 |
| ASRock        | B550 Taichi                 | Desktop     | [524c9eda2c](https://bsd-hardware.info/?probe=524c9eda2c) | May 23, 2024 |
| ASRock        | B550 Taichi                 | Desktop     | [bf60c50ac6](https://bsd-hardware.info/?probe=bf60c50ac6) | May 23, 2024 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [5f31e6dc7e](https://bsd-hardware.info/?probe=5f31e6dc7e) | May 04, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [fc810b38b1](https://bsd-hardware.info/?probe=fc810b38b1) | Apr 16, 2024 |
| Lenovo        | ThinkPad X260 20F60093US    | Notebook    | [3b7eee9621](https://bsd-hardware.info/?probe=3b7eee9621) | Apr 04, 2024 |
| Gateway       | SX2185                      | Desktop     | [45623a4e3a](https://bsd-hardware.info/?probe=45623a4e3a) | Mar 24, 2024 |
| Gateway       | SX2185                      | Desktop     | [8d7eccbfda](https://bsd-hardware.info/?probe=8d7eccbfda) | Mar 24, 2024 |
| Dell          | Latitude 7220 Rugged Ext... | Notebook    | [d882577127](https://bsd-hardware.info/?probe=d882577127) | Mar 07, 2024 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [dced74ec00](https://bsd-hardware.info/?probe=dced74ec00) | Jan 22, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [dab1edae0c](https://bsd-hardware.info/?probe=dab1edae0c) | Jan 08, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [8ff2212812](https://bsd-hardware.info/?probe=8ff2212812) | Jan 04, 2024 |
| Lenovo        | ThinkPad E495 20NE000BSP    | Notebook    | [9ed586661c](https://bsd-hardware.info/?probe=9ed586661c) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [77d8cc2e7c](https://bsd-hardware.info/?probe=77d8cc2e7c) | Jan 02, 2024 |
| Intel         | H61M-DS2                    | Desktop     | [bd541b60c8](https://bsd-hardware.info/?probe=bd541b60c8) | Dec 30, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [742764e130](https://bsd-hardware.info/?probe=742764e130) | Dec 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [02bf1d2cd4](https://bsd-hardware.info/?probe=02bf1d2cd4) | Dec 19, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d9d33d12d7](https://bsd-hardware.info/?probe=d9d33d12d7) | Dec 14, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9654df78b8](https://bsd-hardware.info/?probe=9654df78b8) | Dec 14, 2023 |
| Sony          | VJS122C11L                  | Notebook    | [7d100c8e2c](https://bsd-hardware.info/?probe=7d100c8e2c) | Dec 06, 2023 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [56ef117b12](https://bsd-hardware.info/?probe=56ef117b12) | Dec 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [97267cbee9](https://bsd-hardware.info/?probe=97267cbee9) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | Notebook    | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [6448ed1b12](https://bsd-hardware.info/?probe=6448ed1b12) | Oct 28, 2023 |
| Fujitsu       | D3314-E1 S26361-D3314-E1    | Desktop     | [2cde7906c1](https://bsd-hardware.info/?probe=2cde7906c1) | Oct 27, 2023 |
| Fujitsu       | D3314-A1 S26361-D3314-A1    | Desktop     | [d005339b5f](https://bsd-hardware.info/?probe=d005339b5f) | Oct 27, 2023 |
| Sophos        | UTM                         | Firewall    | [b6232a012b](https://bsd-hardware.info/?probe=b6232a012b) | Oct 27, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | Notebook    | [aa85ff898d](https://bsd-hardware.info/?probe=aa85ff898d) | Oct 26, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f38d89e6c0](https://bsd-hardware.info/?probe=f38d89e6c0) | Oct 15, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [054a6c3902](https://bsd-hardware.info/?probe=054a6c3902) | Oct 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [723569d88a](https://bsd-hardware.info/?probe=723569d88a) | Oct 01, 2023 |
| ASUSTek       | 1005PXD                     | Notebook    | [1b05e8cf1b](https://bsd-hardware.info/?probe=1b05e8cf1b) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [e732d89b06](https://bsd-hardware.info/?probe=e732d89b06) | Sep 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [8816b1ac4a](https://bsd-hardware.info/?probe=8816b1ac4a) | Sep 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [714516a696](https://bsd-hardware.info/?probe=714516a696) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [cac0950717](https://bsd-hardware.info/?probe=cac0950717) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [3c69dd7003](https://bsd-hardware.info/?probe=3c69dd7003) | Sep 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | Notebook    | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| eMachines     | G640                        | Notebook    | [c05619033c](https://bsd-hardware.info/?probe=c05619033c) | Sep 14, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | Notebook    | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66f982c40b](https://bsd-hardware.info/?probe=66f982c40b) | Aug 23, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | EliteBook 750 G1            | Notebook    | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | Notebook    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| ASRockRack    | C226M WS                    | Desktop     | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| ECS           | Z77H2-AX                    | Desktop     | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | Notebook    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell          | Latitude 7300               | Notebook    | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [04f43c3d70](https://bsd-hardware.info/?probe=04f43c3d70) | Feb 23, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | Notebook    | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| HP            | 1589                        | Desktop     | [8a927b43cb](https://bsd-hardware.info/?probe=8a927b43cb) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | Notebook    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | Notebook    | [995a8a5e6f](https://bsd-hardware.info/?probe=995a8a5e6f) | Jul 16, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [4e6381e037](https://bsd-hardware.info/?probe=4e6381e037) | Jun 22, 2022 |
| HP            | 2B29                        | Desktop     | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP            | 1589                        | Desktop     | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
| Dell          | 0Y2G6P A03                  | Server      | [ecb370bba4](https://bsd-hardware.info/?probe=ecb370bba4) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| Dell          | Latitude 5290               | Notebook    | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | Notebook    | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [c4f7b8a774](https://bsd-hardware.info/?probe=c4f7b8a774) | Apr 22, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [95646c7b48](https://bsd-hardware.info/?probe=95646c7b48) | Mar 25, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [09116f9139](https://bsd-hardware.info/?probe=09116f9139) | Mar 24, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| Dell          | Latitude D630               | Notebook    | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| Gigabyte      | X570S GAMING X              | Desktop     | [ff39ace6ec](https://bsd-hardware.info/?probe=ff39ace6ec) | Feb 16, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | Notebook    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | 1000                        | Notebook    | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Dell          | 0M9KCM A01                  | Desktop     | [4db0a0ea05](https://bsd-hardware.info/?probe=4db0a0ea05) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| HP            | ProBook x360 11 G6 EE       | Convertible | [7eaff44a64](https://bsd-hardware.info/?probe=7eaff44a64) | Nov 27, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1bd9270845](https://bsd-hardware.info/?probe=1bd9270845) | Nov 15, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| Unknown       | X79                         | Desktop     | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [767b44a6ae](https://bsd-hardware.info/?probe=767b44a6ae) | Oct 30, 2021 |
| ASUSTek       | X202E                       | Notebook    | [54259ac9a1](https://bsd-hardware.info/?probe=54259ac9a1) | Oct 29, 2021 |
| Sony          | VJS121C11N                  | Notebook    | [d86c621ef0](https://bsd-hardware.info/?probe=d86c621ef0) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [f601f00e7c](https://bsd-hardware.info/?probe=f601f00e7c) | Oct 07, 2021 |
| Dell          | OptiPlex 3020               | Desktop     | [c391177240](https://bsd-hardware.info/?probe=c391177240) | Oct 05, 2021 |
| Dell          | OptiPlex 3020               | Desktop     | [070a0c6d62](https://bsd-hardware.info/?probe=070a0c6d62) | Sep 19, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c5751c736c](https://bsd-hardware.info/?probe=c5751c736c) | Sep 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [d8f8901ae7](https://bsd-hardware.info/?probe=d8f8901ae7) | Sep 19, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [8818f01ff2](https://bsd-hardware.info/?probe=8818f01ff2) | Aug 27, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| HP            | 2000                        | Notebook    | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | Notebook    | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [39ef89f214](https://bsd-hardware.info/?probe=39ef89f214) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [4e7ace8a39](https://bsd-hardware.info/?probe=4e7ace8a39) | Aug 04, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | Notebook    | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Dell          | Inspiron 15-5568            | Notebook    | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| Gigabyte      | Z370 AORUS ULTRAGAMING W... | Desktop     | [13371b2ab8](https://bsd-hardware.info/?probe=13371b2ab8) | Jun 27, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [e91dc55970](https://bsd-hardware.info/?probe=e91dc55970) | Jun 22, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5abce24217](https://bsd-hardware.info/?probe=5abce24217) | Jun 06, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [dab0ca2417](https://bsd-hardware.info/?probe=dab0ca2417) | Jun 01, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [96cc0c27b0](https://bsd-hardware.info/?probe=96cc0c27b0) | May 25, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| Acer          | Aspire E5-551               | Notebook    | [c9ab1cb207](https://bsd-hardware.info/?probe=c9ab1cb207) | Apr 29, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [e9155d12c7](https://bsd-hardware.info/?probe=e9155d12c7) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | Notebook    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| ECT           | One Computer AMD A10-785... | Desktop     | [41a2a2e434](https://bsd-hardware.info/?probe=41a2a2e434) | Apr 07, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [6bc6c5b2bf](https://bsd-hardware.info/?probe=6bc6c5b2bf) | Mar 31, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Acer          | EG43M                       | Desktop     | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| MSI           | MS-N033                     | Notebook    | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| Notebook      | N650DU                      | Notebook    | [90d705dd1e](https://bsd-hardware.info/?probe=90d705dd1e) | Mar 14, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | Notebook    | [733c5edb74](https://bsd-hardware.info/?probe=733c5edb74) | Mar 08, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | Notebook    | [56844725d1](https://bsd-hardware.info/?probe=56844725d1) | Mar 08, 2021 |
| Acer          | EG31M R01-C3                | Desktop     | [1186d46ac9](https://bsd-hardware.info/?probe=1186d46ac9) | Mar 08, 2021 |
| HP            | 158A                        | Desktop     | [da9d6bf86f](https://bsd-hardware.info/?probe=da9d6bf86f) | Mar 07, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [be2ad24d1b](https://bsd-hardware.info/?probe=be2ad24d1b) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0e06b5f17f](https://bsd-hardware.info/?probe=0e06b5f17f) | Mar 06, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [9468eeef92](https://bsd-hardware.info/?probe=9468eeef92) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| Dell          | Latitude 5280               | Notebook    | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [eb7d8c3502](https://bsd-hardware.info/?probe=eb7d8c3502) | Mar 02, 2021 |
| Acer          | EG31M R01-C3                | Desktop     | [046404e65c](https://bsd-hardware.info/?probe=046404e65c) | Mar 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| GEO           | GeoBook3                    | Notebook    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| Clevo         | W55xEU                      | Notebook    | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [cd086a9092](https://bsd-hardware.info/?probe=cd086a9092) | Feb 12, 2021 |
| Clevo         | W55xEU                      | Notebook    | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | Notebook    | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Alienware     | M18xR1                      | Notebook    | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| Dell          | Latitude 3410               | Notebook    | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| Dell          | Latitude E4300              | Notebook    | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [2917a6fbe1](https://bsd-hardware.info/?probe=2917a6fbe1) | Jan 31, 2021 |
| HP            | 0AACh                       | Desktop     | [b7cac343f6](https://bsd-hardware.info/?probe=b7cac343f6) | Jan 29, 2021 |
| HP            | 3399                        | Desktop     | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ba45e27f88](https://bsd-hardware.info/?probe=ba45e27f88) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [d894ae5d09](https://bsd-hardware.info/?probe=d894ae5d09) | Jan 07, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | Desktop     | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [cfc292e9e8](https://bsd-hardware.info/?probe=cfc292e9e8) | Jan 07, 2021 |
| Sony          | VPCM13M1R                   | Notebook    | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| NEC Comput... | PC-GL186Y3AZ                | Notebook    | [b9f8e78467](https://bsd-hardware.info/?probe=b9f8e78467) | Jan 05, 2021 |
| Dell          | Latitude 5280               | Notebook    | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [cfd6a0ab4b](https://bsd-hardware.info/?probe=cfd6a0ab4b) | Jan 04, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [876f5d7b92](https://bsd-hardware.info/?probe=876f5d7b92) | Jan 02, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [889bba9dbc](https://bsd-hardware.info/?probe=889bba9dbc) | Dec 30, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a3e2c4eda1](https://bsd-hardware.info/?probe=a3e2c4eda1) | Dec 30, 2020 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [df9318dcea](https://bsd-hardware.info/?probe=df9318dcea) | Dec 27, 2020 |
| Dell          | Inspiron 5758               | Notebook    | [51ed7b02c2](https://bsd-hardware.info/?probe=51ed7b02c2) | Dec 21, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c8c11a071d](https://bsd-hardware.info/?probe=c8c11a071d) | Dec 14, 2020 |
| Acer          | Aspire V5-122               | Notebook    | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Apple         | MacBookPro11,3              | Notebook    | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| IBM           | 2647NG8                     | Notebook    | [a0f38de52f](https://bsd-hardware.info/?probe=a0f38de52f) | Nov 22, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Acer          | Aspire E5-432               | Notebook    | [39fb05c049](https://bsd-hardware.info/?probe=39fb05c049) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [31f5a66353](https://bsd-hardware.info/?probe=31f5a66353) | Oct 25, 2020 |
| Acer          | Aspire V3-575G              | Notebook    | [1ff0e90d9d](https://bsd-hardware.info/?probe=1ff0e90d9d) | Oct 24, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| Google        | Chell                       | Notebook    | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [407652fc8d](https://bsd-hardware.info/?probe=407652fc8d) | Oct 05, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Dell          | Precision 7530              | Notebook    | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | Notebook    | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | Notebook    | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | Notebook    | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | Notebook    | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Dell          | Vostro 3750                 | Notebook    | [587a9276bb](https://bsd-hardware.info/?probe=587a9276bb) | Sep 06, 2020 |
| Foxconn       | Napa HP P/N                 | Desktop     | [2a7cb7b214](https://bsd-hardware.info/?probe=2a7cb7b214) | Sep 03, 2020 |
| Panasonic     | CF-C1BD06EFG                | Notebook    | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| ASUSTek       | EMERY                       | Desktop     | [c93b86b3ba](https://bsd-hardware.info/?probe=c93b86b3ba) | Aug 27, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | Notebook    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| ASUSTek       | V241ICR-R                   | All in one  | [f21adeb92c](https://bsd-hardware.info/?probe=f21adeb92c) | Aug 20, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [5ef34cd40f](https://bsd-hardware.info/?probe=5ef34cd40f) | Aug 20, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [6ca9384f34](https://bsd-hardware.info/?probe=6ca9384f34) | Aug 20, 2020 |
| HP            | 0A64h                       | Desktop     | [10c48336b0](https://bsd-hardware.info/?probe=10c48336b0) | Aug 20, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [78d714a1a3](https://bsd-hardware.info/?probe=78d714a1a3) | Aug 19, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| Dell          | Latitude 5480               | Notebook    | [907e0da9a4](https://bsd-hardware.info/?probe=907e0da9a4) | Aug 08, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Google        | Lulu                        | Notebook    | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8a3cb911c3](https://bsd-hardware.info/?probe=8a3cb911c3) | Jul 18, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Unknown       | Unknown                     | Notebook    | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [a03e1c19c1](https://bsd-hardware.info/?probe=a03e1c19c1) | Jul 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | Notebook    | [b726c4536b](https://bsd-hardware.info/?probe=b726c4536b) | Jul 04, 2020 |
| ASRock        | Z97 Extreme6/ac             | Desktop     | [9c2d19d0c3](https://bsd-hardware.info/?probe=9c2d19d0c3) | Jul 03, 2020 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [5fac785920](https://bsd-hardware.info/?probe=5fac785920) | Jul 03, 2020 |
| Dell          | Latitude E7240              | Notebook    | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [aa58b291b3](https://bsd-hardware.info/?probe=aa58b291b3) | May 24, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | Notebook    | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NomadBSD 5806f915 | 54        | 23.18%  |
| NomadBSD 1.3.2    | 52        | 22.32%  |
| NomadBSD 20221130 | 34        | 14.59%  |
| NomadBSD 1.4      | 23        | 9.87%   |
| NomadBSD 20240711 | 15        | 6.44%   |
| NomadBSD 20231013 | 11        | 4.72%   |
| NomadBSD 20240126 | 10        | 4.29%   |
| NomadBSD 20231121 | 10        | 4.29%   |
| NomadBSD 1.4-RC1  | 10        | 4.29%   |
| NomadBSD 1.3.1    | 10        | 4.29%   |
| NomadBSD 81e34fc3 | 1         | 0.43%   |
| NomadBSD 80dec9b9 | 1         | 0.43%   |
| NomadBSD 1.3      | 1         | 0.43%   |
| NomadBSD 1.0      | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| NomadBSD | 227       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 218       | 95.61%  |
| i386  | 10        | 4.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 167       | 73.25%  |
| XFCE          | 26        | 11.4%   |
| xinitrc       | 12        | 5.26%   |
| KDE5          | 11        | 4.82%   |
| GNOME         | 7         | 3.07%   |
| Enlightenment | 3         | 1.32%   |
| GNUstep       | 1         | 0.44%   |
| filer         | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 227       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 144       | 63.44%  |
| SDDM    | 81        | 35.68%  |
| LightDM | 2         | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 77        | 33.48%  |
| Unknown | 44        | 19.13%  |
| de_DE   | 19        | 8.26%   |
| en_GB   | 16        | 6.96%   |
| ru_RU   | 10        | 4.35%   |
| es_ES   | 8         | 3.48%   |
| fr_FR   | 7         | 3.04%   |
| zh_TW   | 6         | 2.61%   |
| it_IT   | 6         | 2.61%   |
| hu_HU   | 5         | 2.17%   |
| fi_FI   | 5         | 2.17%   |
| en_AU   | 4         | 1.74%   |
| zh_CN   | 3         | 1.3%    |
| tr_TR   | 3         | 1.3%    |
| pl_PL   | 3         | 1.3%    |
| pt_BR   | 2         | 0.87%   |
| cs_CZ   | 2         | 0.87%   |
| C       | 2         | 0.87%   |
| bg_BG   | 2         | 0.87%   |
| sv_SE   | 1         | 0.43%   |
| nl_NL   | 1         | 0.43%   |
| lt_LT   | 1         | 0.43%   |
| ko_KR   | 1         | 0.43%   |
| et_EE   | 1         | 0.43%   |
| de_CH   | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 220       | 96.49%  |
| BIOS | 8         | 3.51%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 176       | 77.19%  |
| Zfs  | 52        | 22.81%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 162       | 71.05%  |
| MBR  | 66        | 28.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 52        | 22.91%  |
| Hewlett-Packard     | 30        | 13.22%  |
| Dell                | 28        | 12.33%  |
| ASUSTek Computer    | 27        | 11.89%  |
| Acer                | 15        | 6.61%   |
| Gigabyte Technology | 8         | 3.52%   |
| ASRock              | 8         | 3.52%   |
| Apple               | 8         | 3.52%   |
| TUXEDO              | 5         | 2.2%    |
| Fujitsu             | 5         | 2.2%    |
| Sony                | 4         | 1.76%   |
| MSI                 | 4         | 1.76%   |
| Intel               | 4         | 1.76%   |
| Samsung Electronics | 3         | 1.32%   |
| Pegatron            | 2         | 0.88%   |
| Notebook            | 2         | 0.88%   |
| Google              | 2         | 0.88%   |
| Fujitsu Siemens     | 2         | 0.88%   |
| Unknown             | 2         | 0.88%   |
| Toshiba             | 1         | 0.44%   |
| Sophos              | 1         | 0.44%   |
| Semp Toshiba        | 1         | 0.44%   |
| Panasonic           | 1         | 0.44%   |
| NEC Computers       | 1         | 0.44%   |
| Microsoft           | 1         | 0.44%   |
| IBM                 | 1         | 0.44%   |
| GEO                 | 1         | 0.44%   |
| Gateway             | 1         | 0.44%   |
| Foxconn             | 1         | 0.44%   |
| eMachines           | 1         | 0.44%   |
| ECS                 | 1         | 0.44%   |
| Clevo               | 1         | 0.44%   |
| Chuwi               | 1         | 0.44%   |
| ASRockRack          | 1         | 0.44%   |
| Alienware           | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 3         | 1.32%   |
| HP Z420 Workstation                     | 2         | 0.88%   |
| Fujitsu FUTRO S520                      | 2         | 0.88%   |
| ASUS ROG STRIX B550-F GAMING            | 2         | 0.88%   |
| Apple MacBookPro8,1                     | 2         | 0.88%   |
| Apple MacBookPro7,1                     | 2         | 0.88%   |
| Acer Veriton M460                       | 2         | 0.88%   |
| TUXEDO Pulse 15 Gen2                    | 1         | 0.44%   |
| TUXEDO Pulse 15 Gen1                    | 1         | 0.44%   |
| TUXEDO InfinityBook S 15 Gen6           | 1         | 0.44%   |
| TUXEDO InfinityBook Pro AMD Gen9        | 1         | 0.44%   |
| Toshiba Satellite C660                  | 1         | 0.44%   |
| Sophos UTM                              | 1         | 0.44%   |
| Sony VPCM13M1R                          | 1         | 0.44%   |
| Sony VJS122C11L                         | 1         | 0.44%   |
| Sony VJS121C11N                         | 1         | 0.44%   |
| Sony SVE1713S1RW                        | 1         | 0.44%   |
| Semp Toshiba STI                        | 1         | 0.44%   |
| Samsung N150/N210/N220                  | 1         | 0.44%   |
| Samsung N145P/N250P/N260P               | 1         | 0.44%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.44%   |
| Pegatron T12Ah                          | 1         | 0.44%   |
| Pegatron Elite 7300 Series MT           | 1         | 0.44%   |
| Panasonic CF-C1BD06EFG                  | 1         | 0.44%   |
| Notebook W650DC,DD                      | 1         | 0.44%   |
| Notebook N650DU                         | 1         | 0.44%   |
| NEC Computers PC-GL186Y3AZ              | 1         | 0.44%   |
| MSI Prestige 15 A10SC                   | 1         | 0.44%   |
| MSI MS-N033                             | 1         | 0.44%   |
| MSI MS-7C02                             | 1         | 0.44%   |
| MSI MS-7A38                             | 1         | 0.44%   |
| Microsoft Surface Pro 4                 | 1         | 0.44%   |
| Lenovo Yoga 710-11IKB 80V6              | 1         | 0.44%   |
| Lenovo V580 20147                       | 1         | 0.44%   |
| Lenovo ThinkStation P300 30AH000SUS     | 1         | 0.44%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK    | 1         | 0.44%   |
| Lenovo ThinkPad X280 20KESB4T00         | 1         | 0.44%   |
| Lenovo ThinkPad X270 20HN006CUS         | 1         | 0.44%   |
| Lenovo ThinkPad X260 20F60093US         | 1         | 0.44%   |
| Lenovo ThinkPad X230 2325IB1            | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 36        | 15.86%  |
| Dell Latitude         | 10        | 4.41%   |
| Acer Aspire           | 10        | 4.41%   |
| Lenovo IdeaPad        | 6         | 2.64%   |
| HP Pavilion           | 5         | 2.2%    |
| Dell OptiPlex         | 5         | 2.2%    |
| Dell Inspiron         | 5         | 2.2%    |
| HP Compaq             | 4         | 1.76%   |
| HP ProBook            | 3         | 1.32%   |
| HP EliteBook          | 3         | 1.32%   |
| Dell Studio           | 3         | 1.32%   |
| ASUS VivoBook         | 3         | 1.32%   |
| ASUS ROG              | 3         | 1.32%   |
| Unknown               | 3         | 1.32%   |
| TUXEDO Pulse          | 2         | 0.88%   |
| TUXEDO InfinityBook   | 2         | 0.88%   |
| Lenovo ThinkCentre    | 2         | 0.88%   |
| HP Z420               | 2         | 0.88%   |
| HP Laptop             | 2         | 0.88%   |
| Gigabyte Z370         | 2         | 0.88%   |
| Gigabyte X570         | 2         | 0.88%   |
| Fujitsu Siemens AMILO | 2         | 0.88%   |
| Fujitsu LIFEBOOK      | 2         | 0.88%   |
| Fujitsu FUTRO         | 2         | 0.88%   |
| Dell XPS              | 2         | 0.88%   |
| ASUS TUF              | 2         | 0.88%   |
| ASUS PRIME            | 2         | 0.88%   |
| ASRock B550           | 2         | 0.88%   |
| Apple MacBookPro8     | 2         | 0.88%   |
| Apple MacBookPro7     | 2         | 0.88%   |
| Acer Veriton          | 2         | 0.88%   |
| Toshiba Satellite     | 1         | 0.44%   |
| Sophos UTM            | 1         | 0.44%   |
| Sony VPCM13M1R        | 1         | 0.44%   |
| Sony VJS122C11L       | 1         | 0.44%   |
| Sony VJS121C11N       | 1         | 0.44%   |
| Sony SVE1713S1RW      | 1         | 0.44%   |
| Semp Toshiba STI      | 1         | 0.44%   |
| Samsung N150          | 1         | 0.44%   |
| Samsung N145P         | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 26        | 11.45%  |
| 2019 | 21        | 9.25%   |
| 2017 | 18        | 7.93%   |
| 2018 | 16        | 7.05%   |
| 2011 | 16        | 7.05%   |
| 2013 | 15        | 6.61%   |
| 2021 | 14        | 6.17%   |
| 2016 | 13        | 5.73%   |
| 2022 | 12        | 5.29%   |
| 2012 | 12        | 5.29%   |
| 2010 | 12        | 5.29%   |
| 2015 | 11        | 4.85%   |
| 2014 | 10        | 4.41%   |
| 2009 | 10        | 4.41%   |
| 2008 | 7         | 3.08%   |
| 2023 | 5         | 2.2%    |
| 2024 | 4         | 1.76%   |
| 2006 | 3         | 1.32%   |
| 2007 | 1         | 0.44%   |
| 2004 | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 152       | 66.96%  |
| Desktop     | 62        | 27.31%  |
| Convertible | 6         | 2.64%   |
| Mini pc     | 2         | 0.88%   |
| All in one  | 2         | 0.88%   |
| Tablet      | 1         | 0.44%   |
| Firewall    | 1         | 0.44%   |
| Server      | 1         | 0.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 224       | 98.68%  |
| Yes  | 3         | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 79        | 34.65%  |
| 16.01-24.0  | 57        | 25%     |
| 4.01-8.0    | 41        | 17.98%  |
| 32.01-64.0  | 22        | 9.65%   |
| 2.01-3.0    | 13        | 5.7%    |
| 64.01-256.0 | 8         | 3.51%   |
| 3.01-4.0    | 3         | 1.32%   |
| 0.51-1.0    | 3         | 1.32%   |
| 24.01-32.0  | 2         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 110       | 47.62%  |
| 0.51-1.0  | 70        | 30.3%   |
| 1.01-2.0  | 35        | 15.15%  |
| 2.01-3.0  | 10        | 4.33%   |
| 4.01-8.0  | 3         | 1.3%    |
| 3.01-4.0  | 2         | 0.87%   |
| 8.01-16.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 143       | 62.45%  |
| 2      | 38        | 16.59%  |
| 0      | 29        | 12.66%  |
| 3      | 14        | 6.11%   |
| 4      | 4         | 1.75%   |
| 7      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 63.16%  |
| Yes       | 84        | 36.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 87.72%  |
| No        | 28        | 12.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 82.82%  |
| No        | 39        | 17.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 60.53%  |
| No        | 90        | 39.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 42        | 18.5%   |
| Germany      | 30        | 13.22%  |
| France       | 22        | 9.69%   |
| Russia       | 19        | 8.37%   |
| UK           | 16        | 7.05%   |
| Italy        | 8         | 3.52%   |
| Taiwan       | 6         | 2.64%   |
| Hungary      | 6         | 2.64%   |
| Finland      | 6         | 2.64%   |
| Argentina    | 6         | 2.64%   |
| Turkey       | 5         | 2.2%    |
| Spain        | 5         | 2.2%    |
| Australia    | 5         | 2.2%    |
| Switzerland  | 3         | 1.32%   |
| Poland       | 3         | 1.32%   |
| Norway       | 3         | 1.32%   |
| Mexico       | 3         | 1.32%   |
| Colombia     | 3         | 1.32%   |
| China        | 3         | 1.32%   |
| Thailand     | 2         | 0.88%   |
| Romania      | 2         | 0.88%   |
| Netherlands  | 2         | 0.88%   |
| Lithuania    | 2         | 0.88%   |
| Japan        | 2         | 0.88%   |
| Indonesia    | 2         | 0.88%   |
| Egypt        | 2         | 0.88%   |
| Czechia      | 2         | 0.88%   |
| Bulgaria     | 2         | 0.88%   |
| Brazil       | 2         | 0.88%   |
| Ukraine      | 1         | 0.44%   |
| Sweden       | 1         | 0.44%   |
| South Korea  | 1         | 0.44%   |
| Slovakia     | 1         | 0.44%   |
| Serbia       | 1         | 0.44%   |
| Saudi Arabia | 1         | 0.44%   |
| San Marino   | 1         | 0.44%   |
| Philippines  | 1         | 0.44%   |
| Hong Kong    | 1         | 0.44%   |
| Estonia      | 1         | 0.44%   |
| Denmark      | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 12        | 5.24%   |
| Franconville                | 6         | 2.62%   |
| Paris                       | 5         | 2.18%   |
| Hodmezovasarhely            | 5         | 2.18%   |
| Wuppertal                   | 4         | 1.75%   |
| Istanbul                    | 4         | 1.75%   |
| Duncan                      | 4         | 1.75%   |
| Woodland                    | 3         | 1.31%   |
| Whittier                    | 3         | 1.31%   |
| Tijuana                     | 3         | 1.31%   |
| Taipei                      | 3         | 1.31%   |
| Taichung                    | 3         | 1.31%   |
| Rome                        | 3         | 1.31%   |
| Milan                       | 3         | 1.31%   |
| Markt Indersdorf            | 3         | 1.31%   |
| Madrid                      | 3         | 1.31%   |
| Brisbane                    | 3         | 1.31%   |
| Zwingenberg                 | 2         | 0.87%   |
| Warsaw                      | 2         | 0.87%   |
| Volzhskiy                   | 2         | 0.87%   |
| Vollen                      | 2         | 0.87%   |
| Vilnius                     | 2         | 0.87%   |
| Urcuit                      | 2         | 0.87%   |
| Turku                       | 2         | 0.87%   |
| St Petersburg               | 2         | 0.87%   |
| Sofia                       | 2         | 0.87%   |
| Setagaya-ku                 | 2         | 0.87%   |
| San Nicolás de los Arroyos | 2         | 0.87%   |
| Rio de Janeiro              | 2         | 0.87%   |
| Nuremberg                   | 2         | 0.87%   |
| New Braunfels               | 2         | 0.87%   |
| Melun                       | 2         | 0.87%   |
| McDonough                   | 2         | 0.87%   |
| Lutherville-Timonium        | 2         | 0.87%   |
| Los Angeles                 | 2         | 0.87%   |
| London                      | 2         | 0.87%   |
| Greenwich                   | 2         | 0.87%   |
| Drobeta-Turnu Severin       | 2         | 0.87%   |
| Denver                      | 2         | 0.87%   |
| Cologne                     | 2         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 61     | 18.85%  |
| WDC                 | 38        | 46     | 14.62%  |
| Seagate             | 37        | 40     | 14.23%  |
| Toshiba             | 22        | 25     | 8.46%   |
| Crucial             | 13        | 13     | 5%      |
| SanDisk             | 10        | 11     | 3.85%   |
| Kingston            | 9         | 10     | 3.46%   |
| SK hynix            | 8         | 9      | 3.08%   |
| Transcend           | 7         | 7      | 2.69%   |
| Intel               | 7         | 8      | 2.69%   |
| Hitachi             | 7         | 8      | 2.69%   |
| A-DATA Technology   | 6         | 6      | 2.31%   |
| Micron Technology   | 5         | 5      | 1.92%   |
| Apple               | 5         | 6      | 1.92%   |
| Intenso             | 3         | 3      | 1.15%   |
| HGST                | 3         | 3      | 1.15%   |
| Hewlett-Packard     | 3         | 3      | 1.15%   |
| Gigabyte Technology | 3         | 3      | 1.15%   |
| Fujitsu             | 3         | 4      | 1.15%   |
| SPCC                | 2         | 2      | 0.77%   |
| PNY                 | 2         | 2      | 0.77%   |
| OCZ                 | 2         | 2      | 0.77%   |
| Corsair             | 2         | 2      | 0.77%   |
| UMIS                | 1         | 1      | 0.38%   |
| Team                | 1         | 1      | 0.38%   |
| SETHRISE            | 1         | 1      | 0.38%   |
| Phison              | 1         | 1      | 0.38%   |
| Patriot             | 1         | 1      | 0.38%   |
| ORICO               | 1         | 1      | 0.38%   |
| Maxtor              | 1         | 1      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| LITEON              | 1         | 1      | 0.38%   |
| KingDian            | 1         | 1      | 0.38%   |
| GAMER               | 1         | 1      | 0.38%   |
| Dogfish             | 1         | 1      | 0.38%   |
| ASUSTek Computer    | 1         | 2      | 0.38%   |
| AirDisk             | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 970 EVO Plus 1TB         | 4         | 1.44%   |
| Kingston SA400S37240G 240GB          | 4         | 1.44%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.08%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.08%   |
| SanDisk pSSD 16GB                    | 3         | 1.08%   |
| Samsung SSD 840 EVO 250GB            | 3         | 1.08%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.08%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.72%   |
| WDC WD40PURX-64GVNY0 4TB             | 2         | 0.72%   |
| WDC WD2500BEVT-80A23T0 250GB         | 2         | 0.72%   |
| WDC WD1600AAJS-22L7A0 160GB          | 2         | 0.72%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 2         | 0.72%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.72%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.72%   |
| Toshiba HDWD120 2TB                  | 2         | 0.72%   |
| Seagate ST95005620AS 500GB           | 2         | 0.72%   |
| Seagate ST9500325AS 500GB            | 2         | 0.72%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.72%   |
| SanDisk SSD U100 24GB                | 2         | 0.72%   |
| Samsung SSD 980 PRO 250GB            | 2         | 0.72%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.72%   |
| Samsung SSD 870 QVO 2TB              | 2         | 0.72%   |
| Samsung SP2504C 250GB                | 2         | 0.72%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 0.72%   |
| Kingston SA400S37480G 480GB          | 2         | 0.72%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.72%   |
| HP SSD EX950 2TB                     | 2         | 0.72%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 0.72%   |
| Apple SSD SM0512F 500GB              | 2         | 0.72%   |
| A-DATA SU630 240GB                   | 2         | 0.72%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.36%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.36%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.36%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.36%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.36%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.36%   |
| WDC WD60EZRZ-00GZ5B1 6TB             | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 40     | 34.91%  |
| WDC                 | 31        | 34     | 29.25%  |
| Toshiba             | 17        | 19     | 16.04%  |
| Hitachi             | 7         | 8      | 6.6%    |
| Samsung Electronics | 5         | 5      | 4.72%   |
| HGST                | 3         | 3      | 2.83%   |
| Fujitsu             | 3         | 4      | 2.83%   |
| Maxtor              | 1         | 1      | 0.94%   |
| Hewlett-Packard     | 1         | 1      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 27     | 20.95%  |
| SanDisk             | 10        | 11     | 9.52%   |
| Crucial             | 9         | 9      | 8.57%   |
| Kingston            | 8         | 9      | 7.62%   |
| Transcend           | 7         | 7      | 6.67%   |
| A-DATA Technology   | 6         | 6      | 5.71%   |
| WDC                 | 4         | 5      | 3.81%   |
| Micron Technology   | 4         | 4      | 3.81%   |
| Intel               | 4         | 5      | 3.81%   |
| Apple               | 4         | 5      | 3.81%   |
| Toshiba             | 3         | 3      | 2.86%   |
| Intenso             | 3         | 3      | 2.86%   |
| Gigabyte Technology | 3         | 3      | 2.86%   |
| SPCC                | 2         | 2      | 1.9%    |
| SK hynix            | 2         | 2      | 1.9%    |
| PNY                 | 2         | 2      | 1.9%    |
| OCZ                 | 2         | 2      | 1.9%    |
| Team                | 1         | 1      | 0.95%   |
| SETHRISE            | 1         | 1      | 0.95%   |
| Patriot             | 1         | 1      | 0.95%   |
| LITEONIT            | 1         | 1      | 0.95%   |
| LITEON              | 1         | 1      | 0.95%   |
| KingDian            | 1         | 1      | 0.95%   |
| GAMER               | 1         | 1      | 0.95%   |
| Dogfish             | 1         | 1      | 0.95%   |
| Corsair             | 1         | 1      | 0.95%   |
| ASUSTek Computer    | 1         | 2      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 94        | 116    | 39.83%  |
| HDD  | 93        | 116    | 39.41%  |
| NVMe | 49        | 62     | 20.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 167       | 232    | 77.31%  |
| NVMe | 49        | 62     | 22.69%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 123       | 152    | 63.08%  |
| 0.51-1.0   | 49        | 54     | 25.13%  |
| 1.01-2.0   | 11        | 11     | 5.64%   |
| 3.01-4.0   | 7         | 8      | 3.59%   |
| 2.01-3.0   | 4         | 4      | 2.05%   |
| 4.01-10.0  | 1         | 3      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 175       | 76.75%  |
| 101-250    | 23        | 10.09%  |
| 21-50      | 13        | 5.7%    |
| 51-100     | 8         | 3.51%   |
| 251-500    | 4         | 1.75%   |
| 501-1000   | 4         | 1.75%   |
| 1001-2000  | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 223       | 97.81%  |
| 21-50   | 3         | 1.32%   |
| 51-100  | 2         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 2.7%    |
| WDC WD40PURX-64GVNY0 4TB                         | 1         | 1      | 2.7%    |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 2.7%    |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 2.7%    |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 2.7%    |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.7%    |
| WDC WD10EFRX-68PJCN0 1TB                         | 1         | 2      | 2.7%    |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.7%    |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 2.7%    |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 2.7%    |
| Toshiba HDWD120 2TB                              | 1         | 1      | 2.7%    |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 2.7%    |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 2.7%    |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST3250823AS 250GB                        | 1         | 1      | 2.7%    |
| Seagate ST310212A 10GB                           | 1         | 1      | 2.7%    |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 2.7%    |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 2.7%    |
| Samsung Electronics SP2504C 250GB                | 1         | 1      | 2.7%    |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.7%    |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 2.7%    |
| Micron Technology 1100_MTFDDAV256TBN 256GB       | 1         | 1      | 2.7%    |
| Intenso SSD Sata III 248GB                       | 1         | 1      | 2.7%    |
| Intenso SSD Sata III 128GB                       | 1         | 1      | 2.7%    |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 2.7%    |
| Hitachi HTS545050B9A300 500GB                    | 1         | 2      | 2.7%    |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 2.7%    |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 2.7%    |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 2.7%    |
| Hewlett-Packard MB1000GCWCV 1TB                  | 1         | 1      | 2.7%    |
| Crucial CT120M500SSD1 120GB                      | 1         | 1      | 2.7%    |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 2.7%    |
| A-DATA Technology XM13 32GB                      | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 18.92%  |
| Seagate             | 7         | 7      | 18.92%  |
| Toshiba             | 6         | 6      | 16.22%  |
| Samsung Electronics | 3         | 3      | 8.11%   |
| Hitachi             | 3         | 4      | 8.11%   |
| Micron Technology   | 2         | 2      | 5.41%   |
| Intenso             | 2         | 2      | 5.41%   |
| SanDisk             | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Hewlett-Packard     | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| Corsair             | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 25.93%  |
| Seagate             | 7         | 7      | 25.93%  |
| Toshiba             | 6         | 6      | 22.22%  |
| Hitachi             | 3         | 4      | 11.11%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| HGST                | 1         | 1      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 29     | 72.22%  |
| SSD  | 10        | 10     | 27.78%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model             | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 16GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 173       | 246    | 81.6%   |
| Malfunc  | 36        | 39     | 16.98%  |
| Detected | 2         | 8      | 0.94%   |
| Failed   | 1         | 1      | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 148       | 54.01%  |
| AMD                                     | 36        | 13.14%  |
| Samsung Electronics                     | 33        | 12.04%  |
| SanDisk                                 | 12        | 4.38%   |
| ASMedia Technology                      | 8         | 2.92%   |
| Nvidia                                  | 7         | 2.55%   |
| SK hynix                                | 5         | 1.82%   |
| Micron/Crucial Technology               | 5         | 1.82%   |
| VIA Technologies                        | 2         | 0.73%   |
| Toshiba                                 | 2         | 0.73%   |
| Phison Electronics                      | 2         | 0.73%   |
| Micron Technology                       | 2         | 0.73%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.73%   |
| KIOXIA                                  | 2         | 0.73%   |
| Kingston Technology Company             | 2         | 0.73%   |
| Biwin Storage Technology                | 2         | 0.73%   |
| Silicon Motion                          | 1         | 0.36%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.36%   |
| Shenzhen Unionmemory Information System | 1         | 0.36%   |
| JMicron Technology                      | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 7.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 6.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 5.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 4.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 2.86%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8         | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.9%    |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.27%   |
| Intel SATA Controller [RAID Mode]                                              | 4         | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 4         | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 1.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.95%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 0.95%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.63%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 0.63%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.63%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 2         | 0.63%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 0.63%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 2         | 0.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 0.63%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 0.63%   |
| Nvidia MCP61 SATA Controller                                                   | 2         | 0.63%   |
| Nvidia MCP61 IDE                                                               | 2         | 0.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.63%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 2         | 0.63%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 152       | 55.47%  |
| NVMe | 65        | 23.72%  |
| IDE  | 36        | 13.14%  |
| RAID | 18        | 6.57%   |
| SAS  | 3         | 1.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 182       | 79.82%  |
| AMD    | 46        | 20.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.75%   |
| Intel CPU Version                             | 3         | 1.32%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.32%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.32%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.32%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.32%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.32%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.88%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.88%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.88%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.88%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.88%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.88%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.88%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.88%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 2         | 0.88%   |
| Intel Core 2 Duo                              | 2         | 0.88%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 0.88%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 0.88%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.88%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.88%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 0.88%   |
| Intel Xeon CPU E5640 @ 2.67GHz                | 1         | 0.44%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.44%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz              | 1         | 0.44%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 0.44%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz           | 1         | 0.44%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 63        | 27.63%  |
| Intel Core i7           | 48        | 21.05%  |
| Other                   | 14        | 6.14%   |
| Intel Core 2 Duo        | 12        | 5.26%   |
| AMD Ryzen 5             | 12        | 5.26%   |
| AMD Ryzen 7             | 11        | 4.82%   |
| Intel Core i3           | 9         | 3.95%   |
| Intel Xeon              | 7         | 3.07%   |
| Intel Celeron           | 7         | 3.07%   |
| Intel Atom              | 7         | 3.07%   |
| AMD A6                  | 4         | 1.75%   |
| Intel Pentium           | 3         | 1.32%   |
| AMD Ryzen 7 PRO         | 3         | 1.32%   |
| AMD A8                  | 3         | 1.32%   |
| Intel Pentium Dual-Core | 2         | 0.88%   |
| Intel Core i9           | 2         | 0.88%   |
| Intel Celeron Dual-Core | 2         | 0.88%   |
| AMD Ryzen 9             | 2         | 0.88%   |
| AMD GX                  | 2         | 0.88%   |
| AMD Athlon 64 X2        | 2         | 0.88%   |
| Intel Pentium Silver    | 1         | 0.44%   |
| Intel Pentium III       | 1         | 0.44%   |
| Intel Pentium D         | 1         | 0.44%   |
| Intel Genuine           | 1         | 0.44%   |
| Intel Core m5           | 1         | 0.44%   |
| Intel Core 2            | 1         | 0.44%   |
| Intel Core              | 1         | 0.44%   |
| Intel Celeron M         | 1         | 0.44%   |
| AMD Turion 64 X2 Mobile | 1         | 0.44%   |
| AMD Phenom II X4        | 1         | 0.44%   |
| AMD FX                  | 1         | 0.44%   |
| AMD E1                  | 1         | 0.44%   |
| AMD A10                 | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 90        | 39.47%  |
| 4       | 71        | 31.14%  |
| 8       | 14        | 6.14%   |
| 6       | 12        | 5.26%   |
| Unknown | 12        | 5.26%   |
| 16      | 11        | 4.82%   |
| 12      | 9         | 3.95%   |
| 1       | 6         | 2.63%   |
| 24      | 2         | 0.88%   |
| 20      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 223       | 98.24%  |
| 2       | 3         | 1.32%   |
| Unknown | 1         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 128       | 56.14%  |
| 1       | 86        | 37.72%  |
| Unknown | 14        | 6.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 41        | 17.98%  |
| Haswell       | 25        | 10.96%  |
| IvyBridge     | 21        | 9.21%   |
| Skylake       | 19        | 8.33%   |
| Penryn        | 18        | 7.89%   |
| SandyBridge   | 13        | 5.7%    |
| Unknown       | 12        | 5.26%   |
| Bonnell       | 8         | 3.51%   |
| Zen+          | 7         | 3.07%   |
| Zen 2         | 6         | 2.63%   |
| Puma          | 6         | 2.63%   |
| Zen 3         | 5         | 2.19%   |
| CometLake     | 5         | 2.19%   |
| Zen           | 4         | 1.75%   |
| Broadwell     | 4         | 1.75%   |
| Westmere      | 3         | 1.32%   |
| TigerLake     | 3         | 1.32%   |
| Silvermont    | 3         | 1.32%   |
| Nehalem       | 3         | 1.32%   |
| K8 Hammer     | 3         | 1.32%   |
| Jaguar        | 3         | 1.32%   |
| Core          | 3         | 1.32%   |
| P6            | 2         | 0.88%   |
| K10           | 2         | 0.88%   |
| Goldmont plus | 2         | 0.88%   |
| Goldmont      | 2         | 0.88%   |
| Steamroller   | 1         | 0.44%   |
| Piledriver    | 1         | 0.44%   |
| NetBurst      | 1         | 0.44%   |
| K10 Llano     | 1         | 0.44%   |
| Excavator     | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 144       | 56.92%  |
| AMD                        | 55        | 21.74%  |
| Nvidia                     | 51        | 20.16%  |
| VIA Technologies           | 1         | 0.4%    |
| S3 Graphics                | 1         | 0.4%    |
| Matrox Electronics Systems | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 5.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 4.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 4.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.86%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.7%    |
| Intel HD Graphics 620                                                                    | 7         | 2.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.32%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 2.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.54%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.54%   |
| AMD Lucienne                                                                             | 4         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.16%   |
| Intel HD Graphics 530                                                                    | 3         | 1.16%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.16%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 1.16%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.77%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.77%   |
| Intel HD Graphics 630                                                                    | 2         | 0.77%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.77%   |
| Intel HD Graphics 500                                                                    | 2         | 0.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.77%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.77%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.77%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 0.77%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 109       | 47.81%  |
| 1 x AMD         | 49        | 21.49%  |
| 1 x Nvidia      | 29        | 12.72%  |
| Intel + Nvidia  | 20        | 8.77%   |
| 2 x Intel       | 12        | 5.26%   |
| 2 x AMD         | 2         | 0.88%   |
| Intel + AMD     | 2         | 0.88%   |
| AMD + Nvidia    | 2         | 0.88%   |
| 1 x VIA         | 1         | 0.44%   |
| 1 x S3 Graphics | 1         | 0.44%   |
| 1 x Matrox      | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 190       | 83.7%   |
| Proprietary | 19        | 8.37%   |
| Unknown     | 18        | 7.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 82.89%  |
| 0.01-0.5   | 12        | 5.26%   |
| 1.01-2.0   | 9         | 3.95%   |
| 0.51-1.0   | 6         | 2.63%   |
| 3.01-4.0   | 5         | 2.19%   |
| 5.01-6.0   | 4         | 1.75%   |
| 7.01-8.0   | 3         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24        | 12.83%  |
| AU Optronics            | 23        | 12.3%   |
| LG Display              | 19        | 10.16%  |
| BOE                     | 19        | 10.16%  |
| Chimei Innolux          | 15        | 8.02%   |
| Goldstar                | 11        | 5.88%   |
| Dell                    | 10        | 5.35%   |
| Hewlett-Packard         | 6         | 3.21%   |
| Apple                   | 6         | 3.21%   |
| Acer                    | 6         | 3.21%   |
| Sharp                   | 5         | 2.67%   |
| HannStar                | 5         | 2.67%   |
| ViewSonic               | 4         | 2.14%   |
| Fujitsu Siemens         | 4         | 2.14%   |
| Chi Mei Optoelectronics | 4         | 2.14%   |
| Lenovo                  | 3         | 1.6%    |
| Philips                 | 2         | 1.07%   |
| Panasonic               | 2         | 1.07%   |
| NEC Computers           | 2         | 1.07%   |
| BenQ                    | 2         | 1.07%   |
| ASUSTek Computer        | 2         | 1.07%   |
| Ancor Communications    | 2         | 1.07%   |
| ___                     | 1         | 0.53%   |
| Westinghouse            | 1         | 0.53%   |
| Vizio                   | 1         | 0.53%   |
| Toshiba                 | 1         | 0.53%   |
| Sony                    | 1         | 0.53%   |
| LG Philips              | 1         | 0.53%   |
| LG Electronics          | 1         | 0.53%   |
| CSW                     | 1         | 0.53%   |
| CSO                     | 1         | 0.53%   |
| CPT                     | 1         | 0.53%   |
| AOC                     | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 3         | 1.58%   |
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch           | 3         | 1.58%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 2         | 1.05%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 2         | 1.05%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 1.05%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 1.05%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 1.05%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.05%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch             | 2         | 1.05%   |
| Apple LCD Monitor APP9CCB 1280x800 290x180mm 13.4-inch                   | 2         | 1.05%   |
| ___ MY TV LED TV ___0101 1920x1080                                       | 1         | 0.53%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch             | 1         | 0.53%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                     | 1         | 0.53%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                    | 1         | 0.53%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch               | 1         | 0.53%   |
| ViewSonic VA2212 Series VSCBD2B 1920x1080 480x270mm 21.7-inch            | 1         | 0.53%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch            | 1         | 0.53%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch                | 1         | 0.53%   |
| Sony TV SNY5D01 1360x768                                                 | 1         | 0.53%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP14C2 1920x1080 260x140mm 11.6-inch                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 0.53%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch        | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.53%   |
| Samsung Electronics SA300/350/360 SAM07D5 1920x1080 530x300mm 24.0-inch  | 1         | 0.53%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch        | 1         | 0.53%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 0.53%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                        | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3152 1024x600 220x130mm 10.1-inch     | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 72        | 39.34%  |
| 1366x768 (WXGA)    | 42        | 22.95%  |
| 1280x1024 (SXGA)   | 11        | 6.01%   |
| 3840x2160 (4K)     | 9         | 4.92%   |
| 1920x1200 (WUXGA)  | 7         | 3.83%   |
| 1600x900 (HD+)     | 7         | 3.83%   |
| 1440x900 (WXGA+)   | 6         | 3.28%   |
| 1280x800 (WXGA)    | 6         | 3.28%   |
| 1024x600           | 6         | 3.28%   |
| 2560x1440 (QHD)    | 5         | 2.73%   |
| 2880x1800          | 3         | 1.64%   |
| 1680x1050 (WSXGA+) | 2         | 1.09%   |
| 1360x768           | 2         | 1.09%   |
| 3200x1800 (QHD+)   | 1         | 0.55%   |
| 2736x1824          | 1         | 0.55%   |
| 2560x1080          | 1         | 0.55%   |
| 2160x1350          | 1         | 0.55%   |
| 1600x1200          | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 50        | 26.6%   |
| 13      | 32        | 17.02%  |
| 24      | 16        | 8.51%   |
| 17      | 15        | 7.98%   |
| 12      | 14        | 7.45%   |
| 27      | 10        | 5.32%   |
| 19      | 10        | 5.32%   |
| 21      | 8         | 4.26%   |
| 23      | 6         | 3.19%   |
| 10      | 6         | 3.19%   |
| 11      | 5         | 2.66%   |
| Unknown | 4         | 2.13%   |
| 18      | 3         | 1.6%    |
| 22      | 2         | 1.06%   |
| 14      | 2         | 1.06%   |
| 39      | 1         | 0.53%   |
| 37      | 1         | 0.53%   |
| 34      | 1         | 0.53%   |
| 31      | 1         | 0.53%   |
| 25      | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 39.78%  |
| 201-300     | 41        | 22.04%  |
| 501-600     | 30        | 16.13%  |
| 401-500     | 17        | 9.14%   |
| 351-400     | 14        | 7.53%   |
| Unknown     | 4         | 2.15%   |
| 601-700     | 3         | 1.61%   |
| 801-900     | 2         | 1.08%   |
| 701-800     | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 136       | 76.84%  |
| 16/10   | 24        | 13.56%  |
| 5/4     | 11        | 6.21%   |
| 3/2     | 3         | 1.69%   |
| Unknown | 2         | 1.13%   |
| 21/9    | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 39        | 20.74%  |
| 201-250        | 27        | 14.36%  |
| 81-90          | 25        | 13.3%   |
| 61-70          | 13        | 6.91%   |
| 71-80          | 10        | 5.32%   |
| 301-350        | 10        | 5.32%   |
| 151-200        | 10        | 5.32%   |
| 101-110        | 10        | 5.32%   |
| 141-150        | 9         | 4.79%   |
| 121-130        | 8         | 4.26%   |
| 41-50          | 6         | 3.19%   |
| 251-300        | 6         | 3.19%   |
| 51-60          | 5         | 2.66%   |
| Unknown        | 4         | 2.13%   |
| 351-500        | 2         | 1.06%   |
| 501-1000       | 2         | 1.06%   |
| 131-140        | 1         | 0.53%   |
| 111-120        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 53        | 28.8%   |
| 51-100        | 53        | 28.8%   |
| 121-160       | 46        | 25%     |
| 161-240       | 19        | 10.33%  |
| More than 240 | 9         | 4.89%   |
| Unknown       | 4         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 175       | 76.42%  |
| 0     | 41        | 17.9%   |
| 2     | 11        | 4.8%    |
| 3     | 2         | 0.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 126       | 36.52%  |
| Realtek Semiconductor                  | 99        | 28.7%   |
| Qualcomm Atheros                       | 42        | 12.17%  |
| Broadcom                               | 25        | 7.25%   |
| Samsung Electronics                    | 6         | 1.74%   |
| Ralink Technology                      | 5         | 1.45%   |
| TP-Link                                | 4         | 1.16%   |
| Ralink                                 | 4         | 1.16%   |
| Marvell Technology Group               | 4         | 1.16%   |
| Sierra Wireless                        | 2         | 0.58%   |
| Qualcomm                               | 2         | 0.58%   |
| Nvidia                                 | 2         | 0.58%   |
| Mellanox Technologies                  | 2         | 0.58%   |
| MediaTek                               | 2         | 0.58%   |
| Fibocom                                | 2         | 0.58%   |
| Ericsson Business Mobile Networks      | 2         | 0.58%   |
| VIA Technologies                       | 1         | 0.29%   |
| U-Blox                                 | 1         | 0.29%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.29%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.29%   |
| Qualcomm Technologies                  | 1         | 0.29%   |
| NetGear                                | 1         | 0.29%   |
| Microchip Technology                   | 1         | 0.29%   |
| JMicron Technology                     | 1         | 0.29%   |
| Huawei Technologies                    | 1         | 0.29%   |
| Edimax Technology                      | 1         | 0.29%   |
| Dell                                   | 1         | 0.29%   |
| D-Link System                          | 1         | 0.29%   |
| D-Link                                 | 1         | 0.29%   |
| Brooktrout Technology                  | 1         | 0.29%   |
| Atheros                                | 1         | 0.29%   |
| Apple                                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 67        | 15.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 3.02%   |
| Intel Wireless 8265 / 8275                                             | 11        | 2.55%   |
| Intel Wireless 7260                                                    | 11        | 2.55%   |
| Intel Wireless 8260                                                    | 9         | 2.09%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 2.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 1.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7         | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.39%   |
| Intel Wireless 3165                                                    | 6         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.16%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 4         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.93%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.93%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 4         | 0.93%   |
| Intel Wireless 7265                                                    | 3         | 0.7%    |
| Intel WiFi Link 5100                                                   | 3         | 0.7%    |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.7%    |
| Intel Ethernet Controller I225-V                                       | 3         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 0.7%    |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.7%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.46%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 2         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.46%   |
| Ralink RT5372 Wireless Adapter                                         | 2         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 95        | 47.03%  |
| Qualcomm Atheros         | 36        | 17.82%  |
| Realtek Semiconductor    | 32        | 15.84%  |
| Broadcom                 | 16        | 7.92%   |
| Ralink Technology        | 5         | 2.48%   |
| TP-Link                  | 4         | 1.98%   |
| Ralink                   | 4         | 1.98%   |
| MediaTek                 | 2         | 0.99%   |
| Sierra Wireless          | 1         | 0.5%    |
| Qualcomm Technologies    | 1         | 0.5%    |
| NetGear                  | 1         | 0.5%    |
| Marvell Technology Group | 1         | 0.5%    |
| Edimax Technology        | 1         | 0.5%    |
| D-Link System            | 1         | 0.5%    |
| D-Link                   | 1         | 0.5%    |
| Atheros                  | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 11        | 5.34%   |
| Intel Wireless 7260                                            | 11        | 5.34%   |
| Intel Wireless 8260                                            | 9         | 4.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 3.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.91%   |
| Intel Wireless 3165                                            | 6         | 2.91%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 2.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.94%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 1.94%   |
| Intel Wireless 7265                                            | 3         | 1.46%   |
| Intel WiFi Link 5100                                           | 3         | 1.46%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.46%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.97%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2         | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.97%   |
| Ralink RT5372 Wireless Adapter                                 | 2         | 0.97%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 2         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.97%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 0.97%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 0.97%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.97%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 0.97%   |
| TP-Link Wireless USB Adapter                                   | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 89        | 42.58%  |
| Intel                                  | 79        | 37.8%   |
| Broadcom                               | 14        | 6.7%    |
| Qualcomm Atheros                       | 9         | 4.31%   |
| Samsung Electronics                    | 6         | 2.87%   |
| Marvell Technology Group               | 3         | 1.44%   |
| Qualcomm                               | 2         | 0.96%   |
| Nvidia                                 | 2         | 0.96%   |
| VIA Technologies                       | 1         | 0.48%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.48%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.48%   |
| JMicron Technology                     | 1         | 0.48%   |
| Apple                                  | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 67        | 31.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 8.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 6.1%    |
| Intel Ethernet Connection I217-LM                                      | 9         | 4.23%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 3.76%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 2.35%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 2.35%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 2.35%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 1.88%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.88%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.41%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 3         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.94%   |
| Qualcomm ALCATEL RNDIS Interface                                       | 2         | 0.94%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.94%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.94%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.94%   |
| Intel Ethernet Connection (11) I219-V                                  | 2         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.94%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.47%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.47%   |
| Nvidia MCP73 Ethernet                                                  | 1         | 0.47%   |
| Nvidia MCP65 Ethernet                                                  | 1         | 0.47%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 201       | 50%     |
| WiFi     | 189       | 47.01%  |
| Unknown  | 10        | 2.49%   |
| Modem    | 2         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 162       | 57.65%  |
| WiFi     | 114       | 40.57%  |
| Unknown  | 5         | 1.78%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 151       | 66.23%  |
| 1     | 70        | 30.7%   |
| 4     | 3         | 1.32%   |
| 3     | 3         | 1.32%   |
| 0     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 203       | 89.04%  |
| Yes  | 25        | 10.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 47.86%  |
| Realtek Semiconductor           | 12        | 8.57%   |
| Broadcom                        | 11        | 7.86%   |
| Qualcomm Atheros Communications | 9         | 6.43%   |
| Lite-On Technology              | 9         | 6.43%   |
| Apple                           | 8         | 5.71%   |
| IMC Networks                    | 6         | 4.29%   |
| ASUSTek Computer                | 5         | 3.57%   |
| Foxconn / Hon Hai               | 4         | 2.86%   |
| Cambridge Silicon Radio         | 3         | 2.14%   |
| USI                             | 1         | 0.71%   |
| TP-Link                         | 1         | 0.71%   |
| Hewlett-Packard                 | 1         | 0.71%   |
| Dell                            | 1         | 0.71%   |
| Chicony Electronics             | 1         | 0.71%   |
| Alps Electric                   | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 34        | 24.29%  |
| Intel AX201 Bluetooth                                       | 10        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 5%      |
| Intel AX200 Bluetooth                                       | 6         | 4.29%   |
| Apple Bluetooth Host Controller                             | 6         | 4.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 2.86%   |
| Lite-On Bluetooth USB Module                                | 3         | 2.14%   |
| Intel AX211 Bluetooth                                       | 3         | 2.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 2.14%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.43%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.43%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 1.43%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 1.43%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.43%   |
| Intel AX210 Bluetooth                                       | 2         | 1.43%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.43%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.43%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 1.43%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.43%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.71%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1         | 0.71%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.71%   |
| Realtek Bluetooth Adapter                                   | 1         | 0.71%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.71%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.71%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.71%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.71%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.71%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.71%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.71%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 173       | 60.92%  |
| AMD                              | 55        | 19.37%  |
| Nvidia                           | 30        | 10.56%  |
| C-Media Electronics              | 3         | 1.06%   |
| XMOS                             | 2         | 0.7%    |
| Sony                             | 2         | 0.7%    |
| Realtek Semiconductor            | 2         | 0.7%    |
| Corsair                          | 2         | 0.7%    |
| BEHRINGER International          | 2         | 0.7%    |
| VIA Technologies                 | 1         | 0.35%   |
| Tenx Technology                  | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| RME                              | 1         | 0.35%   |
| Quanta                           | 1         | 0.35%   |
| LG Electronics                   | 1         | 0.35%   |
| Lenovo                           | 1         | 0.35%   |
| Focusrite-Novation               | 1         | 0.35%   |
| Creative Technology              | 1         | 0.35%   |
| Creative Labs                    | 1         | 0.35%   |
| Blue Microphones                 | 1         | 0.35%   |
| Audio-Technica                   | 1         | 0.35%   |
| ASUSTek Computer                 | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 32        | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 5.68%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 19        | 5.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 3.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 3.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 12        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 3.41%   |
| Intel 8 Series HD Audio Controller                                         | 12        | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 3.13%   |
| AMD FCH Azalia Controller                                                  | 11        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 2.84%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.42%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 0.85%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.57%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.57%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.57%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 76        | 28.57%  |
| SK hynix            | 49        | 18.42%  |
| Micron Technology   | 35        | 13.16%  |
| Kingston            | 22        | 8.27%   |
| Unknown             | 21        | 7.89%   |
| Crucial             | 10        | 3.76%   |
| Corsair             | 10        | 3.76%   |
| G.Skill             | 8         | 3.01%   |
| Elpida              | 7         | 2.63%   |
| Unknown             | 7         | 2.63%   |
| Nanya Technology    | 5         | 1.88%   |
| A-DATA Technology   | 4         | 1.5%    |
| Transcend           | 3         | 1.13%   |
| Ramaxel Technology  | 2         | 0.75%   |
| 48spaces            | 2         | 0.75%   |
| Unknown (ABCD)      | 1         | 0.38%   |
| Unknown (09D5)      | 1         | 0.38%   |
| Qimonda             | 1         | 0.38%   |
| Magnum Tech         | 1         | 0.38%   |
| EVGA                | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 7         | 2.46%   |
| Unknown                                                          | 7         | 2.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 1.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.06%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.06%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 2         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.7%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 2         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.7%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.7%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.7%    |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 2         | 0.7%    |
| Micron RAM ITC 4GB DIMM DDR3 1066MT/s                            | 2         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.7%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.7%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2933MT/s                | 2         | 0.7%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.7%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 92        | 40.17%  |
| DDR4    | 82        | 35.81%  |
| DDR2    | 23        | 10.04%  |
| LPDDR3  | 12        | 5.24%   |
| SDRAM   | 5         | 2.18%   |
| DDR5    | 4         | 1.75%   |
| LPDDR5  | 3         | 1.31%   |
| Unknown | 3         | 1.31%   |
| LPDDR4  | 2         | 0.87%   |
| RAM     | 1         | 0.44%   |
| DRAM    | 1         | 0.44%   |
| DDR     | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 154       | 67.54%  |
| DIMM         | 58        | 25.44%  |
| Row Of Chips | 10        | 4.39%   |
| Chip         | 4         | 1.75%   |
| Unknown      | 2         | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 92        | 35.94%  |
| 4096  | 77        | 30.08%  |
| 2048  | 44        | 17.19%  |
| 16384 | 26        | 10.16%  |
| 1024  | 10        | 3.91%   |
| 32768 | 5         | 1.95%   |
| 512   | 1         | 0.39%   |
| 128   | 1         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 60        | 24.79%  |
| 3200    | 26        | 10.74%  |
| 2667    | 22        | 9.09%   |
| 2400    | 22        | 9.09%   |
| 2133    | 19        | 7.85%   |
| 1333    | 17        | 7.02%   |
| 800     | 10        | 4.13%   |
| 667     | 10        | 4.13%   |
| 1334    | 9         | 3.72%   |
| 1867    | 7         | 2.89%   |
| Unknown | 6         | 2.48%   |
| 1067    | 5         | 2.07%   |
| 1066    | 5         | 2.07%   |
| 6400    | 3         | 1.24%   |
| 5600    | 3         | 1.24%   |
| 3600    | 3         | 1.24%   |
| 3000    | 3         | 1.24%   |
| 2933    | 3         | 1.24%   |
| 533     | 3         | 1.24%   |
| 4800    | 1         | 0.41%   |
| 4267    | 1         | 0.41%   |
| 1866    | 1         | 0.41%   |
| 1639    | 1         | 0.41%   |
| 975     | 1         | 0.41%   |
| 400     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 25%     |
| Dymo-CoStar        | 1         | 25%     |
| Brother Industries | 1         | 25%     |
| Apple              | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HP PNP Fax Null                                                          | 1         | 20%     |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 20%     |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                     | 1         | 20%     |
| Brother HL-L2340D series                                                 | 1         | 20%     |
| Apple Gamesir-G3s 2.10                                                   | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Seiko Epson ES-H7200 [GT-20000] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 35        | 25.93%  |
| Bison Electronics                      | 16        | 11.85%  |
| Realtek Semiconductor                  | 14        | 10.37%  |
| Sunplus Innovation Technology          | 10        | 7.41%   |
| Suyin                                  | 9         | 6.67%   |
| IMC Networks                           | 9         | 6.67%   |
| Microdia                               | 8         | 5.93%   |
| Quanta                                 | 5         | 3.7%    |
| Logitech                               | 5         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.7%    |
| Lite-On Technology                     | 4         | 2.96%   |
| Silicon Motion                         | 3         | 2.22%   |
| Apple                                  | 2         | 1.48%   |
| Z-Star Microelectronics                | 1         | 0.74%   |
| Syntek                                 | 1         | 0.74%   |
| Supreme Electronics                    | 1         | 0.74%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.74%   |
| Novatek Microelectronics               | 1         | 0.74%   |
| Luxvisions Innotech Limited            | 1         | 0.74%   |
| Intel                                  | 1         | 0.74%   |
| Genesys Logic                          | 1         | 0.74%   |
| Cubeternet                             | 1         | 0.74%   |
| Alcor Micro                            | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 13        | 9.56%   |
| Bison Integrated Camera                                     | 7         | 5.15%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 2.94%   |
| Chicony HD WebCam                                           | 4         | 2.94%   |
| Realtek Lenovo EasyCamera                                   | 3         | 2.21%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.21%   |
| Microdia Integrated_Webcam_HD                               | 3         | 2.21%   |
| Microdia Integrated Webcam                                  | 3         | 2.21%   |
| Suyin Acer Crystal Eye webcam                               | 2         | 1.47%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 1.47%   |
| Quanta Realtek DMFT RGB                                     | 2         | 1.47%   |
| Quanta Front Camera                                         | 2         | 1.47%   |
| Logitech HD Pro Webcam C920                                 | 2         | 1.47%   |
| Lite-On Integrated Camera                                   | 2         | 1.47%   |
| IMC Networks Realtek PC Camera                              | 2         | 1.47%   |
| IMC Networks Integrated Camera                              | 2         | 1.47%   |
| IMC Networks EasyCamera                                     | 2         | 1.47%   |
| Chicony FJ Camera                                           | 2         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 1.47%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.47%   |
| Bison SunplusIT Integrated Camera                           | 2         | 1.47%   |
| Bison EasyCamera                                            | 2         | 1.47%   |
| Apple FaceTime HD Camera                                    | 2         | 1.47%   |
| Z-Star Webcam                                               | 1         | 0.74%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.74%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.74%   |
| Suyin Laptop_Integrated_Webcam_3M                           | 1         | 0.74%   |
| Suyin HP Webcam-50                                          | 1         | 0.74%   |
| Suyin HD WebCam                                             | 1         | 0.74%   |
| Suyin HD Video WebCam                                       | 1         | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.74%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.74%   |
| Supreme Integrated Camera                                   | 1         | 0.74%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.74%   |
| Sunplus Integrated Webcam                                   | 1         | 0.74%   |
| Sunplus Hy HD Camera                                        | 1         | 0.74%   |
| Sunplus HD WebCam                                           | 1         | 0.74%   |
| Sunplus Asus Webcam                                         | 1         | 0.74%   |
| Sunplus 2-USB 2.0 Camera                                    | 1         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 39.47%  |
| Synaptics                  | 11        | 28.95%  |
| Upek                       | 4         | 10.53%  |
| LighTuning Technology      | 3         | 7.89%   |
| Shenzhen Goodix Technology | 2         | 5.26%   |
| Elan Microelectronics      | 1         | 2.63%   |
| Broadcom                   | 1         | 2.63%   |
| AuthenTec                  | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 6         | 15.79%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 4         | 10.53%  |
| Validity Sensors Synaptics WBDI                                              | 4         | 10.53%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 7.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 7.89%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 5.26%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 2.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 2.63%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 1         | 2.63%   |
| LighTuning Fingerprint Reader                                                | 1         | 2.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2.63%   |
| Elan Fingerprint Sensor                                                      | 1         | 2.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.63%   |
| AuthenTec AES1600                                                            | 1         | 2.63%   |
| Unknown                                                                      | 1         | 2.63%   |

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
| 1     | 75        | 32.33%  |
| 2     | 64        | 27.59%  |
| 0     | 40        | 17.24%  |
| 3     | 29        | 12.5%   |
| 4     | 17        | 7.33%   |
| 5     | 4         | 1.72%   |
| 7     | 2         | 0.86%   |
| 6     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 146       | 41.01%  |
| Net/wireless             | 60        | 16.85%  |
| Bluetooth                | 46        | 12.92%  |
| Fingerprint reader       | 37        | 10.39%  |
| Firewire controller      | 27        | 7.58%   |
| Card reader              | 27        | 7.58%   |
| Network                  | 6         | 1.69%   |
| Sound                    | 4         | 1.12%   |
| Net/ethernet             | 2         | 0.56%   |
| Storage/raid             | 1         | 0.28%   |

