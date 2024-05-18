helloSystem 0.6.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.6.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.6.0/Notebook/README.md).

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

Total: 171

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Toshiba       | Satellite C55-A             | Notebook    | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| HP            | 3048h                       | Desktop     | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | Notebook    | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [c4d10a26fd](https://bsd-hardware.info/?probe=c4d10a26fd) | Mar 04, 2022 |
| Intel         | H81                         | Desktop     | [dd19abd47d](https://bsd-hardware.info/?probe=dd19abd47d) | Feb 25, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Sony          | VPCEB1J1E                   | Notebook    | [04c5ee02da](https://bsd-hardware.info/?probe=04c5ee02da) | Feb 05, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [e0e63e69ef](https://bsd-hardware.info/?probe=e0e63e69ef) | Jan 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [460ea5c41d](https://bsd-hardware.info/?probe=460ea5c41d) | Jan 23, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Sony          | VPCYB45JB                   | Notebook    | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [f1fe3fe225](https://bsd-hardware.info/?probe=f1fe3fe225) | Dec 30, 2021 |
| Acer          | Aspire E1-421               | Notebook    | [b2aea3de1b](https://bsd-hardware.info/?probe=b2aea3de1b) | Dec 21, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T440p 20AW007QM... | Notebook    | [9efeb9ee24](https://bsd-hardware.info/?probe=9efeb9ee24) | Dec 16, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [d8bcea438a](https://bsd-hardware.info/?probe=d8bcea438a) | Dec 15, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [34ba809dc2](https://bsd-hardware.info/?probe=34ba809dc2) | Dec 14, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [45f61ab19e](https://bsd-hardware.info/?probe=45f61ab19e) | Dec 14, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [e77489ad74](https://bsd-hardware.info/?probe=e77489ad74) | Dec 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Dell          | Inspiron 3195               | Convertible | [8bbd2c16f7](https://bsd-hardware.info/?probe=8bbd2c16f7) | Dec 11, 2021 |
| HP            | 8054                        | Desktop     | [de953100f6](https://bsd-hardware.info/?probe=de953100f6) | Dec 10, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [a064edad4b](https://bsd-hardware.info/?probe=a064edad4b) | Dec 10, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [a9423b3232](https://bsd-hardware.info/?probe=a9423b3232) | Dec 09, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Philco        | 10B                         | Notebook    | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | Notebook    | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [35b01f0f56](https://bsd-hardware.info/?probe=35b01f0f56) | Dec 05, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [9febab6c01](https://bsd-hardware.info/?probe=9febab6c01) | Dec 05, 2021 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | Notebook    | [e4b923d500](https://bsd-hardware.info/?probe=e4b923d500) | Dec 02, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [0680188ca4](https://bsd-hardware.info/?probe=0680188ca4) | Dec 01, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| Dell          | Inspiron 3195               | Convertible | [5680c947ae](https://bsd-hardware.info/?probe=5680c947ae) | Nov 26, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [ef35dd084e](https://bsd-hardware.info/?probe=ef35dd084e) | Nov 26, 2021 |
| Dell          | Inspiron 3195               | Convertible | [909ab22d27](https://bsd-hardware.info/?probe=909ab22d27) | Nov 25, 2021 |
| HP            | 0A80h                       | Desktop     | [1e1153ee69](https://bsd-hardware.info/?probe=1e1153ee69) | Nov 22, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8fe8caf37d](https://bsd-hardware.info/?probe=8fe8caf37d) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [afd0cf45c6](https://bsd-hardware.info/?probe=afd0cf45c6) | Nov 21, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [a1ece36be8](https://bsd-hardware.info/?probe=a1ece36be8) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [748312bfbf](https://bsd-hardware.info/?probe=748312bfbf) | Nov 07, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | Desktop     | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Shuttle       | FH61R                       | Desktop     | [a231590743](https://bsd-hardware.info/?probe=a231590743) | Nov 07, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7e27b1bc46](https://bsd-hardware.info/?probe=7e27b1bc46) | Nov 07, 2021 |
| Intel         | H81                         | Desktop     | [7f07aecffc](https://bsd-hardware.info/?probe=7f07aecffc) | Nov 07, 2021 |
| HP            | 14                          | Notebook    | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | Notebook    | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | Notebook    | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [b9ad64f354](https://bsd-hardware.info/?probe=b9ad64f354) | Nov 04, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [45576fddfa](https://bsd-hardware.info/?probe=45576fddfa) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z360                | Notebook    | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| Dell          | 0M5DCD A02                  | Desktop     | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430u 3352AA5      | Notebook    | [8619bcca35](https://bsd-hardware.info/?probe=8619bcca35) | Nov 01, 2021 |
| Gateway       | DX4840                      | Desktop     | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Apple         | MacBookAir5,1               | Notebook    | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| HP            | Presario CQ43               | Notebook    | [b97d9ff563](https://bsd-hardware.info/?probe=b97d9ff563) | Oct 30, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [e25f042400](https://bsd-hardware.info/?probe=e25f042400) | Oct 30, 2021 |
| Unknown       | Intel X79                   | Desktop     | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Chuwi         | MiniBook                    | Notebook    | [4ce05f93a8](https://bsd-hardware.info/?probe=4ce05f93a8) | Oct 28, 2021 |
| Dell          | Precision M4600             | Notebook    | [2f848fd2c0](https://bsd-hardware.info/?probe=2f848fd2c0) | Oct 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Acer          | RS880M05                    | Desktop     | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Apple         | MacBookPro4,1               | Notebook    | [10861818b2](https://bsd-hardware.info/?probe=10861818b2) | Oct 20, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3cf20ca77c](https://bsd-hardware.info/?probe=3cf20ca77c) | Oct 19, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [9b4defb194](https://bsd-hardware.info/?probe=9b4defb194) | Oct 19, 2021 |
| HP            | Unknown                     | Notebook    | [ad95186d17](https://bsd-hardware.info/?probe=ad95186d17) | Oct 19, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| HP            | 3398                        | Desktop     | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0cdd3497f6](https://bsd-hardware.info/?probe=0cdd3497f6) | Oct 18, 2021 |
| HP            | 15                          | Notebook    | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [951eb91342](https://bsd-hardware.info/?probe=951eb91342) | Oct 17, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [48169f1d3c](https://bsd-hardware.info/?probe=48169f1d3c) | Oct 16, 2021 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [f2f7fc6463](https://bsd-hardware.info/?probe=f2f7fc6463) | Oct 15, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | Notebook    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek       | U33Jc                       | Notebook    | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| MSI           | MS-16F1                     | Notebook    | [72b9db306a](https://bsd-hardware.info/?probe=72b9db306a) | Oct 09, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [e24f67a603](https://bsd-hardware.info/?probe=e24f67a603) | Oct 08, 2021 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| MSI           | G41M-P25                    | Desktop     | [21eec496b4](https://bsd-hardware.info/?probe=21eec496b4) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | Notebook    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Acer          | Aspire 5741                 | Notebook    | [fd4e40a8d9](https://bsd-hardware.info/?probe=fd4e40a8d9) | Oct 07, 2021 |
| Intel         | H61                         | Desktop     | [6ce71c1b9e](https://bsd-hardware.info/?probe=6ce71c1b9e) | Oct 06, 2021 |
| Lenovo        | ThinkPad R500 2718W92       | Notebook    | [384f10861a](https://bsd-hardware.info/?probe=384f10861a) | Oct 05, 2021 |
| ASUSTek       | UX21A                       | Notebook    | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| HP            | 3397                        | Desktop     | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| HP            | 81BA                        | All in one  | [c2204a3dd2](https://bsd-hardware.info/?probe=c2204a3dd2) | Oct 04, 2021 |
| ASRock        | B365M-ITX/ac                | Desktop     | [1c8820a6d0](https://bsd-hardware.info/?probe=1c8820a6d0) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Dell          | Latitude E4300              | Notebook    | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Toshiba       | dynabook RX3 SM240E/3HD     | Notebook    | [2fe863dff4](https://bsd-hardware.info/?probe=2fe863dff4) | Oct 01, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [445fe665b8](https://bsd-hardware.info/?probe=445fe665b8) | Oct 01, 2021 |
| HP            | Pavilion dm4                | Notebook    | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9b14548c15](https://bsd-hardware.info/?probe=9b14548c15) | Sep 21, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [9d2959b4f1](https://bsd-hardware.info/?probe=9d2959b4f1) | Sep 20, 2021 |
| HP            | 81B4 01                     | Desktop     | [179504116d](https://bsd-hardware.info/?probe=179504116d) | Sep 20, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [790d020ebe](https://bsd-hardware.info/?probe=790d020ebe) | Sep 19, 2021 |
| Lenovo        | G500s 20245                 | Notebook    | [88cd1ca7bd](https://bsd-hardware.info/?probe=88cd1ca7bd) | Sep 18, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| HP            | 3397                        | Desktop     | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Kraftway      | KW10T                       | Notebook    | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| Dell          | Latitude 3540               | Notebook    | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | Notebook    | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [33ba0b7c38](https://bsd-hardware.info/?probe=33ba0b7c38) | Aug 29, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [5aaacec4ad](https://bsd-hardware.info/?probe=5aaacec4ad) | Aug 23, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [d74035a8e7](https://bsd-hardware.info/?probe=d74035a8e7) | Aug 23, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [5fe1a9e521](https://bsd-hardware.info/?probe=5fe1a9e521) | Aug 16, 2021 |
| ASUSTek       | Q505UAR                     | Convertible | [b745dee7d6](https://bsd-hardware.info/?probe=b745dee7d6) | Aug 14, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | Notebook    | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [ef8217ac30](https://bsd-hardware.info/?probe=ef8217ac30) | Aug 01, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [1c3ec31075](https://bsd-hardware.info/?probe=1c3ec31075) | Jul 28, 2021 |
| Lenovo        | ThinkPad SL 2746M3C         | Notebook    | [aa10433581](https://bsd-hardware.info/?probe=aa10433581) | Jul 28, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | Notebook    | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [2c390b4301](https://bsd-hardware.info/?probe=2c390b4301) | Jul 09, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [aea3a11daf](https://bsd-hardware.info/?probe=aea3a11daf) | Jul 08, 2021 |
| eMachines     | eM350                       | Notebook    | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [1a35d2f6ab](https://bsd-hardware.info/?probe=1a35d2f6ab) | Jun 26, 2021 |
| eMachines     | eM350                       | Notebook    | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | Notebook    | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [bb13e61de1](https://bsd-hardware.info/?probe=bb13e61de1) | Jun 21, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [0e448af5f5](https://bsd-hardware.info/?probe=0e448af5f5) | Jun 18, 2021 |
| Dell          | Latitude 7280               | Notebook    | [8fd335f46f](https://bsd-hardware.info/?probe=8fd335f46f) | Jun 18, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [b0b67667d3](https://bsd-hardware.info/?probe=b0b67667d3) | Jun 16, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 139       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 137       | 97.86%  |
| XFCE         | 1         | 0.71%   |
| KDE5         | 1         | 0.71%   |
| GNOME        | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 139       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 139       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 135       | 97.12%  |
| de_DE   | 2         | 1.44%   |
| ru_RU   | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 113       | 80.71%  |
| BIOS | 27        | 19.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 139       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 139       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 20.14%  |
| ASUSTek Computer    | 20        | 14.39%  |
| Hewlett-Packard     | 17        | 12.23%  |
| Dell                | 15        | 10.79%  |
| ASRock              | 8         | 5.76%   |
| Gigabyte Technology | 7         | 5.04%   |
| Apple               | 6         | 4.32%   |
| Toshiba             | 5         | 3.6%    |
| MSI                 | 5         | 3.6%    |
| Acer                | 5         | 3.6%    |
| Intel               | 4         | 2.88%   |
| Sony                | 3         | 2.16%   |
| Itautec             | 2         | 1.44%   |
| T-bao               | 1         | 0.72%   |
| Shuttle             | 1         | 0.72%   |
| Semp Toshiba        | 1         | 0.72%   |
| Sapphire            | 1         | 0.72%   |
| Positivo            | 1         | 0.72%   |
| Philco              | 1         | 0.72%   |
| Medion              | 1         | 0.72%   |
| Kraftway            | 1         | 0.72%   |
| Gateway             | 1         | 0.72%   |
| Fujitsu             | 1         | 0.72%   |
| eMachines           | 1         | 0.72%   |
| Chuwi               | 1         | 0.72%   |
| Acidanthera         | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 1.44%   |
| Toshiba Satellite S55t-B                   | 1         | 0.72%   |
| Toshiba Satellite L50-A                    | 1         | 0.72%   |
| Toshiba Satellite C55-A                    | 1         | 0.72%   |
| Toshiba PORTEGE M780                       | 1         | 0.72%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 0.72%   |
| T-bao MINI PC                              | 1         | 0.72%   |
| Sony VPCYB45JB                             | 1         | 0.72%   |
| Sony VPCEB1J1E                             | 1         | 0.72%   |
| Sony SVS1511AJB                            | 1         | 0.72%   |
| Shuttle SH61R                              | 1         | 0.72%   |
| Semp Toshiba STI NA 1401                   | 1         | 0.72%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044          | 1         | 0.72%   |
| Positivo C14CR01                           | 1         | 0.72%   |
| Philco 10B                                 | 1         | 0.72%   |
| MSI MS-7C91                                | 1         | 0.72%   |
| MSI MS-7B93                                | 1         | 0.72%   |
| MSI MS-7A40                                | 1         | 0.72%   |
| MSI MS-7592                                | 1         | 0.72%   |
| MSI MS-16F1                                | 1         | 0.72%   |
| Medion H61H2-LM3                           | 1         | 0.72%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.72%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 0.72%   |
| Lenovo ThinkPad X61s 76693KG               | 1         | 0.72%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 0.72%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 0.72%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 0.72%   |
| Lenovo ThinkPad W520 4276CTO               | 1         | 0.72%   |
| Lenovo ThinkPad T450s 20BX001PUS           | 1         | 0.72%   |
| Lenovo ThinkPad T440p 20AW007QMS           | 1         | 0.72%   |
| Lenovo ThinkPad T430u 3352AA5              | 1         | 0.72%   |
| Lenovo ThinkPad T420 4180EE8               | 1         | 0.72%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 0.72%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 0.72%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 0.72%   |
| Lenovo ThinkPad 13 20GJCTO1WW              | 1         | 0.72%   |
| Lenovo ThinkCentre M83 10AHS35Q00          | 1         | 0.72%   |
| Lenovo ThinkCentre E73z 10BD004RRU         | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 16        | 11.51%  |
| Dell OptiPlex       | 5         | 3.6%    |
| Dell Inspiron       | 4         | 2.88%   |
| Acer Aspire         | 4         | 2.88%   |
| Toshiba Satellite   | 3         | 2.16%   |
| Lenovo IdeaPad      | 3         | 2.16%   |
| HP Compaq           | 3         | 2.16%   |
| Dell Latitude       | 3         | 2.16%   |
| ASUS TUF            | 3         | 2.16%   |
| Lenovo ThinkCentre  | 2         | 1.44%   |
| Itautec Infoway     | 2         | 1.44%   |
| HP Pavilion         | 2         | 1.44%   |
| HP EliteBook        | 2         | 1.44%   |
| Dell Studio         | 2         | 1.44%   |
| Unknown             | 2         | 1.44%   |
| Toshiba PORTEGE     | 1         | 0.72%   |
| Toshiba dynabook    | 1         | 0.72%   |
| T-bao MINI          | 1         | 0.72%   |
| Sony VPCYB45JB      | 1         | 0.72%   |
| Sony VPCEB1J1E      | 1         | 0.72%   |
| Sony SVS1511AJB     | 1         | 0.72%   |
| Shuttle SH61R       | 1         | 0.72%   |
| Semp Toshiba STI    | 1         | 0.72%   |
| Sapphire EDGE-FT1M1 | 1         | 0.72%   |
| Positivo C14CR01    | 1         | 0.72%   |
| Philco 10B          | 1         | 0.72%   |
| MSI MS-7C91         | 1         | 0.72%   |
| MSI MS-7B93         | 1         | 0.72%   |
| MSI MS-7A40         | 1         | 0.72%   |
| MSI MS-7592         | 1         | 0.72%   |
| MSI MS-16F1         | 1         | 0.72%   |
| Medion H61H2-LM3    | 1         | 0.72%   |
| Lenovo Yoga         | 1         | 0.72%   |
| Lenovo S20-30       | 1         | 0.72%   |
| Lenovo G580         | 1         | 0.72%   |
| Lenovo G550         | 1         | 0.72%   |
| Lenovo G500s        | 1         | 0.72%   |
| Lenovo G500         | 1         | 0.72%   |
| Lenovo B590         | 1         | 0.72%   |
| Kraftway KW10T      | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 17        | 12.23%  |
| 2012 | 15        | 10.79%  |
| 2019 | 14        | 10.07%  |
| 2011 | 13        | 9.35%   |
| 2010 | 13        | 9.35%   |
| 2015 | 11        | 7.91%   |
| 2020 | 10        | 7.19%   |
| 2014 | 10        | 7.19%   |
| 2021 | 8         | 5.76%   |
| 2018 | 7         | 5.04%   |
| 2016 | 7         | 5.04%   |
| 2009 | 5         | 3.6%    |
| 2017 | 4         | 2.88%   |
| 2008 | 3         | 2.16%   |
| 2007 | 2         | 1.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 72        | 51.8%   |
| Desktop     | 61        | 43.88%  |
| Convertible | 2         | 1.44%   |
| Mini pc     | 2         | 1.44%   |
| All in one  | 2         | 1.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 48        | 34.29%  |
| 4.01-8.0    | 46        | 32.86%  |
| 16.01-24.0  | 31        | 22.14%  |
| 32.01-64.0  | 10        | 7.14%   |
| 64.01-256.0 | 3         | 2.14%   |
| 3.01-4.0    | 1         | 0.71%   |
| 2.01-3.0    | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 79        | 56.43%  |
| 0.51-1.0 | 47        | 33.57%  |
| 1.01-2.0 | 11        | 7.86%   |
| 3.01-4.0 | 2         | 1.43%   |
| 2.01-3.0 | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 64.54%  |
| 2      | 26        | 18.44%  |
| 3      | 12        | 8.51%   |
| 4      | 8         | 5.67%   |
| 0      | 3         | 2.13%   |
| 5      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 55.4%   |
| Yes       | 62        | 44.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 92.81%  |
| No        | 10        | 7.19%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 68.35%  |
| No        | 44        | 31.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 59.71%  |
| Yes       | 56        | 40.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 21        | 15.11%  |
| Brazil      | 14        | 10.07%  |
| Germany     | 12        | 8.63%   |
| Russia      | 11        | 7.91%   |
| Ukraine     | 6         | 4.32%   |
| Spain       | 6         | 4.32%   |
| Poland      | 6         | 4.32%   |
| Italy       | 6         | 4.32%   |
| China       | 5         | 3.6%    |
| Australia   | 5         | 3.6%    |
| UK          | 4         | 2.88%   |
| Netherlands | 4         | 2.88%   |
| Mexico      | 4         | 2.88%   |
| Canada      | 3         | 2.16%   |
| South Korea | 2         | 1.44%   |
| New Zealand | 2         | 1.44%   |
| India       | 2         | 1.44%   |
| Chile       | 2         | 1.44%   |
| Bulgaria    | 2         | 1.44%   |
| Venezuela   | 1         | 0.72%   |
| Turkey      | 1         | 0.72%   |
| Thailand    | 1         | 0.72%   |
| Taiwan      | 1         | 0.72%   |
| Syria       | 1         | 0.72%   |
| Switzerland | 1         | 0.72%   |
| Slovakia    | 1         | 0.72%   |
| Singapore   | 1         | 0.72%   |
| Peru        | 1         | 0.72%   |
| Lithuania   | 1         | 0.72%   |
| Libya       | 1         | 0.72%   |
| Japan       | 1         | 0.72%   |
| Hungary     | 1         | 0.72%   |
| Hong Kong   | 1         | 0.72%   |
| Guatemala   | 1         | 0.72%   |
| Greece      | 1         | 0.72%   |
| France      | 1         | 0.72%   |
| Finland     | 1         | 0.72%   |
| Denmark     | 1         | 0.72%   |
| Czechia     | 1         | 0.72%   |
| Cuba        | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Harrisburg        | 3         | 2.11%   |
| Tula de Allende   | 2         | 1.41%   |
| Santiago          | 2         | 1.41%   |
| Nampa             | 2         | 1.41%   |
| Marlborough       | 2         | 1.41%   |
| Maraba            | 2         | 1.41%   |
| Kyiv              | 2         | 1.41%   |
| Hobart            | 2         | 1.41%   |
| Guangzhou         | 2         | 1.41%   |
| Frankfurt am Main | 2         | 1.41%   |
| Ernakulam         | 2         | 1.41%   |
| Barcelona         | 2         | 1.41%   |
| Yeongdong-gun     | 1         | 0.7%    |
| Yekaterinburg     | 1         | 0.7%    |
| Xiamen            | 1         | 0.7%    |
| Wroclaw           | 1         | 0.7%    |
| Wolgast           | 1         | 0.7%    |
| Wellington        | 1         | 0.7%    |
| Warrenton         | 1         | 0.7%    |
| Voronezh          | 1         | 0.7%    |
| Ufa               | 1         | 0.7%    |
| Tyumen            | 1         | 0.7%    |
| Tripoli           | 1         | 0.7%    |
| Torre del Mar     | 1         | 0.7%    |
| The Hague         | 1         | 0.7%    |
| Tampa             | 1         | 0.7%    |
| Taito             | 1         | 0.7%    |
| Stuttgart         | 1         | 0.7%    |
| Stralsund         | 1         | 0.7%    |
| Stara Zagora      | 1         | 0.7%    |
| Stade             | 1         | 0.7%    |
| St Petersburg     | 1         | 0.7%    |
| Sofia             | 1         | 0.7%    |
| Singapore         | 1         | 0.7%    |
| Siedlce           | 1         | 0.7%    |
| Sherwood Park     | 1         | 0.7%    |
| Shepetivka        | 1         | 0.7%    |
| Seoul             | 1         | 0.7%    |
| Seattle           | 1         | 0.7%    |
| SÃ£o Paulo      | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 42     | 18.52%  |
| WDC                 | 34        | 40     | 17.99%  |
| Samsung Electronics | 26        | 32     | 13.76%  |
| Toshiba             | 16        | 20     | 8.47%   |
| Crucial             | 10        | 13     | 5.29%   |
| Kingston            | 9         | 13     | 4.76%   |
| Hitachi             | 9         | 11     | 4.76%   |
| SanDisk             | 6         | 6      | 3.17%   |
| Intel               | 3         | 3      | 1.59%   |
| HGST                | 3         | 3      | 1.59%   |
| Corsair             | 3         | 3      | 1.59%   |
| China               | 3         | 3      | 1.59%   |
| A-DATA Technology   | 3         | 5      | 1.59%   |
| SPCC                | 2         | 2      | 1.06%   |
| Smartbuy            | 2         | 2      | 1.06%   |
| Plextor             | 2         | 2      | 1.06%   |
| OCZ                 | 2         | 2      | 1.06%   |
| KingSpec            | 2         | 3      | 1.06%   |
| Gigabyte Technology | 2         | 2      | 1.06%   |
| Apacer              | 2         | 2      | 1.06%   |
| Verbatim            | 1         | 1      | 0.53%   |
| Transcend           | 1         | 1      | 0.53%   |
| Silicon Motion      | 1         | 1      | 0.53%   |
| PNY                 | 1         | 1      | 0.53%   |
| Patriot             | 1         | 1      | 0.53%   |
| Micron Technology   | 1         | 1      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| LITEON              | 1         | 1      | 0.53%   |
| Lexar               | 1         | 1      | 0.53%   |
| Leven               | 1         | 1      | 0.53%   |
| Hewlett-Packard     | 1         | 1      | 0.53%   |
| GOODRAM             | 1         | 1      | 0.53%   |
| FORESEE             | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |
| AMD                 | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.91%   |
| Toshiba MQ01ABF050 500GB           | 3         | 1.44%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.44%   |
| Seagate ST9500325AS 500GB          | 3         | 1.44%   |
| Samsung SSD 860 EVO 500GB          | 3         | 1.44%   |
| Samsung SSD 860 EVO 1TB            | 3         | 1.44%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 2         | 0.96%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2         | 0.96%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.96%   |
| Seagate ST9500420AS 500GB          | 2         | 0.96%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.96%   |
| Seagate ST3500312CS 500GB          | 2         | 0.96%   |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 0.96%   |
| SanDisk SDSSDA240G 240GB           | 2         | 0.96%   |
| SanDisk SD5SE2256G1002E 256GB      | 2         | 0.96%   |
| Samsung SSD 970 EVO Plus 500GB     | 2         | 0.96%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.96%   |
| Samsung MZ7TE128HMGR-000L1 128GB   | 2         | 0.96%   |
| Samsung HD322HJ 320GB              | 2         | 0.96%   |
| Kingston SA400S37960G 960GB        | 2         | 0.96%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 0.96%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.96%   |
| Crucial CT250MX500SSD1 250GB       | 2         | 0.96%   |
| China SATA SSD 120GB               | 2         | 0.96%   |
| WDC WDS500G2B0A-00SM50 500GB       | 1         | 0.48%   |
| WDC WDS250G2X0C-00L350 250GB       | 1         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.48%   |
| WDC WD800JD-00LSA0 80GB            | 1         | 0.48%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 0.48%   |
| WDC WD5000BPKT-00PK4T0 500GB       | 1         | 0.48%   |
| WDC WD5000BEKT-60KA9T0 500GB       | 1         | 0.48%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1         | 0.48%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 1         | 0.48%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 0.48%   |
| WDC WD5000AAKS-08V0A0 500GB        | 1         | 0.48%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1         | 0.48%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 1         | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 0.48%   |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 0.48%   |
| WDC WD3200AAKS-00UU3A0 320GB       | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 42     | 35.35%  |
| WDC                 | 30        | 35     | 30.3%   |
| Toshiba             | 16        | 20     | 16.16%  |
| Hitachi             | 9         | 11     | 9.09%   |
| Samsung Electronics | 5         | 7      | 5.05%   |
| HGST                | 3         | 3      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 21.05%  |
| Crucial             | 10        | 13     | 13.16%  |
| Kingston            | 9         | 13     | 11.84%  |
| SanDisk             | 6         | 6      | 7.89%   |
| China               | 3         | 3      | 3.95%   |
| WDC                 | 2         | 2      | 2.63%   |
| Smartbuy            | 2         | 2      | 2.63%   |
| Plextor             | 2         | 2      | 2.63%   |
| OCZ                 | 2         | 2      | 2.63%   |
| KingSpec            | 2         | 3      | 2.63%   |
| Intel               | 2         | 2      | 2.63%   |
| Corsair             | 2         | 2      | 2.63%   |
| Apacer              | 2         | 2      | 2.63%   |
| Verbatim            | 1         | 1      | 1.32%   |
| Transcend           | 1         | 1      | 1.32%   |
| SPCC                | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| Patriot             | 1         | 1      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| LITEON              | 1         | 1      | 1.32%   |
| Lexar               | 1         | 1      | 1.32%   |
| Leven               | 1         | 1      | 1.32%   |
| GOODRAM             | 1         | 1      | 1.32%   |
| Gigabyte Technology | 1         | 1      | 1.32%   |
| FORESEE             | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |
| AMD                 | 1         | 1      | 1.32%   |
| A-DATA Technology   | 1         | 2      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 81        | 119    | 49.09%  |
| SSD  | 68        | 87     | 41.21%  |
| NVMe | 16        | 18     | 9.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 128       | 206    | 88.89%  |
| NVMe | 16        | 18     | 11.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 143    | 65.22%  |
| 0.51-1.0   | 40        | 44     | 24.84%  |
| 1.01-2.0   | 8         | 9      | 4.97%   |
| 2.01-3.0   | 4         | 6      | 2.48%   |
| 3.01-4.0   | 3         | 3      | 1.86%   |
| 4.01-10.0  | 1         | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 84        | 58.74%  |
| 101-250    | 32        | 22.38%  |
| 251-500    | 17        | 11.89%  |
| 501-1000   | 7         | 4.9%    |
| 51-100     | 2         | 1.4%    |
| 21-50      | 1         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 139       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                       | 2         | 2      | 5%      |
| Samsung Electronics HD322HJ 320GB               | 2         | 2      | 5%      |
| WDC WD5000AAKX-08ERMA0 500GB                    | 1         | 1      | 2.5%    |
| WDC WD5000AAKX-00ERMA0 500GB                    | 1         | 1      | 2.5%    |
| WDC WD5000AAKS-08V0A0 500GB                     | 1         | 1      | 2.5%    |
| WDC WD5000AAKS-00V1A0 500GB                     | 1         | 1      | 2.5%    |
| WDC WD3200BPVT-22JJ5T0 320GB                    | 1         | 1      | 2.5%    |
| WDC WD3200BEVT-80A0RT0 320GB                    | 1         | 1      | 2.5%    |
| WDC WD3200AAKS-00UU3A0 320GB                    | 1         | 1      | 2.5%    |
| WDC WD10JMVW-11AJGS0 1TB                        | 1         | 1      | 2.5%    |
| Toshiba MQ01UBD100 1TB                          | 1         | 1      | 2.5%    |
| Toshiba MQ01ABF050 500GB                        | 1         | 2      | 2.5%    |
| Toshiba MQ01ABD050 500GB                        | 1         | 1      | 2.5%    |
| Toshiba MK5061GSYN 500GB                        | 1         | 1      | 2.5%    |
| Toshiba MK3261GSYN 320GB                        | 1         | 2      | 2.5%    |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB                          | 1         | 2      | 2.5%    |
| Seagate ST9500325AS 500GB                       | 1         | 1      | 2.5%    |
| Seagate ST9320325AS 320GB                       | 1         | 1      | 2.5%    |
| Seagate ST750LM022 HN-M750MBB 752GB             | 1         | 1      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST3500413AS 500GB                       | 1         | 1      | 2.5%    |
| Seagate ST320LT012-9WS14C 320GB                 | 1         | 1      | 2.5%    |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 2.5%    |
| SanDisk SDSSDA240G 240GB                        | 1         | 1      | 2.5%    |
| SanDisk SD5SE2256G1002E 256GB                   | 1         | 1      | 2.5%    |
| Samsung Electronics HD161HJ 160GB               | 1         | 1      | 2.5%    |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1      | 2.5%    |
| Hitachi HTS722020K9SA00 200GB                   | 1         | 1      | 2.5%    |
| Hitachi HTS541616J9SA00 160GB                   | 1         | 1      | 2.5%    |
| Hitachi HTS541080G9SA00 80GB                    | 1         | 1      | 2.5%    |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 2.5%    |
| Corsair Force GT 120GB                          | 1         | 1      | 2.5%    |
| China SH00M128GB                                | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 31.58%  |
| WDC                 | 8         | 8      | 21.05%  |
| Toshiba             | 7         | 10     | 18.42%  |
| Hitachi             | 3         | 3      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Samsung Electronics | 2         | 3      | 5.26%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Corsair             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 36.36%  |
| WDC                 | 8         | 8      | 24.24%  |
| Toshiba             | 7         | 10     | 21.21%  |
| Hitachi             | 3         | 3      | 9.09%   |
| Samsung Electronics | 2         | 3      | 6.06%   |
| HGST                | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 38     | 86.49%  |
| SSD  | 5         | 5      | 13.51%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 112       | 178    | 73.68%  |
| Malfunc  | 37        | 43     | 24.34%  |
| Detected | 2         | 2      | 1.32%   |
| Failed   | 1         | 1      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 108       | 68.35%  |
| AMD                        | 28        | 17.72%  |
| Samsung Electronics        | 6         | 3.8%    |
| SanDisk                    | 3         | 1.9%    |
| Phison Electronics         | 3         | 1.9%    |
| ASMedia Technology         | 3         | 1.9%    |
| Silicon Motion             | 1         | 0.63%   |
| Realtek Semiconductor      | 1         | 0.63%   |
| Nvidia                     | 1         | 0.63%   |
| Lite-On IT Corp. / Plextor | 1         | 0.63%   |
| JMicron Technology         | 1         | 0.63%   |
| Hewlett-Packard            | 1         | 0.63%   |
| ADATA Technology           | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 9.94%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 8.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 4.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 3.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 3.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.76%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 2.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 2.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.66%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 1.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.1%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.55%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.55%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.55%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.55%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.55%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 75.32%  |
| IDE  | 19        | 12.03%  |
| NVMe | 16        | 10.13%  |
| RAID | 4         | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 110       | 79.14%  |
| AMD    | 29        | 20.86%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3317U CPU @ 1.70GHz           | 3         | 2.16%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3         | 2.16%   |
| Intel CPU Version                           | 2         | 1.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 1.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 1.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.44%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2         | 1.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.44%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.44%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 2         | 1.44%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.44%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.44%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.44%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2         | 1.44%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 1.44%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.44%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 1.44%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.72%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.72%   |
| Intel Xeon                                  | 1         | 0.72%   |
| Intel Processor 5Y70 CPU @ 1.10GHz          | 1         | 0.72%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.72%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.72%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.72%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.72%   |
| Intel Genuine CPU 2160 @ 1.80GHz            | 1         | 0.72%   |
| Intel Genuine CPU                           | 1         | 0.72%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1         | 0.72%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.72%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 1         | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.72%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 0.72%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.72%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.72%   |
| Intel Core i7-3517U CPU @ 1.90GHz           | 1         | 0.72%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 25.9%   |
| Intel Core i3           | 22        | 15.83%  |
| Intel Core i7           | 18        | 12.95%  |
| Intel Core 2 Duo        | 9         | 6.47%   |
| Intel Celeron           | 6         | 4.32%   |
| Other                   | 5         | 3.6%    |
| AMD Ryzen 5             | 5         | 3.6%    |
| AMD FX                  | 5         | 3.6%    |
| AMD Ryzen 7             | 4         | 2.88%   |
| Intel Xeon              | 3         | 2.16%   |
| Intel Pentium           | 3         | 2.16%   |
| Intel Atom              | 3         | 2.16%   |
| AMD Ryzen 9             | 3         | 2.16%   |
| AMD E                   | 3         | 2.16%   |
| Intel Genuine           | 2         | 1.44%   |
| Intel Core 2 Quad       | 2         | 1.44%   |
| AMD Ryzen 3             | 2         | 1.44%   |
| Intel Pentium Dual-Core | 1         | 0.72%   |
| Intel Core m3           | 1         | 0.72%   |
| AMD Ryzen 5 PRO         | 1         | 0.72%   |
| AMD Phenom II X6        | 1         | 0.72%   |
| AMD Phenom II X4        | 1         | 0.72%   |
| AMD C-60                | 1         | 0.72%   |
| AMD A6                  | 1         | 0.72%   |
| AMD A4                  | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 72        | 51.8%   |
| 4       | 33        | 23.74%  |
| Unknown | 7         | 5.04%   |
| 12      | 6         | 4.32%   |
| 8       | 6         | 4.32%   |
| 6       | 6         | 4.32%   |
| 16      | 4         | 2.88%   |
| 24      | 3         | 2.16%   |
| 1       | 2         | 1.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 134       | 96.4%   |
| 2      | 5         | 3.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 73        | 52.52%  |
| 1       | 59        | 42.45%  |
| Unknown | 7         | 5.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 20        | 14.39%  |
| KabyLake    | 15        | 10.79%  |
| Haswell     | 15        | 10.79%  |
| SandyBridge | 14        | 10.07%  |
| Westmere    | 11        | 7.91%   |
| Penryn      | 11        | 7.91%   |
| Zen 2       | 6         | 4.32%   |
| Zen         | 5         | 3.6%    |
| Skylake     | 5         | 3.6%    |
| Piledriver  | 5         | 3.6%    |
| Broadwell   | 5         | 3.6%    |
| Core        | 4         | 2.88%   |
| Bobcat      | 4         | 2.88%   |
| Zen+        | 3         | 2.16%   |
| Silvermont  | 3         | 2.16%   |
| Nehalem     | 3         | 2.16%   |
| K10         | 2         | 1.44%   |
| Excavator   | 2         | 1.44%   |
| Bonnell     | 2         | 1.44%   |
| Zen 3       | 1         | 0.72%   |
| TigerLake   | 1         | 0.72%   |
| CometLake   | 1         | 0.72%   |
| Bulldozer   | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 82        | 54.67%  |
| Nvidia | 40        | 26.67%  |
| AMD    | 28        | 18.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 17        | 11.26%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11        | 7.28%   |
| Intel Core Processor Integrated Graphics Controller                         | 6         | 3.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 3.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 2.65%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4         | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 2.65%   |
| Intel HD Graphics 5500                                                      | 4         | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 2.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 3         | 1.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.99%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2         | 1.32%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2         | 1.32%   |
| Nvidia G84M [GeForce 8600M GT]                                              | 2         | 1.32%   |
| Intel UHD Graphics 620                                                      | 2         | 1.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.32%   |
| Intel HD Graphics 630                                                       | 2         | 1.32%   |
| Intel HD Graphics 620                                                       | 2         | 1.32%   |
| Intel HD Graphics 530                                                       | 2         | 1.32%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 2         | 1.32%   |
| AMD Wrestler [Radeon HD 6320]                                               | 2         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 1.32%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2         | 1.32%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2         | 1.32%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.66%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.66%   |
| Nvidia GT215 [GeForce GT 220]                                               | 1         | 0.66%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1         | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1         | 0.66%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.66%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 0.66%   |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 0.66%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 46.43%  |
| 1 x Nvidia     | 32        | 22.86%  |
| 1 x AMD        | 26        | 18.57%  |
| Intel + Nvidia | 8         | 5.71%   |
| 2 x Intel      | 7         | 5%      |
| Intel + AMD    | 2         | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 116       | 83.45%  |
| Proprietary | 13        | 9.35%   |
| Unknown     | 10        | 7.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 106       | 75.71%  |
| 0.01-0.5   | 10        | 7.14%   |
| 1.01-2.0   | 8         | 5.71%   |
| 3.01-4.0   | 6         | 4.29%   |
| 0.51-1.0   | 4         | 2.86%   |
| 7.01-8.0   | 3         | 2.14%   |
| 5.01-6.0   | 3         | 2.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 13.46%  |
| Samsung Electronics     | 12        | 11.54%  |
| AU Optronics            | 10        | 9.62%   |
| Chimei Innolux          | 8         | 7.69%   |
| BOE                     | 7         | 6.73%   |
| Lenovo                  | 6         | 5.77%   |
| Hewlett-Packard         | 6         | 5.77%   |
| Dell                    | 5         | 4.81%   |
| Chi Mei Optoelectronics | 4         | 3.85%   |
| InfoVision              | 3         | 2.88%   |
| Iiyama                  | 3         | 2.88%   |
| Goldstar                | 3         | 2.88%   |
| BenQ                    | 3         | 2.88%   |
| Ancor Communications    | 3         | 2.88%   |
| Philips                 | 2         | 1.92%   |
| Apple                   | 2         | 1.92%   |
| Acer                    | 2         | 1.92%   |
| Vizio                   | 1         | 0.96%   |
| ViewSonic               | 1         | 0.96%   |
| SGT                     | 1         | 0.96%   |
| Medion                  | 1         | 0.96%   |
| KTC                     | 1         | 0.96%   |
| Haier                   | 1         | 0.96%   |
| Fujitsu Siemens         | 1         | 0.96%   |
| Eizo                    | 1         | 0.96%   |
| ASUSTek Computer        | 1         | 0.96%   |
| AOC                     | 1         | 0.96%   |
| ALP                     | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 3         | 2.86%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 2         | 1.9%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 1.9%    |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 2         | 1.9%    |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                  | 2         | 1.9%    |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch                   | 1         | 0.95%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch               | 1         | 0.95%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                            | 1         | 0.95%   |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch        | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                         | 1         | 0.95%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch      | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch     | 1         | 0.95%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.95%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 1         | 0.95%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                      | 1         | 0.95%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 1         | 0.95%   |
| LG Display LCD Monitor LGD048C 1920x1080 290x170mm 13.2-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 0.95%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 0.95%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 0.95%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch              | 1         | 0.95%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch                   | 1         | 0.95%   |
| Lenovo LEN-E73Z-D LEN00A1 1600x900 440x240mm 19.7-inch                   | 1         | 0.95%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                    | 1         | 0.95%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 0.95%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 41        | 39.42%  |
| 1920x1080 (FHD)    | 32        | 30.77%  |
| 1600x900 (HD+)     | 7         | 6.73%   |
| 1280x1024 (SXGA)   | 4         | 3.85%   |
| 1920x1200 (WUXGA)  | 3         | 2.88%   |
| 1680x1050 (WSXGA+) | 3         | 2.88%   |
| 1280x800 (WXGA)    | 3         | 2.88%   |
| 2560x1440 (QHD)    | 2         | 1.92%   |
| 1024x768 (XGA)     | 2         | 1.92%   |
| 1024x600           | 2         | 1.92%   |
| 3840x2160 (4K)     | 1         | 0.96%   |
| 3440x1440          | 1         | 0.96%   |
| 3200x1800 (QHD+)   | 1         | 0.96%   |
| 1920x540           | 1         | 0.96%   |
| 1360x768           | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 22.12%  |
| 13      | 17        | 16.35%  |
| 23      | 10        | 9.62%   |
| 24      | 9         | 8.65%   |
| 18      | 6         | 5.77%   |
| 12      | 6         | 5.77%   |
| 21      | 5         | 4.81%   |
| 17      | 5         | 4.81%   |
| 11      | 5         | 4.81%   |
| 19      | 4         | 3.85%   |
| 22      | 3         | 2.88%   |
| 14      | 3         | 2.88%   |
| 10      | 3         | 2.88%   |
| Unknown | 2         | 1.92%   |
| 42      | 1         | 0.96%   |
| 34      | 1         | 0.96%   |
| 27      | 1         | 0.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 36.89%  |
| 501-600     | 20        | 19.42%  |
| 201-300     | 20        | 19.42%  |
| 401-500     | 17        | 16.5%   |
| 351-400     | 4         | 3.88%   |
| Unknown     | 2         | 1.94%   |
| 701-800     | 1         | 0.97%   |
| 901-1000    | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 88        | 85.44%  |
| 16/10 | 9         | 8.74%   |
| 5/4   | 3         | 2.91%   |
| 4/3   | 2         | 1.94%   |
| 21/9  | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 25        | 24.04%  |
| 81-90          | 16        | 15.38%  |
| 91-100         | 15        | 14.42%  |
| 101-110        | 10        | 9.62%   |
| 141-150        | 8         | 7.69%   |
| 61-70          | 6         | 5.77%   |
| 51-60          | 5         | 4.81%   |
| 151-200        | 4         | 3.85%   |
| 41-50          | 3         | 2.88%   |
| 121-130        | 3         | 2.88%   |
| 71-80          | 2         | 1.92%   |
| 251-300        | 2         | 1.92%   |
| Unknown        | 2         | 1.92%   |
| 351-500        | 1         | 0.96%   |
| 301-350        | 1         | 0.96%   |
| 501-1000       | 1         | 0.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 41.75%  |
| 101-120       | 35        | 33.98%  |
| 121-160       | 17        | 16.5%   |
| 161-240       | 5         | 4.85%   |
| Unknown       | 2         | 1.94%   |
| More than 240 | 1         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 98        | 70%     |
| 0     | 37        | 26.43%  |
| 2     | 5         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 67        | 33%     |
| Intel                             | 61        | 30.05%  |
| Qualcomm Atheros                  | 26        | 12.81%  |
| Broadcom                          | 22        | 10.84%  |
| Marvell Technology Group          | 4         | 1.97%   |
| Ralink Technology                 | 3         | 1.48%   |
| Ralink                            | 3         | 1.48%   |
| JMicron Technology                | 3         | 1.48%   |
| Ericsson Business Mobile Networks | 3         | 1.48%   |
| Huawei Technologies               | 2         | 0.99%   |
| Xiaomi                            | 1         | 0.49%   |
| TP-Link                           | 1         | 0.49%   |
| Sierra Wireless                   | 1         | 0.49%   |
| Nvidia                            | 1         | 0.49%   |
| IMC Networks                      | 1         | 0.49%   |
| Google                            | 1         | 0.49%   |
| Belkin Components                 | 1         | 0.49%   |
| ASUSTek Computer                  | 1         | 0.49%   |
| Aquantia                          | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 46        | 18.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 3.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 7         | 2.87%   |
| Intel Wireless 7265                                                            | 7         | 2.87%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.46%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 5         | 2.05%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 1.64%   |
| Intel Wireless 7260                                                            | 4         | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 1.23%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 3         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                                | 2         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.82%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.82%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.82%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.82%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 0.82%   |
| Intel Centrino Advanced-N 6235                                                 | 2         | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 0.82%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.82%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III    | 2         | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 2         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 37.25%  |
| Qualcomm Atheros      | 19        | 18.63%  |
| Realtek Semiconductor | 18        | 17.65%  |
| Broadcom              | 16        | 15.69%  |
| Ralink Technology     | 3         | 2.94%   |
| Ralink                | 3         | 2.94%   |
| TP-Link               | 1         | 0.98%   |
| Sierra Wireless       | 1         | 0.98%   |
| IMC Networks          | 1         | 0.98%   |
| Belkin Components     | 1         | 0.98%   |
| ASUSTek Computer      | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 6.6%    |
| Intel Wireless 7265                                                     | 7         | 6.6%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 4.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.77%   |
| Intel Wireless 7260                                                     | 4         | 3.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 2.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.83%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.83%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 3         | 2.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.89%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.89%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.89%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.89%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.89%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.94%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.94%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 1         | 0.94%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.94%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                            | 1         | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.94%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1         | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.94%   |
| Intel Wireless 8260                                                     | 1         | 0.94%   |
| Intel Wireless 3160                                                     | 1         | 0.94%   |
| Intel WiFi Link 5100                                                    | 1         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 56        | 42.11%  |
| Intel                    | 43        | 32.33%  |
| Qualcomm Atheros         | 14        | 10.53%  |
| Broadcom                 | 8         | 6.02%   |
| Marvell Technology Group | 4         | 3.01%   |
| JMicron Technology       | 3         | 2.26%   |
| Xiaomi                   | 1         | 0.75%   |
| Nvidia                   | 1         | 0.75%   |
| Huawei Technologies      | 1         | 0.75%   |
| Google                   | 1         | 0.75%   |
| Aquantia                 | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 46        | 34.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 7.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 6.77%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 4.51%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 3.76%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 2.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 1.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.5%    |
| Intel Ethernet Connection I217-V                                               | 2         | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.5%    |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.5%    |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 1.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.75%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.75%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.75%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.75%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.75%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.75%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.75%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.75%   |
| Huawei USB Device                                                              | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 129       | 56.09%  |
| WiFi     | 96        | 41.74%  |
| Unknown  | 3         | 1.3%    |
| Modem    | 2         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 125       | 61.58%  |
| WiFi     | 75        | 36.95%  |
| Unknown  | 2         | 0.99%   |
| Modem    | 1         | 0.49%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 80        | 57.55%  |
| 1     | 57        | 41.01%  |
| 3     | 2         | 1.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 97.14%  |
| Yes  | 4         | 2.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 39.29%  |
| Broadcom                        | 8         | 14.29%  |
| Apple                           | 8         | 14.29%  |
| Realtek Semiconductor           | 6         | 10.71%  |
| Cambridge Silicon Radio         | 4         | 7.14%   |
| Foxconn / Hon Hai               | 3         | 5.36%   |
| Qualcomm Atheros Communications | 2         | 3.57%   |
| Ralink                          | 1         | 1.79%   |
| Hewlett-Packard                 | 1         | 1.79%   |
| ASUSTek Computer                | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 23.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 7.14%   |
| Apple Bluetooth Host Controller                             | 4         | 7.14%   |
| Realtek Bluetooth Adapter                                   | 2         | 3.57%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 3.57%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 2         | 3.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 3.57%   |
| Realtek Wireless Bluetooth Adapter                          | 1         | 1.79%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.79%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.79%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.79%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.79%   |
| Intel AX201 Bluetooth                                       | 1         | 1.79%   |
| Intel AX200 Bluetooth                                       | 1         | 1.79%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.79%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth             | 1         | 1.79%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 1.79%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 1.79%   |
| Broadcom Bluetooth 4.0                                      | 1         | 1.79%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter            | 1         | 1.79%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.79%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.79%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 1.79%   |
| Apple Bluetooth HCI                                         | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 106       | 56.99%  |
| AMD                     | 36        | 19.35%  |
| Nvidia                  | 28        | 15.05%  |
| C-Media Electronics     | 5         | 2.69%   |
| Texas Instruments       | 3         | 1.61%   |
| Logitech                | 2         | 1.08%   |
| Creative Labs           | 2         | 1.08%   |
| XMOS                    | 1         | 0.54%   |
| Plantronics             | 1         | 0.54%   |
| Hewlett-Packard         | 1         | 0.54%   |
| BEHRINGER International | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 10.41%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 5.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 4.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 3.62%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 3.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 2.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.26%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 2.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.81%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4         | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.81%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 1.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.81%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.36%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.36%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.36%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.9%    |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.9%    |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.9%    |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 0.9%    |
| AMD High Definition Audio Controller                                       | 2         | 0.9%    |
| AMD FCH Azalia Controller                                                  | 2         | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.9%    |
| XMOS USB Audio                                                             | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 29        | 17.16%  |
| SK hynix                     | 26        | 15.38%  |
| Kingston                     | 21        | 12.43%  |
| Unknown                      | 18        | 10.65%  |
| Micron Technology            | 12        | 7.1%    |
| Crucial                      | 11        | 6.51%   |
| Nanya Technology             | 6         | 3.55%   |
| Team                         | 5         | 2.96%   |
| Unknown                      | 5         | 2.96%   |
| Ramaxel Technology           | 4         | 2.37%   |
| G.Skill                      | 4         | 2.37%   |
| Corsair                      | 4         | 2.37%   |
| Teikon                       | 3         | 1.78%   |
| Smart                        | 3         | 1.78%   |
| Elpida                       | 3         | 1.78%   |
| A-DATA Technology            | 3         | 1.78%   |
| Transcend                    | 2         | 1.18%   |
| Patriot                      | 2         | 1.18%   |
| Apacer                       | 2         | 1.18%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.59%   |
| Smart Brazil                 | 1         | 0.59%   |
| SHARETRONIC                  | 1         | 0.59%   |
| PKI/Kingston                 | 1         | 0.59%   |
| Hikvision                    | 1         | 0.59%   |
| ASint Technology             | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown                                                         | 5         | 2.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 3         | 1.72%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s              | 2         | 1.15%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.15%   |
| SK hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s           | 2         | 1.15%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.15%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 2         | 1.15%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s           | 2         | 1.15%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 2         | 1.15%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.15%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s           | 2         | 1.15%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s             | 2         | 1.15%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s           | 2         | 1.15%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s            | 2         | 1.15%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s            | 2         | 1.15%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.15%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s            | 2         | 1.15%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                            | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 400MT/s                             | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                            | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3                              | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1         | 0.57%   |
| Unknown (0x7F7F7F94FFFFFFFF) RAM Module 2GB SODIMM DDR2 667MT/s | 1         | 0.57%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                     | 1         | 0.57%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s               | 1         | 0.57%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s          | 1         | 0.57%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s          | 1         | 0.57%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s           | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 83        | 60.58%  |
| DDR4    | 36        | 26.28%  |
| DDR2    | 8         | 5.84%   |
| Unknown | 5         | 3.65%   |
| LPDDR3  | 2         | 1.46%   |
| SDRAM   | 1         | 0.73%   |
| LPDDR4  | 1         | 0.73%   |
| DDR     | 1         | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 55.47%  |
| DIMM         | 57        | 41.61%  |
| Row Of Chips | 2         | 1.46%   |
| FB-DIMM      | 1         | 0.73%   |
| Chip         | 1         | 0.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 64        | 40.76%  |
| 8192  | 42        | 26.75%  |
| 2048  | 37        | 23.57%  |
| 16384 | 10        | 6.37%   |
| 32768 | 3         | 1.91%   |
| 1024  | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 49        | 32.45%  |
| 1333    | 29        | 19.21%  |
| 1067    | 11        | 7.28%   |
| 2400    | 10        | 6.62%   |
| 2667    | 9         | 5.96%   |
| 2133    | 7         | 4.64%   |
| 1334    | 7         | 4.64%   |
| 667     | 6         | 3.97%   |
| 3200    | 5         | 3.31%   |
| 2666    | 3         | 1.99%   |
| 1066    | 2         | 1.32%   |
| 800     | 2         | 1.32%   |
| 400     | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| 4267    | 1         | 0.66%   |
| 3000    | 1         | 0.66%   |
| 2933    | 1         | 0.66%   |
| 1867    | 1         | 0.66%   |
| 1866    | 1         | 0.66%   |
| 1200    | 1         | 0.66%   |
| 533     | 1         | 0.66%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Brother HL-L2310D series | 1         | 50%     |
| Brother DCP-J100         | 1         | 50%     |

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
| Chicony Electronics                    | 17        | 27.42%  |
| Bison Electronics                      | 8         | 12.9%   |
| IMC Networks                           | 5         | 8.06%   |
| Sunplus Innovation Technology          | 4         | 6.45%   |
| Realtek Semiconductor                  | 4         | 6.45%   |
| Microdia                               | 4         | 6.45%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.45%   |
| Z-Star Microelectronics                | 2         | 3.23%   |
| Suyin                                  | 2         | 3.23%   |
| Importek                               | 2         | 3.23%   |
| Apple                                  | 2         | 3.23%   |
| Tripath Technology                     | 1         | 1.61%   |
| Syntek                                 | 1         | 1.61%   |
| Logitech                               | 1         | 1.61%   |
| Lite-On Technology                     | 1         | 1.61%   |
| Lenovo                                 | 1         | 1.61%   |
| Hewlett-Packard                        | 1         | 1.61%   |
| Foxconn / Hon Hai                      | 1         | 1.61%   |
| ALi                                    | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 8         | 12.9%   |
| Bison Lenovo EasyCamera                                     | 3         | 4.84%   |
| Bison Integrated Camera                                     | 3         | 4.84%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 3.23%   |
| IMC Networks XHC Camera                                     | 2         | 3.23%   |
| Z-Star Integrated Camera                                    | 1         | 1.61%   |
| Z-Star A4 TECH USB2.0 PC Camera J                           | 1         | 1.61%   |
| Tripath 2M Front Camera                                     | 1         | 1.61%   |
| Syntek EasyCamera                                           | 1         | 1.61%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 1.61%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.61%   |
| Sunplus Lenovo EasyCamera                                   | 1         | 1.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.61%   |
| Sunplus Integrated Camera                                   | 1         | 1.61%   |
| Sunplus HP Universal Camera                                 | 1         | 1.61%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.61%   |
| Realtek Dell EasyCamera                                     | 1         | 1.61%   |
| Microdia Webcam                                             | 1         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 1.61%   |
| Microdia Integrated Webcam HD                               | 1         | 1.61%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.61%   |
| Logitech Webcam C270                                        | 1         | 1.61%   |
| Lite-On Integrated Camera                                   | 1         | 1.61%   |
| Lenovo Integrated Webcam                                    | 1         | 1.61%   |
| Importek TOSHIBA HD Web Camera                              | 1         | 1.61%   |
| Importek HP Webcam                                          | 1         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.61%   |
| IMC Networks USB 2.0 UVC HD Webcam                          | 1         | 1.61%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 1.61%   |
| HP Premium Starter Webcam                                   | 1         | 1.61%   |
| Foxconn / Hon Hai USB2.0 Camera                             | 1         | 1.61%   |
| Chicony WebCam                                              | 1         | 1.61%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 1.61%   |
| Chicony USB Video Device                                    | 1         | 1.61%   |
| Chicony Sony Visual Communication Camera                    | 1         | 1.61%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 1         | 1.61%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.61%   |
| Chicony HP Display Camera                                   | 1         | 1.61%   |
| Chicony Asus 720p CMOS webcam                               | 1         | 1.61%   |
| Chicony 1.3M Webcam                                         | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 46.67%  |
| Upek                  | 3         | 20%     |
| AuthenTec             | 3         | 20%     |
| STMicroelectronics    | 1         | 6.67%   |
| Elan Microelectronics | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 26.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 20%     |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 6.67%   |
| Elan Fingerprint Sensor                                                    | 1         | 6.67%   |
| AuthenTec AES2810                                                          | 1         | 6.67%   |
| AuthenTec AES1660                                                          | 1         | 6.67%   |
| AuthenTec AES1600                                                          | 1         | 6.67%   |

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
| 1     | 51        | 36.69%  |
| 0     | 36        | 25.9%   |
| 2     | 34        | 24.46%  |
| 3     | 13        | 9.35%   |
| 4     | 5         | 3.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 84        | 48.84%  |
| Card reader              | 25        | 14.53%  |
| Net/wireless             | 23        | 13.37%  |
| Fingerprint reader       | 15        | 8.72%   |
| Firewire controller      | 10        | 5.81%   |
| Bluetooth                | 6         | 3.49%   |
| Sound                    | 3         | 1.74%   |
| Storage                  | 2         | 1.16%   |
| Network                  | 2         | 1.16%   |
| Net/ethernet             | 2         | 1.16%   |

