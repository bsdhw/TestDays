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

Total: 245

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NomadBSD 5806f915 | 54        | 27.69%  |
| NomadBSD 1.3.2    | 52        | 26.67%  |
| NomadBSD 20221130 | 34        | 17.44%  |
| NomadBSD 1.4      | 23        | 11.79%  |
| NomadBSD 1.4-RC1  | 10        | 5.13%   |
| NomadBSD 1.3.1    | 10        | 5.13%   |
| NomadBSD 20231013 | 8         | 4.1%    |
| NomadBSD 81e34fc3 | 1         | 0.51%   |
| NomadBSD 80dec9b9 | 1         | 0.51%   |
| NomadBSD 1.3      | 1         | 0.51%   |
| NomadBSD 1.0      | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| NomadBSD | 190       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 182       | 95.29%  |
| i386  | 9         | 4.71%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 161       | 84.29%  |
| KDE5          | 10        | 5.24%   |
| xinitrc       | 7         | 3.66%   |
| GNOME         | 7         | 3.66%   |
| Enlightenment | 3         | 1.57%   |
| XFCE          | 1         | 0.52%   |
| GNUstep       | 1         | 0.52%   |
| filer         | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 190       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 144       | 75.79%  |
| SDDM    | 44        | 23.16%  |
| LightDM | 2         | 1.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 65        | 33.85%  |
| Unknown | 38        | 19.79%  |
| de_DE   | 18        | 9.38%   |
| en_GB   | 13        | 6.77%   |
| ru_RU   | 9         | 4.69%   |
| zh_TW   | 6         | 3.13%   |
| fr_FR   | 6         | 3.13%   |
| it_IT   | 5         | 2.6%    |
| hu_HU   | 5         | 2.6%    |
| fi_FI   | 4         | 2.08%   |
| zh_CN   | 3         | 1.56%   |
| tr_TR   | 3         | 1.56%   |
| es_ES   | 3         | 1.56%   |
| pt_BR   | 2         | 1.04%   |
| pl_PL   | 2         | 1.04%   |
| en_AU   | 2         | 1.04%   |
| cs_CZ   | 2         | 1.04%   |
| bg_BG   | 2         | 1.04%   |
| sv_SE   | 1         | 0.52%   |
| lt_LT   | 1         | 0.52%   |
| ko_KR   | 1         | 0.52%   |
| et_EE   | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 184       | 96.34%  |
| BIOS | 7         | 3.66%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 151       | 79.47%  |
| Zfs  | 39        | 20.53%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 131       | 68.59%  |
| MBR  | 60        | 31.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 21.05%  |
| Hewlett-Packard     | 25        | 13.16%  |
| Dell                | 25        | 13.16%  |
| ASUSTek Computer    | 25        | 13.16%  |
| Acer                | 12        | 6.32%   |
| Gigabyte Technology | 8         | 4.21%   |
| ASRock              | 6         | 3.16%   |
| Apple               | 6         | 3.16%   |
| Fujitsu             | 5         | 2.63%   |
| TUXEDO              | 4         | 2.11%   |
| Sony                | 3         | 1.58%   |
| Samsung Electronics | 3         | 1.58%   |
| Intel               | 3         | 1.58%   |
| Pegatron            | 2         | 1.05%   |
| Notebook            | 2         | 1.05%   |
| Google              | 2         | 1.05%   |
| Fujitsu Siemens     | 2         | 1.05%   |
| Unknown             | 2         | 1.05%   |
| Toshiba             | 1         | 0.53%   |
| Sophos              | 1         | 0.53%   |
| Semp Toshiba        | 1         | 0.53%   |
| Panasonic           | 1         | 0.53%   |
| NEC Computers       | 1         | 0.53%   |
| MSI                 | 1         | 0.53%   |
| IBM                 | 1         | 0.53%   |
| GEO                 | 1         | 0.53%   |
| Foxconn             | 1         | 0.53%   |
| eMachines           | 1         | 0.53%   |
| ECS                 | 1         | 0.53%   |
| Clevo               | 1         | 0.53%   |
| Chuwi               | 1         | 0.53%   |
| ASRockRack          | 1         | 0.53%   |
| Alienware           | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 1.58%   |
| HP Z420 Workstation                       | 2         | 1.05%   |
| Fujitsu FUTRO S520                        | 2         | 1.05%   |
| ASUS ROG STRIX B550-F GAMING              | 2         | 1.05%   |
| Acer Veriton M460                         | 2         | 1.05%   |
| TUXEDO Pulse 15 Gen2                      | 1         | 0.53%   |
| TUXEDO Pulse 15 Gen1                      | 1         | 0.53%   |
| TUXEDO InfinityBook S 15 Gen6             | 1         | 0.53%   |
| Toshiba Satellite C660                    | 1         | 0.53%   |
| Sophos UTM                                | 1         | 0.53%   |
| Sony VPCM13M1R                            | 1         | 0.53%   |
| Sony VJS121C11N                           | 1         | 0.53%   |
| Sony SVE1713S1RW                          | 1         | 0.53%   |
| Semp Toshiba STI                          | 1         | 0.53%   |
| Samsung N150/N210/N220                    | 1         | 0.53%   |
| Samsung N145P/N250P/N260P                 | 1         | 0.53%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 1         | 0.53%   |
| Pegatron T12Ah                            | 1         | 0.53%   |
| Pegatron Elite 7300 Series MT             | 1         | 0.53%   |
| Panasonic CF-C1BD06EFG                    | 1         | 0.53%   |
| Notebook W650DC,DD                        | 1         | 0.53%   |
| Notebook N650DU                           | 1         | 0.53%   |
| NEC Computers PC-GL186Y3AZ                | 1         | 0.53%   |
| MSI MS-N033                               | 1         | 0.53%   |
| Lenovo Yoga 710-11IKB 80V6                | 1         | 0.53%   |
| Lenovo V580 20147                         | 1         | 0.53%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK      | 1         | 0.53%   |
| Lenovo ThinkPad X280 20KESB4T00           | 1         | 0.53%   |
| Lenovo ThinkPad X270 20HN006CUS           | 1         | 0.53%   |
| Lenovo ThinkPad X230 2325IB1              | 1         | 0.53%   |
| Lenovo ThinkPad X230 23255NG              | 1         | 0.53%   |
| Lenovo ThinkPad X230 23205UG              | 1         | 0.53%   |
| Lenovo ThinkPad X201 Tablet 311396U       | 1         | 0.53%   |
| Lenovo ThinkPad X13 Yoga Gen 1 20SYS22H00 | 1         | 0.53%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00    | 1         | 0.53%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT  | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU  | 1         | 0.53%   |
| Lenovo ThinkPad W541 20EGS04800           | 1         | 0.53%   |
| Lenovo ThinkPad W520 42844DG              | 1         | 0.53%   |
| Lenovo ThinkPad T530 24295VU              | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 30        | 15.79%  |
| Dell Latitude          | 9         | 4.74%   |
| Acer Aspire            | 9         | 4.74%   |
| Dell OptiPlex          | 5         | 2.63%   |
| HP Compaq              | 4         | 2.11%   |
| HP ProBook             | 3         | 1.58%   |
| HP Pavilion            | 3         | 1.58%   |
| Dell Studio            | 3         | 1.58%   |
| Dell Inspiron          | 3         | 1.58%   |
| ASUS ROG               | 3         | 1.58%   |
| Unknown                | 3         | 1.58%   |
| TUXEDO Pulse           | 2         | 1.05%   |
| Lenovo ThinkCentre     | 2         | 1.05%   |
| Lenovo IdeaPad         | 2         | 1.05%   |
| HP Z420                | 2         | 1.05%   |
| HP Laptop              | 2         | 1.05%   |
| HP EliteBook           | 2         | 1.05%   |
| Gigabyte Z370          | 2         | 1.05%   |
| Gigabyte X570          | 2         | 1.05%   |
| Fujitsu Siemens AMILO  | 2         | 1.05%   |
| Fujitsu LIFEBOOK       | 2         | 1.05%   |
| Fujitsu FUTRO          | 2         | 1.05%   |
| Dell XPS               | 2         | 1.05%   |
| ASUS TUF               | 2         | 1.05%   |
| ASUS PRIME             | 2         | 1.05%   |
| Acer Veriton           | 2         | 1.05%   |
| TUXEDO InfinityBook    | 1         | 0.53%   |
| Toshiba Satellite      | 1         | 0.53%   |
| Sophos UTM             | 1         | 0.53%   |
| Sony VPCM13M1R         | 1         | 0.53%   |
| Sony VJS121C11N        | 1         | 0.53%   |
| Sony SVE1713S1RW       | 1         | 0.53%   |
| Semp Toshiba STI       | 1         | 0.53%   |
| Samsung N150           | 1         | 0.53%   |
| Samsung N145P          | 1         | 0.53%   |
| Samsung 300E5EV        | 1         | 0.53%   |
| Pegatron T12Ah         | 1         | 0.53%   |
| Pegatron Elite         | 1         | 0.53%   |
| Panasonic CF-C1BD06EFG | 1         | 0.53%   |
| Notebook W650DC        | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 23        | 12.11%  |
| 2020 | 20        | 10.53%  |
| 2017 | 16        | 8.42%   |
| 2013 | 13        | 6.84%   |
| 2012 | 13        | 6.84%   |
| 2021 | 12        | 6.32%   |
| 2018 | 12        | 6.32%   |
| 2015 | 11        | 5.79%   |
| 2011 | 11        | 5.79%   |
| 2014 | 10        | 5.26%   |
| 2010 | 10        | 5.26%   |
| 2009 | 10        | 5.26%   |
| 2016 | 8         | 4.21%   |
| 2008 | 7         | 3.68%   |
| 2022 | 6         | 3.16%   |
| 2023 | 3         | 1.58%   |
| 2006 | 3         | 1.58%   |
| 2007 | 1         | 0.53%   |
| 2004 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 125       | 65.79%  |
| Desktop     | 54        | 28.42%  |
| Convertible | 5         | 2.63%   |
| Mini pc     | 2         | 1.05%   |
| All in one  | 2         | 1.05%   |
| Firewall    | 1         | 0.53%   |
| Server      | 1         | 0.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 187       | 98.42%  |
| Yes  | 3         | 1.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 71        | 37.17%  |
| 16.01-24.0  | 43        | 22.51%  |
| 4.01-8.0    | 37        | 19.37%  |
| 32.01-64.0  | 15        | 7.85%   |
| 2.01-3.0    | 10        | 5.24%   |
| 64.01-256.0 | 7         | 3.66%   |
| 3.01-4.0    | 3         | 1.57%   |
| 0.51-1.0    | 3         | 1.57%   |
| 24.01-32.0  | 2         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 99        | 51.3%   |
| 0.51-1.0  | 58        | 30.05%  |
| 1.01-2.0  | 24        | 12.44%  |
| 2.01-3.0  | 7         | 3.63%   |
| 4.01-8.0  | 3         | 1.55%   |
| 3.01-4.0  | 1         | 0.52%   |
| 8.01-16.0 | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 126       | 65.97%  |
| 2      | 34        | 17.8%   |
| 3      | 13        | 6.81%   |
| 0      | 13        | 6.81%   |
| 4      | 4         | 2.09%   |
| 7      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 62.3%   |
| Yes       | 72        | 37.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 89.53%  |
| No        | 20        | 10.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 81.58%  |
| No        | 35        | 18.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 57.59%  |
| No        | 81        | 42.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 37        | 19.47%  |
| Germany     | 28        | 14.74%  |
| France      | 20        | 10.53%  |
| Russia      | 18        | 9.47%   |
| UK          | 12        | 6.32%   |
| Italy       | 7         | 3.68%   |
| Taiwan      | 6         | 3.16%   |
| Turkey      | 5         | 2.63%   |
| Hungary     | 5         | 2.63%   |
| Finland     | 4         | 2.11%   |
| Norway      | 3         | 1.58%   |
| Mexico      | 3         | 1.58%   |
| Colombia    | 3         | 1.58%   |
| China       | 3         | 1.58%   |
| Australia   | 3         | 1.58%   |
| Argentina   | 3         | 1.58%   |
| Thailand    | 2         | 1.05%   |
| Spain       | 2         | 1.05%   |
| Romania     | 2         | 1.05%   |
| Poland      | 2         | 1.05%   |
| Japan       | 2         | 1.05%   |
| Czechia     | 2         | 1.05%   |
| Bulgaria    | 2         | 1.05%   |
| Brazil      | 2         | 1.05%   |
| Ukraine     | 1         | 0.53%   |
| Sweden      | 1         | 0.53%   |
| South Korea | 1         | 0.53%   |
| Slovakia    | 1         | 0.53%   |
| Serbia      | 1         | 0.53%   |
| San Marino  | 1         | 0.53%   |
| Philippines | 1         | 0.53%   |
| Netherlands | 1         | 0.53%   |
| Lithuania   | 1         | 0.53%   |
| Hong Kong   | 1         | 0.53%   |
| Estonia     | 1         | 0.53%   |
| Egypt       | 1         | 0.53%   |
| Denmark     | 1         | 0.53%   |
| Belarus     | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 11        | 5.73%   |
| Franconville          | 6         | 3.13%   |
| Paris                 | 5         | 2.6%    |
| Hodmezovasarhely      | 5         | 2.6%    |
| Wuppertal             | 4         | 2.08%   |
| Istanbul              | 4         | 2.08%   |
| Duncan                | 4         | 2.08%   |
| Woodland              | 3         | 1.56%   |
| Whittier              | 3         | 1.56%   |
| Tijuana               | 3         | 1.56%   |
| Taipei                | 3         | 1.56%   |
| Taichung              | 3         | 1.56%   |
| Milan                 | 3         | 1.56%   |
| Markt Indersdorf      | 3         | 1.56%   |
| Zwingenberg           | 2         | 1.04%   |
| Volzhskiy             | 2         | 1.04%   |
| Vollen                | 2         | 1.04%   |
| Urcuit                | 2         | 1.04%   |
| Turku                 | 2         | 1.04%   |
| St Petersburg         | 2         | 1.04%   |
| Sofia                 | 2         | 1.04%   |
| Setagaya-ku           | 2         | 1.04%   |
| Rome                  | 2         | 1.04%   |
| Rio de Janeiro        | 2         | 1.04%   |
| New Braunfels         | 2         | 1.04%   |
| Melun                 | 2         | 1.04%   |
| McDonough             | 2         | 1.04%   |
| Lutherville-Timonium  | 2         | 1.04%   |
| Los Angeles           | 2         | 1.04%   |
| Greenwich             | 2         | 1.04%   |
| Drobeta-Turnu Severin | 2         | 1.04%   |
| Cologne               | 2         | 1.04%   |
| Changzhou             | 2         | 1.04%   |
| Brisbane              | 2         | 1.04%   |
| BogotГЎ             | 2         | 1.04%   |
| Bangkok               | 2         | 1.04%   |
| Wloszczowa            | 1         | 0.52%   |
| Wissen                | 1         | 0.52%   |
| Winter Haven          | 1         | 0.52%   |
| Wilhelmshaven         | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 56     | 19.23%  |
| WDC                 | 37        | 45     | 15.81%  |
| Seagate             | 32        | 35     | 13.68%  |
| Toshiba             | 21        | 24     | 8.97%   |
| Crucial             | 11        | 11     | 4.7%    |
| SanDisk             | 9         | 10     | 3.85%   |
| SK hynix            | 8         | 9      | 3.42%   |
| Kingston            | 8         | 9      | 3.42%   |
| Transcend           | 6         | 6      | 2.56%   |
| Intel               | 6         | 6      | 2.56%   |
| Hitachi             | 6         | 7      | 2.56%   |
| A-DATA Technology   | 6         | 6      | 2.56%   |
| Apple               | 5         | 6      | 2.14%   |
| Micron Technology   | 3         | 3      | 1.28%   |
| HGST                | 3         | 3      | 1.28%   |
| Hewlett-Packard     | 3         | 3      | 1.28%   |
| SPCC                | 2         | 2      | 0.85%   |
| PNY                 | 2         | 2      | 0.85%   |
| OCZ                 | 2         | 2      | 0.85%   |
| Intenso             | 2         | 2      | 0.85%   |
| Gigabyte Technology | 2         | 2      | 0.85%   |
| Fujitsu             | 2         | 3      | 0.85%   |
| Corsair             | 2         | 2      | 0.85%   |
| UMIS                | 1         | 1      | 0.43%   |
| Team                | 1         | 1      | 0.43%   |
| Phison              | 1         | 1      | 0.43%   |
| ORICO               | 1         | 1      | 0.43%   |
| Maxtor              | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| LITEON              | 1         | 1      | 0.43%   |
| KingDian            | 1         | 1      | 0.43%   |
| Dogfish             | 1         | 1      | 0.43%   |
| ASUSTek Computer    | 1         | 2      | 0.43%   |
| AirDisk             | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 970 EVO Plus 1TB         | 4         | 1.6%    |
| Kingston SA400S37240G 240GB          | 4         | 1.6%    |
| Toshiba MQ01ABD100 1TB               | 3         | 1.2%    |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.2%    |
| SanDisk pSSD 256GB                   | 3         | 1.2%    |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.8%    |
| WDC WD40PURX-64GVNY0 4TB             | 2         | 0.8%    |
| WDC WD2500BEVT-80A23T0 250GB         | 2         | 0.8%    |
| WDC WD1600AAJS-22L7A0 160GB          | 2         | 0.8%    |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 2         | 0.8%    |
| Toshiba MQ01ABF050 500GB             | 2         | 0.8%    |
| Toshiba HDWD120 2TB                  | 2         | 0.8%    |
| Seagate ST95005620AS 500GB           | 2         | 0.8%    |
| Seagate ST9500325AS 500GB            | 2         | 0.8%    |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.8%    |
| SanDisk SSD U100 24GB                | 2         | 0.8%    |
| Samsung SSD 980 PRO 250GB            | 2         | 0.8%    |
| Samsung SSD 970 EVO 500GB            | 2         | 0.8%    |
| Samsung SSD 870 QVO 2TB              | 2         | 0.8%    |
| Samsung SSD 840 EVO 250GB            | 2         | 0.8%    |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 0.8%    |
| Kingston SA400S37480G 480GB          | 2         | 0.8%    |
| HGST HTS725050A7E630 500GB           | 2         | 0.8%    |
| HP SSD EX950 2TB                     | 2         | 0.8%    |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.8%    |
| Crucial CT1000P1SSD8 1TB             | 2         | 0.8%    |
| Apple SSD SM0512F 500GB              | 2         | 0.8%    |
| A-DATA SU630 240GB                   | 2         | 0.8%    |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.4%    |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.4%    |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.4%    |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.4%    |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.4%    |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.4%    |
| WDC WD60EZRZ-00GZ5B1 6TB             | 1         | 0.4%    |
| WDC WD40NMZW-11GX6S1 4TB             | 1         | 0.4%    |
| WDC WD40EFAX-68JH4N0 4TB             | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 35     | 33.33%  |
| WDC                 | 30        | 33     | 31.25%  |
| Toshiba             | 16        | 18     | 16.67%  |
| Hitachi             | 6         | 7      | 6.25%   |
| Samsung Electronics | 4         | 4      | 4.17%   |
| HGST                | 3         | 3      | 3.13%   |
| Fujitsu             | 2         | 3      | 2.08%   |
| Maxtor              | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |
| Apple               | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 25     | 23.08%  |
| SanDisk             | 9         | 10     | 9.89%   |
| Kingston            | 7         | 8      | 7.69%   |
| Crucial             | 7         | 7      | 7.69%   |
| Transcend           | 6         | 6      | 6.59%   |
| A-DATA Technology   | 6         | 6      | 6.59%   |
| WDC                 | 4         | 5      | 4.4%    |
| Apple               | 4         | 5      | 4.4%    |
| Toshiba             | 3         | 3      | 3.3%    |
| Intel               | 3         | 3      | 3.3%    |
| SPCC                | 2         | 2      | 2.2%    |
| SK hynix            | 2         | 2      | 2.2%    |
| PNY                 | 2         | 2      | 2.2%    |
| OCZ                 | 2         | 2      | 2.2%    |
| Micron Technology   | 2         | 2      | 2.2%    |
| Intenso             | 2         | 2      | 2.2%    |
| Gigabyte Technology | 2         | 2      | 2.2%    |
| Team                | 1         | 1      | 1.1%    |
| LITEONIT            | 1         | 1      | 1.1%    |
| LITEON              | 1         | 1      | 1.1%    |
| KingDian            | 1         | 1      | 1.1%    |
| Dogfish             | 1         | 1      | 1.1%    |
| Corsair             | 1         | 1      | 1.1%    |
| ASUSTek Computer    | 1         | 2      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 83        | 106    | 39.15%  |
| SSD  | 82        | 100    | 38.68%  |
| NVMe | 47        | 60     | 22.17%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 148       | 206    | 75.9%   |
| NVMe | 47        | 60     | 24.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 109       | 135    | 63.01%  |
| 0.51-1.0   | 44        | 49     | 25.43%  |
| 1.01-2.0   | 10        | 10     | 5.78%   |
| 3.01-4.0   | 5         | 5      | 2.89%   |
| 2.01-3.0   | 4         | 4      | 2.31%   |
| 4.01-10.0  | 1         | 3      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 150       | 78.95%  |
| 101-250    | 16        | 8.42%   |
| 21-50      | 11        | 5.79%   |
| 51-100     | 6         | 3.16%   |
| 251-500    | 4         | 2.11%   |
| 501-1000   | 3         | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 186       | 97.38%  |
| 21-50   | 3         | 1.57%   |
| 51-100  | 2         | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 3.03%   |
| WDC WD40PURX-64GVNY0 4TB                         | 1         | 1      | 3.03%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 3.03%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 3.03%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 3.03%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 3.03%   |
| WDC WD10EFRX-68PJCN0 1TB                         | 1         | 2      | 3.03%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.03%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.03%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 3.03%   |
| Toshiba HDWD120 2TB                              | 1         | 1      | 3.03%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 3.03%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 3.03%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 3.03%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.03%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 3.03%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 3.03%   |
| Seagate ST3250823AS 250GB                        | 1         | 1      | 3.03%   |
| Seagate ST310212A 10GB                           | 1         | 1      | 3.03%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 3.03%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 3.03%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 3.03%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 3.03%   |
| Intenso SSD Sata III 128GB                       | 1         | 1      | 3.03%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 3.03%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 2      | 3.03%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 3.03%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 3.03%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 3.03%   |
| Hewlett-Packard MB1000GCWCV 1TB                  | 1         | 1      | 3.03%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 3.03%   |
| A-DATA Technology XM13 32GB                      | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 21.21%  |
| Seagate             | 7         | 7      | 21.21%  |
| Toshiba             | 6         | 6      | 18.18%  |
| Hitachi             | 3         | 4      | 9.09%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Corsair             | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 26.92%  |
| Seagate             | 7         | 7      | 26.92%  |
| Toshiba             | 6         | 6      | 23.08%  |
| Hitachi             | 3         | 4      | 11.54%  |
| Samsung Electronics | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 28     | 78.13%  |
| SSD  | 7         | 7      | 21.88%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model              | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 154       | 222    | 81.48%  |
| Malfunc  | 32        | 35     | 16.93%  |
| Detected | 2         | 8      | 1.06%   |
| Failed   | 1         | 1      | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 132       | 56.9%   |
| AMD                                     | 30        | 12.93%  |
| Samsung Electronics                     | 26        | 11.21%  |
| SanDisk                                 | 8         | 3.45%   |
| ASMedia Technology                      | 7         | 3.02%   |
| SK hynix                                | 5         | 2.16%   |
| Nvidia                                  | 5         | 2.16%   |
| Micron/Crucial Technology               | 4         | 1.72%   |
| VIA Technologies                        | 2         | 0.86%   |
| Phison Electronics                      | 2         | 0.86%   |
| Biwin Storage Technology                | 2         | 0.86%   |
| Toshiba                                 | 1         | 0.43%   |
| Silicon Motion                          | 1         | 0.43%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.43%   |
| Shenzhen Unionmemory Information System | 1         | 0.43%   |
| Micron Technology                       | 1         | 0.43%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.43%   |
| KIOXIA                                  | 1         | 0.43%   |
| Kingston Technology Company             | 1         | 0.43%   |
| JMicron Technology                      | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 8.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 5.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 5.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 4.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 2.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.96%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 7         | 2.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.48%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.11%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.11%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 3         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.11%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.74%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 2         | 0.74%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 0.74%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 2         | 0.74%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.74%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.74%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 2         | 0.74%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 2         | 0.74%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                         | 2         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 133       | 57.08%  |
| NVMe | 48        | 20.6%   |
| IDE  | 34        | 14.59%  |
| RAID | 15        | 6.44%   |
| SAS  | 3         | 1.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 156       | 81.68%  |
| AMD    | 35        | 18.32%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.09%   |
| Intel CPU Version                             | 3         | 1.57%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.57%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 1.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.57%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.05%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.05%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.05%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.05%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.05%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.05%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 2         | 1.05%   |
| Intel Core 2 Duo                              | 2         | 1.05%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 1.05%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 1.05%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 1.05%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.05%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 1.05%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.05%   |
| Intel Xeon CPU E5640 @ 2.67GHz                | 1         | 0.52%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.52%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz              | 1         | 0.52%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz           | 1         | 0.52%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.52%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz           | 1         | 0.52%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.52%   |
| Intel Pentium III                             | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.52%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 55        | 28.8%   |
| Intel Core i7           | 40        | 20.94%  |
| Intel Core 2 Duo        | 11        | 5.76%   |
| Other                   | 10        | 5.24%   |
| Intel Core i3           | 9         | 4.71%   |
| AMD Ryzen 5             | 9         | 4.71%   |
| Intel Xeon              | 7         | 3.66%   |
| AMD Ryzen 7             | 7         | 3.66%   |
| Intel Atom              | 6         | 3.14%   |
| Intel Celeron           | 4         | 2.09%   |
| Intel Pentium           | 3         | 1.57%   |
| AMD A8                  | 3         | 1.57%   |
| AMD A6                  | 3         | 1.57%   |
| Intel Pentium Dual-Core | 2         | 1.05%   |
| Intel Core i9           | 2         | 1.05%   |
| Intel Celeron Dual-Core | 2         | 1.05%   |
| AMD Ryzen 9             | 2         | 1.05%   |
| AMD GX                  | 2         | 1.05%   |
| AMD Athlon 64 X2        | 2         | 1.05%   |
| Intel Pentium Silver    | 1         | 0.52%   |
| Intel Pentium III       | 1         | 0.52%   |
| Intel Pentium D         | 1         | 0.52%   |
| Intel Genuine           | 1         | 0.52%   |
| Intel Core m5           | 1         | 0.52%   |
| Intel Core 2            | 1         | 0.52%   |
| Intel Celeron M         | 1         | 0.52%   |
| AMD Ryzen 7 PRO         | 1         | 0.52%   |
| AMD Phenom II X4        | 1         | 0.52%   |
| AMD FX                  | 1         | 0.52%   |
| AMD E1                  | 1         | 0.52%   |
| AMD A10                 | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 80        | 41.88%  |
| 4       | 63        | 32.98%  |
| Unknown | 11        | 5.76%   |
| 8       | 10        | 5.24%   |
| 12      | 7         | 3.66%   |
| 6       | 7         | 3.66%   |
| 16      | 6         | 3.14%   |
| 1       | 5         | 2.62%   |
| 24      | 2         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 187       | 98.42%  |
| 2       | 2         | 1.05%   |
| Unknown | 1         | 0.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 108       | 56.54%  |
| 1       | 70        | 36.65%  |
| Unknown | 13        | 6.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 19.37%  |
| Haswell       | 23        | 12.04%  |
| IvyBridge     | 20        | 10.47%  |
| Penryn        | 17        | 8.9%    |
| Skylake       | 15        | 7.85%   |
| SandyBridge   | 11        | 5.76%   |
| Bonnell       | 7         | 3.66%   |
| Zen+          | 6         | 3.14%   |
| Puma          | 6         | 3.14%   |
| Unknown       | 5         | 2.62%   |
| Zen 2         | 4         | 2.09%   |
| Broadwell     | 4         | 2.09%   |
| Zen 3         | 3         | 1.57%   |
| Zen           | 3         | 1.57%   |
| Westmere      | 3         | 1.57%   |
| Nehalem       | 3         | 1.57%   |
| Core          | 3         | 1.57%   |
| TigerLake     | 2         | 1.05%   |
| Silvermont    | 2         | 1.05%   |
| P6            | 2         | 1.05%   |
| K8 Hammer     | 2         | 1.05%   |
| K10           | 2         | 1.05%   |
| Jaguar        | 2         | 1.05%   |
| Goldmont plus | 2         | 1.05%   |
| Steamroller   | 1         | 0.52%   |
| Piledriver    | 1         | 0.52%   |
| NetBurst      | 1         | 0.52%   |
| K10 Llano     | 1         | 0.52%   |
| Goldmont      | 1         | 0.52%   |
| Excavator     | 1         | 0.52%   |
| CometLake     | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 121       | 57.89%  |
| AMD                        | 45        | 21.53%  |
| Nvidia                     | 40        | 19.14%  |
| VIA Technologies           | 1         | 0.48%   |
| S3 Graphics                | 1         | 0.48%   |
| Matrox Electronics Systems | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 6.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 4.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.21%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.74%   |
| Intel HD Graphics 620                                                                    | 6         | 2.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.34%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 2.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.34%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 1.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.4%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.4%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.93%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.93%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.93%   |
| Intel HD Graphics 630                                                                    | 2         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.93%   |
| Intel HD Graphics 530                                                                    | 2         | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.93%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.93%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 0.93%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.93%   |
| AMD Lucienne                                                                             | 2         | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.93%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 0.93%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.47%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.47%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.47%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.47%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.47%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.47%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 93        | 48.69%  |
| 1 x AMD         | 41        | 21.47%  |
| 1 x Nvidia      | 25        | 13.09%  |
| Intel + Nvidia  | 14        | 7.33%   |
| 2 x Intel       | 11        | 5.76%   |
| Intel + AMD     | 2         | 1.05%   |
| 2 x AMD         | 1         | 0.52%   |
| 1 x VIA         | 1         | 0.52%   |
| 1 x S3 Graphics | 1         | 0.52%   |
| 1 x Matrox      | 1         | 0.52%   |
| AMD + Nvidia    | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 155       | 81.58%  |
| Proprietary | 18        | 9.47%   |
| Unknown     | 17        | 8.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 157       | 82.2%   |
| 0.01-0.5   | 10        | 5.24%   |
| 1.01-2.0   | 8         | 4.19%   |
| 0.51-1.0   | 5         | 2.62%   |
| 5.01-6.0   | 4         | 2.09%   |
| 3.01-4.0   | 4         | 2.09%   |
| 7.01-8.0   | 3         | 1.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 11.18%  |
| AU Optronics            | 17        | 11.18%  |
| Samsung Electronics     | 16        | 10.53%  |
| BOE                     | 15        | 9.87%   |
| Chimei Innolux          | 11        | 7.24%   |
| Goldstar                | 9         | 5.92%   |
| Dell                    | 8         | 5.26%   |
| Acer                    | 6         | 3.95%   |
| Hewlett-Packard         | 5         | 3.29%   |
| HannStar                | 5         | 3.29%   |
| Sharp                   | 4         | 2.63%   |
| Fujitsu Siemens         | 4         | 2.63%   |
| Chi Mei Optoelectronics | 4         | 2.63%   |
| Apple                   | 4         | 2.63%   |
| ViewSonic               | 3         | 1.97%   |
| Lenovo                  | 3         | 1.97%   |
| Philips                 | 2         | 1.32%   |
| Panasonic               | 2         | 1.32%   |
| NEC Computers           | 2         | 1.32%   |
| BenQ                    | 2         | 1.32%   |
| ASUSTek Computer        | 2         | 1.32%   |
| Ancor Communications    | 2         | 1.32%   |
| ___                     | 1         | 0.66%   |
| Westinghouse            | 1         | 0.66%   |
| Vizio                   | 1         | 0.66%   |
| Toshiba                 | 1         | 0.66%   |
| Sony                    | 1         | 0.66%   |
| LG Philips              | 1         | 0.66%   |
| LG Electronics          | 1         | 0.66%   |
| CPT                     | 1         | 0.66%   |
| AOC                     | 1         | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 3         | 1.95%   |
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch           | 3         | 1.95%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 2         | 1.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 1.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 1.3%    |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.3%    |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch             | 2         | 1.3%    |
| ___ MY TV LED TV ___0101 1920x1080                                       | 1         | 0.65%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch             | 1         | 0.65%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                     | 1         | 0.65%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                    | 1         | 0.65%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch               | 1         | 0.65%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch            | 1         | 0.65%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch                | 1         | 0.65%   |
| Sony TV SNY5D01 1360x768                                                 | 1         | 0.65%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.65%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.65%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.65%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 0.65%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch        | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.65%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch        | 1         | 0.65%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                        | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.65%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch        | 1         | 0.65%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 35.33%  |
| 1366x768 (WXGA)    | 39        | 26%     |
| 1280x1024 (SXGA)   | 11        | 7.33%   |
| 1600x900 (HD+)     | 7         | 4.67%   |
| 3840x2160 (4K)     | 6         | 4%      |
| 1920x1200 (WUXGA)  | 6         | 4%      |
| 1024x600           | 5         | 3.33%   |
| 2560x1440 (QHD)    | 4         | 2.67%   |
| 1440x900 (WXGA+)   | 4         | 2.67%   |
| 1280x800 (WXGA)    | 4         | 2.67%   |
| 2880x1800          | 2         | 1.33%   |
| 2880x1620          | 2         | 1.33%   |
| 1680x1050 (WSXGA+) | 2         | 1.33%   |
| 1360x768           | 2         | 1.33%   |
| 3200x1800 (QHD+)   | 1         | 0.67%   |
| 2160x1350          | 1         | 0.67%   |
| 1600x1200          | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 39        | 25.49%  |
| 13      | 27        | 17.65%  |
| 24      | 15        | 9.8%    |
| 17      | 12        | 7.84%   |
| 12      | 11        | 7.19%   |
| 19      | 9         | 5.88%   |
| 27      | 8         | 5.23%   |
| 21      | 7         | 4.58%   |
| 10      | 5         | 3.27%   |
| 11      | 4         | 2.61%   |
| Unknown | 4         | 2.61%   |
| 23      | 3         | 1.96%   |
| 18      | 3         | 1.96%   |
| 22      | 2         | 1.31%   |
| 39      | 1         | 0.65%   |
| 37      | 1         | 0.65%   |
| 25      | 1         | 0.65%   |
| 14      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 60        | 39.74%  |
| 201-300     | 33        | 21.85%  |
| 501-600     | 24        | 15.89%  |
| 401-500     | 15        | 9.93%   |
| 351-400     | 11        | 7.28%   |
| Unknown     | 4         | 2.65%   |
| 801-900     | 2         | 1.32%   |
| 601-700     | 2         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 111       | 77.08%  |
| 16/10   | 19        | 13.19%  |
| 5/4     | 11        | 7.64%   |
| Unknown | 2         | 1.39%   |
| 3/2     | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 30        | 19.61%  |
| 201-250        | 22        | 14.38%  |
| 81-90          | 19        | 12.42%  |
| 71-80          | 10        | 6.54%   |
| 61-70          | 10        | 6.54%   |
| 151-200        | 9         | 5.88%   |
| 141-150        | 9         | 5.88%   |
| 101-110        | 9         | 5.88%   |
| 301-350        | 8         | 5.23%   |
| 251-300        | 6         | 3.92%   |
| 41-50          | 5         | 3.27%   |
| 121-130        | 5         | 3.27%   |
| 51-60          | 4         | 2.61%   |
| Unknown        | 4         | 2.61%   |
| 501-1000       | 2         | 1.31%   |
| 131-140        | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 46        | 31.08%  |
| 51-100        | 45        | 30.41%  |
| 121-160       | 33        | 22.3%   |
| 161-240       | 16        | 10.81%  |
| More than 240 | 4         | 2.7%    |
| Unknown       | 4         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 147       | 76.56%  |
| 0     | 35        | 18.23%  |
| 2     | 8         | 4.17%   |
| 3     | 2         | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 109       | 37.98%  |
| Realtek Semiconductor             | 78        | 27.18%  |
| Qualcomm Atheros                  | 38        | 13.24%  |
| Broadcom                          | 20        | 6.97%   |
| Samsung Electronics               | 5         | 1.74%   |
| Ralink Technology                 | 5         | 1.74%   |
| Ralink                            | 3         | 1.05%   |
| Marvell Technology Group          | 3         | 1.05%   |
| TP-Link                           | 2         | 0.7%    |
| Sierra Wireless                   | 2         | 0.7%    |
| Qualcomm                          | 2         | 0.7%    |
| Mellanox Technologies             | 2         | 0.7%    |
| Fibocom                           | 2         | 0.7%    |
| Ericsson Business Mobile Networks | 2         | 0.7%    |
| VIA Technologies                  | 1         | 0.35%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.35%   |
| Qualcomm Technologies             | 1         | 0.35%   |
| Nvidia                            | 1         | 0.35%   |
| NetGear                           | 1         | 0.35%   |
| Microchip Technology              | 1         | 0.35%   |
| JMicron Technology                | 1         | 0.35%   |
| Edimax Technology                 | 1         | 0.35%   |
| Dell                              | 1         | 0.35%   |
| D-Link System                     | 1         | 0.35%   |
| D-Link                            | 1         | 0.35%   |
| Brooktrout Technology             | 1         | 0.35%   |
| Atheros                           | 1         | 0.35%   |
| Apple                             | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 14.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 3.57%   |
| Intel Wireless 8265 / 8275                                        | 11        | 3.02%   |
| Intel Wireless 7260                                               | 11        | 3.02%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 2.2%    |
| Intel Wireless 8260                                               | 7         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.65%   |
| Intel Wireless 3165                                               | 6         | 1.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.37%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.1%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 4         | 1.1%    |
| Intel Wireless 7265                                               | 3         | 0.82%   |
| Intel WiFi Link 5100                                              | 3         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.82%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 0.55%   |
| Ralink RT5372 Wireless Adapter                                    | 2         | 0.55%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 2         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.55%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 48.21%  |
| Qualcomm Atheros      | 32        | 19.05%  |
| Realtek Semiconductor | 25        | 14.88%  |
| Broadcom              | 13        | 7.74%   |
| Ralink Technology     | 5         | 2.98%   |
| Ralink                | 3         | 1.79%   |
| TP-Link               | 2         | 1.19%   |
| Sierra Wireless       | 1         | 0.6%    |
| Qualcomm Technologies | 1         | 0.6%    |
| NetGear               | 1         | 0.6%    |
| Edimax Technology     | 1         | 0.6%    |
| D-Link System         | 1         | 0.6%    |
| D-Link                | 1         | 0.6%    |
| Atheros               | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 11        | 6.43%   |
| Intel Wireless 7260                                            | 11        | 6.43%   |
| Intel Wireless 8260                                            | 7         | 4.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 3.51%   |
| Intel Wireless 3165                                            | 6         | 3.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 2.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 2.92%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.34%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 2.34%   |
| Intel Wireless 7265                                            | 3         | 1.75%   |
| Intel WiFi Link 5100                                           | 3         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.17%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2         | 1.17%   |
| Ralink RT5372 Wireless Adapter                                 | 2         | 1.17%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 2         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.17%   |
| Intel Wireless-AC 9260                                         | 2         | 1.17%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.17%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.17%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.17%   |
| TP-Link Wireless USB Adapter                                   | 1         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.58%   |
| Sierra Wireless EM7455                                         | 1         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.58%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.58%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller             | 1         | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 72        | 40.22%  |
| Intel                            | 72        | 40.22%  |
| Broadcom                         | 11        | 6.15%   |
| Qualcomm Atheros                 | 9         | 5.03%   |
| Samsung Electronics              | 5         | 2.79%   |
| Marvell Technology Group         | 3         | 1.68%   |
| Qualcomm                         | 2         | 1.12%   |
| VIA Technologies                 | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Nvidia                           | 1         | 0.56%   |
| JMicron Technology               | 1         | 0.56%   |
| Apple                            | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 29.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 7.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 7.1%    |
| Intel Ethernet Connection I217-LM                                 | 8         | 4.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 4.37%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.73%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.19%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.19%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.64%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.09%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 2         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.09%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.09%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.09%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.09%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.09%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.09%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.55%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.55%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.55%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.55%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.55%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 172       | 50.89%  |
| WiFi     | 156       | 46.15%  |
| Unknown  | 9         | 2.66%   |
| Modem    | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 145       | 57.31%  |
| WiFi     | 103       | 40.71%  |
| Unknown  | 5         | 1.98%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 129       | 67.54%  |
| 1     | 56        | 29.32%  |
| 4     | 3         | 1.57%   |
| 3     | 2         | 1.05%   |
| 0     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 169       | 88.48%  |
| Yes  | 22        | 11.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 47.32%  |
| Broadcom                        | 11        | 9.82%   |
| Realtek Semiconductor           | 9         | 8.04%   |
| Qualcomm Atheros Communications | 8         | 7.14%   |
| Lite-On Technology              | 6         | 5.36%   |
| Apple                           | 6         | 5.36%   |
| IMC Networks                    | 5         | 4.46%   |
| ASUSTek Computer                | 5         | 4.46%   |
| Cambridge Silicon Radio         | 3         | 2.68%   |
| Foxconn / Hon Hai               | 2         | 1.79%   |
| USI                             | 1         | 0.89%   |
| Hewlett-Packard                 | 1         | 0.89%   |
| Dell                            | 1         | 0.89%   |
| Alps Electric                   | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 31        | 27.68%  |
| Intel AX201 Bluetooth                                       | 7         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 4.46%   |
| Intel AX200 Bluetooth                                       | 5         | 4.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.57%   |
| Apple Bluetooth Host Controller                             | 4         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 2.68%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.79%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.79%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 1.79%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.79%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.89%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.89%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.89%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.89%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.89%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.89%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.89%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.89%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.89%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.89%   |
| Lite-On Bluetooth USB Module                                | 1         | 0.89%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.89%   |
| Intel AX211 Bluetooth                                       | 1         | 0.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.89%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.89%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.89%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 148       | 62.45%  |
| AMD                              | 45        | 18.99%  |
| Nvidia                           | 25        | 10.55%  |
| XMOS                             | 2         | 0.84%   |
| Sony                             | 2         | 0.84%   |
| Corsair                          | 2         | 0.84%   |
| C-Media Electronics              | 2         | 0.84%   |
| VIA Technologies                 | 1         | 0.42%   |
| Tenx Technology                  | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Realtek Semiconductor            | 1         | 0.42%   |
| Quanta                           | 1         | 0.42%   |
| LG Electronics                   | 1         | 0.42%   |
| Creative Technology              | 1         | 0.42%   |
| Creative Labs                    | 1         | 0.42%   |
| Blue Microphones                 | 1         | 0.42%   |
| BEHRINGER International          | 1         | 0.42%   |
| Audio-Technica                   | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 9.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 6.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 3.74%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 3.4%    |
| AMD FCH Azalia Controller                                                                         | 10        | 3.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.7%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.36%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.36%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.02%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.02%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 1.02%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.68%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.68%   |
| Corsair VOID PRO Wireless Gaming Headset                                                          | 2         | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 27.03%  |
| SK hynix            | 43        | 19.37%  |
| Micron Technology   | 25        | 11.26%  |
| Unknown             | 19        | 8.56%   |
| Kingston            | 19        | 8.56%   |
| G.Skill             | 8         | 3.6%    |
| Crucial             | 8         | 3.6%    |
| Elpida              | 7         | 3.15%   |
| Corsair             | 7         | 3.15%   |
| Unknown             | 6         | 2.7%    |
| Nanya Technology    | 5         | 2.25%   |
| A-DATA Technology   | 4         | 1.8%    |
| Transcend           | 3         | 1.35%   |
| Ramaxel Technology  | 2         | 0.9%    |
| 48spaces            | 2         | 0.9%    |
| Unknown (ABCD)      | 1         | 0.45%   |
| Unknown (09D5)      | 1         | 0.45%   |
| Magnum Tech         | 1         | 0.45%   |
| EVGA                | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 7         | 2.93%   |
| Unknown                                                                   | 6         | 2.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 5         | 2.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 2.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.26%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.26%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.26%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                  | 2         | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.84%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 2         | 0.84%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 0.84%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.84%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 0.84%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM 1600MT/s                          | 2         | 0.84%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.84%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.84%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.84%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.84%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 2         | 0.84%   |
| Micron RAM ITC 4GB DIMM DDR3 1066MT/s                                     | 2         | 0.84%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                     | 2         | 0.84%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s                       | 2         | 0.84%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.84%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                 | 1         | 0.42%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                                 | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 0.42%   |
| Unknown RAM Module 512MB SODIMM SDRAM                                     | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                                         | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                                | 1         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 83        | 43.01%  |
| DDR4    | 63        | 32.64%  |
| DDR2    | 21        | 10.88%  |
| LPDDR3  | 9         | 4.66%   |
| SDRAM   | 5         | 2.59%   |
| Unknown | 4         | 2.07%   |
| LPDDR5  | 2         | 1.04%   |
| LPDDR4  | 2         | 1.04%   |
| RAM     | 1         | 0.52%   |
| DRAM    | 1         | 0.52%   |
| DDR5    | 1         | 0.52%   |
| DDR     | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 67.71%  |
| DIMM         | 50        | 26.04%  |
| Row Of Chips | 7         | 3.65%   |
| Chip         | 3         | 1.56%   |
| Unknown      | 2         | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 73        | 33.95%  |
| 8192  | 71        | 33.02%  |
| 2048  | 39        | 18.14%  |
| 16384 | 19        | 8.84%   |
| 1024  | 9         | 4.19%   |
| 32768 | 2         | 0.93%   |
| 512   | 1         | 0.47%   |
| 128   | 1         | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 55        | 26.96%  |
| 2400    | 22        | 10.78%  |
| 2667    | 20        | 9.8%    |
| 3200    | 15        | 7.35%   |
| 1333    | 15        | 7.35%   |
| 2133    | 13        | 6.37%   |
| 667     | 11        | 5.39%   |
| 1334    | 9         | 4.41%   |
| 800     | 8         | 3.92%   |
| Unknown | 6         | 2.94%   |
| 1867    | 5         | 2.45%   |
| 1066    | 5         | 2.45%   |
| 3600    | 3         | 1.47%   |
| 1067    | 3         | 1.47%   |
| 533     | 3         | 1.47%   |
| 6400    | 2         | 0.98%   |
| 1866    | 2         | 0.98%   |
| 5600    | 1         | 0.49%   |
| 4267    | 1         | 0.49%   |
| 3000    | 1         | 0.49%   |
| 2933    | 1         | 0.49%   |
| 1639    | 1         | 0.49%   |
| 975     | 1         | 0.49%   |
| 400     | 1         | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 33.33%  |
| Dymo-CoStar     | 1         | 33.33%  |
| Apple           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HP PNP Fax Null                                                          | 1         | 25%     |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 25%     |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                     | 1         | 25%     |
| Apple Gamesir-G3s 2.10                                                   | 1         | 25%     |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 28.18%  |
| Bison Electronics                      | 14        | 12.73%  |
| Realtek Semiconductor                  | 12        | 10.91%  |
| Suyin                                  | 8         | 7.27%   |
| Sunplus Innovation Technology          | 8         | 7.27%   |
| IMC Networks                           | 7         | 6.36%   |
| Microdia                               | 6         | 5.45%   |
| Logitech                               | 4         | 3.64%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.64%   |
| Silicon Motion                         | 3         | 2.73%   |
| Quanta                                 | 3         | 2.73%   |
| Lite-On Technology                     | 3         | 2.73%   |
| Z-Star Microelectronics                | 1         | 0.91%   |
| Novatek Microelectronics               | 1         | 0.91%   |
| Luxvisions Innotech Limited            | 1         | 0.91%   |
| Intel                                  | 1         | 0.91%   |
| Genesys Logic                          | 1         | 0.91%   |
| Apple                                  | 1         | 0.91%   |
| Alcor Micro                            | 1         | 0.91%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 11        | 9.91%   |
| Bison Integrated Camera                                     | 6         | 5.41%   |
| Chicony HD WebCam                                           | 4         | 3.6%    |
| Sunplus Integrated_Webcam_HD                                | 3         | 2.7%    |
| Realtek Lenovo EasyCamera                                   | 3         | 2.7%    |
| Realtek Integrated_Webcam_HD                                | 3         | 2.7%    |
| Microdia Integrated Webcam                                  | 3         | 2.7%    |
| Suyin Acer Crystal Eye webcam                               | 2         | 1.8%    |
| Realtek USB 2.0 PC Camera                                   | 2         | 1.8%    |
| Quanta Realtek DMFT RGB                                     | 2         | 1.8%    |
| Microdia Integrated_Webcam_HD                               | 2         | 1.8%    |
| IMC Networks EasyCamera                                     | 2         | 1.8%    |
| Chicony FJ Camera                                           | 2         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 1.8%    |
| Bison ThinkPad Integrated Camera                            | 2         | 1.8%    |
| Bison SunplusIT Integrated Camera                           | 2         | 1.8%    |
| Z-Star Webcam                                               | 1         | 0.9%    |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.9%    |
| Suyin Laptop_Integrated_Webcam_3M                           | 1         | 0.9%    |
| Suyin HD WebCam                                             | 1         | 0.9%    |
| Suyin HD Video WebCam                                       | 1         | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.9%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.9%    |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.9%    |
| Sunplus Integrated Webcam                                   | 1         | 0.9%    |
| Sunplus Hy HD Camera                                        | 1         | 0.9%    |
| Sunplus hama C-600 Pro Webcam                               | 1         | 0.9%    |
| Sunplus Asus Webcam                                         | 1         | 0.9%    |
| Silicon Motion WebCam SCX Series                            | 1         | 0.9%    |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 0.9%    |
| Silicon Motion 300k Pixel Camera                            | 1         | 0.9%    |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 0.9%    |
| Realtek USB Video Composite                                 | 1         | 0.9%    |
| Realtek USB Camera                                          | 1         | 0.9%    |
| Realtek HD Webcam - Realtek                                 | 1         | 0.9%    |
| Quanta Front camera                                         | 1         | 0.9%    |
| Novatek HP High Definition 2MP Webcam                       | 1         | 0.9%    |
| Microdia Sonix USB 2.0 Camera                               | 1         | 0.9%    |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 0.9%    |
| Logitech Webcam C310                                        | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 45.16%  |
| Synaptics                  | 7         | 22.58%  |
| Upek                       | 4         | 12.9%   |
| LighTuning Technology      | 2         | 6.45%   |
| Shenzhen Goodix Technology | 1         | 3.23%   |
| Elan Microelectronics      | 1         | 3.23%   |
| Broadcom                   | 1         | 3.23%   |
| AuthenTec                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                              | 4         | 12.9%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 12.9%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 9.68%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 9.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 9.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 3.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 3.23%   |
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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 68        | 35.05%  |
| 2     | 54        | 27.84%  |
| 0     | 33        | 17.01%  |
| 3     | 21        | 10.82%  |
| 4     | 12        | 6.19%   |
| 5     | 3         | 1.55%   |
| 7     | 2         | 1.03%   |
| 6     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 122       | 41.78%  |
| Net/wireless             | 49        | 16.78%  |
| Bluetooth                | 35        | 11.99%  |
| Fingerprint reader       | 30        | 10.27%  |
| Firewire controller      | 24        | 8.22%   |
| Card reader              | 20        | 6.85%   |
| Network                  | 6         | 2.05%   |
| Sound                    | 4         | 1.37%   |
| Storage/raid             | 1         | 0.34%   |
| Net/ethernet             | 1         | 0.34%   |

