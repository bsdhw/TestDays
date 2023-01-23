BSD in France - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 551

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E6400              | Notebook    | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Dell          | PowerEdge R710              | Desktop     | [720e99b25e](https://bsd-hardware.info/?probe=720e99b25e) | Jan 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7cbcb5b513](https://bsd-hardware.info/?probe=7cbcb5b513) | Jan 12, 2023 |
| Lenovo        | 3138                        | Desktop     | [14876c7561](https://bsd-hardware.info/?probe=14876c7561) | Jan 12, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Lenovo        | ThinkStation D20 415575G    | Desktop     | [0a15d989e3](https://bsd-hardware.info/?probe=0a15d989e3) | Jan 08, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [0d13116822](https://bsd-hardware.info/?probe=0d13116822) | Jan 06, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| Unknown       | Unknown                     | Firewall    | [72eaa7a90f](https://bsd-hardware.info/?probe=72eaa7a90f) | Dec 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d62deb9883](https://bsd-hardware.info/?probe=d62deb9883) | Dec 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [7bd99b62ab](https://bsd-hardware.info/?probe=7bd99b62ab) | Dec 19, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| MSI           | MS-98C8                     | Desktop     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [7f6194b56e](https://bsd-hardware.info/?probe=7f6194b56e) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [218e00e7ea](https://bsd-hardware.info/?probe=218e00e7ea) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Supermicro    | X10SRG-F                    | Desktop     | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| Dell          | 0W13NR A07                  | Server      | [c5b09b219b](https://bsd-hardware.info/?probe=c5b09b219b) | Nov 24, 2022 |
| Medion        | E15415                      | Notebook    | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Shuttle       | FS35V5                      | Mini pc     | [8b634987b4](https://bsd-hardware.info/?probe=8b634987b4) | Nov 13, 2022 |
| HP            | 806A                        | Desktop     | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [655a9e7af2](https://bsd-hardware.info/?probe=655a9e7af2) | Nov 04, 2022 |
| Dell          | Precision M4500             | Notebook    | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [14f174bd7c](https://bsd-hardware.info/?probe=14f174bd7c) | Oct 26, 2022 |
| Intel         | H81U                        | Notebook    | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| HP            | 260 G3 DM                   | Desktop     | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | Desktop     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Intel         | H81U                        | Notebook    | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [5f271a82bf](https://bsd-hardware.info/?probe=5f271a82bf) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [0f87a99ca7](https://bsd-hardware.info/?probe=0f87a99ca7) | Oct 11, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| Clevo         | R130T                       | Desktop     | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Soekris En... | net6501                     | Desktop     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | Desktop     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| PC Engines    | apu1                        | Desktop     | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [d3c50c8d60](https://bsd-hardware.info/?probe=d3c50c8d60) | Oct 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [16f6784862](https://bsd-hardware.info/?probe=16f6784862) | Sep 27, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b8db4655e5](https://bsd-hardware.info/?probe=b8db4655e5) | Sep 26, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [ae535b0b49](https://bsd-hardware.info/?probe=ae535b0b49) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8f4900d0e6](https://bsd-hardware.info/?probe=8f4900d0e6) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [59886931c5](https://bsd-hardware.info/?probe=59886931c5) | Sep 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5029142d61](https://bsd-hardware.info/?probe=5029142d61) | Sep 22, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [1a754b2a9e](https://bsd-hardware.info/?probe=1a754b2a9e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [77727b5832](https://bsd-hardware.info/?probe=77727b5832) | Sep 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [95ae240b55](https://bsd-hardware.info/?probe=95ae240b55) | Sep 13, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [130de630ad](https://bsd-hardware.info/?probe=130de630ad) | Sep 10, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4db37ff154](https://bsd-hardware.info/?probe=4db37ff154) | Sep 07, 2022 |
| AMD           | Larne CRB                   | Desktop     | [787a51fa78](https://bsd-hardware.info/?probe=787a51fa78) | Sep 03, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [525631a32f](https://bsd-hardware.info/?probe=525631a32f) | Aug 28, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d346cf971a](https://bsd-hardware.info/?probe=d346cf971a) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [ab6603e750](https://bsd-hardware.info/?probe=ab6603e750) | Aug 13, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [649021e20c](https://bsd-hardware.info/?probe=649021e20c) | Aug 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [870dface68](https://bsd-hardware.info/?probe=870dface68) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [81441a97b2](https://bsd-hardware.info/?probe=81441a97b2) | Aug 06, 2022 |
| HP            | 3397                        | Desktop     | [6111a627d6](https://bsd-hardware.info/?probe=6111a627d6) | Aug 05, 2022 |
| AMD           | Larne CRB                   | Desktop     | [db094f95af](https://bsd-hardware.info/?probe=db094f95af) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ac69a3ecef](https://bsd-hardware.info/?probe=ac69a3ecef) | Aug 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1b794b3563](https://bsd-hardware.info/?probe=1b794b3563) | Aug 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ac2fc150b](https://bsd-hardware.info/?probe=5ac2fc150b) | Aug 02, 2022 |
| HP            | 3397                        | Desktop     | [dac75fec6e](https://bsd-hardware.info/?probe=dac75fec6e) | Jul 31, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [0eaaa31106](https://bsd-hardware.info/?probe=0eaaa31106) | Jul 31, 2022 |
| Dell          | 0RH817 A00                  | Server      | [7d7740d447](https://bsd-hardware.info/?probe=7d7740d447) | Jul 30, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| AMD           | Larne CRB                   | Desktop     | [794541e833](https://bsd-hardware.info/?probe=794541e833) | Jul 29, 2022 |
| Dell          | 0M877N A02                  | Server      | [c1623d6f23](https://bsd-hardware.info/?probe=c1623d6f23) | Jul 26, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [81586f6d39](https://bsd-hardware.info/?probe=81586f6d39) | Jul 22, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [ce43e9f067](https://bsd-hardware.info/?probe=ce43e9f067) | Jul 22, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [59c576a4ba](https://bsd-hardware.info/?probe=59c576a4ba) | Jul 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [3fe3a46a7a](https://bsd-hardware.info/?probe=3fe3a46a7a) | Jul 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bbca74a96f](https://bsd-hardware.info/?probe=bbca74a96f) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [070ccc68f8](https://bsd-hardware.info/?probe=070ccc68f8) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [9e54e446ef](https://bsd-hardware.info/?probe=9e54e446ef) | Jul 14, 2022 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [d43e397f02](https://bsd-hardware.info/?probe=d43e397f02) | Jul 10, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab2f42b567](https://bsd-hardware.info/?probe=ab2f42b567) | Jun 26, 2022 |
| Dell          | 0M877N A02                  | Server      | [c6f1ccfe6d](https://bsd-hardware.info/?probe=c6f1ccfe6d) | Jun 22, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | Desktop     | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Alienware     | M18xR2                      | Notebook    | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4e0a906acb](https://bsd-hardware.info/?probe=4e0a906acb) | Jun 11, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [776a4892d0](https://bsd-hardware.info/?probe=776a4892d0) | Jun 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude 7490               | Notebook    | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [9bacfc2b0e](https://bsd-hardware.info/?probe=9bacfc2b0e) | May 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| ASRock        | A320M Pro4-F                | Desktop     | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Intel         | H81U                        | Notebook    | [550699602e](https://bsd-hardware.info/?probe=550699602e) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [6cf944b0ef](https://bsd-hardware.info/?probe=6cf944b0ef) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf58c679ef](https://bsd-hardware.info/?probe=cf58c679ef) | May 08, 2022 |
| Intel         | H81U                        | Notebook    | [04646d1cc7](https://bsd-hardware.info/?probe=04646d1cc7) | May 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [3481513b0f](https://bsd-hardware.info/?probe=3481513b0f) | May 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | Notebook    | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell          | Precision 7730              | Notebook    | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [86ade7ce4b](https://bsd-hardware.info/?probe=86ade7ce4b) | Apr 30, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [8fce57c9e4](https://bsd-hardware.info/?probe=8fce57c9e4) | Apr 25, 2022 |
| ASUSTek       | P5KR                        | Desktop     | [cf745ca0da](https://bsd-hardware.info/?probe=cf745ca0da) | Apr 23, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [875d6b2da3](https://bsd-hardware.info/?probe=875d6b2da3) | Apr 22, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a278852381](https://bsd-hardware.info/?probe=a278852381) | Apr 21, 2022 |
| Dell          | 06JWJY A01                  | Desktop     | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| Dell          | Latitude E5450              | Notebook    | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Deciso        | Netboard A10                | Desktop     | [6e0b916230](https://bsd-hardware.info/?probe=6e0b916230) | Apr 16, 2022 |
| HP            | 86E9 A                      | Desktop     | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4b981630d7](https://bsd-hardware.info/?probe=4b981630d7) | Apr 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [06720f3c57](https://bsd-hardware.info/?probe=06720f3c57) | Apr 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [e6ba291c2d](https://bsd-hardware.info/?probe=e6ba291c2d) | Apr 12, 2022 |
| Jetway        | 1.0                         | Desktop     | [ac2ab09363](https://bsd-hardware.info/?probe=ac2ab09363) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e208e9425](https://bsd-hardware.info/?probe=4e208e9425) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [50833ab257](https://bsd-hardware.info/?probe=50833ab257) | Apr 07, 2022 |
| Sophos        | XG                          | Firewall    | [c98fff0cf2](https://bsd-hardware.info/?probe=c98fff0cf2) | Apr 06, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e44ebcb340](https://bsd-hardware.info/?probe=e44ebcb340) | Apr 06, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [35dcbd74e9](https://bsd-hardware.info/?probe=35dcbd74e9) | Apr 05, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [946c8fd467](https://bsd-hardware.info/?probe=946c8fd467) | Apr 04, 2022 |
| PC Engines    | APU2                        | Desktop     | [5eb2e04d11](https://bsd-hardware.info/?probe=5eb2e04d11) | Apr 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [43cbc2ef2c](https://bsd-hardware.info/?probe=43cbc2ef2c) | Apr 02, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [c83fab9193](https://bsd-hardware.info/?probe=c83fab9193) | Apr 01, 2022 |
| Unknown       | Unknown                     | Firewall    | [b5c3949db8](https://bsd-hardware.info/?probe=b5c3949db8) | Mar 29, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [7a991e2f31](https://bsd-hardware.info/?probe=7a991e2f31) | Mar 24, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [acb99d63ce](https://bsd-hardware.info/?probe=acb99d63ce) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [05a81cb5d5](https://bsd-hardware.info/?probe=05a81cb5d5) | Mar 22, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [483cf54bfc](https://bsd-hardware.info/?probe=483cf54bfc) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a4a1c8e5ca](https://bsd-hardware.info/?probe=a4a1c8e5ca) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [b137b25594](https://bsd-hardware.info/?probe=b137b25594) | Mar 15, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [b652261bda](https://bsd-hardware.info/?probe=b652261bda) | Mar 14, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0a2a94839d](https://bsd-hardware.info/?probe=0a2a94839d) | Mar 13, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Supermicro    | X11SDV-8C-TLN2F             | Server      | [e1fceaabc0](https://bsd-hardware.info/?probe=e1fceaabc0) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [0051c86e4c](https://bsd-hardware.info/?probe=0051c86e4c) | Mar 07, 2022 |
| AAEON         | UP-CHT01 V0.4               | Desktop     | [9aaa7c7a32](https://bsd-hardware.info/?probe=9aaa7c7a32) | Mar 05, 2022 |
| Protectli     | VP2410                      | Desktop     | [1f650fc994](https://bsd-hardware.info/?probe=1f650fc994) | Mar 05, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [d73d3760ce](https://bsd-hardware.info/?probe=d73d3760ce) | Mar 04, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [a3611d42bc](https://bsd-hardware.info/?probe=a3611d42bc) | Mar 04, 2022 |
| PC Engines    | apu1                        | Desktop     | [177dc1fbc8](https://bsd-hardware.info/?probe=177dc1fbc8) | Mar 03, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [43bfceb19d](https://bsd-hardware.info/?probe=43bfceb19d) | Mar 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [4367711bff](https://bsd-hardware.info/?probe=4367711bff) | Mar 01, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [7b19f71ce1](https://bsd-hardware.info/?probe=7b19f71ce1) | Feb 26, 2022 |
| PC Engines    | apu1                        | Desktop     | [d904aa7790](https://bsd-hardware.info/?probe=d904aa7790) | Feb 24, 2022 |
| Intel         | CARLOW                      | Desktop     | [d46b68cc28](https://bsd-hardware.info/?probe=d46b68cc28) | Feb 23, 2022 |
| HP            | 8169                        | Desktop     | [f449b4cd6c](https://bsd-hardware.info/?probe=f449b4cd6c) | Feb 23, 2022 |
| Dell          | 0W13NR A07                  | Server      | [22846d44fb](https://bsd-hardware.info/?probe=22846d44fb) | Feb 22, 2022 |
| Dell          | 0TY019 A00                  | Server      | [5f750e021e](https://bsd-hardware.info/?probe=5f750e021e) | Feb 20, 2022 |
| Intel         | CARLOW                      | Desktop     | [b64bf97293](https://bsd-hardware.info/?probe=b64bf97293) | Feb 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [ef5cc6be72](https://bsd-hardware.info/?probe=ef5cc6be72) | Feb 17, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [18576ef86c](https://bsd-hardware.info/?probe=18576ef86c) | Feb 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [fbc24f90e5](https://bsd-hardware.info/?probe=fbc24f90e5) | Feb 17, 2022 |
| MSI           | MS-7253                     | Desktop     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [df529a84b9](https://bsd-hardware.info/?probe=df529a84b9) | Feb 16, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| AMD           | X64                         | Desktop     | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [ee3a7740ec](https://bsd-hardware.info/?probe=ee3a7740ec) | Feb 13, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [09a6920a4f](https://bsd-hardware.info/?probe=09a6920a4f) | Feb 12, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [61c103f80d](https://bsd-hardware.info/?probe=61c103f80d) | Feb 11, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Sophos        | XG                          | Firewall    | [31a8174933](https://bsd-hardware.info/?probe=31a8174933) | Feb 10, 2022 |
| Sophos        | XG                          | Firewall    | [365e4cfbea](https://bsd-hardware.info/?probe=365e4cfbea) | Feb 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [8342bcccf5](https://bsd-hardware.info/?probe=8342bcccf5) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2accc42e21](https://bsd-hardware.info/?probe=2accc42e21) | Feb 06, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [9213769810](https://bsd-hardware.info/?probe=9213769810) | Feb 05, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [00cabbe0bf](https://bsd-hardware.info/?probe=00cabbe0bf) | Feb 05, 2022 |
| Dell          | 0W13NR A07                  | Server      | [1582d0700a](https://bsd-hardware.info/?probe=1582d0700a) | Feb 03, 2022 |
| Deciso        | Netboard A20                | Notebook    | [8cd43fcfd1](https://bsd-hardware.info/?probe=8cd43fcfd1) | Feb 03, 2022 |
| Intel         | SKYBAY                      | Desktop     | [95c3231a3a](https://bsd-hardware.info/?probe=95c3231a3a) | Feb 03, 2022 |
| MSI           | MS-9A45 0A                  | Desktop     | [cfbfdf0e55](https://bsd-hardware.info/?probe=cfbfdf0e55) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | Notebook    | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [ccda2302cf](https://bsd-hardware.info/?probe=ccda2302cf) | Jan 30, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [9dc53740a9](https://bsd-hardware.info/?probe=9dc53740a9) | Jan 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| AMD           | Larne CRB                   | Desktop     | [c6a85da1d5](https://bsd-hardware.info/?probe=c6a85da1d5) | Jan 28, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7a5d842d33](https://bsd-hardware.info/?probe=7a5d842d33) | Jan 27, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f1c7ee0712](https://bsd-hardware.info/?probe=f1c7ee0712) | Jan 26, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [5c58d01f2d](https://bsd-hardware.info/?probe=5c58d01f2d) | Jan 25, 2022 |
| RUNING        | B75M INTEL H3V              | Desktop     | [9a060df0a2](https://bsd-hardware.info/?probe=9a060df0a2) | Jan 23, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [cd745d6377](https://bsd-hardware.info/?probe=cd745d6377) | Jan 23, 2022 |
| AMD           | Larne CRB                   | Desktop     | [6c37b91111](https://bsd-hardware.info/?probe=6c37b91111) | Jan 22, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b01e6eb706](https://bsd-hardware.info/?probe=b01e6eb706) | Jan 22, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [6baaab27fd](https://bsd-hardware.info/?probe=6baaab27fd) | Jan 15, 2022 |
| MSI           | MS-98C8                     | Desktop     | [0102557f05](https://bsd-hardware.info/?probe=0102557f05) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [7062b84459](https://bsd-hardware.info/?probe=7062b84459) | Jan 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1ff4a66d03](https://bsd-hardware.info/?probe=1ff4a66d03) | Jan 12, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Dell          | Latitude E5450              | Notebook    | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [6aeb9adadb](https://bsd-hardware.info/?probe=6aeb9adadb) | Dec 31, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [b6139f57b9](https://bsd-hardware.info/?probe=b6139f57b9) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | Notebook    | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [07221fc111](https://bsd-hardware.info/?probe=07221fc111) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cdb5578df8](https://bsd-hardware.info/?probe=cdb5578df8) | Dec 27, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| Samsung       | R720                        | Notebook    | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | Notebook    | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Supermicro    | X11SSL-F                    | Server      | [a5a440a7a7](https://bsd-hardware.info/?probe=a5a440a7a7) | Dec 20, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [124ac672b0](https://bsd-hardware.info/?probe=124ac672b0) | Dec 20, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [225298bcd6](https://bsd-hardware.info/?probe=225298bcd6) | Dec 12, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [26220d3f14](https://bsd-hardware.info/?probe=26220d3f14) | Dec 09, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [61312aa506](https://bsd-hardware.info/?probe=61312aa506) | Nov 30, 2021 |
| Dell          | VEP-4600-V930 034R2CA03     | Desktop     | [313d1b7032](https://bsd-hardware.info/?probe=313d1b7032) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [16206960c4](https://bsd-hardware.info/?probe=16206960c4) | Nov 24, 2021 |
| HP            | 3031h                       | Desktop     | [056352a663](https://bsd-hardware.info/?probe=056352a663) | Nov 21, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [5cfcc8c5f8](https://bsd-hardware.info/?probe=5cfcc8c5f8) | Nov 13, 2021 |
| HP            | 3031h                       | Desktop     | [d63bbcfceb](https://bsd-hardware.info/?probe=d63bbcfceb) | Oct 31, 2021 |
| HP            | 3031h                       | Desktop     | [c5e39a5e6d](https://bsd-hardware.info/?probe=c5e39a5e6d) | Oct 31, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e2db09bacb](https://bsd-hardware.info/?probe=e2db09bacb) | Oct 30, 2021 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [dfba84ce5a](https://bsd-hardware.info/?probe=dfba84ce5a) | Oct 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e2167afc3b](https://bsd-hardware.info/?probe=e2167afc3b) | Oct 25, 2021 |
| BESSTAR Te... | VB9                         | All in one  | [ac1f5a3339](https://bsd-hardware.info/?probe=ac1f5a3339) | Oct 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3f5b148e23](https://bsd-hardware.info/?probe=3f5b148e23) | Oct 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6f019f05b6](https://bsd-hardware.info/?probe=6f019f05b6) | Oct 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [4b8fb7992f](https://bsd-hardware.info/?probe=4b8fb7992f) | Oct 16, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [c5226ff226](https://bsd-hardware.info/?probe=c5226ff226) | Oct 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Dell          | 04JN2K A04                  | Server      | [f529f87cea](https://bsd-hardware.info/?probe=f529f87cea) | Oct 11, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [4ad37c1848](https://bsd-hardware.info/?probe=4ad37c1848) | Oct 10, 2021 |
| Google        | Terra                       | Notebook    | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [2fd62acb45](https://bsd-hardware.info/?probe=2fd62acb45) | Oct 10, 2021 |
| Lenovo        | 3138                        | Desktop     | [8b5cf892d0](https://bsd-hardware.info/?probe=8b5cf892d0) | Oct 04, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | Notebook    | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [5b7623f03b](https://bsd-hardware.info/?probe=5b7623f03b) | Sep 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [1b8ce81945](https://bsd-hardware.info/?probe=1b8ce81945) | Sep 19, 2021 |
| MSI           | P65 Creator 8RE             | Notebook    | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [5f78c3411f](https://bsd-hardware.info/?probe=5f78c3411f) | Sep 13, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | Desktop     | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| ASUSTek       | P8B-X series                | Server      | [1e7d58cd40](https://bsd-hardware.info/?probe=1e7d58cd40) | Aug 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [827c50f77b](https://bsd-hardware.info/?probe=827c50f77b) | Aug 28, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| PC Engines    | APU2                        | Desktop     | [0a35da2af7](https://bsd-hardware.info/?probe=0a35da2af7) | Aug 24, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [51b5325c85](https://bsd-hardware.info/?probe=51b5325c85) | Aug 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [1dd499d54c](https://bsd-hardware.info/?probe=1dd499d54c) | Aug 12, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [11526a150b](https://bsd-hardware.info/?probe=11526a150b) | Aug 10, 2021 |
| Shuttle       | FS61                        | Desktop     | [b1fbaa8a6b](https://bsd-hardware.info/?probe=b1fbaa8a6b) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [5f9c53366b](https://bsd-hardware.info/?probe=5f9c53366b) | Aug 05, 2021 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [b9ef180b73](https://bsd-hardware.info/?probe=b9ef180b73) | Aug 04, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [3ff984316b](https://bsd-hardware.info/?probe=3ff984316b) | Aug 04, 2021 |
| Dell          | 0G261D A00                  | Desktop     | [2ce00e9f6b](https://bsd-hardware.info/?probe=2ce00e9f6b) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2a1251b320](https://bsd-hardware.info/?probe=2a1251b320) | Aug 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [34d448e1d1](https://bsd-hardware.info/?probe=34d448e1d1) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [846b6cca20](https://bsd-hardware.info/?probe=846b6cca20) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [8aaf18daa1](https://bsd-hardware.info/?probe=8aaf18daa1) | Jul 28, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [4831cc5183](https://bsd-hardware.info/?probe=4831cc5183) | Jul 21, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [2484df8d38](https://bsd-hardware.info/?probe=2484df8d38) | Jul 18, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| HP            | 2B4B                        | Desktop     | [456625c82f](https://bsd-hardware.info/?probe=456625c82f) | Jul 04, 2021 |
| Notebook      | W510LU                      | Notebook    | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [1e66c42238](https://bsd-hardware.info/?probe=1e66c42238) | Jul 02, 2021 |
| Shuttle       | NC10U                       | Desktop     | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [661d3349cb](https://bsd-hardware.info/?probe=661d3349cb) | Jun 26, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [95b0c9a6a3](https://bsd-hardware.info/?probe=95b0c9a6a3) | Jun 25, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| ASRock        | H110M-ITX                   | Desktop     | [124c75ba7c](https://bsd-hardware.info/?probe=124c75ba7c) | Jun 17, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [007ce2b6ce](https://bsd-hardware.info/?probe=007ce2b6ce) | Jun 17, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [e6cbfc417b](https://bsd-hardware.info/?probe=e6cbfc417b) | Jun 10, 2021 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Dell          | 0TY019 A01                  | Server      | [411477e260](https://bsd-hardware.info/?probe=411477e260) | Jun 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [24f3dbd372](https://bsd-hardware.info/?probe=24f3dbd372) | Jun 04, 2021 |
| Shuttle       | FS35V5                      | Mini pc     | [bfd71efa3b](https://bsd-hardware.info/?probe=bfd71efa3b) | May 31, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [cec18015ba](https://bsd-hardware.info/?probe=cec18015ba) | May 30, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [193936b5ca](https://bsd-hardware.info/?probe=193936b5ca) | May 30, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo        | ThinkPad A485 20MVS0FD00    | Notebook    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [16f36a045f](https://bsd-hardware.info/?probe=16f36a045f) | May 26, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [3e650be93d](https://bsd-hardware.info/?probe=3e650be93d) | May 24, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [aafc52d6a1](https://bsd-hardware.info/?probe=aafc52d6a1) | May 24, 2021 |
| Google        | Guado                       | Desktop     | [54f01f821d](https://bsd-hardware.info/?probe=54f01f821d) | May 21, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [c471a8f2fe](https://bsd-hardware.info/?probe=c471a8f2fe) | May 16, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [3468faf656](https://bsd-hardware.info/?probe=3468faf656) | May 07, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [421da89770](https://bsd-hardware.info/?probe=421da89770) | May 06, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| PC Engines    | APU2                        | Desktop     | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e930fac60b](https://bsd-hardware.info/?probe=e930fac60b) | May 05, 2021 |
| Supermicro    | X8STi                       | Desktop     | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | Rampage II GENE             | Desktop     | [4eac97c85c](https://bsd-hardware.info/?probe=4eac97c85c) | May 04, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [4368de8d34](https://bsd-hardware.info/?probe=4368de8d34) | Apr 28, 2021 |
| PC Engines    | APU3                        | Desktop     | [1d6ca07c5a](https://bsd-hardware.info/?probe=1d6ca07c5a) | Apr 27, 2021 |
| PC Engines    | APU3                        | Desktop     | [8fc426b107](https://bsd-hardware.info/?probe=8fc426b107) | Apr 22, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [e262812b4d](https://bsd-hardware.info/?probe=e262812b4d) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430 23495P8       | Notebook    | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [354dc80671](https://bsd-hardware.info/?probe=354dc80671) | Apr 07, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7901474a09](https://bsd-hardware.info/?probe=7901474a09) | Apr 07, 2021 |
| PC Engines    | apu4                        | Desktop     | [160a01d9e1](https://bsd-hardware.info/?probe=160a01d9e1) | Apr 03, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [f3b6d4d5c4](https://bsd-hardware.info/?probe=f3b6d4d5c4) | Apr 03, 2021 |
| ASUSTek       | P8B-X series                | Server      | [f60388bf6a](https://bsd-hardware.info/?probe=f60388bf6a) | Apr 03, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [7031b0ed1e](https://bsd-hardware.info/?probe=7031b0ed1e) | Mar 31, 2021 |
| PC Engines    | APU2                        | Desktop     | [97554df75d](https://bsd-hardware.info/?probe=97554df75d) | Mar 30, 2021 |
| Lenovo        | ThinkPad X220 4290EE8       | Notebook    | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009FR    | Notebook    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [e789c55f2e](https://bsd-hardware.info/?probe=e789c55f2e) | Mar 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [0263b0e32e](https://bsd-hardware.info/?probe=0263b0e32e) | Mar 26, 2021 |
| Lenovo        | 3138                        | Desktop     | [f12dd68efb](https://bsd-hardware.info/?probe=f12dd68efb) | Mar 25, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [68354c00cf](https://bsd-hardware.info/?probe=68354c00cf) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [bef38bd379](https://bsd-hardware.info/?probe=bef38bd379) | Mar 23, 2021 |
| MSI           | MS-N033                     | Notebook    | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [c0df245c1b](https://bsd-hardware.info/?probe=c0df245c1b) | Mar 13, 2021 |
| SECO          | UDOO x86                    | Notebook    | [f8310915b6](https://bsd-hardware.info/?probe=f8310915b6) | Mar 13, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [24b657e7ba](https://bsd-hardware.info/?probe=24b657e7ba) | Mar 12, 2021 |
| Dell          | 05XKKK A05                  | Server      | [d3fe07511a](https://bsd-hardware.info/?probe=d3fe07511a) | Mar 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [bbcc01d2ce](https://bsd-hardware.info/?probe=bbcc01d2ce) | Mar 11, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [17a763a917](https://bsd-hardware.info/?probe=17a763a917) | Mar 11, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [835842d361](https://bsd-hardware.info/?probe=835842d361) | Mar 10, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | Notebook    | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [9468eeef92](https://bsd-hardware.info/?probe=9468eeef92) | Mar 04, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [fc655524ab](https://bsd-hardware.info/?probe=fc655524ab) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Dell          | Latitude 5280               | Notebook    | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| HP            | 86E9 A                      | Desktop     | [215398b88f](https://bsd-hardware.info/?probe=215398b88f) | Feb 28, 2021 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b1f1b3cd82](https://bsd-hardware.info/?probe=b1f1b3cd82) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [929bda8001](https://bsd-hardware.info/?probe=929bda8001) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Acer          | EG43M                       | Desktop     | [22552918ee](https://bsd-hardware.info/?probe=22552918ee) | Feb 21, 2021 |
| Gigabyte      | P15FR7                      | Notebook    | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| Supermicro    | X9DRT                       | Server      | [a3bcb2fcf1](https://bsd-hardware.info/?probe=a3bcb2fcf1) | Feb 18, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [261756a327](https://bsd-hardware.info/?probe=261756a327) | Feb 17, 2021 |
| ASUSTek       | X75VC                       | Notebook    | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [5d39657098](https://bsd-hardware.info/?probe=5d39657098) | Feb 14, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Lenovo        | ThinkPad T580 20LAS2TG00    | Notebook    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| PC Engines    | APU                         | Desktop     | [282a9596c6](https://bsd-hardware.info/?probe=282a9596c6) | Feb 11, 2021 |
| Dell          | Latitude 3410               | Notebook    | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Dell          | 0H28RR A02                  | Server      | [0bbf4a51bb](https://bsd-hardware.info/?probe=0bbf4a51bb) | Feb 10, 2021 |
| Dell          | 0H28RR A02                  | Server      | [eaac725443](https://bsd-hardware.info/?probe=eaac725443) | Feb 10, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Dell          | Latitude E6230              | Notebook    | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [94bcab24a8](https://bsd-hardware.info/?probe=94bcab24a8) | Feb 09, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell          | Latitude 5280               | Notebook    | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| PC Engines    | APU3                        | Desktop     | [e21438c3cc](https://bsd-hardware.info/?probe=e21438c3cc) | Feb 07, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Dell          | Latitude 3410               | Notebook    | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [35bae50659](https://bsd-hardware.info/?probe=35bae50659) | Feb 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [8ef7071a3f](https://bsd-hardware.info/?probe=8ef7071a3f) | Feb 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [857c5aade9](https://bsd-hardware.info/?probe=857c5aade9) | Feb 04, 2021 |
| CompuLab      | fitlet2                     | Mini pc     | [7ff0034c98](https://bsd-hardware.info/?probe=7ff0034c98) | Feb 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [b005d61a99](https://bsd-hardware.info/?probe=b005d61a99) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [f66ccf2f33](https://bsd-hardware.info/?probe=f66ccf2f33) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [c384535b6f](https://bsd-hardware.info/?probe=c384535b6f) | Feb 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a7494d60a5](https://bsd-hardware.info/?probe=a7494d60a5) | Jan 31, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [27a3bb8503](https://bsd-hardware.info/?probe=27a3bb8503) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [dae16641bb](https://bsd-hardware.info/?probe=dae16641bb) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c4d549584](https://bsd-hardware.info/?probe=4c4d549584) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [80edc8dae6](https://bsd-hardware.info/?probe=80edc8dae6) | Jan 22, 2021 |
| PC Engines    | apu4                        | Desktop     | [3507544d2e](https://bsd-hardware.info/?probe=3507544d2e) | Jan 20, 2021 |
| Lenovo        | ThinkPad P50 20EQS0U60C     | Notebook    | [d8cf9e878e](https://bsd-hardware.info/?probe=d8cf9e878e) | Jan 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | Notebook    | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| HP            | 3399                        | Desktop     | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [d894ae5d09](https://bsd-hardware.info/?probe=d894ae5d09) | Jan 07, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | Desktop     | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Dell          | Latitude 5280               | Notebook    | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| Gigabyte      | X79-UD3                     | Desktop     | [a8baf509d9](https://bsd-hardware.info/?probe=a8baf509d9) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | Notebook    | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Dell          | Latitude 5280               | Notebook    | [d1be72cc7e](https://bsd-hardware.info/?probe=d1be72cc7e) | Nov 21, 2020 |
| Dell          | Latitude 5280               | Notebook    | [fd4e8756b4](https://bsd-hardware.info/?probe=fd4e8756b4) | Nov 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Dell          | 03X6X0 A03                  | Server      | [7d7b8ca054](https://bsd-hardware.info/?probe=7d7b8ca054) | Oct 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [1d5bd18d14](https://bsd-hardware.info/?probe=1d5bd18d14) | Oct 29, 2020 |
| Supermicro    | X8STi                       | Desktop     | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| AZW           | Z83 II                      | Desktop     | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | Desktop     | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Intel         | D2500HN                     | Desktop     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| PC Engines    | APU2                        | Desktop     | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | Notebook    | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | Desktop     | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| Intel         | D2500HN                     | Desktop     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| ASUSTek       | X102BA                      | Notebook    | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| ASUSTek       | UX305FA                     | Notebook    | [4ecb1e9cd3](https://bsd-hardware.info/?probe=4ecb1e9cd3) | Sep 25, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [88f2d98930](https://bsd-hardware.info/?probe=88f2d98930) | Sep 12, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [986575086d](https://bsd-hardware.info/?probe=986575086d) | Sep 05, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f95de56bcd](https://bsd-hardware.info/?probe=f95de56bcd) | Sep 03, 2020 |
| Intel         | DH61AG AAG23736-505         | Desktop     | [3f99489a19](https://bsd-hardware.info/?probe=3f99489a19) | Aug 19, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [42de38c478](https://bsd-hardware.info/?probe=42de38c478) | Aug 19, 2020 |
| Intel         | DN2800MT AAG81515-900       | Desktop     | [bcfec367a9](https://bsd-hardware.info/?probe=bcfec367a9) | Aug 14, 2020 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [4ed0c89a67](https://bsd-hardware.info/?probe=4ed0c89a67) | Aug 07, 2020 |
| Dell          | 081N4V A07                  | Server      | [2d835336d9](https://bsd-hardware.info/?probe=2d835336d9) | Aug 07, 2020 |
| Dell          | 081N4V A07                  | Server      | [14a20876f4](https://bsd-hardware.info/?probe=14a20876f4) | Aug 07, 2020 |
| HP            | ProLiant DL120 G7           | Server      | [f873647eb9](https://bsd-hardware.info/?probe=f873647eb9) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [7b8885caf3](https://bsd-hardware.info/?probe=7b8885caf3) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [2e9821f90f](https://bsd-hardware.info/?probe=2e9821f90f) | Aug 07, 2020 |
| Gigabyte      | EP45-DS4                    | Desktop     | [a56a9c50fc](https://bsd-hardware.info/?probe=a56a9c50fc) | Aug 07, 2020 |
| Sony          | VGN-AR630E                  | Notebook    | [b417df513f](https://bsd-hardware.info/?probe=b417df513f) | Aug 07, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [0b111b137c](https://bsd-hardware.info/?probe=0b111b137c) | Aug 07, 2020 |
| MSI           | P65 Creator 8RE             | Notebook    | [4031d186c2](https://bsd-hardware.info/?probe=4031d186c2) | Aug 06, 2020 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [82de136ad3](https://bsd-hardware.info/?probe=82de136ad3) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Intel         | DH61AGL G71256-202          | Desktop     | [666757a826](https://bsd-hardware.info/?probe=666757a826) | Jun 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [dc1c86095f](https://bsd-hardware.info/?probe=dc1c86095f) | Jun 14, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [90e2b57f16](https://bsd-hardware.info/?probe=90e2b57f16) | Jun 14, 2020 |
| HPE           | ProLiant MicroServer Gen... | Server      | [be41b5cd29](https://bsd-hardware.info/?probe=be41b5cd29) | Jun 14, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [9ad34ffa59](https://bsd-hardware.info/?probe=9ad34ffa59) | Jun 14, 2020 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [06beb9ad2c](https://bsd-hardware.info/?probe=06beb9ad2c) | Jun 12, 2020 |
| CompuLab      | fitlet2                     | Mini pc     | [00c1939eac](https://bsd-hardware.info/?probe=00c1939eac) | Jun 03, 2020 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [48dd406069](https://bsd-hardware.info/?probe=48dd406069) | May 30, 2020 |
| Dell          | 0MD99X A12                  | Server      | [e2ab2682cb](https://bsd-hardware.info/?probe=e2ab2682cb) | May 27, 2020 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [94c4617d4e](https://bsd-hardware.info/?probe=94c4617d4e) | May 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [7c8a68918a](https://bsd-hardware.info/?probe=7c8a68918a) | May 27, 2020 |
| MSI           | Z87I GAMING AC              | Desktop     | [5d38b05178](https://bsd-hardware.info/?probe=5d38b05178) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bb2fcf8d92](https://bsd-hardware.info/?probe=bb2fcf8d92) | May 25, 2020 |
| Unknown       | Unknown                     | Desktop     | [3bcdac5d97](https://bsd-hardware.info/?probe=3bcdac5d97) | May 24, 2020 |
| HP            | ZBook 15                    | Notebook    | [3e9076f244](https://bsd-hardware.info/?probe=3e9076f244) | May 23, 2020 |
| HP            | ZBook 15                    | Notebook    | [23ec663f87](https://bsd-hardware.info/?probe=23ec663f87) | May 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OpenBSD 6.8         | 16        | 3.54%   |
| OPNsense 21.1.5     | 14        | 3.1%    |
| FreeBSD 13.1        | 14        | 3.1%    |
| OPNsense 21.7.7     | 13        | 2.88%   |
| OPNsense 22.1       | 12        | 2.65%   |
| helloSystem 0.7.0   | 11        | 2.43%   |
| helloSystem 0.4.0   | 11        | 2.43%   |
| OPNsense 22.1.6     | 10        | 2.21%   |
| OPNsense 22.1.10    | 10        | 2.21%   |
| NomadBSD 1.3.2      | 10        | 2.21%   |
| GhostBSD 20.04.02   | 10        | 2.21%   |
| OPNsense 21.7.1     | 9         | 1.99%   |
| OPNsense 21.1       | 9         | 1.99%   |
| FreeBSD 13.0        | 9         | 1.99%   |
| OPNsense 22.7.9     | 8         | 1.77%   |
| OPNsense 22.7.4     | 8         | 1.77%   |
| OPNsense 22.7       | 8         | 1.77%   |
| OPNsense 22.1.1     | 8         | 1.77%   |
| OPNsense 21.1.3     | 8         | 1.77%   |
| FreeBSD 12.1-p8     | 8         | 1.77%   |
| OPNsense 22.7.7     | 7         | 1.55%   |
| OPNsense 21.7.8     | 7         | 1.55%   |
| OpenBSD 7.1         | 7         | 1.55%   |
| OPNsense 22.1.2     | 6         | 1.33%   |
| OPNsense 21.7.3     | 6         | 1.33%   |
| OPNsense 21.1.4     | 6         | 1.33%   |
| OpenBSD 7.0         | 6         | 1.33%   |
| OpenBSD 6.9         | 6         | 1.33%   |
| helloSystem 0.5.0   | 6         | 1.33%   |
| OPNsense 22.1.4     | 5         | 1.11%   |
| OPNsense 21.7       | 5         | 1.11%   |
| OPNsense 21.1.7     | 5         | 1.11%   |
| OPNsense 21.1.6     | 5         | 1.11%   |
| OPNsense 21.1.1     | 5         | 1.11%   |
| OPNsense 20.7.8     | 5         | 1.11%   |
| NomadBSD 1.4        | 5         | 1.11%   |
| FreeBSD 13.0-STABLE | 5         | 1.11%   |
| FreeBSD 12.2-p4     | 5         | 1.11%   |
| FreeBSD 12.2-p2     | 5         | 1.11%   |
| FreeBSD 12.1-STABLE | 5         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 163       | 44.41%  |
| FreeBSD     | 102       | 27.79%  |
| OpenBSD     | 36        | 9.81%   |
| helloSystem | 29        | 7.9%    |
| NomadBSD    | 15        | 4.09%   |
| GhostBSD    | 14        | 3.81%   |
| NetBSD      | 3         | 0.82%   |
| TrueNAS     | 2         | 0.54%   |
| HardenedBSD | 1         | 0.27%   |
| FuryBSD     | 1         | 0.27%   |
| FreeNAS     | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 349       | 98.31%  |
| i386   | 4         | 1.13%   |
| macppc | 1         | 0.28%   |
| arm64  | 1         | 0.28%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 206       | 55.38%  |
| helloDesktop  | 42        | 11.29%  |
| XFCE          | 30        | 8.06%   |
| fvwm          | 18        | 4.84%   |
| KDE5          | 17        | 4.57%   |
| Openbox       | 16        | 4.3%    |
| MATE          | 13        | 3.49%   |
| TWM           | 9         | 2.42%   |
| GNOME         | 7         | 1.88%   |
| i3            | 4         | 1.08%   |
| LXDE          | 3         | 0.81%   |
| AwesomeWM     | 3         | 0.81%   |
| X-Cinnamon    | 1         | 0.27%   |
| sway          | 1         | 0.27%   |
| Enlightenment | 1         | 0.27%   |
| Cinnamon      | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 212       | 59.38%  |
| X11     | 144       | 40.34%  |
| Wayland | 1         | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 257       | 70.6%   |
| SLiM    | 56        | 15.38%  |
| LightDM | 23        | 6.32%   |
| SDDM    | 14        | 3.85%   |
| XDM     | 9         | 2.47%   |
| GDM     | 5         | 1.37%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 230       | 62.84%  |
| en_US           | 47        | 12.84%  |
| C               | 41        | 11.2%   |
| fr_FR           | 40        | 10.93%  |
| de_DE           | 3         | 0.82%   |
| en_GB           | 2         | 0.55%   |
| fr_FR.US-ASCII  | 1         | 0.27%   |
| es_ES           | 1         | 0.27%   |
| en_US.ISO8859-1 | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 273       | 76.04%  |
| BIOS | 86        | 23.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 174       | 47.41%  |
| Zfs    | 148       | 40.33%  |
| Ffs    | 36        | 9.81%   |
| Cd9660 | 9         | 2.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 301       | 83.84%  |
| MBR     | 55        | 15.32%  |
| Unknown | 3         | 0.84%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 58        | 16.34%  |
| ASUSTek Computer        | 44        | 12.39%  |
| Lenovo                  | 38        | 10.7%   |
| Intel                   | 30        | 8.45%   |
| Hewlett-Packard         | 23        | 6.48%   |
| Unknown                 | 19        | 5.35%   |
| PC Engines              | 18        | 5.07%   |
| Gigabyte Technology     | 15        | 4.23%   |
| Supermicro              | 10        | 2.82%   |
| MSI                     | 10        | 2.82%   |
| ASRock                  | 10        | 2.82%   |
| AMI                     | 7         | 1.97%   |
| Apple                   | 6         | 1.69%   |
| Deciso                  | 5         | 1.41%   |
| BESSTAR Tech            | 5         | 1.41%   |
| Shuttle                 | 4         | 1.13%   |
| Fujitsu                 | 4         | 1.13%   |
| Acer                    | 4         | 1.13%   |
| TUXEDO                  | 3         | 0.85%   |
| Protectli               | 3         | 0.85%   |
| Techvision              | 2         | 0.56%   |
| RUNING                  | 2         | 0.56%   |
| MW                      | 2         | 0.56%   |
| Google                  | 2         | 0.56%   |
| Clevo                   | 2         | 0.56%   |
| AWOW                    | 2         | 0.56%   |
| ASRockRack              | 2         | 0.56%   |
| AMD                     | 2         | 0.56%   |
| ZOTAC                   | 1         | 0.28%   |
| Wistron                 | 1         | 0.28%   |
| VeryPC                  | 1         | 0.28%   |
| Toshiba                 | 1         | 0.28%   |
| Sophos                  | 1         | 0.28%   |
| Sony                    | 1         | 0.28%   |
| Soekris Engineering     | 1         | 0.28%   |
| SECO                    | 1         | 0.28%   |
| Samsung Electronics     | 1         | 0.28%   |
| Raspberry Pi Foundation | 1         | 0.28%   |
| Pegatron                | 1         | 0.28%   |
| Panasonic               | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 20        | 5.63%   |
| Intel Q3XXG4-P V1.0            | 11        | 3.1%    |
| PC Engines APU2                | 10        | 2.82%   |
| AMI Aptio CRB                  | 6         | 1.69%   |
| ASUS All Series                | 4         | 1.13%   |
| PC Engines APU3                | 3         | 0.85%   |
| Intel H81U                     | 3         | 0.85%   |
| Dell Precision M4500           | 3         | 0.85%   |
| Dell PowerEdge R710            | 3         | 0.85%   |
| Dell OptiPlex 9020             | 3         | 0.85%   |
| Deciso Netboard A20            | 3         | 0.85%   |
| TUXEDO InfinityBook13V3        | 2         | 0.56%   |
| Techvision TVI7309X            | 2         | 0.56%   |
| Supermicro Super Server        | 2         | 0.56%   |
| Shuttle XS35V5                 | 2         | 0.56%   |
| RUNING B75M INTEL H3V          | 2         | 0.56%   |
| PC Engines apu4                | 2         | 0.56%   |
| PC Engines apu1                | 2         | 0.56%   |
| MW GMLK-2_5G4L                 | 2         | 0.56%   |
| Intel CRESCENTBAY              | 2         | 0.56%   |
| HP ProLiant MicroServer Gen8   | 2         | 0.56%   |
| Gigabyte X570 I AORUS PRO WIFI | 2         | 0.56%   |
| Dell PowerEdge R815            | 2         | 0.56%   |
| Dell PowerEdge R220            | 2         | 0.56%   |
| Dell PowerEdge R200            | 2         | 0.56%   |
| Dell OptiPlex 7010             | 2         | 0.56%   |
| Dell OptiPlex 3050             | 2         | 0.56%   |
| Dell OptiPlex 3010             | 2         | 0.56%   |
| Dell Latitude 3410             | 2         | 0.56%   |
| BESSTAR Tech N40               | 2         | 0.56%   |
| BESSTAR Tech GK41              | 2         | 0.56%   |
| AWOW PC BOX                    | 2         | 0.56%   |
| ASUS Z170-P D3                 | 2         | 0.56%   |
| ASUS PRIME B450M-A             | 2         | 0.56%   |
| ASUS P8Z68-V LX                | 2         | 0.56%   |
| ZOTAC XXXXXX                   | 1         | 0.28%   |
| Wistron ProLiant ML110 G6      | 1         | 0.28%   |
| VeryPC S400-K7-N-O             | 1         | 0.28%   |
| TUXEDO Aura 15 Gen1            | 1         | 0.28%   |
| Toshiba NB300                  | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 28        | 7.89%   |
| Unknown                 | 20        | 5.63%   |
| Dell OptiPlex           | 17        | 4.79%   |
| Dell PowerEdge          | 16        | 4.51%   |
| Intel Q3XXG4-P          | 11        | 3.1%    |
| Dell Latitude           | 11        | 3.1%    |
| PC Engines APU2         | 10        | 2.82%   |
| ASUS PRIME              | 9         | 2.54%   |
| HP Compaq               | 6         | 1.69%   |
| Dell Precision          | 6         | 1.69%   |
| AMI Aptio               | 6         | 1.69%   |
| HP ProLiant             | 5         | 1.41%   |
| Deciso Netboard         | 4         | 1.13%   |
| ASUS All                | 4         | 1.13%   |
| Acer Aspire             | 4         | 1.13%   |
| PC Engines APU3         | 3         | 0.85%   |
| Lenovo ThinkCentre      | 3         | 0.85%   |
| Intel H81U              | 3         | 0.85%   |
| HP ProDesk              | 3         | 0.85%   |
| HP EliteBook            | 3         | 0.85%   |
| TUXEDO InfinityBook13V3 | 2         | 0.56%   |
| Techvision TVI7309X     | 2         | 0.56%   |
| Supermicro Super        | 2         | 0.56%   |
| Shuttle XS35V5          | 2         | 0.56%   |
| RUNING B75M             | 2         | 0.56%   |
| PC Engines apu4         | 2         | 0.56%   |
| PC Engines apu1         | 2         | 0.56%   |
| MW GMLK-2               | 2         | 0.56%   |
| Lenovo Legion           | 2         | 0.56%   |
| Intel CRESCENTBAY       | 2         | 0.56%   |
| Gigabyte X570           | 2         | 0.56%   |
| Dell Vostro             | 2         | 0.56%   |
| Dell Studio             | 2         | 0.56%   |
| Dell Inspiron           | 2         | 0.56%   |
| BESSTAR Tech N40        | 2         | 0.56%   |
| BESSTAR Tech GK41       | 2         | 0.56%   |
| AWOW PC                 | 2         | 0.56%   |
| ASUS Z170-P             | 2         | 0.56%   |
| ASUS P8Z68-V            | 2         | 0.56%   |
| ZOTAC XXXXXX            | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 43        | 12.11%  |
| 2016    | 42        | 11.83%  |
| 2020    | 41        | 11.55%  |
| 2018    | 37        | 10.42%  |
| 2021    | 26        | 7.32%   |
| 2013    | 24        | 6.76%   |
| 2012    | 21        | 5.92%   |
| 2015    | 20        | 5.63%   |
| 2014    | 18        | 5.07%   |
| 2010    | 16        | 4.51%   |
| 2017    | 15        | 4.23%   |
| 2011    | 14        | 3.94%   |
| 2022    | 9         | 2.54%   |
| 2009    | 8         | 2.25%   |
| 2008    | 8         | 2.25%   |
| Unknown | 7         | 1.97%   |
| 2007    | 5         | 1.41%   |
| 2006    | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 197       | 55.49%  |
| Notebook       | 102       | 28.73%  |
| Mini pc        | 25        | 7.04%   |
| Server         | 24        | 6.76%   |
| Firewall       | 3         | 0.85%   |
| All in one     | 3         | 0.85%   |
| System on chip | 1         | 0.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 333       | 93.8%   |
| Yes  | 22        | 6.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 125       | 34.72%  |
| 4.01-8.0        | 83        | 23.06%  |
| 16.01-24.0      | 78        | 21.67%  |
| 32.01-64.0      | 27        | 7.5%    |
| 2.01-3.0        | 18        | 5%      |
| 64.01-256.0     | 11        | 3.06%   |
| 1.01-2.0        | 6         | 1.67%   |
| 3.01-4.0        | 5         | 1.39%   |
| 24.01-32.0      | 4         | 1.11%   |
| More than 256.0 | 2         | 0.56%   |
| 0.51-1.0        | 1         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 202       | 55.49%  |
| 0.51-1.0    | 96        | 26.37%  |
| 1.01-2.0    | 30        | 8.24%   |
| 2.01-3.0    | 10        | 2.75%   |
| 8.01-16.0   | 6         | 1.65%   |
| 4.01-8.0    | 5         | 1.37%   |
| 3.01-4.0    | 4         | 1.1%    |
| 32.01-64.0  | 3         | 0.82%   |
| Unknown     | 3         | 0.82%   |
| 64.01-256.0 | 2         | 0.55%   |
| 24.01-32.0  | 1         | 0.27%   |
| 16.01-24.0  | 1         | 0.27%   |
| 0           | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 225       | 62.15%  |
| 2      | 63        | 17.4%   |
| 0      | 33        | 9.12%   |
| 3      | 20        | 5.52%   |
| 4      | 8         | 2.21%   |
| 5      | 5         | 1.38%   |
| 6      | 4         | 1.1%    |
| 25     | 2         | 0.55%   |
| 10     | 1         | 0.28%   |
| 8      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 292       | 81.11%  |
| Yes       | 68        | 18.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 341       | 95.79%  |
| No        | 15        | 4.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 193       | 54.21%  |
| Yes       | 163       | 45.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 261       | 72.91%  |
| Yes       | 97        | 27.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 355       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Paris                    | 79        | 19.7%   |
| Toulouse                 | 8         | 2%      |
| Bordeaux                 | 8         | 2%      |
| Roubaix                  | 7         | 1.75%   |
| Franconville             | 7         | 1.75%   |
| Saint-Denis              | 6         | 1.5%    |
| Soisy-sur-Seine          | 5         | 1.25%   |
| Marseille                | 5         | 1.25%   |
| Lyon                     | 5         | 1.25%   |
| Rennes                   | 4         | 1%      |
| Agen                     | 4         | 1%      |
| Villeurbanne             | 3         | 0.75%   |
| Vauvillers               | 3         | 0.75%   |
| Vaulx-en-Velin           | 3         | 0.75%   |
| Thionville               | 3         | 0.75%   |
| Noisy-le-Grand           | 3         | 0.75%   |
| Montfermeil              | 3         | 0.75%   |
| Mâcon                   | 3         | 0.75%   |
| Lille                    | 3         | 0.75%   |
| Fontenay-sous-Bois       | 3         | 0.75%   |
| Colmar                   | 3         | 0.75%   |
| Carry-le-Rouet           | 3         | 0.75%   |
| Bonson                   | 3         | 0.75%   |
| Asnieres-sur-Seine       | 3         | 0.75%   |
| Г‰chirolles           | 2         | 0.5%    |
| Villeneuve-Saint-Georges | 2         | 0.5%    |
| Villejuif                | 2         | 0.5%    |
| Vichy                    | 2         | 0.5%    |
| Stiring-Wendel           | 2         | 0.5%    |
| Seyssinet-Pariset        | 2         | 0.5%    |
| Sarcelles                | 2         | 0.5%    |
| Sallanches               | 2         | 0.5%    |
| Saint-Martin-d'HГЁres  | 2         | 0.5%    |
| Saint-Herblain           | 2         | 0.5%    |
| Rosny-sous-Bois          | 2         | 0.5%    |
| Pau                      | 2         | 0.5%    |
| Nogent-sur-Marne         | 2         | 0.5%    |
| Nice                     | 2         | 0.5%    |
| Nantes                   | 2         | 0.5%    |
| Montpellier              | 2         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 81     | 13.35%  |
| Samsung Electronics | 50        | 74     | 12.14%  |
| WDC                 | 45        | 91     | 10.92%  |
| Crucial             | 36        | 44     | 8.74%   |
| Kingston            | 27        | 43     | 6.55%   |
| Transcend           | 25        | 34     | 6.07%   |
| Toshiba             | 23        | 37     | 5.58%   |
| SanDisk             | 16        | 25     | 3.88%   |
| China               | 14        | 21     | 3.4%    |
| Phison              | 11        | 12     | 2.67%   |
| Intel               | 11        | 17     | 2.67%   |
| HGST                | 9         | 16     | 2.18%   |
| Micron Technology   | 7         | 11     | 1.7%    |
| PNY                 | 6         | 13     | 1.46%   |
| NVMe                | 6         | 6      | 1.46%   |
| Hoodisk             | 6         | 6      | 1.46%   |
| SK hynix            | 5         | 5      | 1.21%   |
| Hitachi             | 5         | 5      | 1.21%   |
| FORESEE             | 4         | 5      | 0.97%   |
| Corsair             | 4         | 5      | 0.97%   |
| OCZ                 | 3         | 4      | 0.73%   |
| LDLC                | 3         | 3      | 0.73%   |
| Hewlett-Packard     | 3         | 6      | 0.73%   |
| Fujitsu             | 3         | 3      | 0.73%   |
| Dell                | 3         | 48     | 0.73%   |
| Apple               | 3         | 5      | 0.73%   |
| SPCC                | 2         | 2      | 0.49%   |
| NETAPP              | 2         | 4      | 0.49%   |
| Innodisk            | 2         | 2      | 0.49%   |
| Generic             | 2         | 2      | 0.49%   |
| A-DATA Technology   | 2         | 2      | 0.49%   |
| TEXTORM             | 1         | 1      | 0.24%   |
| TCSUNBOW            | 1         | 3      | 0.24%   |
| Silicon Power       | 1         | 1      | 0.24%   |
| ShiJi               | 1         | 2      | 0.24%   |
| SABRENT             | 1         | 1      | 0.24%   |
| Pccooler            | 1         | 1      | 0.24%   |
| OPENBSD             | 1         | 2      | 0.24%   |
| Maxtor              | 1         | 2      | 0.24%   |
| LITEON              | 1         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Phison SATA SSD 16GB                | 8         | 1.81%   |
| Kingston SV300S37A120G 120GB        | 5         | 1.13%   |
| Kingston SA400S37240G 240GB         | 5         | 1.13%   |
| Crucial CT1000P1SSD8 1TB            | 5         | 1.13%   |
| China MSATA 32GB SSD                | 5         | 1.13%   |
| Transcend TS256GMTS952T2 256GB      | 4         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 0.9%    |
| SanDisk SSD PLUS 120GB              | 4         | 0.9%    |
| Samsung SSD 850 EVO 250GB           | 4         | 0.9%    |
| Crucial CT250MX500SSD1 250GB        | 4         | 0.9%    |
| Crucial CT120BX500SSD1 120GB        | 4         | 0.9%    |
| Crucial CT1000BX500SSD1 1TB         | 4         | 0.9%    |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 0.68%   |
| Transcend TS128GMSA230S 128GB       | 3         | 0.68%   |
| Seagate ST1000LM049-2GH172 1TB      | 3         | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.68%   |
| Kingston SUV500MS120G 120GB         | 3         | 0.68%   |
| Hoodisk SSD 32GB                    | 3         | 0.68%   |
| HGST HUS724020ALA640 2TB            | 3         | 0.68%   |
| HP RAID 1(1+0) 800GB                | 3         | 0.68%   |
| Crucial CT500MX500SSD1 500GB        | 3         | 0.68%   |
| Crucial CT250P2SSD8 250GB           | 3         | 0.68%   |
| Crucial CT1050MX300SSD1 1TB         | 3         | 0.68%   |
| China MSATA 64GB SSD                | 3         | 0.68%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 0.45%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 0.45%   |
| WDC WD2000FYYX 2TB                  | 2         | 0.45%   |
| Transcend TS256GSSD230S 256GB       | 2         | 0.45%   |
| Transcend TS256GMTS430S 256GB       | 2         | 0.45%   |
| Transcend TS128GSSD420K 128GB       | 2         | 0.45%   |
| Transcend TS120GMTS420S 120GB       | 2         | 0.45%   |
| Toshiba MK2556GSY 250GB             | 2         | 0.45%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB | 2         | 0.45%   |
| Toshiba HDWD120 2TB                 | 2         | 0.45%   |
| SPCC Solid State Disk 512GB         | 2         | 0.45%   |
| SK hynix SC311 SATA 256GB           | 2         | 0.45%   |
| Seagate ST3500418AS 500GB           | 2         | 0.45%   |
| Seagate ST31000524AS 1TB            | 2         | 0.45%   |
| Seagate ST2000NM000A-2J2100 2TB     | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 78     | 34.64%  |
| WDC                 | 39        | 83     | 25.49%  |
| Toshiba             | 18        | 30     | 11.76%  |
| Samsung Electronics | 9         | 16     | 5.88%   |
| HGST                | 9         | 16     | 5.88%   |
| Hitachi             | 5         | 5      | 3.27%   |
| NVMe                | 4         | 4      | 2.61%   |
| Fujitsu             | 3         | 3      | 1.96%   |
| Dell                | 3         | 48     | 1.96%   |
| NETAPP              | 2         | 4      | 1.31%   |
| Generic             | 2         | 2      | 1.31%   |
| SABRENT             | 1         | 1      | 0.65%   |
| OPENBSD             | 1         | 2      | 0.65%   |
| Maxtor              | 1         | 2      | 0.65%   |
| LDLC F6+            | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 1      | 0.65%   |
| Apple               | 1         | 3      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 35     | 12.38%  |
| Crucial             | 26        | 29     | 12.38%  |
| Kingston            | 25        | 40     | 11.9%   |
| Transcend           | 24        | 32     | 11.43%  |
| SanDisk             | 16        | 25     | 7.62%   |
| China               | 14        | 21     | 6.67%   |
| Phison              | 8         | 9      | 3.81%   |
| PNY                 | 6         | 13     | 2.86%   |
| Hoodisk             | 6         | 6      | 2.86%   |
| WDC                 | 5         | 5      | 2.38%   |
| Toshiba             | 5         | 7      | 2.38%   |
| Intel               | 5         | 6      | 2.38%   |
| FORESEE             | 4         | 5      | 1.9%    |
| Corsair             | 4         | 5      | 1.9%    |
| SK hynix            | 3         | 3      | 1.43%   |
| OCZ                 | 3         | 4      | 1.43%   |
| Hewlett-Packard     | 3         | 5      | 1.43%   |
| SPCC                | 2         | 2      | 0.95%   |
| NVMe                | 2         | 2      | 0.95%   |
| Micron Technology   | 2         | 6      | 0.95%   |
| Innodisk            | 2         | 2      | 0.95%   |
| Apple               | 2         | 2      | 0.95%   |
| A-DATA Technology   | 2         | 2      | 0.95%   |
| TEXTORM             | 1         | 1      | 0.48%   |
| TCSUNBOW            | 1         | 3      | 0.48%   |
| Silicon Power       | 1         | 1      | 0.48%   |
| ShiJi               | 1         | 2      | 0.48%   |
| Seagate             | 1         | 2      | 0.48%   |
| Pccooler            | 1         | 1      | 0.48%   |
| LITEON              | 1         | 2      | 0.48%   |
| Kston               | 1         | 1      | 0.48%   |
| Kingchuxing         | 1         | 2      | 0.48%   |
| Integral            | 1         | 1      | 0.48%   |
| Indilinx            | 1         | 7      | 0.48%   |
| EMTEC               | 1         | 1      | 0.48%   |
| BORY                | 1         | 1      | 0.48%   |
| BIWIN               | 1         | 1      | 0.48%   |
| Apacer              | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 194       | 293    | 52.43%  |
| HDD  | 127       | 299    | 34.32%  |
| NVMe | 49        | 72     | 13.24%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 288       | 592    | 85.46%  |
| NVMe | 49        | 72     | 14.54%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 234       | 404    | 69.44%  |
| 0.51-1.0   | 61        | 99     | 18.1%   |
| 1.01-2.0   | 26        | 55     | 7.72%   |
| 4.01-10.0  | 6         | 11     | 1.78%   |
| 3.01-4.0   | 5         | 13     | 1.48%   |
| 2.01-3.0   | 5         | 10     | 1.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 121       | 33.15%  |
| 1-20           | 64        | 17.53%  |
| 251-500        | 54        | 14.79%  |
| 21-50          | 42        | 11.51%  |
| 501-1000       | 33        | 9.04%   |
| 51-100         | 31        | 8.49%   |
| 1001-2000      | 10        | 2.74%   |
| More than 3000 | 5         | 1.37%   |
| 2001-3000      | 4         | 1.1%    |
| Unknown        | 1         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 300       | 82.87%  |
| 21-50          | 27        | 7.46%   |
| 101-250        | 14        | 3.87%   |
| 251-500        | 8         | 2.21%   |
| 51-100         | 7         | 1.93%   |
| More than 3000 | 2         | 0.55%   |
| 501-1000       | 2         | 0.55%   |
| 1001-2000      | 1         | 0.28%   |
| Unknown        | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB          | 2         | 2      | 3.64%   |
| Seagate ST1000NM0011 1TB              | 2         | 3      | 3.64%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 2      | 3.64%   |
| Kingston SV300S37A120G 120GB          | 2         | 2      | 3.64%   |
| WDC WDS240G2G0A-00JH30 240GB          | 1         | 1      | 1.82%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 1.82%   |
| WDC WD5002ABYS-18B1B0 500GB           | 1         | 1      | 1.82%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 1.82%   |
| WDC WD2500BEVS-60UST0 250GB           | 1         | 1      | 1.82%   |
| WDC WD2002FYPS-02W3B0 2TB             | 1         | 1      | 1.82%   |
| WDC WD15EADS-00P8B0 1.5TB             | 1         | 1      | 1.82%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.82%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 1.82%   |
| WDC WD10EAVS-00D7B0 1TB               | 1         | 1      | 1.82%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 1.82%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 1.82%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 1.82%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 1.82%   |
| Toshiba MK1629GSGF 160GB              | 1         | 2      | 1.82%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.82%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 1.82%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.82%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1      | 1.82%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 2      | 1.82%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.82%   |
| Seagate ST380013AS 80GB               | 1         | 2      | 1.82%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 1.82%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 4      | 1.82%   |
| Seagate ST3160212AS 160GB             | 1         | 1      | 1.82%   |
| Seagate ST3160023AS 160GB             | 1         | 1      | 1.82%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 1.82%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.82%   |
| SanDisk SDSSDA240G 240GB              | 1         | 1      | 1.82%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 840 EVO 500GB | 1         | 2      | 1.82%   |
| Samsung Electronics HD322GJ 320GB     | 1         | 1      | 1.82%   |
| Samsung Electronics HD256GJ 250GB     | 1         | 1      | 1.82%   |
| Samsung Electronics HD103UJ 1TB       | 1         | 1      | 1.82%   |
| OCZ VERTEX-TURBO 32GB                 | 1         | 2      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 22     | 28.85%  |
| WDC                 | 14        | 17     | 26.92%  |
| Samsung Electronics | 4         | 7      | 7.69%   |
| Toshiba             | 3         | 4      | 5.77%   |
| Kingston            | 3         | 3      | 5.77%   |
| SanDisk             | 2         | 2      | 3.85%   |
| Hitachi             | 2         | 2      | 3.85%   |
| HGST                | 2         | 3      | 3.85%   |
| A-DATA Technology   | 2         | 2      | 3.85%   |
| OCZ                 | 1         | 2      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| Innodisk            | 1         | 1      | 1.92%   |
| Crucial             | 1         | 1      | 1.92%   |
| Corsair             | 1         | 2      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 22     | 39.47%  |
| WDC                 | 13        | 16     | 34.21%  |
| Toshiba             | 3         | 4      | 7.89%   |
| Samsung Electronics | 3         | 5      | 7.89%   |
| Hitachi             | 2         | 2      | 5.26%   |
| HGST                | 2         | 3      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 52     | 70.83%  |
| SSD  | 14        | 17     | 29.17%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 284       | 571    | 82.08%  |
| Malfunc  | 47        | 69     | 13.58%  |
| Detected | 15        | 24     | 4.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 268       | 63.51%  |
| AMD                           | 63        | 14.93%  |
| Samsung Electronics           | 18        | 4.27%   |
| Broadcom / LSI                | 14        | 3.32%   |
| Micron/Crucial Technology     | 12        | 2.84%   |
| ASMedia Technology            | 7         | 1.66%   |
| Silicon Motion                | 4         | 0.95%   |
| Micron Technology             | 4         | 0.95%   |
| Marvell Technology Group      | 4         | 0.95%   |
| Hewlett-Packard               | 4         | 0.95%   |
| SanDisk                       | 3         | 0.71%   |
| Phison Electronics            | 3         | 0.71%   |
| JMicron Technology            | 3         | 0.71%   |
| VIA Technologies              | 2         | 0.47%   |
| SK hynix                      | 2         | 0.47%   |
| Nvidia                        | 2         | 0.47%   |
| Kingston Technology Company   | 2         | 0.47%   |
| Chelsio Communications        | 2         | 0.47%   |
| Transcend                     | 1         | 0.24%   |
| Silicon Image                 | 1         | 0.24%   |
| Seagate Technology            | 1         | 0.24%   |
| KIOXIA                        | 1         | 0.24%   |
| Integrated Technology Express | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 40        | 8.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 19        | 3.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 16        | 3.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 15        | 3.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 2.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 2.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 2.31%   |
| Intel SATA Controller [RAID mode]                                                | 10        | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 2.1%    |
| AMD FCH SATA Controller [IDE mode]                                               | 10        | 2.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 9         | 1.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 1.68%   |
| Unknown                                                                          | 8         | 1.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 1.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.47%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 7         | 1.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.26%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 1.26%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 5         | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.05%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 5         | 1.05%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 5         | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5         | 1.05%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 4         | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 0.84%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 4         | 0.84%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 4         | 0.84%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 4         | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3         | 0.63%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.63%   |
| Intel SSD 660P Series                                                            | 3         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 279       | 65.19%  |
| NVMe | 54        | 12.62%  |
| IDE  | 48        | 11.21%  |
| RAID | 35        | 8.18%   |
| SAS  | 6         | 1.4%    |
| SCSI | 6         | 1.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 285       | 80.06%  |
| AMD     | 69        | 19.38%  |
| PowerPC | 1         | 0.28%   |
| ARM     | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| AMD GX-412TC SOC                     | 15        | 4.18%   |
| Intel Celeron J4125 CPU @ 2.00GHz    | 7         | 1.95%   |
| Intel Core i3-4010U CPU @ 1.70GHz    | 6         | 1.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz    | 5         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 5         | 1.39%   |
| Intel Celeron CPU J1900 @ 1.99GHz    | 5         | 1.39%   |
| Intel Celeron CPU J3455 @ 1.50GHz    | 4         | 1.11%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz  | 3         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 3         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 3         | 0.84%   |
| Intel Core i5-7500 CPU @ 3.40GHz     | 3         | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 3         | 0.84%   |
| Intel Core i5-4300Y CPU @ 1.60GHz    | 3         | 0.84%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 3         | 0.84%   |
| Intel Core i5-2500K CPU @ 3.30GHz    | 3         | 0.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 3         | 0.84%   |
| Intel Core i5 CPU M 560 @ 2.67GH     | 3         | 0.84%   |
| Intel Core i3-3225 CPU @ 3.30GHz     | 3         | 0.84%   |
| Intel Celeron CPU N3160 @ 1.60GHz    | 3         | 0.84%   |
| Intel Celeron CPU N3150 @ 1.60GHz    | 3         | 0.84%   |
| Intel Celeron CPU J3160 @ 1.60GHz    | 3         | 0.84%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz    | 3         | 0.84%   |
| AMD Ryzen 7 3700X 8-Core Processor   | 3         | 0.84%   |
| AMD Ryzen 5 2600 Six-Core Processor  | 3         | 0.84%   |
| AMD G-T40E Processor                 | 3         | 0.84%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz | 2         | 0.56%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz  | 2         | 0.56%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz  | 2         | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz     | 2         | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 2         | 0.56%   |
| Intel Core i7-4510U CPU @ 2.00GHz    | 2         | 0.56%   |
| Intel Core i5-9300H CPU @ 2.40GHz    | 2         | 0.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 0.56%   |
| Intel Core i5-6500T CPU @ 2.50GHz    | 2         | 0.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz     | 2         | 0.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz     | 2         | 0.56%   |
| Intel Core i5-5250U CPU @ 1.60GHz    | 2         | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 2         | 0.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz     | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 77        | 21.51%  |
| Intel Celeron           | 43        | 12.01%  |
| Intel Core i7           | 40        | 11.17%  |
| Intel Core i3           | 37        | 10.34%  |
| Intel Xeon              | 32        | 8.94%   |
| AMD GX                  | 19        | 5.31%   |
| Intel Atom              | 18        | 5.03%   |
| AMD Ryzen 7             | 11        | 3.07%   |
| Intel Core 2 Duo        | 10        | 2.79%   |
| AMD Ryzen 5             | 9         | 2.51%   |
| Other                   | 8         | 2.23%   |
| Intel Pentium           | 7         | 1.96%   |
| Intel Core 2 Quad       | 6         | 1.68%   |
| AMD EPYC                | 4         | 1.12%   |
| AMD Ryzen 7 PRO         | 3         | 0.84%   |
| AMD Opteron             | 3         | 0.84%   |
| AMD G                   | 3         | 0.84%   |
| Intel Xeon Silver       | 2         | 0.56%   |
| Intel Pentium Gold      | 2         | 0.56%   |
| Intel 686-class         | 2         | 0.56%   |
| AMD E1                  | 2         | 0.56%   |
| AMD Athlon 64 X2        | 2         | 0.56%   |
| AMD Athlon              | 2         | 0.56%   |
| AMD A8                  | 2         | 0.56%   |
| Intel Pentium Dual-Core | 1         | 0.28%   |
| Intel Pentium Dual      | 1         | 0.28%   |
| Intel Genuine           | 1         | 0.28%   |
| Intel Core M            | 1         | 0.28%   |
| Intel Core 2            | 1         | 0.28%   |
| ARM Cortex              | 1         | 0.28%   |
| AMD Ryzen 9             | 1         | 0.28%   |
| AMD Ryzen 3             | 1         | 0.28%   |
| AMD Phenom II X4        | 1         | 0.28%   |
| AMD FX                  | 1         | 0.28%   |
| AMD E                   | 1         | 0.28%   |
| AMD A6                  | 1         | 0.28%   |
| AMD A4                  | 1         | 0.28%   |
| AMD A10                 | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 151       | 42.3%   |
| 2       | 124       | 34.73%  |
| Unknown | 20        | 5.6%    |
| 8       | 17        | 4.76%   |
| 6       | 14        | 3.92%   |
| 16      | 12        | 3.36%   |
| 12      | 11        | 3.08%   |
| 1       | 3         | 0.84%   |
| 64      | 2         | 0.56%   |
| 32      | 1         | 0.28%   |
| 24      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 333       | 93.8%   |
| Unknown | 12        | 3.38%   |
| 2       | 8         | 2.25%   |
| 4       | 2         | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 180       | 50.56%  |
| 2       | 155       | 43.54%  |
| Unknown | 21        | 5.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 54        | 15.08%  |
| Haswell       | 37        | 10.34%  |
| IvyBridge     | 28        | 7.82%   |
| SandyBridge   | 26        | 7.26%   |
| Skylake       | 25        | 6.98%   |
| Silvermont    | 24        | 6.7%    |
| Puma          | 17        | 4.75%   |
| Penryn        | 16        | 4.47%   |
| Broadwell     | 13        | 3.63%   |
| Unknown       | 13        | 3.63%   |
| Westmere      | 11        | 3.07%   |
| Bonnell       | 10        | 2.79%   |
| Zen 2         | 9         | 2.51%   |
| Goldmont plus | 9         | 2.51%   |
| Goldmont      | 9         | 2.51%   |
| Zen+          | 7         | 1.96%   |
| Zen           | 7         | 1.96%   |
| Nehalem       | 7         | 1.96%   |
| Core          | 7         | 1.96%   |
| Jaguar        | 6         | 1.68%   |
| Bobcat        | 5         | 1.4%    |
| Zen 3         | 4         | 1.12%   |
| Piledriver    | 4         | 1.12%   |
| CometLake     | 3         | 0.84%   |
| Excavator     | 2         | 0.56%   |
| TigerLake     | 1         | 0.28%   |
| Steamroller   | 1         | 0.28%   |
| K8 Hammer     | 1         | 0.28%   |
| K10 Llano     | 1         | 0.28%   |
| K10           | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 209       | 61.29%  |
| AMD                        | 51        | 14.96%  |
| Nvidia                     | 48        | 14.08%  |
| Matrox Electronics Systems | 22        | 6.45%   |
| ASPEED Technology          | 11        | 3.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 4.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 4.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 4.06%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 12        | 3.48%   |
| Intel HD Graphics 530                                                                    | 11        | 3.19%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 3.19%   |
| Intel HD Graphics 620                                                                    | 10        | 2.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 2.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 2.61%   |
| Intel HD Graphics 5500                                                                   | 8         | 2.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.45%   |
| Intel HD Graphics 630                                                                    | 5         | 1.45%   |
| Intel HD Graphics 500                                                                    | 5         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.45%   |
| AMD ES1000                                                                               | 5         | 1.45%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.16%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.16%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.16%   |
| Intel HD Graphics 510                                                                    | 4         | 1.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 3         | 0.87%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 3         | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.87%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 0.87%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 0.87%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.87%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 3         | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.87%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 3         | 0.87%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.87%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 182       | 50.84%  |
| 1 x AMD                  | 46        | 12.85%  |
| Other                    | 35        | 9.78%   |
| 1 x Nvidia               | 33        | 9.22%   |
| 1 x Matrox               | 22        | 6.15%   |
| 2 x Intel                | 12        | 3.35%   |
| Intel + Nvidia           | 12        | 3.35%   |
| 1 x ASPEED               | 10        | 2.79%   |
| Intel + AMD              | 2         | 0.56%   |
| 2 x AMD                  | 1         | 0.28%   |
| Nvidia + ASPEED          | 1         | 0.28%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.28%   |
| AMD + Nvidia             | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 291       | 81.28%  |
| Unknown     | 43        | 12.01%  |
| Proprietary | 24        | 6.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 316       | 88.52%  |
| 0.51-1.0   | 12        | 3.36%   |
| 1.01-2.0   | 7         | 1.96%   |
| 0.01-0.5   | 7         | 1.96%   |
| 7.01-8.0   | 6         | 1.68%   |
| 5.01-6.0   | 5         | 1.4%    |
| 3.01-4.0   | 2         | 0.56%   |
| 8.01-16.0  | 2         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 13.04%  |
| LG Display              | 14        | 10.14%  |
| Chimei Innolux          | 14        | 10.14%  |
| Dell                    | 12        | 8.7%    |
| Samsung Electronics     | 10        | 7.25%   |
| BOE                     | 8         | 5.8%    |
| Iiyama                  | 7         | 5.07%   |
| Hewlett-Packard         | 5         | 3.62%   |
| Apple                   | 5         | 3.62%   |
| Philips                 | 4         | 2.9%    |
| Idek Iiyama             | 4         | 2.9%    |
| Goldstar                | 4         | 2.9%    |
| Chi Mei Optoelectronics | 4         | 2.9%    |
| Acer                    | 4         | 2.9%    |
| BenQ                    | 3         | 2.17%   |
| AOC                     | 3         | 2.17%   |
| Ancor Communications    | 3         | 2.17%   |
| LGD                     | 2         | 1.45%   |
| Lenovo                  | 2         | 1.45%   |
| ViewSonic               | 1         | 0.72%   |
| Sony                    | 1         | 0.72%   |
| Sharp                   | 1         | 0.72%   |
| PRI                     | 1         | 0.72%   |
| Packard Bell            | 1         | 0.72%   |
| Nvidia                  | 1         | 0.72%   |
| LG Electronics          | 1         | 0.72%   |
| IBM                     | 1         | 0.72%   |
| CSO                     | 1         | 0.72%   |
| CPT                     | 1         | 0.72%   |
| CKL                     | 1         | 0.72%   |
| ASUSTek Computer        | 1         | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 2.17%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 1.45%   |
| LGD LCD Monitor 1600x900                                                 | 2         | 1.45%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 2         | 1.45%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                               | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.45%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 1.45%   |
| BenQ EW3270U BNQ7950 3840x2160 700x390mm 31.5-inch                       | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 1.45%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                        | 2         | 1.45%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                        | 2         | 1.45%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 0.72%   |
| Sony TV  *00 SNYF903 3840x2160 950x540mm 43.0-inch                       | 1         | 0.72%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SyncMaster 3520x1200                     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                        | 1         | 0.72%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.72%   |
| PRI LED-MONITOR PRI0828 3840x2160 1150x650mm 52.0-inch                   | 1         | 0.72%   |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 0.72%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch                | 1         | 0.72%   |
| Packard Bell Viseo 200Ws PKB00C2 1600x900 440x250mm 19.9-inch            | 1         | 0.72%   |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 0.72%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                        | 1         | 0.72%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.72%   |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 0.72%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch              | 1         | 0.72%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 0.72%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 59        | 44.03%  |
| 1366x768 (WXGA)    | 26        | 19.4%   |
| 3840x2160 (4K)     | 8         | 5.97%   |
| 2560x1440 (QHD)    | 7         | 5.22%   |
| 1600x900 (HD+)     | 7         | 5.22%   |
| 1280x1024 (SXGA)   | 7         | 5.22%   |
| 1280x800 (WXGA)    | 5         | 3.73%   |
| 1440x900 (WXGA+)   | 4         | 2.99%   |
| 1680x1050 (WSXGA+) | 3         | 2.24%   |
| 1024x600           | 2         | 1.49%   |
| 3520x1200          | 1         | 0.75%   |
| 2880x1800          | 1         | 0.75%   |
| 2560x1080          | 1         | 0.75%   |
| 1920x1200 (WUXGA)  | 1         | 0.75%   |
| 1440x960           | 1         | 0.75%   |
| Unknown            | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 19.71%  |
| 13      | 24        | 17.52%  |
| 12      | 12        | 8.76%   |
| 24      | 10        | 7.3%    |
| Unknown | 10        | 7.3%    |
| 27      | 8         | 5.84%   |
| 23      | 8         | 5.84%   |
| 21      | 8         | 5.84%   |
| 19      | 8         | 5.84%   |
| 17      | 8         | 5.84%   |
| 10      | 3         | 2.19%   |
| 52      | 2         | 1.46%   |
| 31      | 2         | 1.46%   |
| 14      | 2         | 1.46%   |
| 43      | 1         | 0.73%   |
| 42      | 1         | 0.73%   |
| 22      | 1         | 0.73%   |
| 18      | 1         | 0.73%   |
| 11      | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 35.77%  |
| 501-600     | 25        | 18.25%  |
| 201-300     | 23        | 16.79%  |
| 401-500     | 14        | 10.22%  |
| Unknown     | 10        | 7.3%    |
| 351-400     | 9         | 6.57%   |
| 601-700     | 3         | 2.19%   |
| 1001-1500   | 2         | 1.46%   |
| 901-1000    | 2         | 1.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 96        | 76.19%  |
| 16/10   | 11        | 8.73%   |
| Unknown | 10        | 7.94%   |
| 5/4     | 7         | 5.56%   |
| 3/2     | 2         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 25        | 18.25%  |
| 91-100         | 23        | 16.79%  |
| 201-250        | 22        | 16.06%  |
| 61-70          | 12        | 8.76%   |
| 151-200        | 11        | 8.03%   |
| Unknown        | 10        | 7.3%    |
| 301-350        | 8         | 5.84%   |
| 121-130        | 5         | 3.65%   |
| 141-150        | 4         | 2.92%   |
| 101-110        | 4         | 2.92%   |
| 41-50          | 3         | 2.19%   |
| More than 1000 | 2         | 1.46%   |
| 351-500        | 2         | 1.46%   |
| 251-300        | 2         | 1.46%   |
| 501-1000       | 2         | 1.46%   |
| 71-80          | 1         | 0.73%   |
| 51-60          | 1         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 43        | 31.85%  |
| 101-120       | 39        | 28.89%  |
| 51-100        | 34        | 25.19%  |
| Unknown       | 10        | 7.41%   |
| 161-240       | 5         | 3.7%    |
| More than 240 | 3         | 2.22%   |
| 1-50          | 1         | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 231       | 63.64%  |
| 1     | 120       | 33.06%  |
| 2     | 12        | 3.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 247       | 48.15%  |
| Realtek Semiconductor           | 132       | 25.73%  |
| Broadcom                        | 44        | 8.58%   |
| Qualcomm Atheros                | 40        | 7.8%    |
| AMD                             | 5         | 0.97%   |
| TP-Link                         | 4         | 0.78%   |
| Ralink Technology               | 3         | 0.58%   |
| Qualcomm                        | 3         | 0.58%   |
| Marvell Technology Group        | 3         | 0.58%   |
| Huawei Technologies             | 3         | 0.58%   |
| Edimax Technology               | 3         | 0.58%   |
| Apple                           | 3         | 0.58%   |
| VIA Technologies                | 2         | 0.39%   |
| QLogic                          | 2         | 0.39%   |
| IMC Networks                    | 2         | 0.39%   |
| D-Link System                   | 2         | 0.39%   |
| Chelsio Communications          | 2         | 0.39%   |
| Xiaomi                          | 1         | 0.19%   |
| Silicom                         | 1         | 0.19%   |
| Sierra Wireless                 | 1         | 0.19%   |
| Samsung Electronics             | 1         | 0.19%   |
| Sagem                           | 1         | 0.19%   |
| Ralink                          | 1         | 0.19%   |
| Qualcomm Atheros Communications | 1         | 0.19%   |
| Nvidia                          | 1         | 0.19%   |
| Microchip Technology            | 1         | 0.19%   |
| MediaTek                        | 1         | 0.19%   |
| Dell                            | 1         | 0.19%   |
| American Megatrends             | 1         | 0.19%   |
| 3Com                            | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 114       | 17.62%  |
| Intel I211 Gigabit Network Connection                                         | 45        | 6.96%   |
| Intel I210 Gigabit Network Connection                                         | 24        | 3.71%   |
| Intel 82574L Gigabit Network Connection                                       | 22        | 3.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 16        | 2.47%   |
| Intel Wi-Fi 6 AX200                                                           | 12        | 1.85%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 1.7%    |
| Intel Wireless 7265                                                           | 10        | 1.55%   |
| Intel Wireless 8265 / 8275                                                    | 9         | 1.39%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8         | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 8         | 1.24%   |
| Intel Wireless 7260                                                           | 8         | 1.24%   |
| Intel Ethernet Controller I225-V                                              | 8         | 1.24%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.24%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 8         | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 1.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 1.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 6         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 6         | 0.93%   |
| Intel Wireless 3165                                                           | 6         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 6         | 0.93%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 0.93%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 0.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 0.77%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                         | 5         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 0.77%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 0.77%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.62%   |
| Intel Wireless-AC 9260                                                        | 4         | 0.62%   |
| Intel Wireless 8260                                                           | 4         | 0.62%   |
| Intel Ethernet Connection X553 1GbE                                           | 4         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                          | 4         | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 0.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 55.06%  |
| Qualcomm Atheros                | 35        | 19.66%  |
| Realtek Semiconductor           | 17        | 9.55%   |
| Broadcom                        | 11        | 6.18%   |
| TP-Link                         | 4         | 2.25%   |
| Ralink Technology               | 3         | 1.69%   |
| Edimax Technology               | 3         | 1.69%   |
| IMC Networks                    | 2         | 1.12%   |
| Sagem                           | 1         | 0.56%   |
| Ralink                          | 1         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.56%   |
| MediaTek                        | 1         | 0.56%   |
| Dell                            | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12        | 6.67%   |
| Intel Wireless 7265                                            | 10        | 5.56%   |
| Intel Wireless 8265 / 8275                                     | 9         | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 4.44%   |
| Intel Wireless 7260                                            | 8         | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 3.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 3.33%   |
| Intel Wireless 3165                                            | 6         | 3.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.22%   |
| Intel Wireless-AC 9260                                         | 4         | 2.22%   |
| Intel Wireless 8260                                            | 4         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 1.67%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3         | 1.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 1.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.11%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 1.11%   |
| Intel WiFi Link 5100                                           | 2         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.11%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 2         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.11%   |
| TP-Link TP-Link Wireless MU-MIMO USB Adapter                   | 1         | 0.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 0.56%   |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 206       | 51.5%   |
| Realtek Semiconductor    | 124       | 31%     |
| Broadcom                 | 35        | 8.75%   |
| Qualcomm Atheros         | 8         | 2%      |
| AMD                      | 5         | 1.25%   |
| Qualcomm                 | 3         | 0.75%   |
| Marvell Technology Group | 3         | 0.75%   |
| VIA Technologies         | 2         | 0.5%    |
| QLogic                   | 2         | 0.5%    |
| D-Link System            | 2         | 0.5%    |
| Chelsio Communications   | 2         | 0.5%    |
| Apple                    | 2         | 0.5%    |
| Xiaomi                   | 1         | 0.25%   |
| Silicom                  | 1         | 0.25%   |
| Samsung Electronics      | 1         | 0.25%   |
| Nvidia                   | 1         | 0.25%   |
| American Megatrends      | 1         | 0.25%   |
| 3Com                     | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 114       | 24.84%  |
| Intel I211 Gigabit Network Connection                                         | 45        | 9.8%    |
| Intel I210 Gigabit Network Connection                                         | 24        | 5.23%   |
| Intel 82574L Gigabit Network Connection                                       | 22        | 4.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 16        | 3.49%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 2.4%    |
| Intel Ethernet Connection I217-LM                                             | 9         | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8         | 1.74%   |
| Intel Ethernet Controller I225-V                                              | 8         | 1.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.74%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 8         | 1.74%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 1.53%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 1.31%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.31%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.09%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                         | 5         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 1.09%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 1.09%   |
| Intel Ethernet Connection X553 1GbE                                           | 4         | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                          | 4         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 0.87%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4         | 0.87%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 4         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3         | 0.65%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 3         | 0.65%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.65%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 0.65%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 3         | 0.65%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 3         | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.44%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 2         | 0.44%   |
| Intel Ethernet Controller X550                                                | 2         | 0.44%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 341       | 66.6%   |
| WiFi     | 163       | 31.84%  |
| Unknown  | 5         | 0.98%   |
| Modem    | 3         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 303       | 79.53%  |
| WiFi     | 78        | 20.47%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 141       | 39.39%  |
| 1     | 64        | 17.88%  |
| 4     | 58        | 16.2%   |
| 3     | 44        | 12.29%  |
| 5     | 15        | 4.19%   |
| 6     | 14        | 3.91%   |
| 8     | 7         | 1.96%   |
| 7     | 5         | 1.4%    |
| 0     | 3         | 0.84%   |
| 12    | 2         | 0.56%   |
| 14    | 1         | 0.28%   |
| 13    | 1         | 0.28%   |
| 11    | 1         | 0.28%   |
| 10    | 1         | 0.28%   |
| 9     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 297       | 79.41%  |
| Yes  | 77        | 20.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 68.69%  |
| Broadcom                        | 8         | 8.08%   |
| IMC Networks                    | 6         | 6.06%   |
| Apple                           | 4         | 4.04%   |
| Cambridge Silicon Radio         | 3         | 3.03%   |
| Foxconn / Hon Hai               | 2         | 2.02%   |
| Dell                            | 2         | 2.02%   |
| Realtek Semiconductor           | 1         | 1.01%   |
| Qualcomm Atheros Communications | 1         | 1.01%   |
| HTC (High Tech Computer)        | 1         | 1.01%   |
| Hewlett-Packard                 | 1         | 1.01%   |
| Creative Technology             | 1         | 1.01%   |
| ASUSTek Computer                | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 26        | 26.26%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 13        | 13.13%  |
| Intel AX200 Bluetooth                                                | 10        | 10.1%   |
| Intel AX201 Bluetooth                                                | 6         | 6.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5         | 5.05%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                          | 4         | 4.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 3         | 3.03%   |
| Apple Bluetooth Host Controller                                      | 3         | 3.03%   |
| Intel AX210 Bluetooth                                                | 2         | 2.02%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 2         | 2.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 2.02%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 2         | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1         | 1.01%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 1         | 1.01%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 1.01%   |
| IMC Networks Bluetooth Radio                                         | 1         | 1.01%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 1         | 1.01%   |
| Dell DW375 Bluetooth Module                                          | 1         | 1.01%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 1.01%   |
| Creative Creative Bluetooth Audio W2                                 | 1         | 1.01%   |
| Broadcom BCM43142A0 Bluetooth Module                                 | 1         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 1.01%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1         | 1.01%   |
| Apple Built-in iSight (no firmware loaded)                           | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 209       | 65.31%  |
| AMD                                          | 54        | 16.88%  |
| Nvidia                                       | 33        | 10.31%  |
| GN Netcom                                    | 3         | 0.94%   |
| C-Media Electronics                          | 3         | 0.94%   |
| Texas Instruments                            | 2         | 0.63%   |
| Lenovo                                       | 2         | 0.63%   |
| Focusrite-Novation                           | 2         | 0.63%   |
| Creative Labs                                | 2         | 0.63%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.31%   |
| VIA Technologies                             | 1         | 0.31%   |
| Sony                                         | 1         | 0.31%   |
| Micronas                                     | 1         | 0.31%   |
| Logitech                                     | 1         | 0.31%   |
| Kingston Technology                          | 1         | 0.31%   |
| iCreate Technologies                         | 1         | 0.31%   |
| Giga-Byte Technology                         | 1         | 0.31%   |
| ESS Technology                               | 1         | 0.31%   |
| DSEA A/S                                     | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 4.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 4.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 4.92%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 4.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 3.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 3.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.85%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.85%   |
| AMD FCH Azalia Controller                                                                         | 11        | 2.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 9         | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9         | 2.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 2.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.81%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.55%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.04%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.78%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.52%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 68        | 20.06%  |
| SK hynix            | 50        | 14.75%  |
| Unknown             | 39        | 11.5%   |
| Kingston            | 35        | 10.32%  |
| Crucial             | 31        | 9.14%   |
| Corsair             | 27        | 7.96%   |
| Micron Technology   | 22        | 6.49%   |
| G.Skill             | 18        | 5.31%   |
| Transcend           | 8         | 2.36%   |
| Unknown (ABCD)      | 6         | 1.77%   |
| Nanya Technology    | 6         | 1.77%   |
| Unknown             | 5         | 1.47%   |
| Elpida              | 4         | 1.18%   |
| A-DATA Technology   | 3         | 0.88%   |
| Patriot             | 2         | 0.59%   |
| Kimtigo             | 2         | 0.59%   |
| Atermiter           | 2         | 0.59%   |
| Apacer              | 2         | 0.59%   |
| V-Color             | 1         | 0.29%   |
| Unknown (0B38)      | 1         | 0.29%   |
| Teikon              | 1         | 0.29%   |
| SHARETRONIC         | 1         | 0.29%   |
| OCZ                 | 1         | 0.29%   |
| Hewlett-Packard     | 1         | 0.29%   |
| Goldenmars          | 1         | 0.29%   |
| CSX                 | 1         | 0.29%   |
| Avant               | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 7         | 1.95%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 6         | 1.67%   |
| Unknown                                                      | 5         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 1.11%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 4         | 1.11%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 4         | 1.11%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 3         | 0.84%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 0.84%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 3         | 0.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 3         | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.84%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.84%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 0.84%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s         | 3         | 0.84%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 1600MT/s          | 3         | 0.84%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                   | 3         | 0.84%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 2         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 2         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 2         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 2         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.56%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 2         | 0.56%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s          | 2         | 0.56%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 2         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 0.56%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.56%   |
| Samsung RAM M393B4G70DM0-YH9 32767MB DIMM DDR3 1333MT/s      | 2         | 0.56%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 2         | 0.56%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s           | 2         | 0.56%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s          | 2         | 0.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 2         | 0.56%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2         | 0.56%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 2         | 0.56%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s         | 2         | 0.56%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 152       | 50.84%  |
| DDR4    | 109       | 36.45%  |
| DDR2    | 15        | 5.02%   |
| Unknown | 12        | 4.01%   |
| LPDDR4  | 6         | 2.01%   |
| LPDDR3  | 5         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 154       | 51.51%  |
| SODIMM       | 140       | 46.82%  |
| Unknown      | 2         | 0.67%   |
| Row Of Chips | 1         | 0.33%   |
| FB-DIMM      | 1         | 0.33%   |
| Chip         | 1         | 0.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 109       | 34.28%  |
| 8192  | 108       | 33.96%  |
| 16384 | 41        | 12.89%  |
| 2048  | 40        | 12.58%  |
| 1024  | 10        | 3.14%   |
| 32768 | 8         | 2.52%   |
| 32767 | 2         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 91        | 29.35%  |
| 1333    | 51        | 16.45%  |
| 2400    | 35        | 11.29%  |
| 2667    | 32        | 10.32%  |
| 3200    | 27        | 8.71%   |
| 2133    | 18        | 5.81%   |
| 800     | 12        | 3.87%   |
| 1334    | 10        | 3.23%   |
| 667     | 8         | 2.58%   |
| 2666    | 4         | 1.29%   |
| 1867    | 4         | 1.29%   |
| 1066    | 4         | 1.29%   |
| 1067    | 2         | 0.65%   |
| 533     | 2         | 0.65%   |
| Unknown | 2         | 0.65%   |
| 5200    | 1         | 0.32%   |
| 3000    | 1         | 0.32%   |
| 1866    | 1         | 0.32%   |
| 1400    | 1         | 0.32%   |
| 1332    | 1         | 0.32%   |
| 1200    | 1         | 0.32%   |
| 975     | 1         | 0.32%   |
| 400     | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Dymo-CoStar | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson Printer                  | 1         | 50%     |
| Dymo-CoStar DYMO LabelWriter 450 DUO | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 29.49%  |
| Sunplus Innovation Technology          | 9         | 11.54%  |
| Acer                                   | 7         | 8.97%   |
| Realtek Semiconductor                  | 6         | 7.69%   |
| Microdia                               | 6         | 7.69%   |
| IMC Networks                           | 5         | 6.41%   |
| Logitech                               | 3         | 3.85%   |
| Lite-On Technology                     | 3         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.85%   |
| Syntek                                 | 2         | 2.56%   |
| Suyin                                  | 2         | 2.56%   |
| ARC International                      | 2         | 2.56%   |
| Alcor Micro                            | 2         | 2.56%   |
| Sonix Technology                       | 1         | 1.28%   |
| Quanta                                 | 1         | 1.28%   |
| Novatek Microelectronics               | 1         | 1.28%   |
| Linux Foundation                       | 1         | 1.28%   |
| Apple                                  | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 9         | 11.39%  |
| Sunplus Integrated_Webcam_HD                        | 5         | 6.33%   |
| Acer Integrated Camera                              | 4         | 5.06%   |
| Microdia Integrated Webcam                          | 3         | 3.8%    |
| Realtek USB Camera                                  | 2         | 2.53%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.53%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.53%   |
| Logitech Webcam C270                                | 2         | 2.53%   |
| Lite-On Integrated Camera                           | 2         | 2.53%   |
| IMC Networks EasyCamera                             | 2         | 2.53%   |
| Chicony HD WebCam                                   | 2         | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 2.53%   |
| ARC International Camera                            | 2         | 2.53%   |
| Acer SunplusIT Integrated Camera                    | 2         | 2.53%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.27%   |
| Syntek Integrated Camera                            | 1         | 1.27%   |
| Suyin USB 2.0 Camera                                | 1         | 1.27%   |
| Suyin Laptop_Integrated_Webcam_FHD                  | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.27%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.27%   |
| Sunplus Asus Webcam                                 | 1         | 1.27%   |
| Sonix USB 2.0 Camera                                | 1         | 1.27%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.27%   |
| Realtek Integrated Webcam HD                        | 1         | 1.27%   |
| Quanta HD WebCam                                    | 1         | 1.27%   |
| Novatek HP High Definition 2MP Webcam               | 1         | 1.27%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.27%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 1.27%   |
| Lite-On Realtek DMFT - RGB                          | 1         | 1.27%   |
| Linux Foundation HD Camera                          | 1         | 1.27%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.27%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.27%   |
| IMC Networks Integrated Camera                      | 1         | 1.27%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.27%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.27%   |
| Chicony ThinkPad T490 Webcam                        | 1         | 1.27%   |
| Chicony Sonix ST50220 USB Video Camera              | 1         | 1.27%   |
| Chicony Ltd., USB2.0 HD UVC WebCam                  | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 33.33%  |
| Synaptics                  | 4         | 19.05%  |
| AuthenTec                  | 4         | 19.05%  |
| Upek                       | 2         | 9.52%   |
| Shenzhen Goodix Technology | 2         | 9.52%   |
| Elan Microelectronics      | 1         | 4.76%   |
| Broadcom                   | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 9.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 9.52%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 9.52%   |
| AuthenTec AES2810                                                            | 2         | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 4.76%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 4.76%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 4.76%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 4.76%   |

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
| 1     | 150       | 40.11%  |
| 0     | 109       | 29.14%  |
| 2     | 61        | 16.31%  |
| 3     | 33        | 8.82%   |
| 4     | 15        | 4.01%   |
| 6     | 4         | 1.07%   |
| 7     | 1         | 0.27%   |
| 5     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 210       | 52.63%  |
| Net/wireless             | 46        | 11.53%  |
| Bluetooth                | 46        | 11.53%  |
| Card reader              | 30        | 7.52%   |
| Firewire controller      | 22        | 5.51%   |
| Fingerprint reader       | 14        | 3.51%   |
| Sound                    | 7         | 1.75%   |
| Net/ethernet             | 7         | 1.75%   |
| Graphics card            | 6         | 1.5%    |
| Storage                  | 4         | 1%      |
| Storage/raid             | 3         | 0.75%   |
| Network                  | 3         | 0.75%   |
| Modem                    | 1         | 0.25%   |

